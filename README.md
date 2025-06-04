Executive Summary
This report presents a data-driven analysis of the CMS Payroll Based Journal (PBJ) Q2 2024 data to help Clipboard Health identify strategic opportunities for expanding contractor staffing services. The analysis explores nationwide trends and pinpoints high-priority facilities where staffing solutions can generate measurable impact.

Key Findings Overview
28.9M+ contractor hours analyzed across all U.S. nursing facilities

341 high-dependency facilities identified as immediate sales targets

$7.15B in penalties — opportunity to position staffing as a cost-avoidance strategy

Major weekend staffing gaps across RN, LPN, and CNA roles

Recommendation 1: Target High Contractor Dependency Facilities
🎯 Immediate Action Required

Finding:
341 facilities have an average contractor dependency ratio of 43.8%, which is 6× the national average.

Business Impact:
These facilities already rely on contractors and are likely to convert quickly to Clipboard Health’s platform.

Implementation Steps:

Prioritize outreach to these 341 facilities

Position Clipboard Health as a more reliable and efficient solution

Highlight ease of transition due to existing dependency

Supporting Analysis:
notebooks/recommendation_1_high_dependency_facilities.ipynb

Recommendation 2: Address Critical Weekend Staffing Gaps
⏰ Weekend Opportunity

Finding:
Weekend staffing levels are significantly lower than weekdays:

RN: 60.4% of weekday staffing

LPN: 37.0%

CNA: 36.9%

Business Impact:
High unmet need for weekend coverage represents a strong growth area.

Implementation Steps:

Create weekend-specific contractor offerings

Launch a “Weekend Staffing Solutions” campaign

Target facilities with lowest weekend contractor usage

Supporting Analysis:
notebooks/recommendation_2_staffing_gaps_analysis.ipynb

Recommendation 3: Target High-Penalty, Low-Contractor Facilities
💰 ROI Opportunity

Finding:
1,043 facilities face $7.15B in penalties but use contractors at just 0.22% on average.

Top States (by facility count):

Texas: 120

California: 79

Washington: 62

Mississippi: 45

Iowa: 45

Business Impact:
Penalties provide a compelling ROI narrative — contractor staffing can reduce regulatory risk.

Implementation Steps:

Build a penalty calculator for sales reps

Create state-level marketing campaigns

Position contractor staffing as a penalty mitigation strategy

Supporting Analysis:
notebooks/recommendation_3_penalty_opportunity_analysis.ipynb

Recommendation 4: Focus on High-Census, Low-Contractor Facilities
📊 Capacity Mismatch Targets

Finding:
Facilities with large resident populations but minimal contractor use.

Examples:

NY Facility: 150 residents, 4.11% contractor usage (Imbalance Score: 128.42)

TX Facility: 120 residents, 3.54% usage (Score: 103.35)

MI Facility: 110 residents, 20.51% usage

Implementation Steps:

Prioritize “high census, low contractor” quadrant

Emphasize scalability of Clipboard Health staffing

Focus on facilities with 100+ residents and <10% contractor use

Supporting Analysis:
notebooks/recommendation_4_census_imbalance_analysis.ipynb

Technical Implementation
Data Sources:

CMS Payroll Based Journal (PBJ) Q2 2024

CMS Provider Information Dataset

CMS Penalties Dataset

Key Metrics Computed:

Contractor Dependency Ratio (CDR)

Hours Per Patient Day (HPPD)

Opportunity Scores

Imbalance Scores

Tools Used:

Python: pandas, numpy, matplotlib, seaborn

Jupyter Notebooks

CMS.gov public datasets

Repository Structure

notebooks/           - Individual analysis notebooks
data/                - Processed datasets
visualizations/      - Charts and plots
requirements.txt     - Python dependencies

Next Steps for Sales Leadership
1]Begin outreach to the 341 high-dependency facilities

2]Launch weekend-focused contractor campaign

3]Roll out penalty reduction ROI calculators

4]Initiate state-specific targeting for Texas, California, Washington, Mississippi, and Iowa
