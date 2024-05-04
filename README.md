# ansible-playbook-motioneye-on-raspios
Install motioneye on [RaspiOS](https://downloads.raspberrypi.com/raspios_lite_armhf/images/raspios_lite_armhf-2024-03-15/2024-03-15-raspios-bookworm-armhf-lite.img.xz)

Steps from https://github.com/motioneye-project/motioneye/tree/dev#installation

* download
* /etc/wpa_supplicant.conf
* /boot/ssh


ansible-playbook motioneye-on-raspios-install.yml -i ../private/hosts -l rpi0-w-usbcam-01
