* Install screen

sudo adduser $USER dialout
sudo apt-get install screen

* Use "screen" to check the USB is connected

screen /dev/ttyUSB1 115200

* Check for Processes Using the Port

sudo lsof /dev/ttyUSB2

If a process is listed, terminate it using:

sudo kill -9 <PID>
