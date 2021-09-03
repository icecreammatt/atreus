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
<img width="1205" alt="layer0" src="https://user-images.githubusercontent.com/1154569/132023651-ea615bfe-b710-413e-b7de-4cf5d575460f.png">
> Layer 1 (Special)
<img width="1199" alt="layer1" src="https://user-images.githubusercontent.com/1154569/132023658-77c159f5-f4aa-4865-a9bd-a0f0742964f4.png">
> Layer 2 (10 key and F keys)
<img width="1196" alt="layer2" src="https://user-images.githubusercontent.com/1154569/132023662-80e69f74-d10e-4e16-8e5f-be9a924da33f.png">
> Layer 3 (Gaming / FPS)
<img width="1199" alt="layer3" src="https://user-images.githubusercontent.com/1154569/132023665-9a2e8838-fd23-4a73-afce-248c4e499a5d.png">
> Layer 9
<img width="1197" alt="layer9" src="https://user-images.githubusercontent.com/1154569/132023669-a78ce815-9763-4ba2-b976-852e1c7fa577.png">
