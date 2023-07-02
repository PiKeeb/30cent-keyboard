# 30cent-keyboard/plate_files

## Folder Structure

- `/dxf` contains the DXF drawings of the key plates 
- `/step` contains STEP 3D models of the key plates

## Production instructions

All key plates have standart 1.5mm thickness.

`MidPlate` and `TopPlate` and `BotPlateCombined` are layout-agnostic. However, due to the location of stabilizer and switch holes, it's recommended to use `BotPlate*` tailored to your specific bottom row layout. If for example you'd like to use the **10U** spacebar, use the `BotPlate10.00u`.

You can omit the `BotPlate*` and/or the `TopPlate` if you don't plan to use bottom and/or top row(s).