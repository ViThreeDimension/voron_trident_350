# My Voron Trident 350

This documentation is to know where to find replacement parts for the mods. 
When I will be at the software step, I will add klipper configs, make files. 

Built from this [Voron Trident R1 commit](https://github.com/VoronDesign/Voron-Trident/tree/VTr1)

[Voron 2.4 R0 - 300](https://github.com/ViThreeDimension/voron2.4) big brother

## Mods
- [Carbon Pin Mod](/mods/own%20mods/Trident%20Carbon%20Pin%20Mod/) (slightly lower holes diameter) based on [hartk pin mod](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/hartk1213/Voron2.4_Trident_Pins_Mod) - [(fork)](https://github.com/ViThreeDimension/VoronUsers/tree/timelocked-mods/Trident/printer_mods/hartk1213/Voron2.4_Trident_Pins_Mod)
- [Fish3DP's front idlers "Tackle Box"](/mods/fishTackleBox/Fish%20Tackle%20Box%20other_front_idler.md)
- Umbelical
- Can Toolhead SHT-36
  - [Can Mount](/mods/STH-36_sherpa_mini_mounting_plate_overmold_strain.stl) from [KayorMaker Can Mount Repo](https://github.com/KayosMaker/CANboard_Mounts)
  - [CanBus Documentation](documentation_subpages/CAN%20configuration.md)
- [Toolhead smol mantis](/mods/smol_mantis/) from [FoonieTunes repo](https://github.com/sporkus/smol_mantis)
  - [Sherpa mini from annex](https://github.com/Annex-Engineering/Sherpa_Mini-Extruder)
  - [Mini Sherpa Angled Front Brace from Mandryd](https://github.com/Annex-Engineering/Annex-Engineering_User_Mods/tree/main/Extruders/Sherpa_Mini/Extruder_Mods/Long-housing_front_angled_front_brace)
  - Can Bus SHT-36 - [Documentation](https://mellow.klipper.cn/#/board/fly_sht36_42/)
- [KlickyNG](https://github.com/ViThreeDimension/Klicky-Probe/tree/timelocked-mods/Trident)
- [Sexbolt for Trident with kinematic bed](/mods/sexbolt%20trident%20for%20kinematic%20bed/) based on [sexbolt by hartk](https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_SexBolt_ZEndstop)
- Panel locker [by V6C1](https://github.com/v6cl/My-Voron2.4-Customs/tree/main/Panel_Locker)
- V2.2 doors modified for 5mm acrylic and 8mm foam: [here](mods/front%20panel%20handle)
- Gantry Backers [by whoppingpochard](https://github.com/ViThreeDimension/VoronUsers/tree/timelocked-mods/Trident/printer_mods/whoppingpochard/extrusion_backers)
- Trident kinematic_bed [by whoppingpochard](https://github.com/tanaes/whopping_Voron_mods/tree/main/kinematic_bed)
- [Nevermore](https://github.com/nevermore3d/Nevermore_Micro) and Nevermore Extension [by Outrider305](https://github.com/Outrider305/Nevermore_Spacer_Mount) - ([cache](https://github.com/ViThreeDimension/Nevermore_Spacer_Mount))
- [Decontaminator Bucket and brush](https://github.com/LoganFraser/VoronMods/blob/main/DecontaminatorTrident/)
- 
## Electronics
- 24v alimentation & 48v for A-B Motors
- SHT36 v1 for Toolhead - [Documentation](https://mellow.klipper.cn/#/board/fly_sht36_42/)
- Octopus Pro 446 main board 
  - [Official Documentation](https://github.com/bigtreetech/BIGTREETECH-OCTOPUS-Pro/) - [(cached)](documentation_subpages/BTT_Octopus_pro_EN.pdf)
  - [Klipper Installation (VoronDocs)](https://docs.vorondesign.com/build/software/octopus_klipper.html)
  - [My doc](documentation_subpages/BTT_Octopus_pro_vince.md)
- 110V bed heater


# Todo
- ADXL: Add Front keystone skirt


# Wishlist to sort
- [gcode buttons](https://github.com/VoronDesign/VoronUsers/tree/master/legacy_printers/printer_mods/meteyou/gcode_buttons)
