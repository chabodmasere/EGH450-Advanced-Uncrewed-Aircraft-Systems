<h1 align="center">EGH450 Advanced Uncrewed Aircraft Systems</h1>

<p align="center">
  <strong>A quadrotor, from thrust stand to printed hardware.</strong><br>
  Airframe, power and propulsion subsystem work at the Queensland University of Technology.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Result-High%20Distinction-b4632f" alt="Result: High Distinction">
  <img src="https://img.shields.io/badge/CAD-Fusion%20360-555" alt="CAD: Fusion 360">
  <img src="https://img.shields.io/badge/FEA-ANSYS%20Workbench-555" alt="FEA: ANSYS Workbench">
  <img src="https://img.shields.io/badge/Made%20with-3D%20printing-555" alt="Made with 3D printing">
</p>

<p align="center">
  <img src="images/hero.jpg" width="760" alt="The quadrotor with a bronze printed cover, blue arm mounts and carbon-fibre arms">
</p>

<table align="center">
  <tr>
    <td align="center"><h3>3.4 kgf</h3>total peak thrust, four motors at 12 V</td>
    <td align="center"><h3>15 → 6 gf/W</h3>efficiency, idle to full throttle</td>
    <td align="center"><h3>5</h3>printable enclosure files</td>
    <td align="center"><h3>2</h3>ANSYS studies: static and modal</td>
  </tr>
</table>

## How it came together

| When | Milestone |
| --- | --- |
| **23 April 2025** | Motor and propeller characterised on a thrust stand |
| **July 2025** | Assembled with closed printed enclosures |
| **October 2025** | Rebuilt around honeycomb enclosures |

Dates come from the bench test log and the photo timestamps.

## The July build

Carbon-fibre arms, blue printed arm mounts, foam-wrapped landing skids and a bronze printed shell.

<table>
  <tr>
    <td width="33%"><img src="images/july-front.jpg" alt="Front view of the July build"></td>
    <td width="33%"><img src="images/july-top.jpg" alt="View from above, showing all four motors"></td>
    <td width="33%"><img src="images/july-low.jpg" alt="Low front view with the landing skids"></td>
  </tr>
  <tr>
    <td align="center"><sub>Front</sub></td>
    <td align="center"><sub>From above</sub></td>
    <td align="center"><sub>From below the arms</sub></td>
  </tr>
</table>

The cover lifts off for access to the electronics.

<table>
  <tr>
    <td width="50%"><img src="images/july-open.jpg" alt="Cover lifted to show the electronics inside"></td>
    <td width="50%"><img src="images/july-detail.jpg" alt="Close-up of the printed cover and antennas"></td>
  </tr>
  <tr>
    <td align="center"><sub>Cover off</sub></td>
    <td align="center"><sub>Printed shell up close</sub></td>
  </tr>
</table>

## The October build: honeycomb

By October the closed boxes had given way to honeycomb walls, which cut mass, let air through and leave the wiring easy to reach.

<table>
  <tr>
    <td width="33%"><img src="images/1.jpeg" alt="Front view of the October build"></td>
    <td width="33%"><img src="images/2.jpeg" alt="The October build from above"></td>
    <td width="33%"><img src="images/6.jpeg" alt="Side view showing the enclosures under the airframe"></td>
  </tr>
  <tr>
    <td align="center"><sub>Front</sub></td>
    <td align="center"><sub>From above, cover on</sub></td>
    <td align="center"><sub>Enclosures under the airframe</sub></td>
  </tr>
  <tr>
    <td colspan="2"><img src="images/4.jpeg" alt="Printed battery enclosure with the battery strapped in"></td>
    <td><img src="images/5.jpeg" alt="Honeycomb enclosure fitted to the airframe"></td>
  </tr>
  <tr>
    <td colspan="2" align="center"><sub>Battery strapped into its sleeve</sub></td>
    <td align="center"><sub>Honeycomb enclosure on the airframe</sub></td>
  </tr>
</table>

## Printed parts

Each STL is a print plate, so most files hold two parts: a long slotted sleeve and a small box.

<table>
  <tr>
    <td align="center"><img src="images/parts/battery_case.gif" width="260" alt="Rotating model of battery_case.stl"></td>
    <td align="center"><img src="images/parts/final.gif" width="260" alt="Rotating model of final.stl"></td>
    <td align="center"><img src="images/parts/3D_Print.gif" width="260" alt="Rotating model of 3D_Print.stl"></td>
  </tr>
  <tr>
    <td align="center"><code>battery_case.stl</code><br><sub>Slotted sleeve and closed-wall box</sub></td>
    <td align="center"><code>final.stl</code><br><sub>Slotted sleeve and honeycomb box</sub></td>
    <td align="center"><code>3D_Print.stl</code><br><sub>Two honeycomb-walled enclosures</sub></td>
  </tr>
</table>

| File | Plate size (mm) | What's on the plate |
| --- | --- | --- |
| `battery_case.stl` | 244 × 172 × 92 | Slotted sleeve and closed-wall box |
| `final.stl` | 310 × 260 × 108 | Slotted sleeve and honeycomb box |
| `pi_case.stl` | 310 × 260 × 108 | Variant of `final.stl` with a different cut-out pattern |
| `raspberry_pi_case.stl` | 310 × 260 × 108 | Second variant of `final.stl` with a different cut-out pattern |
| `3D_Print.stl` | 102 × 158 × 114 | Two honeycomb-walled enclosures |

Sizes are the bounding box of the whole file, not of a single part.

<p align="center">
  <img src="images/8.png" width="46%" alt="CAD of the honeycomb enclosure">
  <img src="images/9.png" width="46%" alt="CAD of an enclosure with mounting rails">
</p>

## Airframe

The airframe was modelled in Fusion 360 and analysed in ANSYS Workbench (2019 R3) with a static structural study and a modal study.

<p align="center">
  <img src="images/7.png" width="48%" alt="CAD model of the airframe">
  <img src="images/10.png" width="40%" alt="Top view of the airframe CAD">
</p>

| File | Contents |
| --- | --- |
| `STATIC TEST.f3d` | Fusion 360 design used for the static test |
| `Airframe_Analysis.wbpj` | ANSYS Workbench project with the static structural and modal systems |

Only the Workbench project file is included, not its data folder, so the file records the analysis setup but will not reopen the mesh or results on its own.

## Propulsion: what the thrust stand showed

<p align="center">
  <img src="images/bench-test.svg" width="820" alt="Thrust rises from 0.05 to 0.85 kgf while efficiency falls from 15.2 to 6.1 gram-force per watt between 1200 and 2000 microseconds">
</p>

More throttle buys thrust at a falling return, so hovering well below full throttle is what buys endurance.

- **Peak thrust is about 0.85 kgf per motor**, or roughly 3.4 kgf across four motors at this supply voltage.
- **The ESC saturates at 2000 µs.** The 2100 µs step produces the same thrust and current.
- **The three sweeps repeat closely**, with peak thrust within 0.005 kgf of each other.
- **Supply voltage sags** from 12.1 V to 11.9 V at full current.

<details>
<summary><strong>Test method and full results</strong></summary>

<br>

`Motor_bench_test.xls` is a stepped throttle test of one motor and propeller on a thrust stand, recorded on 23 April 2025. The ESC signal was stepped from 900 µs to 2100 µs in 100 µs steps, holding each step for 3.5 s, and the sweep was repeated three times from a 12 V supply. The log records thrust, torque, voltage, current, electrical power and vibration. The two motor speed columns were not recorded and read zero.

Averages across the three sweeps:

| ESC signal (µs) | Thrust (kgf) | Current (A) | Electrical power (W) | Thrust per watt (gf/W) |
| ---: | ---: | ---: | ---: | ---: |
| 1200 | 0.05 | 0.28 | 3.4 | 15.2 |
| 1400 | 0.18 | 1.31 | 15.8 | 11.1 |
| 1600 | 0.37 | 3.47 | 41.8 | 8.8 |
| 1800 | 0.61 | 7.10 | 85.1 | 7.2 |
| 2000 | 0.85 | 11.77 | 139.9 | 6.1 |

</details>

## How the subsystems trade off

Every choice here feeds back into the others: a bigger battery adds endurance, but its mass pushes the hover point up the less efficient end of the thrust curve.

```mermaid
flowchart LR
    A["Airframe and enclosure mass"] --> B["Thrust needed to hover"]
    B --> C["Current draw, from the bench test"]
    C --> D["Endurance for a given battery"]
    D --> E["Battery size"]
    E -->|"more mass"| A
```

## Tools

| Tool | Used for |
| --- | --- |
| Fusion 360 | CAD of the airframe and enclosures |
| ANSYS Workbench | Static structural and modal analysis |
| 3D printing | Enclosures and airframe parts |
| Thrust stand and Excel | Motor bench testing and data |

## Author

**Chabod Masere**

🎓 Master of Robotics and Artificial Intelligence
<br>
🎓 Bachelor of Engineering, Electrical & Aerospace
