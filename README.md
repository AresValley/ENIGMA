<!-- PROJECT LOGO -->
<p align="center">
  <a href="https://github.com/AresValley/ENIGMA">
    <img src="img/logo.svg" alt="Logo" width="300">
  </a>
  <h3 align="center">ENIGMA I (Dora reflector)</h3>
  <p align="center">
Device number: 24b 656<br />
Year of manufacturing: 1943<br />
Chiffriermaschinen AG Heimsoeht & Rinke in Berlin-Wilmersdorf
  </p>
</p>

<!-- TABLE OF CONTENTS -->
- [Rack/Plug Board - Gestell/Steckerbrett](#rackplug-board---gestellsteckerbrett)
- [Reflector - Umkehrwalze (UKW)](#reflector---umkehrwalze-ukw)
  - [1. Complete Reflector](#1-complete-reflector)
  - [Wiring](#wiring)
- [Rotor - Walzensatz](#rotor---walzensatz)
  - [1. Rollbody](#1-rollbody)
  - [2. Clamp](#2-clamp)
  - [3. Complete Rotor](#3-complete-rotor)
  - [4. Rotors Stacking](#4-rotors-stacking)
  - [Wiring](#wiring-1)
- [Material Designation](#material-designation)
- [Acknowledgements](#acknowledgements)

<!-- ABOUT THE PROJECT -->
## About The Project <!-- omit from toc -->
This project was created to transfer the blueprints of every single component of an ENIGMA I cipher device in a digital format (.stl, in the future other formats will be available) useful for 3D printing and eventual production through Computer-aided manufacturing (CAM).

<!-- RACK -->
## Rack/Plug Board - Gestell/Steckerbrett
<div align="center">

| ID | Description | Material designation | Weight (Kg) |
| :--- | :----: | :---: | :---: |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rack/100001">100 001</a> | Bearing Block Left | <a href="#material-designation">S235JR</a> | 0.155 |
| 100 002 | ■ |  |  |
| ... | ... | ... | ... |
| 100 073 | ■ |  |  |

</div>

<!-- REFLECTOR -->
## Reflector - Umkehrwalze (UKW)
The **reflector** known as the **reversing drum** or, from the German, the **Umkehrwalze** (or **UKW**) is a fixed wiring mechanism within the Enigma machine. After the input character is encoded by passing through a series of rotating cipher wheels (known as rotors, see below), the signal would then be sent to the Reflector and back to rotors again. Instead of producing a new letter substitution, the Reflector's purpose was to create a reciprocal mapping of letters, effectively ensuring that the encryption process is symmetric. This means that if a letter "A" was encrypted as "D," the decryption process would reverse this, decrypting "D" back to "A". Enigma can then be used to both encrypt or decrypt a message using the same initial settings. Unfortunately, incorporating a reflector into the system introduces an encryption vulnerability: the encrypted version of a given letter can never be that letter itself.

### 1. Complete Reflector

<img src="img/reflector_exp.webp" alt="reflector">

<div align="center">

| POS | Part Nr | Name | Material designation | Weight (Kg) |
| :---: | :---: | :---: | :---: | :---: |
| 1 | <a href="https://github.com/AresValley/ENIGMA/tree/master/reflector/300009">300 009</a> | Axle | <a href="#material-designation">S235JR</a> | 0.0004 |
| 2 | <a href="https://github.com/AresValley/ENIGMA/tree/master/reflector/300002">300 002</a> | Cabinet | <a href="#material-designation">MATERIAL</a> | 0.1364 |
| 3 | | Countersink M2 x 4 | |
| 4 | | Countersink M3 x 6 | |
| 5 | <a href="https://github.com/AresValley/ENIGMA/tree/master/reflector/300003">300 003</a> | Wedge Holder | <a href="#material-designation">S235JR</a> | 0.0529 |
| 6 | <a href="https://github.com/AresValley/ENIGMA/tree/master/reflector/300004">300 004</a> | Wedge | <a href="#material-designation">S235JR</a> | 0.0096 |
| 7 | | Countersink M3 x 5 | |
| 8 | | Screw M1.6 x 4 | |
| 9 | <a href="https://github.com/AresValley/ENIGMA/tree/master/reflector/300008">300 008</a> | Isolator Plate | <a href="#material-designation">PA6 (Black)</a> | 0.0002 |
| 10 | <a href="https://github.com/AresValley/ENIGMA/tree/master/reflector/300005">300 005</a> | Blank | <a href="#material-designation">CuZn40</a> | 0.0003 |
| 11 
| 12 
| 13 
| 14 | <a href="https://github.com/AresValley/ENIGMA/tree/master/reflector/300001">300 001</a> | Reverse Roll | <a href="#material-designation">PA6 (Black)</a> | 0.0044 |
| 15 | <a href="https://github.com/AresValley/ENIGMA/tree/master/reflector/300007">300 007</a> | Screw Plate | <a href="#material-designation">S235JR</a> | 0.0001 |
| 16 | <a href="https://github.com/AresValley/ENIGMA/tree/master/reflector/300006">300 006</a> | Bushing | <a href="#material-designation">CuZn40</a> | 0.0019 |
| 17 
| 18 
| 19 
| 20 | | Countersink M3x8 | |

</div>

<!-- REFLECTOR WIRING -->
### Wiring

<!-- ROTORS -->
## Rotor - Walzensatz 
<div align="center">

| ID | Description | Material designation | Weight (Kg) |
| :--- | :----: | :---: | :---: |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400001">400 001</a> | Kerfring | <a href="#material-designation">S235JR</a> | 0.0169 |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400002">400 002</a> | Digitring | <a href="#material-designation">X12Cr13</a> | 0.1130 |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400003">400 003</a> | Bushing | <a href="#material-designation">S235JR</a> | 0.0540 |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400004">400 004</a> | Roll Shaft | <a href="#material-designation">S235JR</a> | 0.0270 |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400005">400 005</a> | Bracket | <a href="#material-designation">S235JR</a> | 0.0020 |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400006">400 006</a> | Clamp | <a href="#material-designation">38Si7</a> | 0.0013 |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400007">400 007</a> | Pin | <a href="#material-designation">S235JR</a> | 0.0004 |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400008">400 008</a> | ■ | <a href="#material-designation">MATERIAL</a> | 0.0xxx |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400009">400 009</a> | ■ | <a href="#material-designation">MATERIAL</a> | 0.0xxx |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400010">400 010</a> | Contact Die | <a href="#material-designation">CuZn40</a> | 0.0001 |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400011">400 011</a> | Rollplate | <a href="#material-designation">PA6</a> | 0.0090 |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400012">400 012</a> | ■ | <a href="#material-designation">MATERIAL</a> | 0.0xxx |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400013">400 013</a> | ■ | <a href="#material-designation">MATERIAL</a> | 0.0xxx |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400014">400 014</a> | Toothed Wheel | <a href="#material-designation">S235JR</a> | 0.1140 |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400015">400 015</a> | ■ | <a href="#material-designation">MATERIAL</a> | 0.0xxx |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400016">400 016</a> | Contact Pin | <a href="#material-designation">CuZn40</a> | 0.0003 |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400017">400 017</a> | ■ | <a href="#material-designation">MATERIAL</a> | 0.0xxx |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400018">400 018</a> | Spring Pin | <a href="#material-designation">CuZn40</a> | 0.0003 |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400019">400 019</a> | ■ | <a href="#material-designation">MATERIAL</a> | 0.0xxx |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400020">400 020</a> | ■ | <a href="#material-designation">MATERIAL</a> | 0.0xxx |
| <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400021">400 021</a> | ■ | <a href="#material-designation">MATERIAL</a> | 0.0xxx |

</div>

### 1. Rollbody

### 2. Clamp

<img src="img/clamp_exp.webp" alt="reflector">

<div align="center">

| POS | Part Nr | Name | Material designation | Weight (Kg) |
| :---: | :---: | :---: | :---: | :---: |
| 1 | <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400006">400 006</a> | Clamp | <a href="#material-designation">38Si7</a> | 0.0013 |
| 2 | <a href="https://github.com/AresValley/ENIGMA/tree/master/rotors/400007">400 007</a> | Pin | <a href="#material-designation">S235JR</a> | 0.0004 |
| 3 | <a href="https://github.com/AresValley/ENIGMA/tree/master/reflector/400008">400 008</a> | ■ | <a href="#material-designation">S235JR</a> | 0. |

</div>

### 3. Complete Rotor

### 4. Rotors Stacking

<!-- ROTORS WIRING -->
### Wiring

<!-- MD -->
## Material Designation

### S235JR <!-- omit from toc -->
**S235JR** is a European standard non-alloy, low carbon, manganese-containing structural steel commonly supplied in the untreated or normalised condition. It is easy to weld and bend. Similar desginations are: **SS1312**, **1.0038**, **Fe 360 BFN**, **RSt37-2**, **40 B**, **SB1312**, **IM2191**.

### X12Cr13 <!-- omit from toc -->
Martensitic grade chromium steel which exhibits good mechanical properties coupled with good corrosion resistance in moderately corrosive environments. It is used for the production of components working in contact with water and steam. It exhibits very good resistance to adipic, arsenic, benzoic, boric, maleic, gallic, and malic acid, or at low temperatures or concentrations to: nitric, chromic, gallotannic, carbolic, barium, aluminum, and potassium acids, and ammonium hydroxide. It is not resistant to salts and sulfur compounds. It does not exhibit significant strength properties compared to conventional structural steels due to its relatively low carbon content, but unlike steels with a higher carbon content, it is more resistant to corrosion.

### 38Si7 <!-- omit from toc -->
Spring steel used in quenched and tempered condition. It is used for spring rings, spring plates, screw locks and load securing devices. 

### CuZn40 <!-- omit from toc -->
A copper-zinc alloy with a duplex alpha-plus-beta phase structure and excellent hot-working properties. Service environment must be considered to predict corrosion behaviour. **CuZn40** has somewhat better cold-working and joining properties, but is less readily machined, than the similar low-leaded alloy **CuZn40Pb**. The most commonly used wrought forms are plate, rod and sections/shapes.

### PA6 <!-- omit from toc -->
Polyamide 6, also known as Nylon 6 is a widely used industrial polymer. Nylon 6 fibres are tough, possessing high tensile strength, as well as elasticity and lustre. They are wrinkleproof and highly resistant to abrasion and chemicals such as acids and alkalis.

### POM-C <!-- omit from toc -->
Polyacetal, also commonly known as acetal or polyoxymethylene, is a formaldehyde-based, semi-crystalline engineering thermoplastic. It is widely used in the production of precision parts for applications demanding good dimensional stability and sliding properties. The polymer serves as an alternative to metals due to its low friction and wear characteristics as well as its excellent balance of mechanical and chemical properties.

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements