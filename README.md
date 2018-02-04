## To Install
This is an updated driver for DYMO LabelWriter (This includes the DYMO 450, 450 Turbo, etc). It fixes an number of issues with broke or missing reference that make it impossible to compile the driver.


### Run the commands from the terminal on a Raspberry Pi.

*Clone this repo `git clone https://github.com/googler4/dymo-raspi.git`
*cd into the repo `cd dymo-raspi`
*Run the following commands to install the needed libraries and compile the driver for CUPs
```
sudo apt-get install -yq cups libcups2-dev libcupsimage2-dev gcc g++
sudo ./configure
sudo make
sudo make install
```
