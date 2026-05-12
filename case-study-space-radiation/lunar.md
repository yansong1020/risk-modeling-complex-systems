# Lunar Surface Mission

## Objective
Assess radiation risk for a 14-day crewed mission on the lunar surface, where exposure occurs entirely outside Earth’s geomagnetic shielding.

---

## Environment

Unlike LEO, the lunar surface has:

- No atmospheric shielding  
- No geomagnetic protection  

Radiation exposure is fully determined by interplanetary conditions.

Two components dominate:

- Continuous background from Galactic Cosmic Rays (GCR)  
- Intermittent but intense Solar Energetic Particle (SEP) events  

---

## Approach

This study applies a probabilistic risk assessment (PRA) framework to evaluate both continuous and event-driven exposure.

- GCR exposure modeled using :OLTARIS (Badhwar–O’Neill 2020 model)  
- Habitat shielding: 10 g/cm² aluminum equivalent  
- SEP events modeled using long-term F₃₀ statistics (Usoskin & Kovaltsov, 2012) as input parameters to OLTARIS SEP events model
- Event occurrence modeled as a Poisson process over a 14-day mission  

---

## Key Results

### Baseline Exposure (GCR)

- **GCR dose (14 days): 9.358 mSv**

---

### SEP Event Contribution

- Event doses: **127 mSv to 634 mSv**  
- Per-mission probabilities:  
  - ~3.8 × 10⁻⁴ (moderate extreme)  
  - ~3.8 × 10⁻⁶ (very extreme)

Expected SEP contribution:

- **E[D_SEP] = 6.32 × 10⁻² mSv**

---

### Total Expected Dose

- **E[D_total] ≈ 9.42 mSv**

---

## Risk Structure Insight

The lunar radiation environment exhibits a **dual-risk structure**:

### 1. Continuous Risk (GCR)
- Dominates expected dose  
- Drives cumulative exposure over mission duration  

### 2. Contingent Risk (SEP)
- Extremely high consequence (up to hundreds of mSv)  
- Very low probability  
- Not reflected in expected value alone  

Extreme SEP events do not dominate expected dose,  
but they **define the worst-case exposure scenario**.

---

## Design Implications

Unlike LEO, where operational response plays a major role, lunar missions rely heavily on **built-in protection**:

- Habitat shielding becomes a primary design driver  
- Dedicated storm shelter capability is required  
- Protection must account for extreme SEP scenarios, not just average exposure  
- Design must balance:
  - Continuous GCR exposure  
  - Rare but severe SEP events  

Radiation risk must be treated as both a **baseline design constraint** and a **contingency-driven requirement**.

---

## Key Takeaway

Radiation risk on the lunar surface is not defined by average exposure.

It is shaped by the coexistence of:

- **Continuous background risk (GCR)**  
- **Intermittent, potentially dose-dominant events (SEP), spanning moderate to extreme scenarios**  

This fundamentally shifts radiation from an environmental factor  
to a **primary architectural constraint** in mission design.
