# Technical Inventory: Global Neurotechnology & BCI Landscape (2026)

## 1. High-Density Intracortical & CMOS-Integrated Interfaces
*Focus: Scaling channel counts ($N$) while minimizing the physical footprint of the "wiring bottleneck" through on-chip signal processing.*

| Company | Lead / Origin | Core Technology | Biophysical Moat |
| :--- | :--- | :--- | :--- |
| **Corticale** | Berdondini / Italy | SiNAPS CMOS Probes | High-density active pixels for large-scale extracellular mapping; minimizes passive lead-count issues. |
| **Paradromics** | USA | Connexus® DDI | "Micro-wire" bundle bonded to a CMOS sensor; treats the cortex as a high-bandwidth data bus ($Gpbs$). |
| **Blackrock Neurotech** | USA | Utah Array (Pedestal) | The clinical gold standard for $SL$ (Single-Unit) recording; robust longitudinal human data. |
| **Mint Neuro** | UK | Ultra-low-power ASICs | Focus on the thermal-dissipation limit ($<1^\circ\text{C}$); critical for high-density implanted computation. |

---

## 2. Flexible ECoG & Surface Interfaces
*Focus: High-resolution recording without penetrating the Blood-Brain Barrier (BBB), utilizing MEMS and thin-film materials.*

* **Precision Neuroscience (USA):** * *Technology:* The Layer 7 Cortical Interface. 
    * *Nuance:* High-density micro-ECoG that provides "semi-invasive" mapping. By staying above the parenchyma, they avoid the chronic inflammatory response/gliosis typical of penetrating silicon.
* **NeuroOne (USA):** * *Technology:* Thin-film electrodes for cortical mapping. Primarily focused on clinical epilepsy and functional neurosurgery.
* **GBrain (South Korea):** * *Technology:* Graphene-based electrodes. 
    * *Insight:* Leveraging the unique electrochemical properties of graphene to achieve exceptionally low impedance ($Z$) at small geometric surface areas.

---

## 3. Visual Prosthetics & Sensory Restoration
*Focus: Bridging the gap between optoelectronic sensors and the visual hierarchy (Retina or V1).*

* **Science Corporation (USA):** * *Project:* PRIMA. 
    * *Mechanism:* A subretinal photovoltaic implant. It converts light into electrical pulses to stimulate the inner retina, bypassing degenerated photoreceptors.
* **Phosphoenix (Netherlands):** * *Project:* Visual Cortical Prosthesis. 
    * *Mechanism:* Direct intracortical stimulation of the visual cortex (V1) to generate phosphenes, circumventing the optic nerve entirely.

---

## 4. Bioelectronic Medicine: Vagal Nerve Stimulation (VNS)
*Focus: Modulating the Autonomic Nervous System (ANS) to influence systemic physiology via the Inflammatory Reflex.*

* **SetPoint Medical (USA):** * *Application:* Rheumatoid Arthritis & Crohn’s. 
    * *Theory:* Targeted stimulation of the Vagus nerve to activate the "Cholinergic Anti-inflammatory Pathway," reducing systemic $TNF$-$\alpha$ and other pro-inflammatory cytokines.
* **Neuroloop (Germany):** * *Application:* Hypertension (Baroreceptor modulation). 
    * *Design:* Multi-channel cuff electrodes (with B. Braun) allowing for "selective" stimulation of specific fiber bundles within the Vagus nerve.
* **CorTec (Germany):** * *Application:* Closed-loop "Brain Interchange" system. 
    * *Design:* High-performance cuff electrodes and implantable "hubs" for bi-directional peripheral and central communication.

---

## 5. Specialized Neural Platforms
* **Canaery (USA):** * *Focus:* "Neuro-olfactory" BCI. Using the biological olfactory bulb as a high-sensitivity chemical sensor for industrial/defense applications.
* **Science Corp (Beyond PRIMA):** * *Focus:* Building a verticalized neurotech "foundry" for high-bandwidth neural interfaces.

---

### Collaborative Analysis & Critical Gaps:
* **Electrode-Tissue Impedance ($Z$):** While many of these companies (GBrain, Corticale) focus on density, the long-term stability of the $Si/SiO_2$ or Metal interface remains the primary failure mode.
* **Power/Data telemetry:** For the high-bandwidth systems (Paradromics, Precision), the $I^2R$ heating of the transmitter is often the limiting factor for true "wireless" chronic use.
