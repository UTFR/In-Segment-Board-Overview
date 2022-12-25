# Temperature-Motherboard-Overview
By: Ayrton Antenucci, Electric Powertrain Lead, University of Toronto Formula Racing

Each year, the University of Toronto Formula Racing Team (UTFR) designs and builds a car to compete in international Formula SAE (Formula Student) events. As such, the team must ensure all elements of the vehicle, including the electric powertrain, comply entirely with Formula SAE regulations. This article will discuss the 'In-Segment PCBs responsible for voltage tap and temperature measurement harnessing. All of UTFR’s boards are fabricated in collaboration with JLCPCB (www.jlcpcb.com/RAT), a leading PCB manufacturer providing high quality, reliable, and cost-effective PCBs at a consistently rapid pace.

## Purpose and Functionality

As per Formula SAE (FSAE) regulations, the temperature of at least 30% of the cells within the accumulator must be monitored at all times. In addition, UTFR's battery mangement system (BMS) must directly monitor the voltage of each cell in the battery pack through 'voltage taps'. The in-segment PCBs are responsible for harnessing and interfacing all cells in the battery pack with the BMS by providing electrical connections to the Energus cell modules' terminals and temperature sensors used in the accumulator.

## Schematic and PCB Design

The schematic and layout of the In-Segment Boards were designed using Altium Designer, and is shown below. Given that the primary purpose of the board is to harness signals, it is electrically quite simple. The board features fuses for all voltage tap connections and designated temperature and voltage tap connectors for the BMS.

<img width="729" alt="Screenshot 2022-12-24 at 9 43 48 PM" src="https://user-images.githubusercontent.com/88075549/209455627-cb684b82-d4dc-4f9c-8ec3-eee70329c59c.png">

The In-Segment boards' layout is largely mechanically focused, as shown below. They are designed to rest on top of the cells within the accumulator whilst allowing room for further mechanical components such as busbars, positive locking mechanisms, and bolts. Holes through the centre allow JST connections to the Energus module temperature sensors, and plated holes allow bolted connections to cell terminals for voltage taps.

<img width="1016" alt="Screenshot 2022-12-24 at 9 45 02 PM" src="https://user-images.githubusercontent.com/88075549/209455712-06dbf508-79d4-484f-b92d-f8c2c5e4f9ed.png">

## Ordering and Fabrication

The Temperature Motherboard was manufactured with exceptional quality by JLCPCB within days of ordering. If desired, JLCPCB also offers professional SMT assembly with just a 24h turnaround time - more information can be found at www.jlcpcb.com/smt-assembly. The ordering process is remarkably simple:

<ol>
  <li> Export Gerber files of PCB project
  <li> Click ‘Order Now’ on www.jlcpcb.com
  <li> Upload Gerber files, confirm generated PCB requirements and preferences (including SMT assembly)
  <li> Once all PCBs are saved to cart, proceed to checkout.
<ol>
