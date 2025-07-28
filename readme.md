# Ion Cleanse

##  What is it?

**Ion Cleanse** is a low-cost, 5-stage water purification device designed to clean polluted canal water. It combines **physical filtration, electric sterilization (PEF), and chemical adsorption** to remove solids, bacteria, and harmful ions like lead or mercury.

##  Why did I build it?

Canal water in many urban and rural regions is contaminated, making it unsafe for direct use or irrigation. I wanted to build a **modular**, **portable**, and **smart** purification device that uses **accessible components** and offers real-time monitoring.

##  System Overview

- **Stage 1:** Cotton Mesh Filter → traps visible solids  
- **Stage 2:** PEF Chamber → electric field sterilizes bacteria/viruses  
- **Stage 3:** Activated Carbon → removes chlorine, odor, VOCs  
- **Stage 4:** Ion Exchange Resin → removes heavy metals and salts  
- **Stage 5:** Chemical Chamber → pH correction (optional)

###  Features

- **Arduino Nano** controls pump flow & electric pulses  
- **3x 12V Water Pumps** for multi-stage flow  
- **TDS, pH, and Turbidity Sensors** for live monitoring  
- **PVC housing** with removable caps for easy cleaning  
- **Real-world testing** showed up to **62% TDS reduction** in canal water samples

##  Photos & Diagrams

- ![alt text](<koppen.png>)  
- ![alt text](kop.jpg)
- ![alt text](kopp.jpg)

---

##  Bill of Materials (BOM)

| Component                                | Purpose                             | Cost (USD) | Source |
|------------------------------------------|--------------------------------------|------------|--------|
| PVC Pipes (4 sections)                   | Structural housing                   | $18        | Local store |
| Mesh Filter (cotton fiber)              | Captures solids                      | $6         | Fabric store |
| Activated Carbon (coal)                 | VOC + chlorine removal               | $12        | Aquarium supply |
| Ion Exchange Resin                      | Removes salts/metals                 | $10        | resintech.com |
| Water Pump (12V) ×3                     | Moves water                          | $49.5      | [Amazon](https://www.amazon.eg/Ultra-Fountain-Height-Submersible-Aquarium/dp/B0DTFKNHMS) |
| Arduino Due + jumper wires              | Controls flow + PEF logic            | $61 + $13  | [Arduino Store](https://store.arduino.cc/products/arduino-due) |
| Electrodes (2 pcs)                      | PEF (pathogen elimination)           | $16        | Local lab supply |
| Sulfuric Acid (H₂SO₄)                   | Optional pH control                  | $14        | Sigma Aldrich |
| Hydrochloric Acid (HCl)                 | Converts carbonate/pH                | $18        | Sigma Aldrich |
| Sodium Hydroxide (NaOH)                 | Neutralizes acid                     | $13        | Chemical supplier |
| TDS, pH, Turbidity sensors              | Measures water purity                | $70        | [DFRobot](https://www.dfrobot.com) |
| Misc. wires, connectors, tubing         | Assembly                             | $16        | General store |

**Total Cost: $316.5**
