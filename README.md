# Unraveling Telangana's Path to Inclusive Development: A Multi-Sectoral Empirical & Qualitative Analysis (2019–2024)
**BDM Capstone Project | Indian Institute of Technology Madras (IIT Madras)**
![Telangana-Formation-Day](https://raw.githubusercontent.com/jishnukoliyadan/Telangana-Inclusive-Growth-Analysis/refs/heads/main/assets/Telangana-Formation-Day.jpg)
## :pushpin: Project Overview & Context
This project delivers a multi-domain socio-economic and policy evaluation of Telangana's growth trajectory between **January 2019 and December 2024**. Utilizing high-frequency administrative datasets from **[Open Data Telangana](https://data.telangana.gov.in/)** combined with real-world qualitative ground-truthing from state news and policy documentation, this capstone investigates four core pillars of inclusive development:
1. **Industrial Governance & Speed:** Operational efficiency, bureaucratic friction, and pending incentive backlogs within the **TS-iPASS** framework and **Telangana MSME Policy 2024**.
2. **Digital Governance & Revenue Integrity:** Spatial adoption kinetics, slot booking mandates, and municipal revenue transfers of the **E-Stamp and Slot Booking systems** across land registrations.
3. **Agricultural Adaptation & Climate Volatility:** Structural mismatches between **farm mechanization** (tractor/equipment subsidies) and **monsoon unpredictability** (drought vs. flood cycles).
4. **Social Inclusion & Regional Balance:** Institutional approval timelines and market access challenges for marginalized entrepreneurs, including SC/ST sub-categorization impacts.
## :hammer_and_wrench: Data Architecture & Methodology
![Data_Architecture](https://raw.githubusercontent.com/jishnukoliyadan/Telangana-Inclusive-Growth-Analysis/refs/heads/main/assets/Data_Architecture.png)
### Data Sources & Metrics
All datasets were extracted from the **Open Data Telangana** portal covering the period from **January 2019 to December 2024**:
1. **TS-iPASS Approvals:** Unit counts, sector classifications, investment amounts (₹ Cr), employment generated, and approval lead times (days).m
	- Investment scale (₹ Cr), clearance times (days), employment numbers, and sector groupings across all 33 districts
	- Investment sizes, sector classifications, approval dates, and timeline delays across all 33 districts.
2. **RTA Vehicle Registrations:** Monthly counts of newly registered tractors, combine harvesters, and commercial agricultural haulage vehicles.
	- Monthly counts of tractor, combine harvester, and agricultural trailer registrations
	- Monthly tractor and agricultural equipment registration counts.
3. **Registration & Stamps Department:** Monthly revenue receipts, transaction counts, and e-stamp vs. physical stamp utilization ratios.
	- E-stamp utilization rates, physical stamp revenues, slot booking metrics, and municipal tax disbursements.
	- Document registration volumes, e-stamp vs. traditional stamp revenue.
4. **Directorate of Economics and Statistics:** Monthly district-level actual vs. normal rainfall figures (mm) and calculated Coefficient of Variation (CV).
	- District-wise actual vs. normal rainfall figures (mm), monsoon deviation metrics, and Coefficient of Variation (CV)
	- Monthly rainfall data and climate variance metrics.
5. **Policy & News Readings:** Qualitative media coverage, state budget releases, and government policy notifications.
### Methodology
* **Data Processing & Cleaning:** Handled missing attributes, standardized district boundaries post-reorganization, and aggregated monthly operational metrics.
* **Exploratory Data Analysis (EDA):** Correlation analysis between project investment tiers and clearance duration; spatial mapping of registration revenue and machinery deployment.
* **Policy Synthesis:** Translated data insights into actionable interventions for state governance and economic development.
## :open_file_folder: Key Project Deliverables & Reports
Access all primary project documents, reports, proposals, and presentations directly via the links below:

| Deliverable                    | Description                                                                                                    | Location / Link                                                                                                                                                             |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Project Proposal**           | Initial problem formulation, literature framework, dataset mapping, and methodological roadmap.                | [`Reports/01-Capstone-Project-Proposal.pdf`](https://github.com/jishnukoliyadan/Telangana-Inclusive-Growth-Analysis/blob/main/Reports/01-Capstone-Project-Proposal.pdf)     |
| **Supporting Articles & News** | Qualitative ground-truthing, media coverage, and policy contextualization across state domains.                | [`assets/Supporting-Articles.md`](https://github.com/jishnukoliyadan/Telangana-Inclusive-Growth-Analysis/blob/main/assets/Supporting-Articles.md)                           |
| **Final Submission Report**    | Complete academic report containing comprehensive methodology, EDA, empirical findings, and policy frameworks. | [`Reports/02-Capstone-Final-Submission.pdf`](https://github.com/jishnukoliyadan/Telangana-Inclusive-Growth-Analysis/blob/main/Reports/02-Capstone-Final-Submission.pdf)     |
| **Presentation Deck**          | Executive slide deck detailing core problem statements, visual findings, and strategic recommendations.        | [`Reports/03-Capstone-Final-Presentation.pdf`](https://github.com/jishnukoliyadan/Telangana-Inclusive-Growth-Analysis/blob/main/Reports/03-Capstone-Final-Presentation.pdf) |

## :bar_chart: Core Research Domains, Findings & Qualitative Ground-Truthing
### 1. Industrial Approvals, MSME Policy & Capital Scale (TS-iPASS)
- **Initial Hypothesis:** Small and Medium Enterprises (MSMEs) face systemic bureaucratic inertia and clearance delays compared to mega industrial projects.
- **Empirical Findings:** **Hypothesis Disproved on Pure Timelines, but Supported on Financial Friction**.
    - Micro/Small Enterprises ($< \text{₹1 Cr}$) average approval turnaround within **$\sim 25$ days** under TS-iPASS, whereas Mega-projects ($> \text{₹100 Cr}$) average **$\sim 100$ days** due to complex environmental, fire, and land-use compliance (e.g., Real Estate, Infrastructure, Textiles).
	- ![average_approval_delay_by_project_investment_size](https://raw.githubusercontent.com/jishnukoliyadan/Telangana-Inclusive-Growth-Analysis/refs/heads/main/assets/images/report_graphs/average_approval_delay_by_project_investment_size.png)
- **Qualitative News Insights:**
    - Despite fast clearance timelines, small firms face severe **working capital bottlenecks due to overdue government incentive payouts** (over ₹3,200 Cr in pending subsidies), forcing reliance on high-interest loans.
    - The release of the **Telangana MSME Policy 2024** aims to address these structural hurdles in power caps, land access, and credit guarantees.
- **Actionable Policy Interventions:**
    - Establish dedicated digital fast-track clearance tracks for multi-clearance mega-projects.
    - Pivot MSME support from simple timeline reduction to **timely subsidy disbursement**, T-Hub incubation onboarding, and direct capital access.
### 2. Digital Governance & Municipal Fiscal Flows (E-Stamps & Registrations)
- **Empirical Findings:**
    - E-stamp adoption experienced explosive growth post-late 2020, becoming the dominant mechanism for non-agricultural property registrations.
    - Revenue generation is tightly clustered in urban growth corridors: **Rangareddy, Medchal-Malkajgiri, and Hyderabad** account for over $60\%$ of total state registration duty.
    - ![monthly_total_revenue_vs_estamps_revenue](https://raw.githubusercontent.com/jishnukoliyadan/Telangana-Inclusive-Growth-Analysis/refs/heads/main/assets/images/report_graphs/monthly_total_revenue_vs_estamps_revenue.png)
- **Qualitative News Insights:**
    - Mandatory slot booking and e-stamp charges resulted in a $48\%$ H1 revenue spurt, generating massive windfalls (e.g., ₹3,000+ Cr cleared to GHMC and local bodies).
    - **Operational Vulnerabilities:** Delays in transferring registration dues to local municipalities hamper critical urban infrastructure projects. Rural property digitization lags, leaving farmers with limited access to formal collateral and credit markets.
- **Actionable Policy Interventions:**
    - Expand mandatory e-stamping and digital land cards (e.g., _Bhudhar_) to agricultural holdings to eliminate title fraud and streamline farm loans.
    - Automate real-time inter-departmental tax distribution to local bodies to maintain municipal infrastructure funds.
### 3. Agricultural Mechanization vs. Climate Volatility Mismatch
- **Empirical Findings:**
    - High equipment and tractor registration densities are concentrated in districts with moderate rainfall variability (e.g., **Nalgonda, Suryapet, Khammam**).
    - Highly climate-vulnerable districts subject to severe rainfall volatility remain significantly under-mechanized.
	- ![rainfall_variability_vs_agricultural_vehicle_registrations_by_district](https://raw.githubusercontent.com/jishnukoliyadan/Telangana-Inclusive-Growth-Analysis/refs/heads/main/assets/images/report_graphs/rainfall_variability_vs_agricultural_vehicle_registrations_by_district.png)
- **Qualitative News Insights:**
    - **Mismatched Mechanization:** Over 200 mandals faced drought-like conditions in recent seasons while unseasonal floods triggered massive crop loss compensation rollouts (e.g., ₹79.57 Cr state relief).
    - Farmers in arid zones frequently purchase equipment tailored for water-heavy crops (e.g., paddy tractors in drought-prone areas), leading to underutilized machinery, loan default risks, and altered sowing patterns.
- **Actionable Policy Interventions:**
    - Re-orient agricultural subsidies away from blanket tractor purchases toward **climate-aligned micro-irrigation (drip/sprinkler), check dams, and water harvesting infrastructure** in high-variance districts.
    - Expand Custom Hiring Centers (CHCs) to allow smallholders access to machinery without incurring individual debt burdens.
### 4. Inclusion Barriers & Regional Economic Imbalance
- **Qualitative News & Institutional Insights:**
    - Following the Supreme Court verdict on SC/ST sub-categorization, Telangana became the first state to notify sub-classification to foster targeted upliftment.
    - **The Execution Gap:** Marginalized entrepreneurs in rural districts continue to experience delayed TS-iPASS clearances, limited industrial land access, and job concentration limited primarily to the Hyderabad/Rangareddy belt.
- **Actionable Policy Interventions:**
    - Create dedicated, monitored processing windows for SC/ST and women-owned MSME industrial applications to close the policy-execution gap.
    - Decentralize industrial parks toward Tier-2 and Tier-3 districts to balance regional growth and curb rural-urban migration.
## :file_folder: Complete Repository Structure
```
.
├── 01_Data_Scrapper.ipynb                   # Data acquisition pipeline from Open Data Telangana
├── 02_Data_Cleaning.ipynb                   # Raw data parsing & missing-value handling
├── 03_Data_Preprocessing.ipynb              # Aggregation, feature engineering & Parquet/CSV generation
├── 04_Exploratory_Data_Analysis.ipynb       # Comprehensive cross-domain EDA, distribution plots & statistical tests
├── 05_Insight_Report.ipynb                  # Executive insight generation notebook
│
├── assets
│   ├── images
│   │   ├── Flow_Chart-{date}.jpg            # Workflow diagrams across iterations
│   │   ├── Gantt_Chart-{date}.png           # Project timeline visualization assets
│   │   ├── report_graphs/                   # Analytical charts generated during EDA
│   │   └── telangana-map.png                # Base state mapping asset
│   └── Supporting-Articles.md               # Qualitative news context & policy references
│
├── Data
│   ├── interim/                             # Intermediate dataset states in Parquet format
│   ├── processed/                           # Cleaned, merged, and geometrically aligned datasets
│   └── raw/                                 # Raw Unprocessed source datasets from Open Data Telangana
│
├── environment.yml                          # Project environment dependencies
├── Gantt_Chart.ipynb                        # Project timeline management notebook
├── LICENSE                                  # License information
├── README.md                                # Complete project documentation
│
└── Reports/
    ├── 01-Capstone-Project-Proposal.pdf     # Initial Capstone Project Proposal
    ├── 02-Capstone-Final-Submission.pdf     # Capstone Final Submission Report
    ├── 03-Capstone-Final-Presentation.pdf   # Slide deck presentation for capstone defense
    └── Rejected/                            # Earlier proposal drafts & revisions
```
## :computer: Environment Setup & Quickstart
### Prerequisites
- [Anaconda](https://anaconda.com/)
### Installation Steps
1. **Clone the repository :**
	```sh
	git clone https://github.com/jishnukoliyadan/Telangana-Inclusive-Growth-Analysis.git
	cd Telangana-Inclusive-Growth-Analysis
	```
2. **Establish a virtual conda environment  :**
	```sh
	conda create --file environment.yml
	conda activate telangana_analysis
	```
3. **Launch JupyterLab:**
	```sh
	jupyter lab
	```
## :page_facing_up: License
This repository is licensed under the [MIT License](https://github.com/jishnukoliyadan/Telangana-Inclusive-Growth-Analysis/blob/main/LICENSE). Datasets sourced from [Open Data Telangana](https://data.telangana.gov.in/) are subject to the government's open data licensing policies.