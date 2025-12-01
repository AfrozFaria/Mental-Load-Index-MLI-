# Mental Load Index (MLI) – Interactive Tableau Visualization

This repository contains an interactive visualization project on **Mental Load Index (MLI)** for university students, built with **Tableau** as part of a **Interactive Data Visualization** course in the Master’s programme at the **University of Helsinki**.

The goal of the project is to help students **reflect on their mental load** by exploring how factors such as stress, sleep, study time, and screen time interact over time.

## Project Overview

The project follows **Munzner’s Nested Design Model** and focuses on:

- Defining a **realistic domain situation**: university students dealing with stress, time pressure, and lifestyle imbalance.
- Designing **tasks and interactions** that support self-reflection and pattern discovery.
- Building an **interactive Tableau dashboard** that allows users to:
  - Explore their Mental Load Index (MLI) over time  
  - Relate MLI to lifestyle factors (sleep, study hours, screen time, etc.)
  - Identify overload periods and potential risk patterns

I have **enhanced the interaction design**, **clarified the visual encodings**, and included a **discussion grounded in Mackinlay’s visual variable ranking table** to justify the design choices.

---

## Target Users & Domain

- **Target users:** University students (and potentially academic advisors) interested in monitoring and reflecting on their mental well-being.
- **Domain situation:** Students often struggle to balance coursework, sleep, social life, and screen time. The visualization helps them:
  - Spot when their mental load becomes too high  
  - Understand how different habits contribute to that load  
  - Make more informed decisions about workload and lifestyle

---

## Data & Preprocessing

The project uses a dataset that combines:

- **Stress levels**
- **Sleep duration**
- **Study hours**
- **Screen time**
- (Optionally) Other lifestyle or well-being indicators

Preprocessing steps (done before or within Tableau) include:

- Cleaning missing or inconsistent values  
- Transforming time-related data (e.g., daily/weekly aggregation)  
- Creating a **Mental Load Index (MLI)** metric from multiple input variables  
- Deriving additional fields for filtering and grouping (e.g., time ranges, categories)

---

## Tasks & Interaction Design

The visualization is designed to support tasks such as:

- **T1 – Overview:** See how MLI evolves over time for a given student or group.
- **T2 – Relate:** Compare MLI with sleep, study time, and screen time to identify relationships.
- **T3 – Detect:** Spot peaks in mental load and potential periods of overload.
- **T4 – Compare:** Compare different time periods or categories (e.g., exam weeks vs. normal weeks).
- **T5 – Drill-down:** Inspect detailed data for specific days or intervals.

### Visual Encodings

The visual design is grounded in **Mackinlay’s ranking of visual variables**, choosing encodings that match the data types and task priorities, for example:

- **Position on a common scale** for quantitative values (e.g., MLI over time)
- **Length / height** in bar or line charts for comparing magnitudes
- **Color hue/intensity** to highlight levels of mental load or risk
- **Faceting / small multiples** to support comparisons across categories or time windows

These choices are explained and justified in the project report.

---

## 🧪 User Study & Iteration

As an iterative step, the current Tableau prototype was evaluated with **at least three target users (n ≥ 3)**, one at a time. The study included:

- **Briefing & training:** Short introduction and orientation to the dashboard  
- **Think-aloud tasks:** Users performed 1–2 analysis tasks while verbalizing their thoughts  
- **Questionnaire & interview:** Background info, perceived usefulness, clarity, and usability feedback  

Insights from the study were used to:

- Refine **interaction flows** (e.g., filters, tooltips, navigation)
- Clarify **labels, legends, and encodings**
- Improve **layout and affordances** to make the dashboard more intuitive



