# Keyboard (hardware part)

software parts:

- https://github.com/sb-child/keyboard-software-core

- https://github.com/sb-child/keyboard-software-scanner

## v1 (rev 2 ~ 3)

**This version is _deprecated_, please check the latest version [v1(rev5)](#v1-rev-5)**

<details>
<summary>view details of v1(rev3)</summary>

### pictures

rendered image, [_download blender model_](./v1/render.blend)

![render image](./v1/render.png)

actual

![image](./v1/v1.png)

### PCB

[kicad pcb files](./v1/pcb-rev3.zip)

### plates

download dxf files below:

size: 462.44 mm x 133.83 mm

[top plate (1.5mm stainless steel)](./v1/plate-top.dxf)

[bottom plate (5mm poly methyl methacrylate)](./v1/plate-bottom.dxf)

</details>

## v1 (rev 4)

**This version is _deprecated_, please check the latest version [v1(rev5)](#v1-rev-5)**

<details>
<summary>view details of v1(rev4)</summary>

changelog:

- replaced all LDOs with the RT9193
- replaced almost all 0805 smd capacitors with 0603
- replaced 3 segment displays with two SSD1306 OLED screens
- moved the BOOT and RESET buttons closer to the edge of the pcb

backward compatibility:

at a minimum, these components will need to be replaced to upgrade to this version:

- from `v1 rev2` or `v1 rev3`
  - _replace_ board 3
  - _replace_ board 6
  - _replace_ top plate
  - _add_ OLED panel

### pictures

rendered image, [_download blender model_](./v1/render-v1-rev4.blend)

![render image](./v1/render-v1-rev4.png)

actual

todo

### PCB

[kicad pcb files](./v1/pcb-rev4.zip)

### plates

download dxf files below:

size: 462.44 mm x 133.83 mm

[top plate (1.5mm stainless steel)](./v1/plate-top-rev4.dxf)

[bottom plate (3mm POM plastic / 5mm ABS plastic)](./v1/plate-bottom.dxf)

</details>

## v1 (rev 5)

changelog:

- fix incorrect footprints of RT9193

backward compatibility:

at a minimum, these components will need to be replaced to upgrade to this version:

- from `v1 rev4`
  - _replace_ board 2
  - _replace_ board 3
  - _replace_ board 6

### pictures

rendered image, [_download blender model_](./v1/render-v1-rev4.blend)

![render image](./v1/render-v1-rev4.png)

actual

todo

### PCB

[kicad pcb files](./v1/pcb-rev4.zip)

### plates

download dxf files below:

size: 462.44 mm x 133.83 mm

[top plate (1.5mm stainless steel)](./v1/plate-top-rev4.dxf)

[bottom plate (3mm POM plastic / 5mm ABS plastic)](./v1/plate-bottom.dxf)

### BOM and soldering

todo

### assembling

todo

### wiring

todo
