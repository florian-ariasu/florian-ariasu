Computer Science and Information Technology student at Politehnica University of Bucharest, currently interning as an Application Support Engineer at IDEMIA Secure Transactions. I build 
across software engineering, applied AI, and systems programming. I care about the craft around the code — structured repositories, clean documentation, and consistent standards across 
every project I ship.

---

## Relevant Projects

### [Dental Caries Detection](https://github.com/florian-ariasu/dental-caries-cascade)
*A two-stage cascade system for dental caries detection in panoramic radiographs, combining YOLOv8 localization with ResNet50 patch verification to improve diagnostic precision.*

- Engineered a hybrid decision pipeline to suppress false positives caused by radiological artefacts and metallic restorations, achieving a global mAP50 of 0.938.
- Coordinated the processing of over 18,000 dental image patches, producing a robust training environment for early-stage lesion detection.
- Conducted a structured comparative evaluation between the baseline and cascade system, documenting methodological limitations in a final IEEE-format report.

`Python` `YOLOv8` `ResNet50`

### [Java Banking System](https://github.com/florian-ariasu/java-banking-system)
*Java platform built around Command, Factory, and Strategy design patterns with premium financial logic.*

- Modelled a commission engine using the Strategy pattern, enabling runtime-configurable rules across standard and premium user tiers.
- Implemented an SMA crossover algorithm for stock recommendations, integrating multi-currency exchange logic with a CSV-driven rate matrix.
- Applied Command and Factory patterns to decouple input parsing from business logic, producing a clean, extensible command-driven architecture.

`Java` `Gradle`

### [RSA-CRT PACD Fault Injection Attack](https://github.com/florian-ariasu/rsa-crt-pacd-attack)
*Lattice-based fault injection attack on RSA-CRT signatures implementing PACD reduction to HNP with LLL, based on Barbu et al. (IACR 2024).*

- Implemented the PACD attack with implicit reduction to HNP via SDA lattice construction in SageMath, recovering the secret prime factor from partially corrupted signatures (L=7 MSBs zeroed, t=61–70 signatures).
- Evaluated success rate across lattice dimensions and fault parameters, confirming the qualitative behaviour described in the reference paper with results matching the 2024 state-of-the-art threshold.
- Documented methodology, experimental comparison, and countermeasure analysis (multiplicative blinding) in a structured LaTeX report.

`Python` `SageMath` `Cryptography` `LaTeX`

### [OpenBook — Open-Source E-Reader](https://github.com/florian-ariasu/openbook-e-reader)
*An open-source hardware project for building a portable, ESP32-C6–based e-book reader with an E-Paper display, microSD storage, USB-C power/data, and Li-Po battery support.*

- Designed the full ESP32-C6 pinout across SPI and I²C buses, integrating the E-Paper display, BME680 sensor, RTC, fuel gauge, NOR flash, and microSD card on shared communication lines.
- Managed the PCB routing phase in Autodesk Fusion 360, resolving DRC and ERC violations and manually approving non-critical SMD hole warnings after physical verification.

`ESP32-C6` `Autodesk Fusion 360` `E-Paper Display`

**Other Projects**
- [IIR Filter Design](https://github.com/florian-ariasu/iir-filter-design) — Butterworth and Chebyshev-I low-pass IIR filters implemented from scratch in Python, applied to ECG denoising. `Python`
- [Air Traffic Control System](https://github.com/florian-ariasu/air-traffic-control-system) — OOP Java ATC system with generic runways, priority-based scheduling, and custom exceptions. `Java` `Gradle`

---

## Technical Skills

| Category | Details |
| :--- | :--- |
| **Languages** | Java · C · C++ · C# · Python · Lua |
| **Tools** | Git · GitHub · Bash/Zsh · Ubuntu · Docker · Gradle · Jupyter |
| **AI Usage** | Daily driver — across development, debugging, research, writing, and tooling |
| **Practices** | Technical Documentation (IEEE Format) · Structured repo organisation · Markdown |

---

## Education

**B.Eng. in Computer Science and Information Technology**
Politehnica University of Bucharest — Faculty of Automatic Control and Computer Science
*2022 – 2027 (expected)*
