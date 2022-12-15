# CAN Documentation

- [TeamFDM - how to use can toolhead boards connected directly to octopus pro](https://www.teamfdm.com/forums/topic/672-how-to-use-can-toolhead-boards-connected-directly-to-octopus-octopus-pro-on-canboot/)
- [Octopus Pro Documentation](https://github.com/bigtreetech/BIGTREETECH-OCTOPUS-Pro/) - [(cached pdf)](BTT_Octopus_pro_EN.pdf)
- [Mellow SHT36 CanBus Toolhead](https://mellow.klipper.cn/#/advanced/canboot)
  - UTOC device -> Bus 001 Device 003: ID 1d50:606f OpenMoko, Inc. 
- [Octopus and SB2040](https://github.com/akhamar/voron_canbus_octopus_sb2040#useful-tricks-to-be-able-to-update-an-octopus-11-in-usb-to-can-bridge)
- [Maz0r Canbus for Klipper](https://maz0r.github.io/klipper_canbus/)
- EddieTheEngineer Videos
  - [Klipper Mainsail Can setup guide](https://www.youtube.com/watch?v=XkcxSQhRR3I)
  - [BTT EBB V1.0 CAN Setup Guide](https://www.youtube.com/watch?v=_FELCN8CbWA)
  - [Flash your Huvud over Canbus!](https://www.youtube.com/watch?v=YrF99Sff9g8)
  - [Flash all your klipper MCUs with 1 script](https://www.youtube.com/watch?v=1P4UrJxChL8) 

# My CAN configuration
- Start with UTOC-3 from Mazor https://maz0r.github.io/klipper_canbus/controller/utoc1-3.html

## PI Setup

` sudo nano /etc/network/interfaces.d/can0 `

auto can0
iface can0 can static
 bitrate 500000
 up ifconfig $IFACE txqueuelen 256
 pre-up ip link set can0 type can bitrate 500000
 pre-up ip link set can0 txqueuelen 256

and press Ctrl+X to save.

you can now reboot the pi with ` sudo reboot `
## Test the network

Once the pi has rebooted you can run the ip -s link show can0 command to check your network status.

You should see a line like the below in the results. The key thing to note is that the network is UP for now.

![iplink](utoc-1-iplink-from-mazor.png)

- If not working test this 
https://mellow.klipper.cn/#/advanced/can_rpi