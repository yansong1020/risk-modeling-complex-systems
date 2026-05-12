# Low Earth Orbit (LEO)

## Objective
Evaluate radiation exposure for a 5-day crewed mission in Low Earth Orbit (LEO) and assess the impact of a significant solar energetic particle (SEP) event.

---

## Mission Scenario

- Circular orbit at 400 km altitude  
- Inclination: 51.6° (ISS-like orbit)  
- Mission duration: 5 days  

---

## Approach

The baseline radiation environment was modeled using OLTARIS, accounting for:

- Galactic Cosmic Rays (GCR) using the Badhwar–O’Neill 2020 model  
- Trapped protons using the AP9 model  
- Shielding represented by 10 g/cm² slab geometry  
- Human exposure modeled using the CAF anatomical model  

To evaluate event-driven risk, this study incorporates in-situ measurements from the March 7–8, 2012 SEP event observed aboard the ISS.

---

## Key Results

Baseline cumulative dose (5-day mission):

- GCR: 0.734 mSv  
- Trapped protons: 1.096 mSv  
- **Total baseline: 1.859 mSv**

SEP event contribution:

- Additional dose: ~0.448 mSv  
- **Increase: ~24% over baseline**

---

## Risk Insight

The results show that SEP events are not dominant under nominal conditions but can **significantly increase cumulative exposure over short durations**.

A single strong SEP event can increase total mission dose by ~24%.

More severe events would result in substantially higher short-term exposure.

his establishes SEP as a **time-critical hazard**, rather than a background risk.

---

## Design Implications

In LEO missions, orbital parameters are largely fixed. Radiation risk mitigation must therefore be addressed through system and architectural design:

- Incorporate localized shielding in designated protection zones  
- Ensure availability of accessible shielded areas for crew during events  
- Integrate continuous radiation monitoring with space weather data  
- Define operational thresholds based on dose rate and cumulative exposure  

Embedding these capabilities early enables **real-time, metric-driven decision-making** during elevated radiation conditions.

---

## Key Takeaway

Radiation risk in LEO is not purely cumulative.

👉 Short-duration events can materially alter mission exposure and must be treated as **operationally actionable hazards**, not just environmental background.
