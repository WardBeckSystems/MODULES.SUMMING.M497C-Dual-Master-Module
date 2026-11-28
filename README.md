# M497C Dual Master Module · Summing

Ward-Beck Systems M497C, 1978|11. Wiki page: [M497C on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M497C.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 61 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 6 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 6 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 190 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 16 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 37 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1978 - M497C - P003 - 1-1.jpg](MANUALS/1978%20-%20M497C%20-%20P003%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | 8 dB nominal +18 dB +/-0.5 dB maximum: Trim control is provided. |
| **Frequency response** | +/-0.2 dB from 20 Hz to 20 kHz (tailored frequency response). |
| **Noise** | 75 dB below +8 dBm nominal output level (20 Hz to 20 kHz) |
| **Harmonic distortion** | Less than 0.059 THD from 30 Hz to 20 kHz at +24 dBm output or less_ Less than 0.019 at kHz at +27 dBm output: |
| **Source impedances** | Summing: External: 30,000 ohms balanced 600 ohms maximum balanced. [nput Impedances: Summing: External: |
| **Less than ohms** | 30,000 ohms |
| **Input level** | External: dBm nominal, +16 dBm maximum |
| **Output impedances** | Program: Monitor: Mono: 60 ohms, balanced_ ohms; balanced_ 36,000 ohms balanced |
| **Load impedances** | Program: Monitor: Mono: 600 Ohms; balanced (minimum) Bridging, balanced (SK ohms minimum) Summing, less than ohms balanced: |
| **Output level** | Program: Monitor; Mono: +8 dBm nominal, +28 dBm maximum (into one 600 ohm load). +8 dBm nominal_ +28 dBm maximum dBm nominal when summed into second M497C. |
| **Channel separation** | 60 dB between Left and Right channels (50 Hz to 15 kHz). |
| **Phasing** | Input and output terminals designated phase. numbers are |
| **Power requirements** | +/-25 volts dc, 50 mA nominal, 200 mA maximum Ambient Temperature: to 60 degrees Celsius Dimensions: 6&quot; wide x 7.0&quot; high x 6.5&quot; deep: (41 mm 178 mm 165 mm) |

## Circuit description

From [1978 - M497C - P004 - 2-1.jpg](MANUALS/1978%20-%20M497C%20-%20P004%20-%202-1.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M497C accommodates two separate signal channels It is designed to receive the mixed feeds from the left and right mixer buses console The two signals are independently processed and amplified standard line levels: The outputs of the M497C supply the main program outputs the console system Both channels operate similar manner. The following description refers specifically to thc LEFT channel, loss the input network and provides additional gain produce nominal line level of +8 dBm the output the module: ohm resistive dividing network inserted between the 8-109E and the IWo module outputs pins 12/N and [3/P Each of the two outputs has maximum drive capability of +24 dBm into bridging load_ Input A separate MONITOR output is provided_ designed feed the M495 STEREO MONITOR module as well as to drive standard VU meter The signal originating from the external mixing network enters the module pins 1/A and is applied to the summing current nodes of ZI and Z2. ZI through 23 with their associated components, providean actively balanced input well balanced output: The output operates at nominal level of 0 dBm and appears at pins 6/F Right ChanncLand MONQ Output The right channel of the M497 operates manner similar [0 the left channel a5 described above: For the MONO output, both channels are combined and appear at pins M/M The signal Icvcl of this output i5 such that; when connected the summing input of second M497, it will produce output of +8 dBm, with the left right channel of the first unit operating at +8 dBm_ Insert balanced INSERT point is provided between pins 6/F and 8/J_ permitting the insertion external cqualizer_ filter compressor_ either using M499 insert switcher Or by direct wiring: Level_Adjustment Power_Supply_Decoupling From the INSERT point; thc signal returned the module at pins 8/J and fed the 8-109E output amplifier via attenuator network: R42 level trim potentiometer permitting adjustment the module output level: small hole in thc module front panel allows access to the trim control. An active power supply decoupling network consisting of Q1 through provides isolation between the module and the +/-25 volt supply rails: Transistors Q3 and Q6 monitor the supply current: In the event of excessive power supply demands, such as from component failure or amplifier overdrive, the currcnt flowing through QI and Q4 will be limited. Outline Thc 8-109E output amplifier operates with gain dB. It recovers the

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNS1IZF9qWGRzS0U/view?resourcekey=0-GuB2qv206pV4h-XbFdVm3g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNS1IZF9qWGRzS0U&resourcekey=0-GuB2qv206pV4h-XbFdVm3g" width="240" alt="1978 - M497C - 497-04-006 - DUAL MASTER MODULE FRONT PANEL.jpg"></a><br><sub>1978|11 · 497-04-006 - DUAL MASTER MODULE FRONT PANEL · <a href="MECHANICAL/1978%20-%20M497C%20-%20497-04-006%20-%20DUAL%20MASTER%20MODULE%20FRONT%20PANEL%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M497C.stl`](MECHANICAL/M497C.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M497C)

- **Size:** 54.19 × 211.58 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 4 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M497C - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M497C.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWHRON2R3Qnd6UGc/view?resourcekey=0-Dz7W1elLdyo4x5miUztJyw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWHRON2R3Qnd6UGc&resourcekey=0-Dz7W1elLdyo4x5miUztJyw" width="240" alt="1978 - M497C - 497-01-004 - DUAL MASTER MODULE FUNCTIONAL DIAGRAM.jpg"></a><br><sub>1978|11 · 497-01-004 - DUAL MASTER MODULE FUNCTIONAL DIAGRAM · <a href="SCHEMATICS/1978%20-%20M497C%20-%20497-01-004%20-%20DUAL%20MASTER%20MODULE%20FUNCTIONAL%20DIAGRAM%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS1JYcU03MEl2TWc/view?resourcekey=0-ITqDbDRPvDVFWPNhx6p3zA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS1JYcU03MEl2TWc&resourcekey=0-ITqDbDRPvDVFWPNhx6p3zA" width="240" alt="1978 - M497C - 497-01-004 - OHMS LEFT LEVEL INSERT.jpg"></a><br><sub>1978|11 · 497-01-004 - OHMS LEFT LEVEL INSERT · <a href="SCHEMATICS/1978%20-%20M497C%20-%20497-01-004%20-%20OHMS%20LEFT%20LEVEL%20INSERT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1czOHZDNDAtdnM/view?resourcekey=0-PuoZMfwzZGWXIJNhtpOFbA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1czOHZDNDAtdnM&resourcekey=0-PuoZMfwzZGWXIJNhtpOFbA" width="240" alt="1978 - M497C - 497-02-003 - NOT USD SHORT PINS IIM TOGETER LEFT OUTPUTS.jpg"></a><br><sub>1978|11 · 497-02-003 - NOT USD SHORT PINS IIM TOGETER LEFT OUTPUTS · <a href="SCHEMATICS/1978%20-%20M497C%20-%20497-02-003%20-%20NOT%20USD%20SHORT%20PINS%20IIM%20TOGETER%20LEFT%20OUTPUTS%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNURKdFQwY2pLZFk/view?resourcekey=0-HmJ7J78LmJMUw8ZK9tE0fQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNURKdFQwY2pLZFk&resourcekey=0-HmJ7J78LmJMUw8ZK9tE0fQ" width="240" alt="1978 - M497C - 497-02-003 - SOT SOT REE CRI TIP.jpg"></a><br><sub>1978|11 · 497-02-003 - SOT SOT REE CRI TIP · <a href="SCHEMATICS/1978%20-%20M497C%20-%20497-02-003%20-%20SOT%20SOT%20REE%20CRI%20TIP%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS2FYemdQSVdEYTA/view?resourcekey=0-2LOgwB6wmroSo0_umo2JNg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS2FYemdQSVdEYTA&resourcekey=0-2LOgwB6wmroSo0_umo2JNg" width="240" alt="1978 - M497C - 497-02-003.jpg"></a><br><sub>1978|11 · 497-02-003 · <a href="SCHEMATICS/1978%20-%20M497C%20-%20497-02-003%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWnJ0U0ljYkhfVjA/view?resourcekey=0-UXVjdluxaklBLcSIU2Hd_Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWnJ0U0ljYkhfVjA&resourcekey=0-UXVjdluxaklBLcSIU2Hd_Q" width="240" alt="1978 - M497C - 497-06-004 - ISSU IDATE MVBOR.jpg"></a><br><sub>1978|11 · 497-06-004 - ISSU IDATE MVBOR · <a href="SCHEMATICS/1978%20-%20M497C%20-%20497-06-004%20-%20ISSU%20IDATE%20MVBOR%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOHJQOWNfS3dHa3c/view?resourcekey=0-j5qiJb5Rll4y7lnbzU9GZA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOHJQOWNfS3dHa3c&resourcekey=0-j5qiJb5Rll4y7lnbzU9GZA" width="240" alt="1978 - M497C - 497-06-004 - LEFT FFRBU.jpg"></a><br><sub>1978|11 · 497-06-004 - LEFT FFRBU · <a href="SCHEMATICS/1978%20-%20M497C%20-%20497-06-004%20-%20LEFT%20FFRBU%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTnBYT1pNenpLU0U/view?resourcekey=0-wZkSnIt5QbNOZYv1oB0JOQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTnBYT1pNenpLU0U&resourcekey=0-wZkSnIt5QbNOZYv1oB0JOQ" width="240" alt="1978 - M497C - 497-06-004.jpg"></a><br><sub>1978|11 · 497-06-004 · <a href="SCHEMATICS/1978%20-%20M497C%20-%20497-06-004%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSTBsQU95SWdpNU0/view?resourcekey=0-ncXmewNHkAvzql0wLC9xiQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSTBsQU95SWdpNU0&resourcekey=0-ncXmewNHkAvzql0wLC9xiQ" width="240" alt="1978 - M497C - 8-109-02-006 - REVISION NOMINAL VALUE.jpg"></a><br><sub>1978|11 · 8-109-02-006 - REVISION NOMINAL VALUE · <a href="SCHEMATICS/1978%20-%20M497C%20-%208-109-02-006%20-%20REVISION%20NOMINAL%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0JLM1gyVmVSd0k/view?resourcekey=0-6HuoOTC-IdFAaiqAHUj2_A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0JLM1gyVmVSd0k&resourcekey=0-6HuoOTC-IdFAaiqAHUj2_A" width="240" alt="1978 - M497C - 8-109-02-006 - RII RIZ.jpg"></a><br><sub>1978|11 · 8-109-02-006 - RII RIZ · <a href="SCHEMATICS/1978%20-%20M497C%20-%208-109-02-006%20-%20RII%20RIZ%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKanRZZ1Jnd28yUHc/view?resourcekey=0-dXb7yWrkgMDhNEQjBnNhbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKanRZZ1Jnd28yUHc&resourcekey=0-dXb7yWrkgMDhNEQjBnNhbw" width="240" alt="1978 - M497C - 8-109-06-006 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1978|11 · 8-109-06-006 - BOOSTER AMPLIFIER · <a href="SCHEMATICS/1978%20-%20M497C%20-%208-109-06-006%20-%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM3dMLWNLV3FBTWc/view?resourcekey=0-HgTvzoHxRh3V1Ms1MN0ZdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM3dMLWNLV3FBTWc&resourcekey=0-HgTvzoHxRh3V1Ms1MN0ZdQ" width="240" alt="1978 - M497C - 8-109-06-006.jpg"></a><br><sub>1978|11 · 8-109-06-006 · <a href="SCHEMATICS/1978%20-%20M497C%20-%208-109-06-006%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1nJeQ_Iu1uv8ogrX0tFetqlUTM2GrXESA/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1nJeQ_Iu1uv8ogrX0tFetqlUTM2GrXESA" width="240" alt="1992 - M497C - DOC - 920383-01-001 - MONITOR MQDULE SWTCHEO DIRECT FUTURE MONITOR OUTPUTS.jpg"></a><br><sub>1992|25 · DOC - 920383-01-001 - MONITOR MQDULE SWTCHEO DIRECT FUTURE MONITOR OUTPUTS · <a href="SCHEMATICS/1992%20-%20M497C%20-%20DOC%20-%20920383-01-001%20-%20MONITOR%20MQDULE%20SWTCHEO%20DIRECT%20FUTURE%20MONITOR%20OUTPUTS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1dzQuhcHLqZHYuCyZf_ADrXlexs0zpLmo/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1dzQuhcHLqZHYuCyZf_ADrXlexs0zpLmo" width="240" alt="1992 - M497C - DOC - 920477-01-001 - OHMS SWTCHED SSUE REMSION FUTURE FUTURE.jpg"></a><br><sub>1992|25 · DOC - 920477-01-001 - OHMS SWTCHED SSUE REMSION FUTURE FUTURE · <a href="SCHEMATICS/1992%20-%20M497C%20-%20DOC%20-%20920477-01-001%20-%20OHMS%20SWTCHED%20SSUE%20REMSION%20FUTURE%20FUTURE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/109KQyA72uuIDv0gHiqS2qh5Zof3KCBMs/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=109KQyA72uuIDv0gHiqS2qh5Zof3KCBMs" width="240" alt="2017 - M497C - DOC - 920170-01-001 - SWTCHED DIRECT MONITOR OUTPUTS DDZME.jpg"></a><br><sub>2017|50 · DOC - 920170-01-001 - SWTCHED DIRECT MONITOR OUTPUTS DDZME · <a href="SCHEMATICS/2017%20-%20M497C%20-%20DOC%20-%20920170-01-001%20-%20SWTCHED%20DIRECT%20MONITOR%20OUTPUTS%20DDZME%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M497C - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 27 of 27 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | LEFT SUM IN | in | SUM IN L | high |
| 2 | RIGHT SUM IN | in | SUM IN R | high |
| 3 | SHIELD | shield | shield | high |
| 4 | LEFT EXT IN | in | EXT IN L | high |
| 5 | RIGHT EXT IN | in | EXT IN R | high |
| 6 | LEFT PRE OUT | out | PRE OUT L | high |
| 7 | RIGHT PRE OUT | out | PRE OUT R | high |
| 8 | LEFT LEV CTL IN | control_in | LEV CTL IN L | high |
| 9 | RIGHT LEV CTL IN | control_in | LEV CTL IN R | high |
| 10 | SHIELD | shield | shield | high |
| 11 | MONO OUT | out | MONO OUT | high |
| 12 | LEFT OUT 1 | out | OUT 1 L | high |
| 13 | LEFT OUT 2 | out | OUT 2 L | high |
| 14 | LEFT MON OUT | out | MON OUT L | high |
| 15 | RIGHT OUT 1 | out | OUT 1 R | high |
| 16 | RIGHT OUT 2 | out | OUT 2 R | high |
| 17 | RIGHT MON OUT | out | MON OUT R | high |
| 18 | N/C | nc |  | high |
| 19 | -25 V | power |  | high |
| 20 | 25 V COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS | ground |  | high |
| A | LEFT SUM IN | in | SUM IN L | high |
| B | RIGHT SUM IN | in | SUM IN R | high |
| C | SHIELD | shield | shield | high |
| D | LEFT EXT IN | in | EXT IN L | high |
| E | RIGHT EXT IN | in | EXT IN R | high |
| F | LEFT PRE OUT | out | PRE OUT L | high |
| H | RIGHT PRE OUT | out | PRE OUT R | high |
| J | LEFT LEV CTL IN | control_in | LEV CTL IN L | high |
| K | RIGHT LEV CTL IN | control_in | LEV CTL IN R | high |
| L | SHIELD | shield | shield | high |
| M | MONO OUT | out | MONO OUT | high |
| N | LEFT OUT 1 | out | OUT 1 L | high |
| P | LEFT OUT 2 | out | OUT 2 L | high |
| R | LEFT MON OUT | out | MON OUT L | high |
| S | RIGHT OUT 1 | out | OUT 1 R | high |
| T | RIGHT OUT 2 | out | OUT 2 R | high |
| U | RIGHT MON OUT | out | MON OUT R | high |
| V | N/C | nc |  | high |
| W | N/C | nc |  | high |
| X | N/C | nc |  | high |
| Y | N/C | nc |  | high |
| Z | N/C | nc |  | high |

**Straps:** JMP.8.6: P2-8 P2-6 · JMP.F.J: P2-J P2-F · JMP.7.9: P2-7 P2-9 · JMP.H.K: P2-H P2-K

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT0xYSjBMTTFncEE/view?resourcekey=0-4OjAU-zlRuQgCQXv68ifZA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT0xYSjBMTTFncEE&resourcekey=0-4OjAU-zlRuQgCQXv68ifZA" width="240" alt="1978 - M497C - Dual Master Module (2).pdf"></a><br><sub>1978|11 · Dual Master Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbTJJeFF3czN6UEk/view?resourcekey=0-idV5KCFDKvgV7_JTNK50ug" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbTJJeFF3czN6UEk&resourcekey=0-idV5KCFDKvgV7_JTNK50ug" width="240" alt="1978 - M497C - Dual Master Module.pdf"></a><br><sub>1978|11 · Dual Master Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR2RtR1Vrb2RzUzg/view?resourcekey=0-7JlRoFY9hwiyZV5pF8pEjQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR2RtR1Vrb2RzUzg&resourcekey=0-7JlRoFY9hwiyZV5pF8pEjQ" width="240" alt="1978 - M497C - P001 - Title Page.jpg"></a><br><sub>1978|11 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWnF0ekUtb0EyeWs/view?resourcekey=0-_5O9Ea9dCtvUyf-_j6n3RA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWnF0ekUtb0EyeWs&resourcekey=0-_5O9Ea9dCtvUyf-_j6n3RA" width="240" alt="1978 - M497C - P002.jpg"></a><br><sub>1978|11 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUkpkZFNnajVGdE0/view?resourcekey=0-IWYaHpIPfC8assWzAx224Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUkpkZFNnajVGdE0&resourcekey=0-IWYaHpIPfC8assWzAx224Q" width="240" alt="1978 - M497C - P003 - 1-1.jpg"></a><br><sub>1978|11 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRXZPdkdRWkVucW8/view?resourcekey=0-AOcyLnlTJBD0za00v9UtVw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRXZPdkdRWkVucW8&resourcekey=0-AOcyLnlTJBD0za00v9UtVw" width="240" alt="1978 - M497C - P004 - 2-1.jpg"></a><br><sub>1978|11 · P004 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbmhydUpvaVVFcnM/view?resourcekey=0-StubIkjf7st4hxj1VVH7Pg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbmhydUpvaVVFcnM&resourcekey=0-StubIkjf7st4hxj1VVH7Pg" width="240" alt="1978 - M497C - P005 - 3-1.jpg"></a><br><sub>1978|11 · P005 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWlduZUo4aTBjTlk/view?resourcekey=0-k4g5cAIUXlvxP3nB0qLz1g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWlduZUo4aTBjTlk&resourcekey=0-k4g5cAIUXlvxP3nB0qLz1g" width="240" alt="1978 - M497C - P006 - 3-2.jpg"></a><br><sub>1978|11 · P006 - 3-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMUduNEU2cC1aWFE/view?resourcekey=0-fluL-zCfxrSH7aDUWWRYsw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMUduNEU2cC1aWFE&resourcekey=0-fluL-zCfxrSH7aDUWWRYsw" width="240" alt="1978 - M497C - P007 - 3-3.jpg"></a><br><sub>1978|11 · P007 - 3-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYlRaY1d1MkVnTWc/view?resourcekey=0-U15hYRJpz3GQw-_9srq7FQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYlRaY1d1MkVnTWc&resourcekey=0-U15hYRJpz3GQw-_9srq7FQ" width="240" alt="1978 - M497C - P008 - 4-1.jpg"></a><br><sub>1978|11 · P008 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWVE2TElBSnd2WFk/view?resourcekey=0-h3dZpnVNeSVB1AiuR5gUeQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWVE2TElBSnd2WFk&resourcekey=0-h3dZpnVNeSVB1AiuR5gUeQ" width="240" alt="1978 - M497C - P013.jpg"></a><br><sub>1978|11 · P013</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR0t2VEJZSUhzVXM/view?resourcekey=0-7q_c0kZEjqIEU1plruiYlA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR0t2VEJZSUhzVXM&resourcekey=0-7q_c0kZEjqIEU1plruiYlA" width="240" alt="1978 - M497C - P014 - 8-109.jpg"></a><br><sub>1978|11 · P014 - 8-109</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1VrOEoxcmM0Rm8/view?resourcekey=0-Lha0OH8tID5Aa0lydniIOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1VrOEoxcmM0Rm8&resourcekey=0-Lha0OH8tID5Aa0lydniIOw" width="240" alt="1978 - M497C - P015 - 8-109-1-1.jpg"></a><br><sub>1978|11 · P015 - 8-109-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWG5SNVpGek1JczQ/view?resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWG5SNVpGek1JczQ&resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" width="240" alt="1978 - M497C - P016 - 8-109-1-2.jpg"></a><br><sub>1978|11 · P016 - 8-109-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWXRGSER4Z2VZUjg/view?resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWXRGSER4Z2VZUjg&resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" width="240" alt="1978 - M497C - P017 - 8-109-2-1.jpg"></a><br><sub>1978|11 · P017 - 8-109-2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVhIS1l0dHZTOFk/view?resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVhIS1l0dHZTOFk&resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" width="240" alt="1978 - M497C - P018 - 8-109-2-2.jpg"></a><br><sub>1978|11 · P018 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEhSMFN4X1lnSjg/view?resourcekey=0-51aI3iimlChrQy4-0Vfs7A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEhSMFN4X1lnSjg&resourcekey=0-51aI3iimlChrQy4-0Vfs7A" width="240" alt="1978 - M497C - P019 - 8-109-2-3.jpg"></a><br><sub>1978|11 · P019 - 8-109-2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNGNLVHZ2c2pzSnc/view?resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNGNLVHZ2c2pzSnc&resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" width="240" alt="1978 - M497C - P020 - 8-109-2-4.jpg"></a><br><sub>1978|11 · P020 - 8-109-2-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0pTTjJiTU5yOEk/view?resourcekey=0-I38P4wx8KdToHSF039nWHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0pTTjJiTU5yOEk&resourcekey=0-I38P4wx8KdToHSF039nWHA" width="240" alt="1978 - M497C - P021 - 8-109-2-5.jpg"></a><br><sub>1978|11 · P021 - 8-109-2-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1I9lRAj6XxlnLgAq29r-o81hOi7Ej1v1k/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1I9lRAj6XxlnLgAq29r-o81hOi7Ej1v1k" width="240" alt="19xx - M497C - DOC - 2021-3-16-22-34-19.jpg"></a><br><sub>19xx - M497C - DOC - 2021-3-16-22-34-19</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1-kteFUrteyg5A3w0Il1sCShPPiVRsT2Z/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1-kteFUrteyg5A3w0Il1sCShPPiVRsT2Z" width="240" alt="19xx - M497C - DOC - MCNLIOR MODULE OHMS SSUEI REMSION DIRECT.jpg"></a><br><sub>19xx - M497C - DOC - MCNLIOR MODULE OHMS SSUEI REMSION DIRECT</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - M497C - 497-01-004 - DUAL MASTER MODULE FUNCTIONAL DIAGRAM.kicad_sch](KICAD/1978%20-%20M497C%20-%20497-01-004%20-%20DUAL%20MASTER%20MODULE%20FUNCTIONAL%20DIAGRAM.kicad_sch)
- [1978 - M497C - 497-01-004 - OHMS LEFT LEVEL INSERT.kicad_sch](KICAD/1978%20-%20M497C%20-%20497-01-004%20-%20OHMS%20LEFT%20LEVEL%20INSERT.kicad_sch)
- [1978 - M497C - 497-02-003 - NOT USD SHORT PINS IIM TOGETER LEFT OUTPUTS.kicad_sch](KICAD/1978%20-%20M497C%20-%20497-02-003%20-%20NOT%20USD%20SHORT%20PINS%20IIM%20TOGETER%20LEFT%20OUTPUTS.kicad_sch)
- [1978 - M497C - 497-02-003 - SOT SOT REE CRI TIP.kicad_sch](KICAD/1978%20-%20M497C%20-%20497-02-003%20-%20SOT%20SOT%20REE%20CRI%20TIP.kicad_sch)
- [1978 - M497C - 497-02-003.kicad_sch](KICAD/1978%20-%20M497C%20-%20497-02-003.kicad_sch)
- [1978 - M497C - 8-109-02-006 - REVISION NOMINAL VALUE.kicad_sch](KICAD/1978%20-%20M497C%20-%208-109-02-006%20-%20REVISION%20NOMINAL%20VALUE.kicad_sch)
- [1978 - M497C - 8-109-02-006 - RII RIZ.kicad_sch](KICAD/1978%20-%20M497C%20-%208-109-02-006%20-%20RII%20RIZ.kicad_sch)
- [1978 - M497C - Dual Master Module (2) p10.kicad_sch](KICAD/1978%20-%20M497C%20-%20Dual%20Master%20Module%20(2)%20p10.kicad_sch)
- [1978 - M497C - Dual Master Module p10.kicad_sch](KICAD/1978%20-%20M497C%20-%20Dual%20Master%20Module%20p10.kicad_sch)
- [1978 - M497C - Dual Master Module p12.kicad_sch](KICAD/1978%20-%20M497C%20-%20Dual%20Master%20Module%20p12.kicad_sch)
- [1978 - M497C - Dual Master Module p26.kicad_sch](KICAD/1978%20-%20M497C%20-%20Dual%20Master%20Module%20p26.kicad_sch)
- [1992 - M497C - DOC - 920383-01-001 - MONITOR MQDULE SWTCHEO DIRECT FUTURE MONITOR OUTPUTS.kicad_sch](KICAD/1992%20-%20M497C%20-%20DOC%20-%20920383-01-001%20-%20MONITOR%20MQDULE%20SWTCHEO%20DIRECT%20FUTURE%20MONITOR%20OUTPUTS.kicad_sch)
- [1992 - M497C - DOC - 920477-01-001 - OHMS SWTCHED SSUE REMSION FUTURE FUTURE.kicad_sch](KICAD/1992%20-%20M497C%20-%20DOC%20-%20920477-01-001%20-%20OHMS%20SWTCHED%20SSUE%20REMSION%20FUTURE%20FUTURE.kicad_sch)
- [2017 - M497C - DOC - 920170-01-001 - SWTCHED DIRECT MONITOR OUTPUTS DDZME.kicad_sch](KICAD/2017%20-%20M497C%20-%20DOC%20-%20920170-01-001%20-%20SWTCHED%20DIRECT%20MONITOR%20OUTPUTS%20DDZME.kicad_sch)
- [M497C.kicad_sym](KICAD/M497C.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
