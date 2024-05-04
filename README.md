# ansible-playbook-motioneye-on-raspios
Install motioneye on [RaspiOS](https://downloads.raspberrypi.com/raspios_lite_armhf/images/)

Steps from https://github.com/motioneye-project/motioneye/tree/dev#installation

* download
* /etc/wpa_supplicant.conf
* /boot/ssh


ansible-playbook motioneye-on-raspios-install.yml -i ../private/hosts -l rpi0-w-usbcam-01
