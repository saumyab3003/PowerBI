# Recruitment Channel Value Analytics Dashboard

## Overview

This Power BI project analyzes recruitment channel effectiveness across the complete hiring lifecycle, from candidate acquisition and funnel conversion through probation, retention, post-hire performance, and successful-hire economics.

The analysis goes beyond traditional recruitment metrics such as hiring volume and Cost per Hire to answer a more strategic question:

> **Which recruitment channels deliver sustainable, high-quality hires at a reasonable acquisition cost?**

The dashboard was developed for the **ZoomCharts 4U Recruitment Analytics Challenge** and uses interactive ZoomCharts Drill Down visuals to enable deeper exploration of recruitment performance.

---

## Business Objective

Recruitment channels can appear effective when evaluated only on initial hiring outcomes.

A channel may:

- Generate a high number of hires
- Have a reasonable Cost per Hire
- Deliver candidates quickly

But those metrics alone do not show whether those hires:

- Pass probation
- Remain with the organization
- Perform effectively
- Become successful long-term hires

This dashboard connects **recruitment acquisition metrics with post-hire outcomes** to provide a broader view of recruitment channel value.

---

# Dashboard

The report consists of two analytical pages.

## Page 1: Recruitment Analytics

**Focus:** Recruitment acquisition, cost, efficiency, and candidate conversion.

### Key KPIs

- Recruitment Spend
- Hires
- Cost per Hire
- Average Time to Fill
- Applicant-to-Hire Rate

### Analysis

#### Recruitment Spend by Channel
Compares recruitment investment across channel groups and allows drill-down into individual channels and providers.

#### Recruitment Spend & Hires Trend
Tracks recruitment investment and hiring activity over time using:

**Year → Quarter → Month**

#### 180-Day Successful Hires by Channel
Shows how successful hires are distributed across recruitment channels.

#### Candidate Conversion Funnel
Tracks candidate progression through:

**Applicants → Qualified Applicants → Interviews → Offers → Accepted Offers → Hires**

This helps identify where candidate volume decreases throughout the recruitment process.

---

## Page 2: Channel Value & Hire Quality

**Focus:** Post-hire quality and the economics of successful recruitment outcomes.

### Key KPIs

- Probation Pass Rate
- 180-Day Retention Rate
- 180-Day Successful Hires
- Average Performance Score
- Cost per Successful Hire

### Analysis

#### Post-Hire Quality by Channel
Compares probation and 180-day retention outcomes across recruitment channels.

#### Channel Cost vs Hire Quality
Evaluates the relationship between:

- Cost per Successful Hire
- 180-Day Retention Rate

This helps identify channels that combine lower acquisition cost with stronger post-hire retention.

#### Post-Hire Performance by Channel
Compares average performance outcomes across recruitment channel groups.

#### Successful Hire Economics
Compares:

**Cost per Hire vs Cost per Successful Hire**

This provides a quality-adjusted view of recruitment economics and highlights cases where an apparently reasonable acquisition cost becomes significantly higher after post-hire outcomes are considered.

---

# Analytical Framework

The dashboard follows the recruitment lifecycle beyond the initial hire:

```text
Applicants
    ↓
Qualified Candidates
    ↓
Interviews
    ↓
Offers
    ↓
Accepted Offers
    ↓
Hires
    ↓
Probation
    ↓
180-Day Retention
    ↓
Successful Hire
    ↓
Post-Hire Performance
```

This allows recruitment channels to be evaluated across three dimensions:

### 1. Acquisition Efficiency
How efficiently does a channel convert recruitment investment into hires?

### 2. Hire Quality
Do employees sourced through the channel pass probation, remain retained, and perform effectively?

### 3. Sustainable Recruitment Value
What does it actually cost to generate a successful hire rather than simply make a hire?

---

# Business Questions Addressed

The dashboard is designed to answer questions such as:

1. Which recruitment channels receive the highest investment?
2. Which channels generate the greatest hiring volume?
3. How efficiently does recruitment spend translate into hires?
4. Where does candidate conversion drop within the recruitment funnel?
5. Which channels produce stronger probation outcomes?
6. Which channels deliver stronger 180-day retention?
7. How does employee performance vary by recruitment source?
8. Which channels generate the most successful hires?
9. Which channels have the lowest Cost per Successful Hire?
10. Does a low Cost per Hire still represent good value after retention and post-hire outcomes are considered?

---

# Key Measures

| Metric | Purpose |
|---|---|
| Applicants | Total candidate volume |
| Qualified Candidates | Candidates meeting qualification criteria |
| Interviews | Candidates progressing to interview |
| Offers | Offers issued |
| Accepted Offers | Offers accepted |
| Hires | Completed hires |
| Recruitment Spend | Total recruitment investment |
| Cost per Hire | Recruitment cost per completed hire |
| Average Time to Fill | Recruitment speed |
| Applicant-to-Hire Rate | Overall funnel conversion |
| Probation Pass Rate | Early post-hire success |
| 180-Day Retention Rate | Medium-term employee retention |
| 180-Day Successful Hires | Sustainable hiring outcome |
| Average Performance Score | Post-hire performance indicator |
| Cost per Successful Hire | Quality-adjusted recruitment acquisition cost |

---

# Interactive Features

The dashboard supports filtering by:

- **Date**
- **Role Family**
- **Country**
- **Recruitment Channel**

ZoomCharts visuals provide interactive drill-down paths including:

```text
Channel Group
    ↓
Channel
    ↓
Provider
```

and time-based exploration through:

```text
Year
  ↓
Quarter
  ↓
Month
```

Cross-filtering enables users to investigate specific segments while retaining the overall recruitment and post-hire context.

---

# Why Cost per Successful Hire Matters

Traditional recruitment reporting often stops at:

```text
Recruitment Spend
        ÷
      Hires
        =
   Cost per Hire
```

This project extends the analysis to:

```text
Recruitment Spend
        ÷
180-Day Successful Hires
        =
Cost per Successful Hire
```

The distinction matters because a recruitment source that looks cost-effective based solely on initial hires may look very different after probation, retention, and successful-hire outcomes are considered.

This provides a more complete view of recruitment channel economics.

---

# Tools & Technologies

- **Microsoft Power BI Desktop**
- **DAX**
- **Power BI Data Modeling**
- **ZoomCharts Drill Down Visuals**
- Drill-down hierarchies
- Interactive slicers
- Cross-filtering
- Recruitment funnel analysis
- Cost and efficiency analysis
- Post-hire quality analytics

---

# Power BI Measures

The report includes measures covering the full recruitment and post-hire lifecycle, including:

### Recruitment Funnel

```text
Applicants
Qualified Candidates
Interviews
Offers
Accepted Offers
Hires
```

### Recruitment Efficiency

```text
Recruitment Spend
Cost per Hire
Average Time to Fill
Applicant-to-Hire Rate
Qualification Rate
Interview Rate
Offer Rate
Offer Acceptance Rate
Hire Conversion Rate
```

### Post-Hire Quality

```text
90-Day Eligible Hires
Passed Probation Hires
Probation Pass Rate

180-Day Eligible Hires
180-Day Retained Hires
180-Day Retention Rate
180-Day Successful Hires

Performance Rated Hires
Average Performance Score
Cost per Successful Hire
```

---

# Dashboard Preview

## Recruitment Analytics

![Recruitment Analytics Dashboard](screenshots/recruitment-analytics-overview.png)

The overview page combines recruitment spend, hiring efficiency, channel analysis, recruitment trends, successful hires, and the complete candidate conversion funnel.

---

## Channel Value & Hire Quality

![Channel Value and Hire Quality Dashboard](screenshots/channel-value-hire-quality.png)

The second page evaluates recruitment channels using probation results, retention, employee performance, successful hires, and quality-adjusted recruitment cost.

---

# Repository Structure

```text
Recruitment-Channel-Value-Analytics/
│
├── Recruitment Dashboard_ZoomCharts.pbix
├── README.md
│
└── screenshots/
    ├── recruitment-analytics-overview.png
    └── channel-value-hire-quality.png
```

---

# Project Highlights

- End-to-end recruitment lifecycle analysis
- Candidate conversion funnel analysis
- Recruitment channel cost comparison
- Cost per Hire and Cost per Successful Hire analysis
- Probation outcome analysis
- 180-day retention analysis
- Post-hire performance analysis
- Interactive ZoomCharts drill-down functionality
- Channel Group → Channel → Provider exploration
- Year → Quarter → Month time analysis
- Interactive filtering across Date, Role Family, Country, and Channel
- Two-page executive-focused dashboard design

---

# Key Takeaway

Recruitment channel effectiveness should not be evaluated only by **how many people are hired** or **how cheaply those hires are acquired**.

A more complete assessment considers what happens after hiring.

By connecting acquisition cost with probation, retention, successful-hire outcomes, and performance, this dashboard provides a framework for evaluating:

> **Which recruitment channels generate sustainable hiring value, not just hiring volume?**

---

# Challenge

Created as a submission for the **ZoomCharts 4U Recruitment Analytics Power BI Challenge**.

The project uses multiple ZoomCharts Drill Down visuals to provide interactive exploration while maintaining a concise two-page analytical experience.

---

# Author

**Saumya Sangamkar**

Power BI | Data Analytics | AI & Automation

[Connect with me on LinkedIn](https://www.linkedin.com/in/saumya-bartaria-3003/)
