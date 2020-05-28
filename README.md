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

> Layer 0 (Default)
<img width="601" alt="Screen Shot 2020-05-26 at 7 28 19 AM" src="https://user-images.githubusercontent.com/1154569/83106012-94b6a300-a070-11ea-88fd-aec2d737e21e.png">

> Layer 1 (Special)
<img width="602" alt="Screen Shot 2020-05-26 at 7 28 25 AM" src="https://user-images.githubusercontent.com/1154569/83106015-9718fd00-a070-11ea-9d71-1ec7fd0b3ede.png">

> Layer 2 (10 key and F keys)
<img width="606" alt="Screen Shot 2020-05-26 at 7 28 29 AM" src="https://user-images.githubusercontent.com/1154569/83106024-997b5700-a070-11ea-9f0d-9a3d078aaf4f.png">

> Layer 3 (Gaming / FPS)
<img width="601" alt="Screen Shot 2020-05-26 at 7 28 34 AM" src="https://user-images.githubusercontent.com/1154569/83106030-9b451a80-a070-11ea-803c-ed9f9bb724d2.png">

> Layer 9
<img width="605" alt="Screen Shot 2020-05-26 at 7 28 39 AM" src="https://user-images.githubusercontent.com/1154569/83106093-b7e15280-a070-11ea-8a0b-b523ec0a58a9.png">
