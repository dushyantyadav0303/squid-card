<h1 align="center">
  <br>
  <img width=20% alt="logo" src="https://github.com/user-attachments/assets/47dd5c37-2a05-4650-8d7d-947d18e880b3" />

  <br>
 Squid card
  <br>
</h1>


<div align="center">

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Project](https://img.shields.io/badge/Project-Hardware-yellow.svg)
![Series](https://img.shields.io/badge/Series-Converter-red.svg)
![Devlog](https://img.shields.io/badge/Devlog-13Hr7min-blue)

</div>

<p align="center">
  <a href="#about-the-project">About</a> •
  <a href="#repository-structure">Structure</a> •
  <a href="#schematic-on-easyeda">Schematic</a> •
  <a href="#pcb-on-easyeda">PCB</a> •
  <a href="#cad">CAD</a> •
  <a href="#bill-of-materials">BOM</a> •
  <a href="#license">License</a> •
  <a href="#credits">Credits</a>
</p>

<br>
<br>
<p align=center>
<img src="https://github.com/user-attachments/assets/dc91abca-dbaf-45ba-8aa7-b416cdc9381c" alt="Banner" width=80%/>
</p>



## About the Project

**Squid card** - it is PCB Business card with NFC in Squid game theme.

### Features

- **Programmable NFC**
- **Led Indicators**

## Repository Structure

- `src/PCB/` — EasyEDA project sources
- `production/pcb/` — PCB fabrication files (Gerbers, BOM, Pick & Place)


## Schematic on EasyEDA

Source : `src/PCB/Systematic/`  

<img width=90% alt="SCH_Schematic1_1-P1_2026-05-15 (1)" src="https://github.com/user-attachments/assets/d3c94810-2d41-4e03-89c6-90e2d68b6bbf" />



## PCB on EasyEDA

Source : `src/PCB/Board/`  

<div align="center">
  <table>
    <tr>
      <td valign="bottom"><img width=90% alt="image" src="https://github.com/user-attachments/assets/453fe05b-f1fe-4f30-bc80-5c516fdab79a" />

</td>
      <td valign="bottom"><img width=120% alt="image" src="https://github.com/user-attachments/assets/913aad31-66fa-4f28-b856-89e99b39654e" />

</td>
  </table>
</div>
<div align="center">
  <table>
    <tr>
      <td valign="bottom"><img width=90% alt="image" src="https://github.com/user-attachments/assets/b974a31e-b422-4460-85e1-9b4fcb1b2508" />

</td>
      <td valign="bottom"><img width=120% alt="image" src="https://github.com/user-attachments/assets/29e51aa2-1db7-4a70-91d6-d4ffcd0bf44e" />

</td>
  </table>
</div>

### Render

<div align="center">
  <table>
    <tr>
      <td valign="bottom"><img width=90% alt="image" src="https://github.com/user-attachments/assets/eff4067e-14e1-4b03-973c-d758ab19d944" />
</td>
      <td valign="bottom"><img width=120% alt="image" src="https://github.com/user-attachments/assets/09ca45ad-32f1-41fc-b2ac-799e1c3d2940" />
  </td>
  </table>
</div>

- source: `src/3D model/`  

## Bill of Materials

Source: `production/pcb/bom.csv`

|No.|Quantity|Comment                              |Designator|Footprint                               |Value   |LCSC Price|Link to buy|
|---|--------|-------------------------------------|----------|----------------------------------------|--------|----------|-----------|
|1  |1       |13.56MHz                             |U1        |XQFN-8_L1.6-W1.6-P0.50-BL_NT3H2111W0FHKH|13.56MHz|2.7$      |[BUY](https://www.lioncircuits.com/parts/NT3H2111W0FHKH)|
|2  |1       |220nF                                |C1        |C0603                                   |220nF   |0.05$    |[Buy](https://robu.in/product/cl21b104kcc5pnc-samsung-cap-ceramic-0-1uf-100v-x7r-10-pad-smd-0805-omd-cap-125c-automotive-aec-q200-t-r/)|
|3  |1       |KT-0603R                             |LED1      |LED-SMD_L1.6-W0.8-R-RD                  |        |0.07$         |[BUY](https://robu.in/product/xl-2012vrc-xinglight-5ma-90mcd-red-lens-615nm630nm-positive-stick-red-120-75mw-2-7v3-3v-0805-led-indication-discrete-rohs/)|
|4  |1       |PCB                             |       |         |9.5$      |[BUY](https://robu.in/product/online-pcb-manufacturing-service/)|


## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions, improvements, and remixes are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) guide to get started.



## Credits

This project uses:

- **EasyEDA** - PCB design and schematic capture
- **[Jutebox](https://www.jukeboxprint.com/blog/the-making-of-the-squid-game-business-card)** for Squid game card All dimensions
- **[@NotARoomba](https://github.com/notaroomba) & [@Gabouin](https://github.com/Gabouin)** - Readme template
