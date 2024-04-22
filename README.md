# The Kakuhomaru Bridge Pickup for Electric Violins 

The Kakuho-Maru (角宝丸) bridge is a piezoelectric pickup for electric violins featuring a ‘one-sensor-per-string’ design, ensuring each note you play is captured with clarity and richness. 

Listen to the open string sample here:

https://github.com/penk/Kakuhomaru-bridge/assets/61878/6f59927d-60b6-4801-80bd-5c879a68bae8

## Bill of materials  

Each Kakuhomaru bridge is composed of 4 main parts:

- Piezoelectric rods and shielded cable (repurposed from guitar under-saddle pickup) 
- Custom printed circuit board (PCB) with castellated holes 
- Semi-rigid electronically conductive foam (30 Ohm m) 
- 3D printable case

While some parts may require a few days of lead time, the assembly is straightforward and DIY-friendly once all components are in hand.

## Ordering the PCB

To get started with your custom PCB, upload the production file to the PCB manufacturer of your choice, such as JLCPCB or PCBWay. Please ensure you select the option for `Castellated Holes` — this is vital for the functionality of our bridge pickup.

Below are the specific settings I used for our prototype: 
```
PCB Thickness: 1.6 mm 
Castellated Holes: yes
Edges: 2
```
## Assembly Instructions 

- Step 1: Glue the Piezoelectric Rods 
- Step 2: Solder the Shielded Cable & Insert the Conductive Foam
- Step 3: Close the Protective Cover 

## Setting up 

The PCB is designed with a solid ground plane, eliminating the need for copper shielding tape. However, it is important to establish a grounding connection. This can be done by connecting the shielded cable to the tuning pegs (if applicable) or the strings, depending on your setup.

For the bridge feet, proceed with your usual sanding process to ensure a proper fit. Additionally, mark the grooves along the edge of the PCB with a pencil to facilitate smooth sliding of the strings.

## Further Customization

For those looking to tailor the bridge pickup to different sizes or heights, an editable STEP file is available. This file allows you to make precise adjustments to the bridge to perfectly fit your instrument's unique specifications.

Additionally, if your setup requires a pickup for five or more strings, you can take advantage of the fully editable KiCad project. This project includes a DXF outline, enabling you to design and customize your PCB to accommodate the specific needs of multi-string electric violins.
