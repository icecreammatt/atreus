# Atreus keyboard

1. Update layout [here](https://config.qmk.fm/#/atreus/astar/LAYOUT)
1. Update this repo with latest keymap.json
1. Compile using website

## Flashing
Press `Reset` key on keyboard to enter flash mode or short pins on rear

```bash
avrdude -p atmega32u4 -c avr109 -U flash:w:atreus_astar.hex -P /dev/cu.usbmodem1410
```

## Tooling
1. OSX Setup Instructions
1. `brew tap osx-cross/avr`
1. `brew install avrdude`

## Layout
<img width="682" alt="Screen Shot 2020-05-13 at 12 22 58 AM" src="https://user-images.githubusercontent.com/1154569/81782635-fb539280-94ae-11ea-9d84-8262f02cdcb0.png">
<img width="686" alt="Screen Shot 2020-05-13 at 12 23 04 AM" src="https://user-images.githubusercontent.com/1154569/81782642-fd1d5600-94ae-11ea-9bec-40667529df33.png">
<img width="678" alt="Screen Shot 2020-05-13 at 12 23 11 AM" src="https://user-images.githubusercontent.com/1154569/81782648-fee71980-94ae-11ea-9997-7de1f4e0c547.png">
<img width="677" alt="Screen Shot 2020-05-13 at 12 23 17 AM" src="https://user-images.githubusercontent.com/1154569/81782652-00184680-94af-11ea-918a-4e90a6a110b7.png">
<img width="683" alt="Screen Shot 2020-05-13 at 12 23 24 AM" src="https://user-images.githubusercontent.com/1154569/81782659-01e20a00-94af-11ea-88b3-8a9045dc8563.png">
