# project-houston-controllers
This project is about controlling Air Conditioner with Raspberry Pi 3 using LIRC library which can be installed using the following command:
```
sudo apt-get install lirc
```
But before executing this command it is better to make sure that everything is up to date by running the following commands:
```
sudo apt-get update
sudo apt-get upgrade
sudo rpi-update
```
If rpi modules are not installed then you can easily install it by running:
```
sudo apt-get install rpi-update
```
Now you are all set to go to the next stage, but in order to be on the safe side, it is better to reboot your pi by running:
```
sudo reboot
```
After installing lirc you can check start or stop it by typing following command:
```
sudo /etc/init.d/lirc start
sudo /etc/init.d/lirc stop
```
The output of the following commands should look something like this:
start:
```
[ ok ] Starting lirc (via systemctl): lirc.service.
```
stop:
```
[ ok ] Stopping lirc (via systemctl): lirc.service.
```

