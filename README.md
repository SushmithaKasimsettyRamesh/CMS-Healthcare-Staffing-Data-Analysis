# CMS Nursing Home Staffing Analysis for Clipboard Health

## Executive Summary
Analysis of CMS Payroll Based Journal (PBJ) data to identify high-opportunity sales targets for Clipboard Health's staffing platform. This comprehensive analysis examines 2024Q2 data across multiple dimensions to provide actionable recommendations for the sales leadership team.

## Key Findings Overview
- **28.9M+ contractor hours** analyzed across all US nursing facilities
- **341 high-dependency facilities** identified as immediate targets
- **$7.15B in penalties** represent opportunity for facilities with low contractor usage
- **Significant weekend staffing gaps** across all staff categories

---

## Recommendation 1: Target High Contractor Dependency Facilities
### 🎯 **Immediate Action Required**

**Finding:** 341 facilities with average contractor dependency ratio of 43.8% (6× national average)

**Business Impact:** These facilities already rely heavily on contractors and represent the easiest conversion targets

**Implementation:**
- Prioritize outreach to these 341 facilities
- Position Clipboard Health as a more efficient contractor solution
- Expected high conversion rate due to existing contractor dependency

**Supporting Analysis:** `notebooks/recommendation_1_high_dependency_facilities.ipynb`

---

## Recommendation 2: Address Critical Weekend Staffing Gaps
### ⏰ **Weekend Opportunity**

**Finding:** Weekend staffing dramatically lower than weekdays:
- RN weekend staffing: 60.4% of weekday levels
- LPN weekend staffing: 37.0% of weekday levels  
- CNA weekend staffing: 36.9% of weekday levels

**Business Impact:** Massive untapped market for weekend contractor staffing

**Implementation:**
- Develop weekend-specific contractor packages
- Target facilities with lowest weekend contractor utilization
- Create "Weekend Staffing Solutions" sales campaign

**Supporting Analysis:** `notebooks/recommendation_2_staffing_gaps_analysis.ipynb`

---

## Recommendation 3: Target High-Penalty, Low-Contractor Facilities
### 💰 **ROI Opportunity**

**Finding:** 1,043 facilities facing $7.15B in penalties with average contractor usage of only 0.22%

**Geographic Concentration:**
- Texas: 120 facilities
- California: 79 facilities  
- Washington: 62 facilities
- Mississippi: 45 facilities
- Iowa: 45 facilities

**Business Impact:** Clear ROI story - contractor costs vs. penalty costs

**Implementation:**
- Create penalty calculator tool for sales reps
- Develop state-specific campaigns
- Position staffing as penalty reduction strategy

**Supporting Analysis:** `notebooks/recommendation_3_penalty_opportunity_analysis.ipynb`

---

## Recommendation 4: Focus on High-Census, Low-Contractor Facilities
### 📊 **Capacity Mismatch Targets**

**Finding:** Facilities with high resident census but underutilized contractor staffing

**Top Targets:**
- NY Facility: 150 residents, 4.11% contractor usage (Imbalance Score: 128.42)
- TX Facility: 120 residents, 3.54% contractor usage (Imbalance Score: 103.35)
- MI Facility: 110 residents, 20.51% contractor usage

**Implementation:**
- Target facilities in "high census, low contractor" quadrant
- Emphasize scalability benefits of contractor staffing
- Focus on facilities with 100+ residents and <10% contractor usage

**Supporting Analysis:** `notebooks/recommendation_4_census_imbalance_analysis.ipynb`

---

## Technical Implementation

### Data Sources
- CMS Payroll Based Journal (PBJ) Q2 2024
- CMS Provider Information Dataset
- CMS Penalties Dataset

### Key Metrics Calculated
- Contractor Dependency Ratio (CDR)
- Hours Per Patient Day (HPPD)  
- Opportunity Scores
- Imbalance Scores

### Tools Used
- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebooks
- CMS.gov datasets

## Repository Structure
```
├── notebooks/           # Individual analysis notebooks
├── data/               # Processed datasets
├── visualizations/     # Charts and plots
└── requirements.txt    # Python dependencies
```

## Next Steps
1. Sales team to prioritize the 341 high-dependency facilities
2. Develop weekend staffing campaign materials
3. Create penalty-reduction ROI calculators
4. Implement geographic targeting strategy for top 5 states

---

*Analysis completed using CMS Q2 2024 data. Contact for questions about methodology or implementation.*
