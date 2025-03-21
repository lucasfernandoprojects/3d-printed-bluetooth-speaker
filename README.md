# 3D-Printed Bluetooth Speaker

*I've recently posted a tutorial about this project on YouTube. You can watch it [here](https://www.youtube.com/watch?v=bhGaHZuU-Os) or, if you prefer, you can read a [blog post](https://www.elecrow.com/sharepj/how-to-build-a-3d-printed-bluetooth-speaker-595.html) about it.*

## Overview
This project is a 3D-printed Bluetooth speaker that you can build at home. The enclosure was designed in Fusion 360 and 3D-printed, while the electronics include a Bluetooth amplifier module, speakers, and a rechargeable battery system. The enclosure is hand-painted to achieve a stunning wood-like finish.

![3D-printed Bluetooth speaker - front view.](https://github.com/lucasfernandoprojects/3d-printed-bluetooth-speaker/blob/main/photos/1.jpg)

## Features
- Bluetooth connectivity
- Infrared remote control & physical buttons
- Rechargeable battery-powered
- 3D-printed enclosure with wood-like finish
- Dual 5W speakers & passive bass radiators for enhanced sound

## Why 3D Printing?
After experimenting with different materials like PVC and MDF, 3D printing was chosen for its precision, flexibility, and ease of customization. It allows for a lightweight, compact, and aesthetically pleasing enclosure without requiring woodworking tools.

Here's the schematics of this project.

![Bluetooth speaker schematics](https://github.com/lucasfernandoprojects/3d-printed-bluetooth-speaker/blob/main/photos/schematics.png)

## Components

### Electronics:
- **[Bluetooth + Amplifier Module](https://www.aliexpress.us/item/3256806644153211.html?spm=a2g0o.order_list.order_list_main.5.48b81802Hh27U6&gatewayAdapt=glo2usa4itemAdapt)**: Kebidu 5W (supports Bluetooth, FM radio, SD cards, USB drives, and infrared remote control)
- **[Speakers](https://www.aliexpress.us/item/3256806681202647.html?spm=a2g0o.order_list.order_list_main.10.48b81802Hh27U6&gatewayAdapt=glo2usa4itemAdapt)**: 5W, 4-ohm, 40mm diameter (generic)
- **Battery**: Two 18650 Li-Po batteries connected in parallel
- **[Charger Module](https://www.aliexpress.us/item/3256804241424963.html?spm=a2g0o.order_list.order_list_main.40.48b81802Hh27U6&gatewayAdapt=glo2usa4itemAdapt)**: TP4056 USB-C module
- **[Passive Radiators](https://www.aliexpress.us/item/2251832825900859.html?spm=a2g0o.order_list.order_list_main.25.48b81802Hh27U6&gatewayAdapt=glo2usa4itemAdapt)**: 66mm passive bass radiators

### Other materials:
- 2x **3mm LEDs** (power & charge indicators)
- **Super glue**
- **2mm EVA foam sheets** (for sound insulation)
- **Paints & brushes** (for finishing)

## Design Process
### 1. **Fusion 360 for enclosure design**: Modeled to fit all components precisely.
### 2. **Iterative improvements**:
- Redesigned the back panel for durability.
- Adjusted screw placements for better assembly.
- Ensured proper airflow and sealing for sound optimization.

## Building Steps
### 1. Modifying the Charger Module
- Replaced built-in LEDs with **external 3mm LEDs** for visibility.
### 2. Wiring & Electronics Setup
- Connected batteries to **TP4056 charger module**.
- Wired the **amplifier module** and **Bluetooth module**.
- Soldered **speakers and passive radiators** for enhanced bass.
### 3. Painting & Finishing the Enclosure
- **Spray paint** with caramel-colored base coat.
- Use **Copic Ink Refills** to create a **realistic wood grain texture**.
- Lined the interior with **2mm EVA foam sheets** to reduce vibrations.
### 4. Final Assembly
- Carefully placed and secured all components inside the **3D-printed enclosure**.
- Sealed the speaker to **prevent air leaks** and maximize bass response.

## Challenges & Learnings
- **Passive Radiator Optimization**: The chosen radiators were too heavy for the small speakers. Future designs will incorporate better-matched radiators based on software calculations.
- **Structural Adjustments**: The original back panel broke under pressure, requiring a redesign.
- **Painting Techniques**: Using Copic Inks on 3D prints resulted in a realistic wood finish, improving aesthetics dramatically.

## Results
- Premium-looking speaker with a custom wood finish.
- Great sound quality, although further improvements can be made to the bass response.
- A fun and rewarding project that enhances 3D design and electronics skills.

<div style="display: flex; flex-wrap: wrap;">
    <img src="https://github.com/lucasfernandoprojects/3d-printed-bluetooth-speaker/blob/main/photos/2.jpg" width="400" height="250" style="margin: 10px;">
    <img src="https://github.com/lucasfernandoprojects/3d-printed-bluetooth-speaker/blob/main/photos/3.jpg" width="400" height="250" style="margin: 10px;">
    <img src="https://github.com/lucasfernandoprojects/3d-printed-bluetooth-speaker/blob/main/photos/4.jpg" width="400" height="250" style="margin: 10px;">
    <img src="https://github.com/lucasfernandoprojects/3d-printed-bluetooth-speaker/blob/main/photos/5.jpg" width="400" height="250" style="margin: 10px;">
    <img src="https://github.com/lucasfernandoprojects/3d-printed-bluetooth-speaker/blob/main/photos/6.jpg" width="400" height="250" style="margin: 10px;">
    <img src="https://github.com/lucasfernandoprojects/3d-printed-bluetooth-speaker/blob/main/photos/7.jpg" width="400" height="250" style="margin: 10px;">
</div>
</br>

## How to Build It Yourself
1. **Download the STL files** from this repository.
2. **Print the parts** using your 3D printer or an online printing service.
3. **Gather the electronic components** (see the full list above).
4. **Follow the wiring diagram** and solder the connections.
5. **Paint and assemble the enclosure**.
6. Enjoy your custom Bluetooth speaker!

## Files in This Repository
- /files/ - 3D printable files for the enclosure.
- /photos/schematics.png - Wiring diagrams for the electronics.

## Future Improvements
- **Better passive radiator selection** based on tuning frequency calculations.
- **Customizable enclosure options**, such as different sizes or shapes.

## Credits
- **Inspired by various DIY Bluetooth speaker projects**.
- **Special thanks to Off Earth for the wood texture painting technique**.

If you enjoyed this project, consider subscribing to [my YouTube channel](https://www.youtube.com/@lucasfernandochannel) for more DIY electronics builds! 🚀
