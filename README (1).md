# Ghana Tech Ecosystem Survey 2025 - Dashboard Project

![Project Status](https://img.shields.io/badge/Status-Ready%20for%20Implementation-success)
![Data Period](https://img.shields.io/badge/Data%20Period-July%202025-blue)
![Total Respondents](https://img.shields.io/badge/Respondents-286-orange)

---

## Project Overview

This project transforms raw survey data from the **Ghana Tech Ecosystem Survey 2025** into an interactive, actionable dashboard that provides deep insights into Ghana's technology sector. The survey captured responses from 286 tech professionals across Ghana, covering demographics, skills, tools, work arrangements, and ecosystem needs.

**Project Timeline:** July 2025 - February 2026
**Survey Period:** July 2025
**Analysis Period:** January - February 2026

---

![Dashboard](images/Screenshot%20(83).png)
![DRILL THROUGH](images/Screenshot%20(84).png)
![DRILL THROUGH 1](images/Screenshot%20(85).png)

## Purpose & Objectives

### Primary Purpose

To provide stakeholders in Ghana's tech ecosystem with **data-driven insights** that inform:

- **Policy decisions** (government, regulators)
- **Investment strategies** (VCs, angel investors)
- **Talent development** (training institutions, bootcamps)
- **Business planning** (tech companies, startups)
- **Career decisions** (tech professionals, job seekers)

### Key Objectives

1. **Map the Current Landscape**

   - Identify who works in tech in Ghana
   - Understand demographic composition
   - Track work arrangements and employment patterns
2. **Identify Skills Gaps**

   - Determine which skills are in highest demand
   - Understand technology adoption patterns
   - Map learning and development trends
3. **Uncover Ecosystem Needs**

   - Identify barriers to growth
   - Understand what the ecosystem lacks
   - Prioritize interventions for maximum impact
4. **Enable Data-Driven Decisions**

   - Provide interactive drill-through capabilities
   - Allow filtering and segmentation
   - Support evidence-based policy and planning
5. **Track Diversity & Inclusion**

   - Monitor gender representation across roles
   - Understand regional distribution
   - Identify equity gaps

---

## 📊 Data Summary

### Survey Coverage

| Metric                           | Value                      |
| -------------------------------- | -------------------------- |
| **Total Responses**        | 286                        |
| **Unique Respondents**     | 279 (7 submitted twice)    |
| **Data Points Collected**  | 7,425 individual responses |
| **Survey Questions**       | 43 unique questions        |
| **Response Categories**    | 7 major categories         |
| **Data Collection Period** | July 31, 2025              |

### Geographic Distribution

- **Greater Accra:** 232 respondents (81.1%)
- **Ashanti:** 20 respondents (7.0%)
- **Other Regions:** 34 respondents (11.9%)

### Demographics Snapshot

- **Age:** 71% are 18-28 years old
- **Gender:** 88.5% Male, 11.5% Female
- **Education:** 81.5% have Bachelor's degrees
- **Experience:** Average of 4.2 years in tech
- **Employment:** 61% full-time employed

### Key Findings

#### Tech Verticals

1. **Fintech** leads with 40.6% (116 workers)
2. E-commerce/Retail Tech: 18.9%
3. SaaS/B2B Solutions: 16.8%
4. Healthtech: 14.0%
5. Edtech: 13.3%

#### Top Roles

1. **Software Engineer:** 53.5% (153 people)
2. UX/UI Designer: 11.2% (32 people)
3. Data Scientist: 5.9% (17 people)
4. Founder/CEO: 5.2% (15 people)
5. Product Manager: 3.8% (11 people)

#### Skills Gaps (Top 5)

1. Technical Writing: 22.7%
2. Data Science/ML Engineering: 17.8%
3. AI Ethics & Governance: 17.5%
4. Deep Tech R&D: 17.5%
5. Investment/Fundraising: 17.1%

#### Ecosystem Needs (Top 5)

1. Better-paying jobs locally: 56.3%
2. Access to capital/funding: 52.8%
3. Stronger mentorship: 48.3%
4. Global market access: 47.6%
5. Better infrastructure: 46.9%

#### AI Tool Adoption

- **ChatGPT:** 81.8% usage rate
- **Claude:** 54.5% usage rate
- **Google Gemini:** 39.2% usage rate
- **GitHub Copilot:** 33.9% usage rate

---

## 📦 Project Deliverables

### 1. Data Cleaning & Preparation

- Cleaned demographics dataset (286 rows × 22 columns)
- Melted responses dataset (7,425 rows × 6 columns)
- Data dictionary with all field definitions
- Primary key identified: `submission_id`

### 2. Dashboard Specifications

- Complete 4-page dashboard design
- 25-30 visualizations mapped out
- 14 drill-through paths defined
- Interactive HTML mockups created
- Color scheme (Ghana flag themed)

### 3. Implementation Guides

- Step-by-step dashboard build guide
- Drill-through implementation tutorial
- Calculated fields reference (18 measures)
- Implementation checklist (35 tasks, 60 hours)

### 4. Reference Materials

- Drill-through relationship map
- Color palette reference
- Data model diagram

---

## Dashboard Structure

### Page 1: Executive Overview

**Purpose:** High-level snapshot for quick insights
**Audience:** All users (landing page)

**KPIs (4):**

- Total Respondents: 286
- Average Experience: 4.2 years
- Remote Work Adoption: 44%
- Top Tech Vertical: Fintech

**Visualizations (5):**

1. Respondents by Region (Map/Bar) - *Drill-through enabled*
2. Age Distribution (Donut Chart)
3. Employment Status (Stacked Bar)
4. Top 5 Tech Verticals (Horizontal Bar) - *Drill-through enabled*
5. Income Distribution (Column Chart) - *Drill-through enabled*

**Filters:**

- Region (multi-select)
- Age Range
- Gender
- Years of Experience

---

### Page 2: Talent & Workforce Insights

**Purpose:** Deep dive into people and roles
**Audience:** Recruiters, HR, Training institutions

**KPIs (3):**

- Average Income: GHS 150K
- Female Representation: 11.5%
- Most Common Role: Software Engineer (53.5%)

**Visualizations (6):**

1. Primary Roles Distribution (Tree Map) - *Drill-through enabled*
2. Experience vs Income (Scatter Plot) - *Drill-through enabled*
3. Education Levels (Stacked Column)
4. Work Arrangement Trends (Pie Chart) - *Drill-through enabled*
5. Work-Life Balance (Gauge/Stacked Bar)
6. Gender Distribution by Role (Clustered Bar) - *Drill-through enabled*

---

### Page 3: Skills & Technology Landscape

**Purpose:** Technology adoption and skills gaps
**Audience:** Tech leads, Trainers, Developers

**KPIs (3):**

- AI Tool Adoption: 82%
- Top Skill Gap: Technical Writing
- Learning Platforms Used: 17

**Visualizations (6):**

1. AI Tool Adoption (Multiple Donuts) - *Drill-through enabled*
2. Top 10 Skills Gaps (Horizontal Bar) - *Drill-through enabled*
3. Tech Stack Heatmap (Matrix) - *Drill-through enabled*
4. Learning Platform Usage (Bubble Chart)
5. Company AI Encouragement (Pie Chart)
6. Tech Communities Engagement (Bar/Word Cloud)

---

### Page 4: Ecosystem Health & Opportunities

**Purpose:** Growth opportunities and gaps
**Audience:** Policy makers, Investors, Ecosystem builders

**KPIs (4):**

- Top Ecosystem Need: Better Jobs (56%)
- Event Attendance: 48%
- Open Source Interest: 60%
- Want Mentoring: 87%

**Visualizations (6):**

1. Top Ecosystem Needs (Diverging Bar) - *Drill-through enabled*
2. Mentoring Network (Sankey Diagram) - *Drill-through enabled*
3. Open Source Contribution (Funnel Chart)
4. Tech Event Attendance (Pie + Bar Combo) - *Drill-through enabled*
5. Benefits Received (Clustered Bar)
6. Organization Location (Stacked Bar)

---

### Page 5: Drill-Through Details (Hidden/Dynamic)

**Purpose:** Detailed view of selections
**Activated:** When user clicks drill-through elements

**Features:**

- Dynamic title based on selection
- Breadcrumb navigation
- Summary KPI cards
- Detailed data table
- Related insights
- Back button

---

## 🔍 Key Insights

### Talent Pool Insights

1. **Young Workforce:** 71% are under 29, indicating a growing, emerging talent base
2. **Gender Gap:** Only 11.5% female representation - major D&I opportunity
3. **Education:** Highly educated (81.5% have degrees), but experience distribution suggests retention challenges
4. **Income Disparity:** 36% earn less than GHS 25K/year while some roles command GHS 500K+

### Skills & Technology Insights

1. **AI Revolution:** 82% use AI tools, with ChatGPT dominating
2. **Critical Gaps:** Technical writing, data science, and AI ethics identified as top needs
3. **Tool Preference:** JavaScript ecosystem (React, Node.js) most popular
4. **Learning:** YouTube (83%) is primary learning platform, suggesting preference for free/accessible resources

### Work & Culture Insights

1. **Remote First:** 44% work remotely, 32% hybrid - total 76% have flexibility
2. **Work-Life Balance:** 40% rate as "Good," but 43% struggle (Fair to Very Poor)
3. **Benefits Gap:** 58% get remote work, but only 39% get health insurance
4. **Community:** 34% not part of any tech community - opportunity for engagement

### Ecosystem Insights

1. **Job Quality Crisis:** 56% want better-paying jobs - top concern
2. **Funding Gap:** 53% cite lack of capital as barrier
3. **Mentorship Void:** 87% want mentoring (as mentor, mentee, or both)
4. **Local Focus:** 52% didn't attend tech events - opportunity for activation
5. **Open Source:** 60% interested but not yet contributing - conversion opportunity

---

## 💻 Technical Implementation

### Data Architecture

```
┌─────────────────────────┐
│  demographics_cleaned   │
│  (Primary: submission_id)│
│  - 286 rows             │
│  - 22 columns           │
│  - Demographics & work  │
└──────────┬──────────────┘
           │ 1
           │
           │ Many
┌──────────▼──────────────┐
│  melted_responses       │
│  (Foreign: Submission ID)│
│  - 7,425 rows           │
│  - 6 columns            │
│  - All true/false data  │
└─────────────────────────┘
```

### Tools & Technologies

- **Primary Tool:** Microsoft Power BI Desktop
- **Alternative Options:** Tableau, Looker Studio
- **Data Prep:** Python (Pandas), Excel
- **Format:** CSV files
- **Color Scheme:** Ghana flag colors (Red, Gold, Green)

---

### For Analysts & Researchers

**Quick Analysis:**

1. Open `demographics_cleaned.xlsx`
2. Use pivot tables on summary sheets
3. Cross-reference with `ghana_tech_survey_melted.csv`

**Advanced Analysis:**

```python
import pandas as pd

# Load data
demo = pd.read_csv('data/demographics_cleaned.csv')
responses = pd.read_csv('data/ghana_tech_survey_melted.csv')

# Merge for analysis
merged = responses.merge(demo, 
                        left_on='Submission ID', 
                        right_on='submission_id')

# Analyze by any dimension
merged.groupby(['primary_role', 'Response']).size()
```

---

## 🙏 Acknowledgments

- **286 survey respondents** who shared their insights
- **Ghana tech communities** (DevCongress, GDG, Flutter Ghana, etc.) for participation
- **Survey design team** for comprehensive question set
- **Analysis tools:** Power BI, Python, Pandas
- **Ghana flag** for inspiring our color palette 🇬🇭

---

## 📜 License

This project and its findings are intended for:

- Public good
- Policy development
- Ecosystem growth
- Research and education

**Data Privacy:** All individual responses are anonymized. Only aggregate insights are shared.

---

## 🔄 Version History

**v1.0** (February 2026)

- Initial dashboard design
- Data cleaning and preparation
- Implementation guides created
- Ready for Power BI build

---

**Built with ❤️ for Ghana's Tech Ecosystem**

*Last Updated: February 6, 2026*
