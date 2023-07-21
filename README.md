# Corne Keyboard

### Prerequisites
1. Download latest [QMK Toolbox release](https://github.com/qmk/qmk_toolbox/releases)
2. Download latest [Vial release](https://get.vial.today/download/)
3. Download all firmware from this repository
4. Detach USB cable from PC
5. Detach TRRS cable

### Flash left
1. Open QMK Toolbox
2. Select firmware `crkbd-qmk-firmware-left.hex`
3. Select `Auto-flash option`
4. Attach PC to left split only
5. Double press keyboard reset button (above TRRS port)
6. Wait until completion and keyboard disconnected is prompted

### Flash right
1. Select firmware `crkbd-qmk-firmware-right.hex`
2. Select `Auto-flash option`
3. Attach PC to right split only
4. Double press keyboard reset button (above TRRS port)
5. Wait until completion and keyboard disconnected is prompted

### Keybindings
1. Open Vial
2. File > Load saved layout
3. Select `crkbd-vial-layout.vil`
