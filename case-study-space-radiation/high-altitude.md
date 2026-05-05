# High-Altitude Flight (~30 km)

## Objective
Assess radiation risk during near-space high-altitude flights (~30 km), with a focus on rare but high-impact solar energetic particle events (GLEs).

---

## Approach

This analysis applies a probabilistic risk assessment (PRA) framework to quantify radiation exposure from Ground Level Enhancement (GLE) events.

- GLEs are categorized into four classes: Weak, Strong, Severe, and Extreme  
- Each class is modeled as a Poisson process based on historical event frequency  
- For a representative 6-hour flight, the probability of occurrence is estimated for each class  
- Expected radiation dose is calculated by combining event probability and dose consequence  

👉 This allows both likelihood and severity to be captured in a single risk metric.

---

## Key Result

The expected radiation dose contribution from GLE events per flight is:

**E[D_GLE] = 3.54 × 10⁻⁴ mSv**

Although this expected value is small, it masks an important risk structure.

---

## Risk Structure Insight

The results reveal a classic **low-probability, high-consequence** pattern:

- Weak and strong events occur more frequently but contribute little to total dose  
- Severe and extreme events are extremely rare  
- However, they dominate the expected dose due to their high magnitude  

👉 In particular, extreme events contribute disproportionately despite their very low probability.

---

## Exceedance Risk

The probability of exceeding key dose thresholds is summarized below:

- >1 mSv: ~1 in 47,000 flights  
- >20 mSv: ~1 in 135,000 flights  
- >100 mSv: ~1 in 1.75 million flights  

These results confirm that high-dose exposure is driven exclusively by rare extreme events.

---

## Design Implications

The PRA results suggest that radiation risk should not be managed using uniform conservative assumptions. Instead, targeted strategies are more effective:

- Optimize flight altitude and latitude to maximize geomagnetic shielding  
- Monitor solar activity and delay flights during elevated risk periods  
- Apply localized shielding in critical areas rather than across the entire structure  
- Establish operational procedures for crew relocation during in-flight events  

👉 This demonstrates how probabilistic risk modeling can directly inform architectural and operational decisions.
