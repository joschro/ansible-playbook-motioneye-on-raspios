# ansible-playbook-motioneye-on-raspios
Install motioneye on RaspiOS

Steps from https://github.com/motioneye-project/motioneye/tree/dev#installation

* download
* /etc/wpa_supplicant.conf
* /boot/ssh


ansible-playbook motioneye-on-raspios-install.yml -i ../private/hosts -l rpi0-w-usbcam-01
