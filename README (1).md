# FACT-Score Calculator

**Facial-fracture Adverse-event Clinical Triage (FACT) Score**

A temporally validated clinical risk stratification tool for 30-day surgical complications after operative facial fracture repair.

## About

The FACT-Score uses five perioperative variables to estimate the probability of 30-day postoperative complications:

1. **Operative time** (minutes)
2. **Fracture type** (Mandible, ZMC, Orbital, LeFort, Multiple)
3. **Wound classification** (Clean, Clean/Contaminated, Contaminated, Dirty/Infected)
4. **ASA physical status** (I-IV)
5. **Smoking status** (Yes/No)

### Risk Tiers

| Tier | Threshold | Observed Rate | Recommended Action |
|------|-----------|--------------|-------------------|
| Low | < 3.5% | 1.8% | Standard postoperative care |
| Moderate | 3.5-10% | 7.1% | Enhanced monitoring, next-day wound check |
| High | >= 10% | 22.8% | Extended observation (>=48h), proactive surveillance |

### Validation

- **Cohort:** 4,805 adults, ACS-NSQIP 2007-2022
- **Temporal validation:** AUC 0.797 (95% CI 0.755-0.839)
- **Calibration:** Intercept -0.02, Slope 0.978
- **High vs Low OR:** 15.88 (95% CI 8.78-31.25)

## Privacy

This calculator runs entirely in the browser. No patient data is transmitted, stored, or logged. The tool contains only published regression coefficients - no individual patient records.

## Citation

Catic A, Karamitros G, Barbieri S. The FACT Score: Development and Temporal Validation of a Clinical Risk Stratification Tool for 30-Day Complications After Operative Facial Fracture Repair. *J Craniofac Surg.* 2026.

## Disclaimer

This tool is provided for research and clinical decision support only. It is not a substitute for clinical judgement.
