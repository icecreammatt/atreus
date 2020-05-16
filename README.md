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
<img width="889" alt="Screen Shot 2020-05-15 at 5 53 37 PM" src="https://user-images.githubusercontent.com/1154569/82106388-75656080-96d5-11ea-834b-90dae43cea47.png">
<img width="890" alt="Screen Shot 2020-05-15 at 5 53 24 PM" src="https://user-images.githubusercontent.com/1154569/82106391-78f8e780-96d5-11ea-91bb-f649d7a67db0.png">
<img width="888" alt="Screen Shot 2020-05-15 at 5 53 48 PM" src="https://user-images.githubusercontent.com/1154569/82106394-7d250500-96d5-11ea-9f7d-c4e50c8abf4e.png">
<img width="878" alt="Screen Shot 2020-05-15 at 5 53 58 PM" src="https://user-images.githubusercontent.com/1154569/82106400-7f875f00-96d5-11ea-9d9f-d9e1c0b53ac2.png">
<img width="875" alt="Screen Shot 2020-05-15 at 5 54 13 PM" src="https://user-images.githubusercontent.com/1154569/82106404-82824f80-96d5-11ea-8aa7-75c040c196ce.png">
