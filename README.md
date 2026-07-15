# Kindastuff Solar Analytics
 
**Free, browser-based solar PV calculators for O&M engineers, asset managers, and EPC professionals.**

No sign-ups. No data uploads. All calculations run locally in your browser.
 
🌐 **[kindastuff.com](https://kindastuff.com/)**

---

## Available Calculators
 
### Generation Metrics

| Tool | What It Calculates |
| :-- | :-- |
| [CUF / PLF](https://kindastuff.com/conventional-cuf-or-plf/) | Capacity Utilization Factor against DC or AC capacity — accepts both IEC 61724-1 and PPA conventions |
| [Degradation & Insolation Corrected CUF](https://kindastuff.com/degradation-insolation-corrected-cuf/) | CUF adjusted for module aging and irradiance deviation from design-year assumptions |
| [Specific Yield & PTI](https://kindastuff.com/yield-performance-metrics/) | Final Yield (kWh/kWp) per IEC 61724-1 §7.3 and Performance Target Index |
| [NMGG Calculator](https://kindastuff.com/nmgg-calculator/) | Net Minimum Guaranteed Generation targets for contractual compliance |

### Performance Ratio Analytics
 
| Tool | What It Calculates |
| :-- | :-- |
| [Capacity-Based PR](https://kindastuff.com/capacity-based-pr/) | Performance Ratio using DC nameplate capacity and POA insolation — IEC 61724-1 §7.5 |
| [Efficiency-Based PR](https://kindastuff.com/efficiency-based-pr/) | PR using total active module area and rated module efficiency |
| [Instantaneous PR](https://kindastuff.com/instantaneous-pr/) | Real-time PR from SCADA power and irradiance readings |
| [Temperature-Corrected PR](https://kindastuff.com/temperature-corrected-pr/) | PR normalized for module temperature using manufacturer temperature coefficient — IEC 61724-1 Annex B |

### Diagnostic & Corrected Analytics
 
| Tool | What It Calculates |
| :-- | :-- |
| [Soiling Analysis](https://kindastuff.com/soiling-analysis/) | Module conversion efficiency before and after cleaning events — supports up to 20 sample pairs |
| [Solar Inverter Efficiency Dashboard](https://kindastuff.com/solar-inverter-efficiency-dashboard/) | DC-to-AC conversion efficiency per inverter from CSV/Excel uploads — batch analysis up to 5 inverters |

 
### Availability & Loss Analytics
 
| Tool | What It Calculates |
| :-- | :-- |
| [Plant & Grid Generation Loss](https://kindastuff.com/plant-grid-generation-loss/) | Loss attribution between plant-side and grid-side causes |
| [Plant & Grid Availability](https://kindastuff.com/plant-and-grid-availability/) | Downtime analysis against irradiance-weighted available hours |

 
### Solar Resource Analytics
 
| Tool | What It Calculates |
| :-- | :-- |
| [Solar Insolation — POA](https://kindastuff.com/solar-insolation-calculator/) | Back-calculate plane-of-array insolation from plant output data |
 
---
 
## Calculation Methodology
 
All calculators are built on publicly documented engineering standards. Formulas, variable definitions, input validation rules, and standard references are published in full:

👉 **[METHODOLOGY.md](METHODOLOGY.md)**
 
Standards referenced include:
 
| Standard | Scope |
| :-- | :-- |
| IEC 61724-1:2021 | PV system performance monitoring — yield, PR, and loss indices |
| IEC 61724-2:2016 | Capacity evaluation method |
| IEC 61724-3:2016 | Energy evaluation method |
| IEC 61215-1:2021 | Module design qualification — basis for degradation rates |
| IEC 61683:1999 | Inverter efficiency measurement procedure |
 
---

## Privacy-First Architecture
 
Most solar software requires account creation and server-side data processing. Kindastuff does not.
 
- All calculations execute in the user's browser via JavaScript
- No plant data, energy figures, or inputs are transmitted to any server
- No database storage of any kind
- Google Analytics is used for basic traffic measurement only — no input data is captured
This matters for O&M teams and asset managers working with commercially sensitive generation data.
 
---

## Built by a Solar Professional
 
Kindastuff was created by **Aman Yadav**, a solar plant performance engineer with hands-on experience in plant operations, performance monitoring, and data analytics.
 
The tools reflect real O&M workflows — not theoretical use cases. Each calculator handles the edge cases that matter in practice: DC vs. AC capacity conventions, irradiance sensor data quality flags, temperature correction direction, soiling measurement methodology, and inverter data validation.
 
📫 **[LinkedIn — Aman Yadav](https://www.linkedin.com/in/aman-yadav55/)**

---
 
## Feedback and Issues
 
Found a calculation error? Have a feature request? Want to suggest a new calculator?
 
👉 **[Open an Issue](https://github.com/kindastuff/solar-analytics-calculators/issues)**
 
Calculation errors are treated as high priority. If you believe a formula deviates from the referenced standard, open an issue with the specific section reference and expected result.
 
---

## License
 
This repository documents the methodology behind the calculators at kindastuff.com. The website source code is not open-source.
 
Repository content is available under the **MIT License**.
 
---
 
⭐ If you find these tools useful, starring this repository helps other solar professionals discover it.

