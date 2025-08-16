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

##  Photos & Diagrams

- ![alt text](asset/koppen.png)  
- ![alt text](asset/kop.jpg)
- ![alt text](asset/kopp.jpg)

---

##  Bill of Materials (BOM)

| Component                                | Purpose                             | Cost (USD) | Source |
|------------------------------------------|--------------------------------------|------------|--------|
| PVC Pipes                 | Structural housing                   | $26        | [link](https://www.amazon.eg/-/en/Meksular-12mm-ID-15mm-OD/dp/B0BCJZT74X/) |
| Mesh Filter (cotton fiber)              | Captures solids                      | $21         | [link](https://www.amazon.eg/-/en/Filter-Capsule-Refrigerator-Screen-Blue2pc/dp/B0F5BVZLRL/) |
| Activated Carbon (coal)                 | VOC + chlorine removal               | $25        | [link](https://www.amazon.com/Activated-Charcoal-Gummies-Supplements-Coconut/dp/B0BTVS1PW4?th=1) |
| Ion Exchange Resin                      | Removes salts/metals                 | $21        | [link](https://www.alibaba.com/product-detail/Lowest-Price-EXTREPURE-strong-acid-cation_1600292886243.html?)|
| Water Pump (12V) ×2                     | Moves water                          | $34.6      | [Amazon](https://www.amazon.eg/Ultra-Fountain-Height-Submersible-Aquarium/dp/B0DTFKNHMS) |
| Arduino Due + jumper wires              | Controls flow + PEF logic            | $61   | [Arduino Store](https://store.arduino.cc/products/arduino-due) |
|Breadboard kit for also the jumpers	| connecting| $31.07| [link](https://ar.aliexpress.com/item/1005009232305446.html?)|
| Electrodes                     | PEF (pathogen elimination)           | $27        | [link](https://ar.aliexpress.com/item/1005004637566449.html?) |
| Sulfuric Acid (H₂SO₄)                   | Optional pH control                  | $25        | [link](https://www.alibaba.com/product-detail/Sulphamic-Acid-Sulfamic-Acid-5329-14_1600587438591.html?) |
| Hydrochloric Acid (HCl)                 | Converts carbonate/pH                | $2.7        | [link](https://www.alibaba.com/product-detail/Acid-Corrosion-Inhibitor-Oilfield-for-Hydrochloric_1600950548123.html?) |
| Sodium Hydroxide (NaOH)                 | Neutralizes acid                     | $4.2        | [link](https://www.alibaba.com/product-detail/New-Technology-Low-sodium-Aluminum-Hydroxide_1601008916711.html?) |
| TDS             | Measures water purity                | $15        | [link](https://www.amazon.eg/-/en/Detection-Module-Filter-Measuring-Quality/dp/B0FK5Y9R8Q/) |
| pH              | Measures water purity                | $44        | [link](https://www.amazon.eg/-/en/Generic-YY6237-Analog-Sensor-Kit/dp/B0FD4YSQQ7/) |
| Turbidity sensors              | Measures water purity                | $14        | [link](https://ar.aliexpress.com/item/32995232611.html?) |

**Total Cost: $310**


