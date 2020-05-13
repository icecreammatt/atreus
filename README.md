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

<img width="685" alt="Screen Shot 2020-05-12 at 10 53 37 PM" src="https://user-images.githubusercontent.com/1154569/81775945-ad389200-94a2-11ea-9064-ef8af0b6fd37.png">
<img width="691" alt="Screen Shot 2020-05-12 at 10 53 43 PM" src="https://user-images.githubusercontent.com/1154569/81775946-ae69bf00-94a2-11ea-94bd-460535b1fc70.png">
<img width="684" alt="Screen Shot 2020-05-12 at 10 53 49 PM" src="https://user-images.githubusercontent.com/1154569/81775948-af9aec00-94a2-11ea-9608-057dac9d884c.png">
<img width="677" alt="Screen Shot 2020-05-12 at 10 53 54 PM" src="https://user-images.githubusercontent.com/1154569/81775952-b164af80-94a2-11ea-8135-0c6b2af328bf.png">
<img width="677" alt="Screen Shot 2020-05-12 at 10 54 01 PM" src="https://user-images.githubusercontent.com/1154569/81775955-b3c70980-94a2-11ea-951a-cb9314ba8b32.png">

