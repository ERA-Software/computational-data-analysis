# Suggested project tracks

## Track 1: Heat-risk screening

**Guiding question**  
Which locations are most at risk of high heat exposure?

**Tasks**
- Define a heat-risk metric (e.g., exceedance rate, 95th percentile)
- Rank stations by risk
- Compare rankings under different:
  - thresholds
  - filtering strategies

**Required analysis**
- Stability of rankings over time
- Sensitivity to threshold and data filtering

**Decision framing**  
Where should mitigation or intervention be prioritized?

---

## Track 2: Heat alert system

**Guiding question**  
Can we predict high-heat events reliably enough to trigger alerts?

**Tasks**
- Define a binary target (e.g., temperature above threshold)
- Train a classification model
- Tune the decision threshold

**Required analysis**
- Precision vs recall trade-off
- False positives vs false negatives
- Performance across time (e.g., extreme vs normal periods)

**Decision framing**  
What alert threshold should be used given the trade-off between missed events and false alarms?

---

## Track 3: Drivers of heat risk

**Guiding question**  
What factors are most associated with high heat risk, and how robust are these insights?

**Tasks**
- Define a target (continuous or binary)
- Train baseline and improved models
- Identify important features (e.g., coefficients, feature importance)

**Required analysis**
- Rank and interpret key drivers (direction + magnitude)
- Sensitivity to:
  - feature selection
  - time subsets
  - threshold definition
- Discuss limitations 

**Decision framing**  
What factors should be prioritized to reduce heat risk?

---

## Track 4: Monitoring and representativeness

**Guiding question**  
How much data is needed to obtain stable heat-risk estimates?

**Tasks**
- Define a heat-risk metric
- Compute it using different time windows (e.g., 2 weeks, 1 month, 2 months)
- Shift windows in time

**Required analysis**
- Stability of estimates across:
  - window length
  - window position
- Quantify variability

**Decision framing**  
How long should we monitor to obtain informative conclusions?

---

## Note on alternative project framings

Students may propose their own project framing instead of selecting one of the tracks above.  
Such proposals must:
- Be clearly formulated and aligned with the dataset
- Include a well-defined analytical pipeline (data → model → validation → decision)
- Be approved by the instructors in advance

The key requirement is that the project is consistent with the goals of the course.