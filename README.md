# 📊 Recruitment Channel Performance & Long-Term Value Dashboard (Power BI)

An interactive 3-page **Power BI** report designed for Talent Acquisition leaders, HR teams, Finance partners, and hiring managers to evaluate recruitment channel efficiency beyond surface-level hiring volume and upfront Cost Per Hire (CPH).

Built across **609 closed recruitment campaigns (2024–2026)** covering **€9.58M in acquisition spend**, **141,271 applicants**, and **4,048 hires**, this dashboard pairs **ZoomCharts Drill Down PRO** visuals with mature-cohort **DAX** modeling to answer one central question:

> 🎯 **Which recruitment channels deliver suitable hires at a reasonable acquisition cost, and which continue to provide value after probation, 180-day retention, and performance are considered?**

---

## 🖼️ Dashboard Preview

### 💰 Page 1: Spend & Channel Efficiency
<img width="100%" alt="Spend & Channel Efficiency (Cost vs. Volume)" src="https://github.com/user-attachments/assets/d935a42e-5497-4f1f-96bd-a25cdf1af764" />

### 🔍 Page 2: Candidate Quality & Funnel Drop-off
<img width="100%" alt="Candidate Quality & Funnel Drop-off" src="https://github.com/user-attachments/assets/f5e1fe5a-eadc-458b-b255-8cb8021d1be9" />

### 🏆 Page 3: Long-Term Hiring Value (90d/180d ROI)
<img width="100%" alt="Long-Term Hiring Value (Probation, Retention & ROI)" src="https://github.com/user-attachments/assets/a8e36ce0-ee21-439b-947c-21252c39ec0a" />

---

## 📈 Executive KPI Snapshot (2024–2026)

| Pillar | Metric | Overall Result | Key Highlight |
| :--- | :--- | :---: | :--- |
| 💸 **Spend & Speed** | Total Recruitment Spend | **€9.58M** | 56.1% Agency Fees • 31.7% Internal • 6.8% Referral • 5.4% Ad |
| ⏱️ **Spend & Speed** | Total Hires • Upfront CPH | **4,048 • €2,367** | Avg Time to Fill: **55.5 days** • **20.0 recruiter hrs/hire** |
| 🧪 **Funnel Quality** | Total Applicants • Qual Rate | **141,271 • 24.7%** | 34.9 applicants/hire • 81.6% offer acceptance |
| ✅ **Long-Term Value** | 90-Day Probation Pass Rate | **86.8%** | 3,188 / 3,672 mature 90-day hires |
| ⭐ **Long-Term Value** | 180-Day Retention • Success | **79.5% • 65.3%** | Avg Performance Score: **3.41 / 5.00** |
| 💎 **True ROI** | Cost Per Successful 180d Hire | **€3,677** | **1.53x** mature initial CPH (€2,401) • +€1,276 attrition premium |

---

## 🧭 Page-by-Page Breakdown & Key Insights

### 1️⃣ Spend & Channel Efficiency (Cost vs. Volume)

* **Visuals:** ZoomCharts Drill Down Combo Bar PRO (stacked cost components + CPH markers), ZoomCharts Drill Down Combo PRO (Spend Share % vs. Hire Share % & Department/Role/Seniority efficiency), and a Native Efficiency Matrix Scatter Plot with dynamic hire-weighted reference lines.
* **Key Findings:**
  * 🔥 **Budget Concentration:** External agencies absorb **59.2% of total spend (€5.67M at €11,339 CPH)** while generating only **12.4% of hires (500 hires)**.
  * ⚙️ **Volume Engines:** Job Boards (**26.9% of hires**) and Employee Referrals (**18.6% of hires**) jointly deliver **45.4% of hiring volume** using just **23.1% of spend**.
  * 🏢 **Department & Seniority Drivers:** Finance (**€3,666 CPH**), Technology (**€3,218 CPH**), and Senior roles (**€4,908 CPH**) drive the highest acquisition costs due to >62% reliance on external agencies.
  * ⚡ **Speed Leaders:** Employee Referrals fill roles fastest (**40.6 days**, **€1,348 CPH**), whereas Social Media is slowest (**69.2 days**).

### 2️⃣ Candidate Quality & Recruitment Funnel Drop-off

* **Visuals:** End-to-End Recruitment Funnel (`% of previous` stage tracking), ZoomCharts Signal vs. Noise stacked bar chart (`Qualified` vs. `Unqualified` + Qualification Rate markers), ZoomCharts Department/Seniority conversion combo chart, and a conditional-formatted Provider Scorecard Matrix.
* **Key Findings:**
  * 📉 **Primary Drop-off Cliffs:** The funnel loses **75.3% of candidates at screening** (106,392 unqualified) and **72.5% after interviews** (13,832 not offered), resulting in a **2.9%** overall applicant-to-hire rate.
  * 📡 **Signal vs. Noise:** Social Media (`SocialReach Ads`) drives **41.4% of all applicants (58,453)** at just **9.5% qualification** (**92.6 apps/hire**). By contrast, `TalentBridge Specialists` (**82.4% qual**; **6.8 apps/hire**) and `Employee Referral Programme` (**70.1% qual**; **91.0% offer acceptance**; **12.6 recruiter hrs/hire**) deliver high-signal pipelines.
  * ⏳ **Hidden Internal Effort:** Direct Sourcing delivers strong screening quality (**68.9%**) but requires the heaviest recruiter workload at **30.7 hours/hire**.

### 3️⃣ Long-Term Hiring Value (Probation, 180-Day Retention & True ROI)

* **Visuals:** ZoomCharts True ROI Reversal chart (Initial CPH + Hidden Attrition Cost Premium + Effective Cost Multiplier), Native Provider Quality Matrix Scatter Plot (`180d Success %` vs. `Avg Performance Score`), ZoomCharts Cohort Stability Trend (`Year -> Quarter -> Month`), and a conditional-formatted Provider Durability & Effective Cost Scorecard.
* **Key Findings:**
  * 🚨 **The Low-CPH Illusion:** Up front, Social Media looks like the second-cheapest channel (**€1,008 CPH**). After factoring in its **30.6% probation failure rate** and **39.9% 180-day success rate** (**2.98 avg performance**), its true cost surges **2.50x to €2,524 per successful 180-day hire**—making it **54% more expensive than Employee Referrals (€1,638)** and **63% more expensive than Direct Sourcing (€1,552)**.
  * ⚖️ **Sharp Agency Divergence:** Within external agencies, `TalentBridge Specialists` achieves the highest 180-day success rate of any provider (**82.1%**, **3.60 performance**, **1.22x**), whereas `HireFast Recruitment` drops to **56.1% success** (**3.21 performance**, **1.78x**, **€12,537 per successful hire**)—underperforming Job Boards at over 6x the cost.

---

## 🏅 Provider Long-Term Value Summary (Mature Cohorts)

| Provider | Channel | Qual % | Probation Pass % | 180d Retention % | 180d Success % | Avg Perf | Initial CPH | True CPH (180d) | Multiplier |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 🥇 **TalentBridge Specialists** | Agency | 82.4% | 98.5% | 91.5% | **82.1%** | 3.60 | €14,761 | €17,990 | 1.22x |
| 🥈 **Employee Referral Programme** | Employee referrals | 70.1% | 96.5% | 89.6% | **81.8%** | 3.62 | €1,341 | €1,638 | 1.22x |
| 🥉 **Internal Talent Team** | Direct sourcing | 68.9% | 94.6% | 86.1% | **74.6%** | 3.51 | €1,159 | €1,552 | 1.34x |
| **Company Careers** | Careers site | 32.7% | 89.1% | 81.6% | **66.9%** | 3.40 | €731 | €1,094 | 1.50x |
| **ProNetwork Jobs** | Job boards | 29.2% | 84.4% | 77.2% | **60.6%** | 3.38 | €1,107 | €1,826 | 1.65x |
| **ReachBoard** | Job boards | 15.4% | 81.0% | 74.1% | **58.4%** | 3.29 | €1,156 | €1,979 | 1.71x |
| ⚠️ **HireFast Recruitment** | Agency | 57.9% | 79.3% | 72.0% | **56.1%** | 3.21 | €7,031 | €12,537 | 1.78x |
| 🔴 **SocialReach Ads** | Social media | 9.5% | 69.4% | 62.2% | **39.9%** | 2.98 | €1,008 | €2,524 | 2.50x |

---

## 🚀 Strategic Recommendations

1. **🔄 Review Agency Provider Mix:** Audit spend allocated to `HireFast Recruitment` (56.1% success at €12,537/successful hire). Reserve premium agency spend for specialized/senior searches with `TalentBridge Specialists` while shifting mid-level volume toward Employee Referrals and Direct Sourcing.
2. **🎯 Re-evaluate Social Media Targeting:** Tighten top-of-funnel pre-screening or reallocate `SocialReach Ads` budget (9.5% qualification; 2.50x effective cost multiplier) toward `ProNetwork Jobs` and Referral incentives.
3. **📈 Scale High-ROI Channels Carefully:** Expand Employee Referral participation across Technology, Finance, and Sales, and monitor recruiter capacity before scaling Direct Sourcing (30.7 recruiter hrs/hire).

---

## 🛠️ Technical Architecture

### 🧱 Data Model (Star Schema)

* **Fact Table:** `FactRecruitment` (campaign-channel grain; foreign keys hidden in report view)
* **Dimension Tables:**
  * 📅 `DimDate` (marked as Date Table; linked to `FactRecruitment[CloseDate]`; sorted by `MonthNo` and `YearMonthSort`)
  * 💼 `DimRole` (`Department -> RoleFamily -> Seniority -> RoleTitle`; `Seniority` sorted by `SeniorityOrder`)
  * 📣 `DimChannel` (`ChannelGroup -> Channel -> Provider`, with consistent `ColorHex` visual encoding)
  * 🌍 `DimLocation` (`Region -> Country`)
* **Dedicated Measure Table:** 📐 `_Measures`

### 🧮 Core DAX Highlights

```dax
// Cohort-aligned Effective Cost Per Successful 180-Day Hire (includes zero-hire mature campaign spend)
Mature 180d Spend (€) =
CALCULATE([Total Spend (€)], FactRecruitment[Mature180] = 1)

Cost Per Successful Hire 180d =
DIVIDE([Mature 180d Spend (€)], [Successful 180d Count], BLANK())

Effective Cost Multiplier =
DIVIDE([Cost Per Successful Hire 180d], [Mature 180d Initial CPH], BLANK())

// Dynamic Hire-Weighted Scatter Reference Line
Overall CPH (Ref Line) =
CALCULATE([Cost Per Hire (CPH)], ALLSELECTED(DimChannel))
```

### ✨ Interactive & UX Features

* 🔎 **Multi-Level Drill-Down:** Click directly on ZoomCharts bars to explore `ChannelGroup -> Channel -> Provider`, `Department -> RoleFamily -> Seniority -> RoleTitle`, and `Year -> Quarter -> YearMonth`.
* 🔗 **Synced Global Slicers:** Filter by `Department`, `Seniority`, `Region`, and `Year` seamlessly across all 3 pages.
* 🧭 **Built-in Usability Controls:** Active-state page navigation bar, one-click **Reset Filters** (`Clear all slicers`) button, and an interactive **`?` Guided Help** tooltip on every page.

---

## 📌 Methodological Notes & Guardrails

* **Cohort Attribution:** Spend and hires are attributed to campaign close cohort (`CloseDate`), representing actual historical acquisition cost rather than approved budget variance.
* **Cohort Maturity Discipline:** 90-day probation metrics restrict strictly to mature 90-day cohorts (`Mature90 = 1`; through June 2026; 3,672 hires). 180-day retention, performance, and True CPH metrics restrict to mature 180-day cohorts (`Mature180 = 1`; through April 2026; 3,340 hires) so recent unassessed hires never distort outcomes.
* **Descriptive Context:** Channel comparisons are influenced by role mix, seniority, and internal capacity; historical CPH gaps should inform sourcing reviews rather than be multiplied directly into guaranteed savings.

---

## 📂 Repository Structure

```text
├── assets/
│   ├── page1_spend_efficiency.png
│   ├── page2_funnel_quality.png
│   └── page3_long_term_value.png
├── data/
│   └── Recruitment_Channel_Value_Challenge.xlsx
├── Recruitment_Channel_Value_Dashboard.pbix
└── README.md
```

---

## 💻 How to Run Locally

1. Clone this repository and open `Recruitment_Channel_Value_Dashboard.pbix` in **Power BI Desktop**.
2. If prompted for custom visuals, sign in to Power BI Desktop to load **ZoomCharts Drill Down Combo PRO** and **Drill Down Combo Bar PRO** from AppSource.
3. To refresh data locally, go to **Transform data → Data source settings** and point the Excel path to `data/Recruitment_Channel_Value_Challenge.xlsx`.
