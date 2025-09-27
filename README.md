# ME302: Compressor Operation Map Analysis

Scaling analysis of a closed-loop turbomachinery test facility, ensuring Mach and Reynolds similarity under structural and operational constraints.

---

## 📌 Abstract
This project determines the **maximum geometric scaling factor** that can be applied to a closed-loop turbomachinery test facility.  
The facility must satisfy:
- Structural constraint: **p < 250 kPa** throughout the loop  
- Closed-loop flow condition: **p₀₅ ≥ p₀₁**  
- Similarity conditions for Mach number (**M = 0.55**) and Reynolds number (**Re = 3.0×10⁶**)  

Using compressor map data and Python-based analysis, the study computes the scale, pressures, and validates feasibility.

---

## ⚙️ Methodology
1. Derived expressions for scaling factor **s** from Mach & Reynolds similarity.  
2. Incorporated compressor map data into the formulation.  
3. Developed a **Python script** to compute scaling factor and stagnation pressures.  
4. Checked results against **structural and operational constraints**.  

---

## ✅ Key Results
- **Maximum Scaling Factor (s):** 0.618  
- **Inlet Stagnation Pressure (p₀₁):** 204.7 kPa  
- **Compressor Exit Pressure (p₀₂):** 247.8 kPa  
- All computed pressures < 250 kPa ✅  
- Closed-loop feasibility satisfied: **p₀₅ ≥ p₀₁**



