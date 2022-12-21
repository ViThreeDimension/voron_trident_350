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
- [KlickyNG](https://github.com/ViThreeDimension/Klicky-Probe/tree/timelocked-mods/Trident)
- Sexbolt for Trident with kinematic bed (I will probably need to have one with more Z due to the kinematic adding some height to the bed plate)
- Panel locker [https://github.com/v6cl/My-Voron2.4-Customs/tree/main/Panel_Locker](https://github.com/v6cl/My-Voron2.4-Customs/tree/main/Panel_Locker)
- Doors 
  - [270 Clamping Hinges](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/AlexanderT-Moss/270-Clamping-Hinges)
  - Or Full size door like V2.2
- Gantry Backers [by whoppingpochard](https://github.com/ViThreeDimension/VoronUsers/tree/timelocked-mods/Trident/printer_mods/whoppingpochard/extrusion_backers)
- Trident kinematic_bed [by whoppingpochard](https://github.com/tanaes/whopping_Voron_mods/tree/main/kinematic_bed)
- Nevermore Duo V2 - 1.8 mod https://github.com/nevermore3d/Nevermore_Micro
  - Nevermore Spacer for Trident: https://github.com/Outrider305/Nevermore_Spacer_Mount
- https://github.com/LoganFraser/VoronMods/blob/main/DecontaminatorTrident/
    

## Electronics
- 24v alimentation & 48v for A-B Motors
- SHT36 v1 for Toolhead
- Octopus Pro 446 main board 
  - [Official Documentation](https://github.com/bigtreetech/BIGTREETECH-OCTOPUS-Pro/) - [(cached)](documentation_subpages/BTT_Octopus_pro_EN.pdf)
  - [Klipper Installation (VoronDocs)](https://docs.vorondesign.com/build/software/octopus_klipper.html)
  - [My doc](documentation_subpages/BTT_Octopus_pro_vince.md)
- 110V bed heater



# Todo
- ADXL <-> RJ45 Keystone <-> Raspberry Pi
  - Add Side-Front keystone skirt
- lights 24V
  - Top lights - for print defaults
  - On Vertical extrusions above AB tensioners? For photo lights
  - On Front Horizontal Extrusion + Back


# Wishlist to sort
- klicky AB holder
- Gantry Nozzle Brush
- No exhaust back: [link to blueDragonX fork](https://github.com/ViThreeDimension/3d-printer-mods/tree/master/printers/voron_2.4/exhaust)
- Side panels with Plywood? 
- [gcode buttons](https://github.com/VoronDesign/VoronUsers/tree/master/legacy_printers/printer_mods/meteyou/gcode_buttons)
