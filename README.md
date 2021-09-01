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
<img width="1205" alt="layer0" src="https://user-images.githubusercontent.com/1154569/131729357-2272c19f-7294-4e28-b92c-d3699a147939.png">
> Layer 1 (Special)
<img width="1194" alt="layer1" src="https://user-images.githubusercontent.com/1154569/131729365-71830523-116d-46da-bf23-a53656c740de.png">
> Layer 2 (10 key and F keys)
<img width="1196" alt="layer2" src="https://user-images.githubusercontent.com/1154569/131729369-df406f10-1ca7-4659-aa72-0e1a577e8652.png">
> Layer 3 (Gaming / FPS)
<img width="1205" alt="layer3" src="https://user-images.githubusercontent.com/1154569/131729372-32726285-9bdb-4fea-bb6f-0b63ee9bc745.png">
> Layer 9
<img width="1202" alt="layer9" src="https://user-images.githubusercontent.com/1154569/131729374-fbf61111-e7d4-42d9-acf9-a2d7c11cd4e5.png">
