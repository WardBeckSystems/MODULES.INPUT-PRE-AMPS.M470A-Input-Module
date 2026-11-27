# M470A Input Module · Input Pre Amps

Ward-Beck Systems M470A, 1977|10. Wiki page: [M470A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M470A.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 21 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 8 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 11 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 211 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 32 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 7 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 58 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [25 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1977 - M470A - Input Module.pdf](MANUALS/1977%20-%20M470A%20-%20Input%20Module.pdf) page 5 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Input sensitivities** | Line: Mic Pad: Mic: -10:0 +20 dBm (ref. 600 ohm source) -40 to -10 dBm (ref 150 ohm source -60 to -30 dBm (ref. 150 ohm source) |
| **Frequency response** | ±0.25 dB from 30 Hz to 20 kHz |
| **Noise** | -125 dBm EIN at maximum sensitivity (20 Hz to 20 kHz)= 75 dB S/N ratio or better for Tine sensitivities from 0 co +20 dBm. |
| **Harmonic distortion** | Less than 0.35% from 30 Hz to 15 khz at +24 dBm output or Tes $ Less than 0.1X at kHz at +24 dBm output |
| **Source impedances** | Line: Mic: 150/600 ohms ba Tanced/unbaTanced 150 ohms ba lanced/ unbalanced. |
| **Input impedances** | Line: Mic: 30,000 ohms 750 ohms minimum. |
| **Output impedance** | Less than 100 ohms at insert and direct outputs |
| **Load impedance** | 600 ohms balanced (at insertion Point). TOkohms balanced (at direct output) dBm nominal, +26 dBm maXimum. |
| **Phasing** | Input and output terminals designated by numbers are in phase |
| **Power requirements** | +25 volts dc, 20 MA nomina], 80 MAma ximum. |
| **Ambient temperature** | 0 to 60 degrees Celsius 6 &quot; wide X 14.15&quot; high 6.5 &quot; deep (41 Mm X 360 MM X 165 Mm) |

## Circuit description

From [1979 - M470A - Input Module.pdf](MANUALS/1979%20-%20M470A%20-%20Input%20Module.pdf) pages 3-8 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

3 High -P ass Fl1 te r 3-1 • Parts List 4· 1 t o 4-7

5 Drawings M470 A Front Panel 84 70-04-006 H4 7 0A Functional B4 70-01 · 0 n H470A Schematic L 8 47 0 -0 2 -0 0 2 M4 7 0A Component layout 84 7 0·06-002 H4 7 0A Connector Layout 84 70-04-005

**WARRANT Y**

de fl!' cth e Materials and workManship fora period year frOM date o f shipMent.

Ward~ 8e c k SysteMS will repair o r replace. a tits option, without ch. r ge, all said products or parts thereof which, upon fl ct o r y tn spec t ton, proye t o bede f ec the dur 1n9 the warranty pe rfo d pro\lided that:

a) Orf9i nal s e r tat nU llb ers are intact and have not been tampered with.

b) The purchasers hall return any equ i pllent or parts thereof to War dBeck Systems only.. Her ob taf nf n9 p r fora u thor i z a t ion and shipping instructions from the fa cl o r y. Ward ·R e c~ Systems reserves the right to inspector repair u n the purchaser's p r e mfses.

c) The purchaser assumes the obligation o f.. 11 expenses incurred i nco nn e ct lon.l t h shipping andre turning such goods, once authorization has been obtained.

This 'oI a rra n ty does not ccve rite ms nor llla l l y considered expendable Such as fuses and lamps.

ThiS 'oIar r anly does not cover da.a ge s caused by Misuse, accident, neglect. unauthorized alteration. repair by una u thor i zed personnel. o r daM age caused by act of God, war orc i v i l insurrection.

I n no e\lent shall Ward-Be ck SysteMS be liable for conse~ quen tlal daMages. Ward·Be ck SysteMS shall have the ri9h t off ina l deterMfnatlon a s tot he applicability of this warranty.

Sys t eliS reserves the r19ht, at any t tee • to lIlate Ward ~ Beck Cha n9U i n e qu t pee n t, c Olllponent spec ifica t ions and desi9n

a s lIay be warranted by progress int e ch no l o9Y.

The w.rranty set forth herein Is i n lieu o fall other war

ranti e s, express or Implied, including the warranties of Merch an tab fl lty and Fitness.

Tt CHN ICAL DATA

Input Sensitivities:

l1 ne: -10 t o +20 dBm (ref. 600 ohm sour ce!_ Mit Plod: · 40 to -10 dBm (ref. 150 ohll source. Mit: · 60 to -30 dBm (ref. 150 ohll sou rce). Frequency Response: t o. 25 dB (ro. 30 Hz to 20 kHz. Hohe: -125 dBII [IN a t. axillU II sensitivity (20 Hz to 20 kHz). 75 dB SIN ratio or better (or lines enslti vft ies fro ll o to +20 dBm.

&quot; &quot; r mon it Distortion: Less than 0.351 frOIl 30 Hz to 15 kHz at +24 dBII output Dr less. Leu than 0.11 at 1 kHz at +24 dB II out put.

Source I lIped&quot;nces:

line: 150/6 00 OIiIlS, bala need/ unbalanced. Mic: 150011 115, ba l anc ed/ unbalanced.

Input I llpedances:

Line: 3D. 000 0lills.

Mic: 750 01l 1lS llin 1l1uII.

Out put I lIped&quot;nce: Less tllan 100 Olills at insert ud di r et tout puts • 600 OhllS, ba l lnced (a t i nsertf on point).

IDkohlls,b al ance d (a t direct out put).

Output Level: o dB. nee une t, +26 dBIl lIax illull. Phasing: Input and output terminals designated by numbers are in pllase.

Power Requirements: ±25 volts dc, 20 mA nominal, 80 mA

ma xf mum.

Ambient Temperature: o t o 60 degrees Cel sf us.

Dimensions: 1.6&quot; wf de X 14.1 5&quot; IIf911 X 6.5 &quot; deep

(41 mm X 360 mm X 165 mm).

1• 1

WA FID -BE CK SYSTEMS L.TD.

ClRC UIT DESCRIPTION

**M4 70A INPUT MODULE**

The M4 70A input module provides the facilities of a c o ~p 1 et e input.i ~i ng channel with the e~cepti on oft he attenuator and an optional external equalizer.

Input INPUT Selector switches SW 1, SW2 and SW3 allow a choice o fin put selection between one 11 ne and two. Ic rop hone inputs. Additionally, SW4 provideS the insert ion of a 20 dB loss pad forth e microphone sources. When operating fro. a MICROPHONEs ource, the input Illp ed ance oft he unit iss ubstant ia l ly higher than the source ill pe dance. In the LINE position. the &quot;,. 70A presents i bridging lmpedance of 30k 01'1. tot hes ource. All inputs t o the lIlodu1e are tra nsfor.er coupled tot he prea lllp l 1f i er. Pr ealllplifl er These condary side of the input trans fo r.e r Tl connects tot he pr e a.pl i fie r input section, c o ~pr i sing Ql through 05 with their associated co. ponent s. SENS ITIY I TY control R26 allows continuous level adjust llle nt of all inputs i gna ls over a range of 30 dB. TheSE NSI TI VI TY control thuS perllli ts operation with.ic ro phone input levels fro. -60 to -30 dB. i n the direct.od e, and with levels fro. -40 t o -10 dBII when the PAD i s inserted. Silllil a r ly. line levels froll -10 dB. t o +20 dB. can be a c c o ~ mod lt e dint he LINE.o de.

[qu all zer Insert Fo l low1ng Q4 lind Q5. the sign. l is brought out to connector Pl. pin 22 and returned t o the unit vi. Pl, pin Z. This insert point lI.y be used t o insert the 1'14 72 equ a11 ze r into the signal path.

HIGH -P ASS Filter Following Pl, pin Z, a 12 dB/ octave HI GHPASS filter is i nte. grated f nto the prea mp lifier. Three distinct cutoff fr eque n

ci e scan be selected, By pressing SWS, SW6 or both switches simultaneously, the - ] dB ro l l-of f point will be located atp s.

70 Hz, 100 Hz or 150 Hz respectively.

Pr e amplf f i er Output and PHASE Reversal

The output of the filter feeds the prea mplif ier outputs ta ge,

CI RCU ll DESCRIPTION

**M4 70A INPUT MODULE**

consisting Df Zl, Q6, Q7, Z2, Q8 and Q9. The actively balanced output is subsequently routed through the PHASE reversal switch tD the insert pDint.

lNS ERT PD int A balanced INSERT point i s provided between P2. pins 8/ J and P2. pins 6/F t D al 1D w the use of insert jacks, permittl ng the 1n sertion of an c l1 1ary equipment l nto the signal path. The INSERT pDi nt is f D11 0w ed by t h ~ CHANNEL ON switch. CHANNEL ON Switch The CHANNEL ON switch SW B controls all Dutpu tS oft he module with the exception of the PFL out put.

PREF AO ELISTEN (PFL) and PEAK Overload Indicator The bridging takeoff for the PF L output and the PEAK overload indicator is plc ked up between the INSERT point and the CHANNEL ON switch. Z3 operates as a voltage compa rat or. I t compares there ct if ied audio signal with an externally supplied reference voltage, applied t o connector P2, pin 16. With the reference voltage ranging from 0 t o approximately +10 volts, calibration of the overload point from -6 dBm to +27 dBm i s possible. PEAK overload i s indicated on OS2.

**FAD ER**

Following SW 8, the signal i s brought out of the module via P2, pins 7/ H for insertion of a balanced fade r. The output oft he f a der i s returned t o the module on P2, pins 5/£. The inputs ide oft he fa der also supplies the feed for the four PREFACE AU Xl LIARV channels via switches SWg through SW1 2. Booster Amplifier Z4 and Z5 comprise the booster amplifier. operating at again Df

15 dB. The booster recovers the loss incurred with the fade r

placed in its nominal 15 dB &quot;i n-hand &quot; position.

DIRECT Out put

The outputs ig nal o f the booster amplifier feeds the Dl REC Tout

**H47 0A INPUT MODULE**

put at connector Pl, p\ns 3/C. This output is designed to operate into abridging load of 10k oh_ or higher. The no.ina l level Of the DIRECT output i s 0 dB•.

MASTER, SU BMASTE Rand AUXILIARY Outputs The booster a.pl ifier also provides the feeds for the left and right MASTER and SUBMASTER outputs via PAN switch SW13 and PAN control RB4 through R8 7. Additional feeds are supplied to the SOLO out put via SWl2 and t o the four AUXILIARY outputs when in the POSTFAOE mode. With the exception of the DIRECT output, all outputs are designed a s 30k ohm current sources, t o operate into zero impedance summing nodes. Each summing out put is equipped with its own assignment switch.

Control Functions DC control and logic muting functions are provided through the Hi e/LIN E INPUT Selector switches and the CHANNEL ON switch t o facilitate studio mute control functions. to minimize system transients. the de current i n these circuits should be limited t o I mAo further control contacts are provided on the SOLO switch SW22 as well as on all SUB HAST ER and HASTE R assign ~ent switches.

Power Supply Deco upl ing Power supply dec oupling i s provided by QIO. Qi land their associated co~pon e n t s. The de coupling network reduces the ~o d u l e voltage t o !20 volts fro. the no_ina l supply voltage o f:!: 25 voles.

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb1c5ZUhGR3BjTVE/view?resourcekey=0-IF0RKfKeKg5vVk6ga0p1aQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb1c5ZUhGR3BjTVE&resourcekey=0-IF0RKfKeKg5vVk6ga0p1aQ" width="240" alt="1977 - M470A - 12.jpg"></a><br><sub>1977|10 · 12</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSUFibWVMWDliNVE/view?resourcekey=0-GSBt0m_daH8NAaDB6wcuxQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSUFibWVMWDliNVE&resourcekey=0-GSBt0m_daH8NAaDB6wcuxQ" width="240" alt="1977 - M470A - Input Module Front.jpg"></a><br><sub>1977|10 · Input Module Front</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVmxIZUtzVlJVT0E/view?resourcekey=0-KJptudin6dUkm4w0LmkeFw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVmxIZUtzVlJVT0E&resourcekey=0-KJptudin6dUkm4w0LmkeFw" width="240" alt="1977 - M470A - Input Module Side 3.jpg"></a><br><sub>1977|10 · Input Module Side 3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVXBXdmx5SzFUam8/view?resourcekey=0-55DFfPgrEwHSGS1xUEBibQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVXBXdmx5SzFUam8&resourcekey=0-55DFfPgrEwHSGS1xUEBibQ" width="240" alt="1977 - M470A - Pres - Old Style.jpg"></a><br><sub>1977|10 · Pres - Old Style</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMjJRZVVGZ1pwTTQ/view?resourcekey=0-pjI_y49wEdlOIOwK4aPhCQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMjJRZVVGZ1pwTTQ&resourcekey=0-pjI_y49wEdlOIOwK4aPhCQ" width="240" alt="1977 - M470A - Small (2).jpg"></a><br><sub>1977|10 · Small (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKakR6TWY4dHlzUGs/view?resourcekey=0-Hm22Pp-OEXB539WHWO28XA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKakR6TWY4dHlzUGs&resourcekey=0-Hm22Pp-OEXB539WHWO28XA" width="240" alt="1977 - M470A - Switch Mod 1.jpg"></a><br><sub>1977|10 · Switch Mod 1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMmNYc0d3NWdJTUU/view?resourcekey=0-uM_4iUY-SB_IRq9mBNTYXQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMmNYc0d3NWdJTUU&resourcekey=0-uM_4iUY-SB_IRq9mBNTYXQ" width="240" alt="1977 - M470A - Switch Mod 2.jpg"></a><br><sub>1977|10 · Switch Mod 2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYWE2cHRDcXFKaWM/view?resourcekey=0-qwrf4x-TGywS-_SJQUk-WQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYWE2cHRDcXFKaWM&resourcekey=0-qwrf4x-TGywS-_SJQUk-WQ" width="240" alt="1977 - M470A - file.jpg"></a><br><sub>1977|10 · file</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKelhYZElDclNqVnM/view?resourcekey=0-35hLPSCCTR7Fe9opX185DQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKelhYZElDclNqVnM&resourcekey=0-35hLPSCCTR7Fe9opX185DQ" width="240" alt="1977 - M470A - wbsps - module - m470a input module 003.jpg"></a><br><sub>1977|10 · wbsps - module - m470a input module 003</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcnpIaGlleGhvZ0E/view?resourcekey=0-w348ewSDMwFLAaG946GtZQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcnpIaGlleGhvZ0E&resourcekey=0-w348ewSDMwFLAaG946GtZQ" width="240" alt="1977 - M470A - wbsps - module - m470a input module 009.jpg"></a><br><sub>1977|10 · wbsps - module - m470a input module 009</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0FZVVFQTjlzZDQ/view?resourcekey=0-xgrJy1iAXAisupe_t8GkoA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0FZVVFQTjlzZDQ&resourcekey=0-xgrJy1iAXAisupe_t8GkoA" width="240" alt="1977 - M470A - wbsps - module - m470a input module 010.jpg"></a><br><sub>1977|10 · wbsps - module - m470a input module 010</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVzU1MXNCRUozVjA/view?resourcekey=0-hy1VcQcVhqzM0h924NJpgg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVzU1MXNCRUozVjA&resourcekey=0-hy1VcQcVhqzM0h924NJpgg" width="240" alt="1977 - M470A - wbsps - module - m470a input module 011.jpg"></a><br><sub>1977|10 · wbsps - module - m470a input module 011</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS3VUN1FMa25MQzQ/view?resourcekey=0-eoh1T4-Hc8R8VmCQTZ5VBQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS3VUN1FMa25MQzQ&resourcekey=0-eoh1T4-Hc8R8VmCQTZ5VBQ" width="240" alt="1977 - M470A - wbsps - module - m470a input module 012.jpg"></a><br><sub>1977|10 · wbsps - module - m470a input module 012</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUjVUS0JZZFlBaTA/view?resourcekey=0-OwhESLzqzjeLUeSo73VzUw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUjVUS0JZZFlBaTA&resourcekey=0-OwhESLzqzjeLUeSo73VzUw" width="240" alt="1977 - M470A - wbsps - module - m470a input module 013.jpg"></a><br><sub>1977|10 · wbsps - module - m470a input module 013</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWHVEa3RwdXJ1Ykk/view?resourcekey=0-9qffYP58S12YVM51r7NEhw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWHVEa3RwdXJ1Ykk&resourcekey=0-9qffYP58S12YVM51r7NEhw" width="240" alt="1977 - M470A - wbsps - module - m470a input module 014.jpg"></a><br><sub>1977|10 · wbsps - module - m470a input module 014</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbVZEZkJacUw2SVk/view?resourcekey=0-6Sl8PIhKSoAeGSUtB2YJDQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbVZEZkJacUw2SVk&resourcekey=0-6Sl8PIhKSoAeGSUtB2YJDQ" width="240" alt="1977 - M470A - wbsps - module - m470a input module 015.jpg"></a><br><sub>1977|10 · wbsps - module - m470a input module 015</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZjl5QlJaT3RuTUk/view?resourcekey=0-diQcljGW7Km9oFE5o7uJ8A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZjl5QlJaT3RuTUk&resourcekey=0-diQcljGW7Km9oFE5o7uJ8A" width="240" alt="1977 - M470A - wbsps - module - m470a input module 016.jpg"></a><br><sub>1977|10 · wbsps - module - m470a input module 016</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQkEzWW9DQlRwR0E/view?resourcekey=0-OVg4KyJ5m7u8bnrp6w_1HQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQkEzWW9DQlRwR0E&resourcekey=0-OVg4KyJ5m7u8bnrp6w_1HQ" width="240" alt="1977 - M470A - wbsps - module - m470a input module 017.jpg"></a><br><sub>1977|10 · wbsps - module - m470a input module 017</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT01wNDFsbFFrbVU/view?resourcekey=0-nOX-asAH7tvZEw4jvL8UCQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT01wNDFsbFFrbVU&resourcekey=0-nOX-asAH7tvZEw4jvL8UCQ" width="240" alt="1977 - M470A - wbsps - module - m470a input module 018.jpg"></a><br><sub>1977|10 · wbsps - module - m470a input module 018</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQnVydThsa1ZLOEU/view?resourcekey=0-mlCsaWdNz0CE7SHRPVoQaw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQnVydThsa1ZLOEU&resourcekey=0-mlCsaWdNz0CE7SHRPVoQaw" width="240" alt="1977 - M470A - wbsps - module - m470a input module 019.jpg"></a><br><sub>1977|10 · wbsps - module - m470a input module 019</sub></td></tr>
</table>

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTWJSMUZ0azV3cnc/view?resourcekey=0-6FYv6yhvIczHeU6uRKSMxQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTWJSMUZ0azV3cnc&resourcekey=0-6FYv6yhvIczHeU6uRKSMxQ" width="240" alt="1977 - M470A - 470-04-006 - IGNA FOL OWING CHE FADER AND CRA SWITCH.jpg"></a><br><sub>1977|10 · 470-04-006 - IGNA FOL OWING CHE FADER AND CRA SWITCH · <a href="MECHANICAL/1977%20-%20M470A%20-%20470-04-006%20-%20IGNA%20FOL%20OWING%20CHE%20FADER%20AND%20CRA%20SWITCH%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN3RtdFNKZkY1Mm8/view?resourcekey=0-VjUDk-8NMnlpuxDVPMF2hA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN3RtdFNKZkY1Mm8&resourcekey=0-VjUDk-8NMnlpuxDVPMF2hA" width="240" alt="1977 - M470A - 470-01-002 - OLO CONTROL EXTERNAL PEAK CALIBRATION PEAK INDICATOR.jpg"></a><br><sub>1977|10 · 470-01-002 - OLO CONTROL EXTERNAL PEAK CALIBRATION PEAK INDICATOR · <a href="SCHEMATICS/1977%20-%20M470A%20-%20470-01-002%20-%20OLO%20CONTROL%20EXTERNAL%20PEAK%20CALIBRATION%20PEAK%20INDICATOR%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZjFOeVVtckxpZjQ/view?resourcekey=0-mPRzhvzywlFup4LKDFFzBg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZjFOeVVtckxpZjQ&resourcekey=0-mPRzhvzywlFup4LKDFFzBg" width="240" alt="1977 - M470A - P19 - Schematic.jpg"></a><br><sub>1977|10 · P19 - Schematic · <a href="SCHEMATICS/1977%20-%20M470A%20-%20P19%20-%20Schematic%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeUZyREZadUptRU0/view?resourcekey=0-7Y_y_k6kkNwgWArQ-ruINw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeUZyREZadUptRU0&resourcekey=0-7Y_y_k6kkNwgWArQ-ruINw" width="240" alt="1977 - M470A - P20 - Component Layout.jpg"></a><br><sub>1977|10 · P20 - Component Layout · <a href="SCHEMATICS/1977%20-%20M470A%20-%20P20%20-%20Component%20Layout%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1977|10 · P20 - Component Layout (2)](https://drive.google.com/file/d/0B0yR0b5T78SKcFdPamJUWjc1OE0/view?resourcekey=0-T9z_5znSj_Q6CdNedLluLQ)

Not on Google Drive yet: `M470A - P18 - Functional Diagram.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU1JGN3NLN0VqWGM/view?resourcekey=0-sb5RyfxJer8K8aYa2sph6g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU1JGN3NLN0VqWGM&resourcekey=0-sb5RyfxJer8K8aYa2sph6g" width="240" alt="1977 - M470A - 470-04-005 - FIMISH NPUT MODULE CONNECTOR REAR VIEW.jpg"></a><br><sub>1977|10 · 470-04-005 - FIMISH NPUT MODULE CONNECTOR REAR VIEW · <a href="PINOUTS/1977%20-%20M470A%20-%20470-04-005%20-%20FIMISH%20NPUT%20MODULE%20CONNECTOR%20REAR%20VIEW%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M470A - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 50 of 52 contacts; 2 to check (`conflicts`). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- disagree P2-5: kept ATT OUT - (out); RTO-144 sheet says FADER-RETURN + (in)
- disagree P2-E: kept ATT OUT + (out); RTO-144 sheet says FADER-RETURN - (in)
- polarity assumed: 42 contacts given + / − that the drawing does not mark (e.g. P1-A MASTER 2 OUT +) (M470A: 1977 - M470A - 470-04-005 - FIMISH NPUT MODULE CONNECTOR REAR VIEW.jpg)

**Inserts:** EQUALIZER INSERT: EQUAL OUT → EQUAL IN

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| P1-1 | MASTER 2 OUT - | out | MASTER 2 OUT - | high |
| P1-2 | INTERNALLY CONNECTED | other |  | high |
| P1-3 | SUB 4 OUT - | out | SUB 4 OUT - | high |
| P1-4 | SUB 2 OUT - | out | SUB 2 OUT - | high |
| P1-5 | MASTER 1 OUT - | out | MASTER 1 OUT - | high |
| P1-6 | INTERNALLY CONNECTED | other |  | high |
| P1-7 | SUB 3 OUT - | out | SUB 3 OUT - | high |
| P1-8 | SUB 1 OUT - | out | SUB 1 OUT - | high |
| P1-9 | AUX 4 OUT - | out | AUX 4 OUT - | high |
| P1-10 | AUX 3 OUT - | out | AUX 3 OUT - | high |
| P1-11 | AUX 2 OUT - | out | AUX 2 OUT - | high |
| P1-12 | AUX 1 OUT - | out | AUX 1 OUT - | high |
| P1-13 | PFL - | bus | PFL - | high |
| P1-14 | SOLO - | bus | SOLO - | high |
| P1-15 | N/C | nc |  | high |
| P1-16 | N/C | nc |  | high |
| P1-17 | N/C | nc |  | high |
| P1-18 | N/C | nc |  | high |
| P1-19 | MIC 1 - | in | MIC 1 - | high |
| P1-20 | MIC 2 - | in | MIC 2 - | high |
| P1-21 | MIC SHIELD | shield | shield | high |
| P1-22 | EQUALIZER RETURN | insert_return | EQUAL IN | high |
| P1-A | MASTER 2 OUT + | out | MASTER 2 OUT + | high |
| P1-B | INTERNALLY CONNECTED | other |  | high |
| P1-C | SUB 4 OUT + | out | SUB 4 OUT + | high |
| P1-D | SUB 2 OUT + | out | SUB 2 OUT + | high |
| P1-E | MASTER 1 OUT + | out | MASTER 1 OUT + | high |
| P1-F | INTERNALLY CONNECTED | other |  | high |
| P1-H | SUB 3 OUT + | out | SUB 3 OUT + | high |
| P1-J | SUB 1 OUT + | out | SUB 1 OUT + | high |
| P1-K | AUX 4 OUT + | out | AUX 4 OUT + | high |
| P1-L | AUX 3 OUT + | out | AUX 3 OUT + | high |
| P1-M | AUX 2 OUT + | out | AUX 2 OUT + | high |
| P1-N | AUX 1 OUT + | out | AUX 1 OUT + | high |
| P1-P | PFL + | bus | PFL + | high |
| P1-R | SOLO + | bus | SOLO + | high |
| P1-S | N/C | nc |  | high |
| P1-T | N/C | nc |  | high |
| P1-U | N/C | nc |  | high |
| P1-V | N/C | nc |  | high |
| P1-W | MIC 1 + | in | MIC 1 + | high |
| P1-X | MIC 2 + | in | MIC 2 + | high |
| P1-Y | MIC SHIELD | shield | shield | high |
| P1-Z | EQUALIZER SEND | insert_send | EQUAL OUT | high |
| P2-1 | LINE IN - | in | LINE IN - | high |
| P2-2 | N/C | nc |  | high |
| P2-3 | DIRECT - | out | DIRECT - | high |
| P2-4 | SHIELD | shield | LINE IN shield | high |
| P2-5 | ATT OUT - | out | ATT OUT - | high |
| P2-6 | CH ON IN - | control_in | CH ON IN - | high |
| P2-7 | CH ON OUT - | control_out | CH ON OUT - | high |
| P2-8 | PRE OUT - | out | PRE OUT - | high |
| P2-9 | N/C | nc |  | high |
| P2-10 | MASTER 2 CTL | control_out | MASTER 2 CTL | high |
| P2-11 | N/C | nc |  | high |
| P2-12 | SUB 4 CTL | control_out | SUB 4 CTL | high |
| P2-13 | SUB 2 CTL | control_out | SUB 2 CTL | high |
| P2-14 | MASTER CTL COMMON | ground |  | high |
| P2-15 | CH ON AUX CONTACT - | control_out | CH ON AUX CONTACT - | high |
| P2-16 | CTL COMMON | ground |  | high |
| P2-17 | MIC 2 MUTE CTL | control_in | MIC 2 MUTE CTL | high |
| P2-18 | CTL COMMON | ground |  | high |
| P2-19 | -25 V | power |  | high |
| P2-20 | 25 V COMMON | ground |  | high |
| P2-21 | +25 V | power |  | high |
| P2-22 | CHASSIS GROUND | ground |  | high |
| P2-A | LINE IN + | in | LINE IN + | high |
| P2-B | N/C | nc |  | high |
| P2-C | DIRECT + | out | DIRECT + | high |
| P2-D | SHIELD | shield | LINE IN shield | high |
| P2-E | ATT OUT + | out | ATT OUT + | high |
| P2-F | CH ON IN + | control_in | CH ON IN + | high |
| P2-H | CH ON OUT + | control_out | CH ON OUT + | high |
| P2-J | PRE OUT + | out | PRE OUT + | high |
| P2-K | N/C | nc |  | high |
| P2-L | MASTER 1 CTL | control_out | MASTER 1 CTL | high |
| P2-M | N/C | nc |  | high |
| P2-N | SUB 3 CTL | control_out | SUB 3 CTL | high |
| P2-P | SUB 1 CTL | control_out | SUB 1 CTL | high |
| P2-R | SUB CTL COMMON | ground |  | high |
| P2-S | CH ON AUX CONTACT + | control_out | CH ON AUX CONTACT + | high |
| P2-T | LINE MUTE CTL | control_in | LINE MUTE CTL | high |
| P2-U | MIC 1 MUTE CTL | control_in | MIC 1 MUTE CTL | high |
| P2-V | SOLO CTL | control_out | SOLO CTL | high |
| P2-W | CH ON CTL COMMON | ground |  | high |
| P2-X | MIC/LINE CTL COMMON | ground |  | high |
| P2-Y | +24 V | power |  | high |
| P2-Z | CH ON LAMP | control_in | CH ON LAMP | high |

**Straps:** JMP.Z.W: P2-Z P2-W · JMP.2: P2-W P2-18 · JMP.Y.21: P2-Y P2-21 · JMP.20.18: P2-20 P2-18 · JMP.8.6: P2-8 P2-6 · JMP.J.F: P2-J P2-F · JMP.7.5: P2-7 P2-5 · JMP.H.E: P2-H P2-E · JMP.Z.22: P1-Z P1-22

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMGxnVm1oZ2dVQ0U/view?resourcekey=0-S7RalVH_8lSlPh7BDKtMXg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMGxnVm1oZ2dVQ0U&resourcekey=0-S7RalVH_8lSlPh7BDKtMXg" width="240" alt="1977 - M470A - Input Module (2).pdf"></a><br><sub>1977|10 · Input Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUzNoR3VPVF81MGc/view?resourcekey=0-84xtY31OOprJpkXG29aMTQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUzNoR3VPVF81MGc&resourcekey=0-84xtY31OOprJpkXG29aMTQ" width="240" alt="1977 - M470A - P01 - Cover.jpg"></a><br><sub>1977|10 · P01 - Cover</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ2I5SWJOc25oY2s/view?resourcekey=0-EX1NXO7adqyDlIkIJ4AsAQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ2I5SWJOc25oY2s&resourcekey=0-EX1NXO7adqyDlIkIJ4AsAQ" width="240" alt="1977 - M470A - P02.jpg"></a><br><sub>1977|10 · P02</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdkxWS3A3RlJkV0E/view?resourcekey=0-k0Y6Y9xSQBjYvajU7H8Y1g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdkxWS3A3RlJkV0E&resourcekey=0-k0Y6Y9xSQBjYvajU7H8Y1g" width="240" alt="1977 - M470A - P04.jpg"></a><br><sub>1977|10 · P04</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS213WDFxcl9RN0U/view?resourcekey=0-fCPUqrRB7Nl_JugMupc5Fg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS213WDFxcl9RN0U&resourcekey=0-fCPUqrRB7Nl_JugMupc5Fg" width="240" alt="1977 - M470A - P05 - 1-1.jpg"></a><br><sub>1977|10 · P05 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSzlGLXJac2QwX00/view?resourcekey=0-NgmRP2_d0_lkisgsmjBd5w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSzlGLXJac2QwX00&resourcekey=0-NgmRP2_d0_lkisgsmjBd5w" width="240" alt="1977 - M470A - P06 - 2-1.jpg"></a><br><sub>1977|10 · P06 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSXYwOHhSVG5NdXM/view?resourcekey=0-UrCTnCVuvotKbMOWqbisVg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSXYwOHhSVG5NdXM&resourcekey=0-UrCTnCVuvotKbMOWqbisVg" width="240" alt="1977 - M470A - P07 - 2-2.jpg"></a><br><sub>1977|10 · P07 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSm1HUjUtX2QtMms/view?resourcekey=0-53xLV26J2oPG-nTSkh4BGA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSm1HUjUtX2QtMms&resourcekey=0-53xLV26J2oPG-nTSkh4BGA" width="240" alt="1977 - M470A - P08 - 2-3.jpg"></a><br><sub>1977|10 · P08 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMzlHSlhnbkVVb1k/view?resourcekey=0-YWLnXUP0k1YuZtXFHgCChA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMzlHSlhnbkVVb1k&resourcekey=0-YWLnXUP0k1YuZtXFHgCChA" width="240" alt="1977 - M470A - P09 - 3-1.jpg"></a><br><sub>1977|10 · P09 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUFB2SW5IbllkWWc/view?resourcekey=0-hBnz4od_K1LR_eW4v90aOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUFB2SW5IbllkWWc&resourcekey=0-hBnz4od_K1LR_eW4v90aOw" width="240" alt="1977 - M470A - P10 - 4-1.jpg"></a><br><sub>1977|10 · P10 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdHgyNGtHclFXUDA/view?resourcekey=0-NHpyLyyIT27FPDpk-gSXqw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdHgyNGtHclFXUDA&resourcekey=0-NHpyLyyIT27FPDpk-gSXqw" width="240" alt="1977 - M470A - P11 - 4-2.jpg"></a><br><sub>1977|10 · P11 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUVNkNkU2REQ1SDA/view?resourcekey=0-7Yc-6nUY47T9E9ov85YEUQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUVNkNkU2REQ1SDA&resourcekey=0-7Yc-6nUY47T9E9ov85YEUQ" width="240" alt="1977 - M470A - P12 - 4-3.jpg"></a><br><sub>1977|10 · P12 - 4-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNUpkUEZnN0pld00/view?resourcekey=0-68naQJJqDYJYOfUA3wZ4TA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNUpkUEZnN0pld00&resourcekey=0-68naQJJqDYJYOfUA3wZ4TA" width="240" alt="1977 - M470A - P13 - 4-4.jpg"></a><br><sub>1977|10 · P13 - 4-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY3l0LXpKUGRrWlU/view?resourcekey=0-olu2FWFYJ3PyPO60ewBeEQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY3l0LXpKUGRrWlU&resourcekey=0-olu2FWFYJ3PyPO60ewBeEQ" width="240" alt="1977 - M470A - P14 - 4-5.jpg"></a><br><sub>1977|10 · P14 - 4-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKendUeVpQRHRKZE0/view?resourcekey=0-16u3yVuriZ8MRndgKA-Icg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKendUeVpQRHRKZE0&resourcekey=0-16u3yVuriZ8MRndgKA-Icg" width="240" alt="1977 - M470A - P15 - 4-6.jpg"></a><br><sub>1977|10 · P15 - 4-6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS01DaEpmSUg0d2c/view?resourcekey=0-PVDnlC3s3l0A4Rpjq7nEgA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS01DaEpmSUg0d2c&resourcekey=0-PVDnlC3s3l0A4Rpjq7nEgA" width="240" alt="1977 - M470A - P16 - 4-7.jpg"></a><br><sub>1977|10 · P16 - 4-7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX2M1WDNuRTFURk0/view?resourcekey=0-6CqAM2khIn8jTnJjxcMv6Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX2M1WDNuRTFURk0&resourcekey=0-6CqAM2khIn8jTnJjxcMv6Q" width="240" alt="1979 - M470A - Input Module.pdf"></a><br><sub>1979|12 · Input Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZTkxZHB2bG1VcFU/view?resourcekey=0-WzhOP7ElMwBrYcQoqY-XpQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZTkxZHB2bG1VcFU&resourcekey=0-WzhOP7ElMwBrYcQoqY-XpQ" width="240" alt="1979 - M470A - P03 - TOC.jpg"></a><br><sub>1979|12 · P03 - TOC</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX2RtQjZCdnRtMzQ/view?resourcekey=0-Rp2Zdtqqfjf328-IE2MLsg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX2RtQjZCdnRtMzQ&resourcekey=0-Rp2Zdtqqfjf328-IE2MLsg" width="240" alt="19xx - M470A - DOC - STEREO L SERIES - P002.jpg"></a><br><sub>19xx - M470A - DOC - STEREO L SERIES - P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUWxLOWlQbEl5emM/view?resourcekey=0-6-2efC6h4TfoUYxpel_8gg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUWxLOWlQbEl5emM&resourcekey=0-6-2efC6h4TfoUYxpel_8gg" width="240" alt="19xx - M470A - DOC - _untitled_ 011.jpg"></a><br><sub>19xx - M470A - DOC - _untitled_ 011</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1977|10 · Input Module](https://drive.google.com/file/d/0B0yR0b5T78SKd1JSdURjbndxelk/view?resourcekey=0-v1MqSjYGhqKtfnquDNsN9Q)

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1977 - M470A - 470-01-002 - OLO CONTROL EXTERNAL PEAK CALIBRATION PEAK INDICATOR.kicad_sch](KICAD/1977%20-%20M470A%20-%20470-01-002%20-%20OLO%20CONTROL%20EXTERNAL%20PEAK%20CALIBRATION%20PEAK%20INDICATOR.kicad_sch)
- [1977 - M470A - Input Module (2) p18.kicad_sch](KICAD/1977%20-%20M470A%20-%20Input%20Module%20(2)%20p18.kicad_sch)
- [1977 - M470A - Input Module p18.kicad_sch](KICAD/1977%20-%20M470A%20-%20Input%20Module%20p18.kicad_sch)
- [1977 - M470A - P19 - Schematic.kicad_sch](KICAD/1977%20-%20M470A%20-%20P19%20-%20Schematic.kicad_sch)
- [M470A - P18 - Functional Diagram.kicad_sch](KICAD/M470A%20-%20P18%20-%20Functional%20Diagram.kicad_sch)
- [M470A.kicad_sym](KICAD/M470A.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
