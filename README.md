# Mindful-Audio-Device
These are all the files needed, to recreate my self built music-player. Please note that this is a one man project, so progress is slow and may be painful.

List of hardware components you will need to recreate this device:
  x RaspberryPi Zero W / RaspberryPi Zero W2 (3d models are made to fit the Pi Zero W without GPIO Header, however I belive the Zero W 2 will fit aswell)
  x 4 - 128 GB MicroSD-Card (the bigger the card, the more offline music you can store)
  x 5 Inch Display, with HDMI connector, preferably touchscreen
  x Mini HDMI Type C to "normal" HDMI adapter
  x The smallest possible HDMI "cable"
  x Micro USB to USB C/3.5mm Connector
  x Adafruit 1000c Powerboost Board
  x Lithium-Ion-Battery (capcity of your choice, I used 2000 mAh)
  x Jumper-Wires
  x Keyboard-Switches of your choice

List of things you need to manufacture this device:
  x Soldering Iron
  x 3d-Printer
  x Any device to create a bootable microSD with RaspberryPi-OS

List of Software I used to create this device (you can use any other, similar software, however in my opinion this combination worked best)
  x SpotDL to download (of course copyright free) music to my server
  x Navidrome as a music server
  x PsySonic as Navidrome-Client (mostly because of it's really customisable design)
  x The python scripts in this repository, to manage the custom buttons as well as download the music from your navidrome server to a local directory in case your client doesn't support that
