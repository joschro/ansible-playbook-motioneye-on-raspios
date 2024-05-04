# ansible-playbook-motioneye-on-raspios
Install motioneye on [RaspiOS 32bit](https://downloads.raspberrypi.com/raspios_lite_armhf/images/) (e.g. Raspberry Pi Zero) or [RaspiOS 64bit](https://downloads.raspberrypi.com/raspios_lite_arm64/images/) (e.g. Raspberry Pi Zero 2)

Steps from https://github.com/motioneye-project/motioneye/tree/dev#installation

* download
* /etc/wpa_supplicant.conf
* /boot/ssh


ansible-playbook motioneye-on-raspios-install.yml -i ../private/hosts -l rpi0-w-usbcam-01

Then point your browser to http://<ip-address>:8765
