# KeyBoardLayouts
Have the different layouts accessible

.eep if from the tmk builder
.hex if form the qmk builder

Always run the tqk as sudo to be able to flash it 

Manual way of flashing

sudo dfu-programmer atmega32u4 erase --force
sudo dfu-programmer atmega32u4 flash [filename].hex
sudo dfu-programmer atmega32u4 reset
