# Corne Keyboard (crkbd/rev1)

## Guide to flash firmware

### QMK

1. Detach keyboard from PC (USB cable)
2. Detach keyboard splits (TRSS cable)
3. Open QMK Toolbox
4. Click `Open` local file
5. Select `firmware_name.hex` file
6. Check `Auto-flash` option
7. Attach PC to left split only
8. Double press keyboard reset button
9. Wait until completion and device disconnected message is displayed
10. Detach left split from PC
11. Attach PC to right split only
12. Double press keyboard reset button
13. Wait until completion and device disconnected message is displayed
14. Detach right split from PC
15. Attach PC to left split only (USB cable)
16. Attach keyboard splits (TRSS cable)

### Vial

1. Detach keyboard from PC (USB cable)
2. Detach keyboard splits (TRSS cable)
3. Open QMK Toolbox
4. Click `Open` local file
5. Select `firmware_name_vial-left.hex` file
6. Check `Auto-flash` option
7. Attach PC to left split only
8. Double press keyboard reset button
9. Wait until completion and device disconnected message is displayed
10. Detach left split from PC
11. Click `Open` local file
12. Select `firmware_name_vial-right.hex` file
13. Attach PC to right split only
14. Double press keyboard reset button
15. Wait until completion and device disconnected message is display
16. Detach right split from PC
17. Attach PC to left split only (USB cable)
18. Attach keyboard splits (TRSS cable)

## Guide to configure keymap

### QMK

1. Open [QMK online configurator](https://config.qmk.fm/#/crkbd/rev1/LAYOUT_split_3x6_3)
2. Select crkbd/rev1
3. Select layout
4. Edit keymap
5. Complile
6. Download firmware
7. Flash firmware

### Via/Vial

1. Open [VIA online configurator](https://usevia.app/)
2. Select corne
3. Edit keymap
