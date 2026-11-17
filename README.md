# Elektronika MK-35
Information about the Soviet B3-35/MK-35 calculator from the Russian SFSR.  It was manufactured by NPO Elektronika (Boguchar) from 1979 and is apparently based on the Australian Hanimex ESR Master calculator.  <br>

Its initial price was 105 roubles, dropping to 65 roubles in 1981.<br>

The example I have was manufactured in September (09) 1990 and purchased on 2/Nov/1990.<br>

## MK-35 Passport
Summary of the factory passport (паспорт) that came with this unit.

### This unit
| Field | Value |
|---|---|
| Serial number | 006581 |
| Release date (дата выпуска) | September 1990 |
| QC (ОТК) stamp | 149 |
| Date of sale (дата продажи) | 2 November 1990 |
| Retail price | 65 roubles (supplementary price list № 139/107, item 393) |
| Manufacturer | NPO Elektronika, 396750 Boguchar, Voronezh Oblast, ul. Zdorovya 11 (Bureau of External Inspection) |
| Technical specification | 11МО.080.173 ТУ |

### Technical data

| Parameter | Value |
|---|---|
| Functions | Four arithmetic operations; natural and common logarithms and antilogarithms; trigonometric and inverse trigonometric functions; square root; powers; reciprocal; round and square brackets; factorial; memory; degree ↔ radian conversion |
| Arithmetic operation time | ≤ 0.6 s |
| Decimal point | Natural and floating |
| Number range | 10⁻⁹⁹ ≤ \|x\| ≤ 9.9999999 × 10⁹⁹ |
| Power consumption | ≤ 0.45 W |
| Nominal supply voltage | 5 V ± 2% |
| Power source | 4 × Д-0,26Д NiCd cells and/or the Д2-37К mains adapter (220 V +10/−15%, 50 Hz) |
| Operating temperature | 10–35 °C |
| Dimensions | 143 × 79 × 22 mm |
| Mass | ≤ 0.250 kg |

### Supplied contents (комплект поставки)

- Calculator, without the batteries fitted: 1
- Д2-37К power supply: 1
- Д-0,26Д batteries, supplied discharged: 4
- Operating manual: 1
- Calculator passport: 1
- Power supply passport: 1 (printed as "БП2-3К", which is struck out by hand)
- Case (футляр): 1
- Packaging: 1

### Power: important for anyone working on one

The calculator uses **positive ground**. The common rail (⊥) is positive and the supply rail is −5 V. Its internal DC-DC converter (VT2, VT3, transformer ТПр11-10М) makes approximately −20 V and −30 V for the p-MOS processor and the VFD.

Calculator power socket XS2 (ОНП-ВС-18):

| Pin | Function |
|---|---|
| 1 | −5 V |
| 2 | ⊥ common (positive) |
| 3 | Заряд (battery charging) |

To use a modern 5 V supply, connect its **+ to pin 2** and its **− to pin 1**. Do not put DC on pin 3: it expects the current-limited charging feed from the original adapter.

The schematic also allows the **БП2-3К** supply as a substitute. To use it, fit a 270 Ω 0.5 W resistor between points 16 and 17 and link points 20 and 4 (XP1:A1).

### Processor marking (from the "ВНИМАНИЕ!" note)

Each КР145ИП16Б chip has a fraction painted on its case:

- **Numerator:** that chip's supply voltage range, Uп, in volts.
- **Denominator:** the clock-setting resistor value, Rf, in kΩ. This is **R24\*** on the schematic, listed as 68 kΩ with 82 kΩ and 120 kΩ as alternatives.

If you replace the chip, set R24 and check Uп to match its marking.

### Main components (from the parts list)

| Ref | Part |
|---|---|
| D1 | КР145ИП16Б processor |
| HG1 | ИЛЦ2-12/8Л vacuum fluorescent display |
| VT1–VT3 | КТ3107А / КТ3107В transistors |
| VD1, VD3, VD4 | КД521В diodes |
| VD2 | КС220Ж zener diode |
| T1 | ТПр11-10М converter transformer |
| A2 | ВМ24-3 keyboard unit |
| G2–G5 | 4 × Д-0,26Д NiCd cells |

### Precious metal content (calculator)

| Metal | Component | Qty | Per item (g) | Total (g) |
|---|---|---|---|---|
| Gold | КТ3107А,В transistor | 3 | 0.0011082 | 0.0033246 |
| Gold | КД521В diode | 3 | 0.00000013 | 0.00000039 |
| Gold | ВМ24-3 keyboard | 1 | 0.1374401 (0.063555 with steel membranes) | 0.1374401 (0.063555) |
| Silver | КД521В diode | 3 | 0.0000278 | 0.0000834 |
| Silver | КС220Ж zener | 1 | 0.0000462 | 0.0000462 |
| Silver | К10-7В capacitor | 1 | 0.0055 | 0.0055 |
| Silver | К10-7В capacitor | 2 | 0.0049638 | 0.0099276 |

The component leads contain no precious metals.

### Warranty terms (summary)

- 24 months from the date of sale. If the retailer's mark is missing, the period runs from the factory release date.
- The batteries are not covered.
- No claims are accepted without the warranty card, or if the seals on the calculator or the power supply have been broken.
- Faults caused by breaking the operating rules are not covered.
- Replacement through the retail network only, and only on the written finding of a repair enterprise.
- Repairs were done by Rembyttekhnika (рембыттехника) and Soyuzschettekhnika (Союзсчеттехника) enterprises and regional electronics service centres.
- The passport includes three tear-off warranty repair coupons and a customer feedback form addressed to the factory.

## Д2-37К Passport

| Parameter | Value |
|---|---|
| Purpose | Powering microcalculators |
| OKP codes | Д2-37М: 40 1398 4771; Д2-37К: 40 1398 4781 |
| Output "Р", stabilised | 5 ± 0.2 V at 0.14 A |
| Output "З" (charging), nominal | 2.7 ± 0.5 V at 0.026 A |
| Input | 220 V, 50 Hz |
| Dimensions | 75 × 51 × 68 mm |
| Mass | ≤ 0.26 kg |
| Precious metals | Gold 0.0007 g, silver 0.0095 g, platinum 0.0002 g |
| Copper and its alloys | 25.5 g |
| Storage | 5–35 °C, relative humidity up to 85% |
| Warranty | 24 months |
| Specification | 2.087.066 ТУ. Made under state acceptance (госприёмка). |
| Supplied contents | Power supply, passport, box |

**Circuit:**

- Transformer T1 has a centre-tapped secondary feeding a full-wave rectifier, VD1 and VD2 (КД243А), and C1 (470 µF).
- **D1, a КР142ЕН5А (Soviet 7805 equivalent),** regulates to 5 V, with C2 (1 µF) on its output.
- The regulator's +5 V output goes to the terminal marked **"Общ."** (common), and its ground goes to **"Р"**. That makes Р **−5 V relative to common**.
- The charging output "З" is a half-wave feed through VD3 (КД243А), R1 (150 Ω) and switch S1. At 26 mA it is about C/10 for the 260 mAh cells.
- The passport notes that the manufacturer may use different components, provided performance is not worse.

**Note for use outside the USSR:** the adapter is rated for 220 V +10/−15%. That allows up to 242 V, which covers nominal 230/240 V mains, but its transformer will run warmer. Check the insulation and C1 before relying on an original unit.
