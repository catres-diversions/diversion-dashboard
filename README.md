# Flight Diversion Analytics Dashboard

## Overview

This dashboard provides an interactive overview of **domestric flight diversion patterns across the United States (July, 2021-Dec, 2024)**. It is designed to support exploratory analysis of when, where, and how diverted flights are distributed across airports and airlines.

The tool is part of the **[Center for Air Transportation Resilience (CATRes)](https://catres.berkeley.edu/) diversions workstream**, with the goal of supporting exploration of system disruptions and identifying patterns relevant to **airport operations, airline behavior, and network resilience**.

👉 **Live dashboard:**
[https://catres-diversions.github.io/diversion-dashboard/](https://catres-diversions.github.io/diversion-dashboard/)

---

## Purpose

Focusing on domestic diverted flights from July 2021 to December 2024, this dashboard enables users to:

* Identify high-volume diversion-receiving airports
* Examine monthly temporal patterns of diverted flights
* Compare airline-level diversion behavior

---

## How to Use

### 1. Year Filter (Top Right)

* Toggle between **All years** or specific years (2021-2024)
* All panels update dynamically

---

### 2. Map: Diverted-To vs Planned Destination Airports

* **Diverted-To Airports**: where flights actually landed after diversion
* **Planned Destination Airports**: original intended destinations

**Interpretation:**

* Bubble size = number of diverted flights
* Color:

  * 🔴 High volume
  * 🟠 Medium volume
  * 🟢 Lower volume

Use the toggle to compare intended vs actual system behavior.

---

### 3. Monthly Diverted Flights (Heatmap)

* Rows = months
* Columns = years
* Each cell = total number of diverted flights in that month

**Interpretation:**

* Darker color = higher diversion volume
* Useful for identifying:

  * seasonal patterns
  * disruption clusters
  * anomalous months

Hover over a cell for exact values.

---

### 4. Diverted Flights by Operating Airline

Shows how diversion activity is distributed across airlines.

For each airline:

* Total number of diverted flights
* % of diverted flights routed to airlines' **hub airports**
* Top **diverted-to airports**

**Interpretation:**

* Highlights differences in:

  * operational strategies
  * reliance on hub recovery

⭐ indicates an airline's hub airport.

---

## Key Observations (Preliminary)

* **Diversions are spatially concentrated**, with a subset of airports handling a large share of diverted traffic.
* **Seasonal peaks** (summer months) show higher diversion volumes, likely associated with weather and demand.
* Airlines differ in their use of **hub airports for recovery**, suggesting varying operational strategies.
* Some airports appear frequently as **planned destinations but not diversion receivers**, indicating asymmetric network roles.

---

## Data Notes

* Data are aggregated at the **monthly and airport level**
* Values represent **counts of diverted flights**
* Airline metrics are scaled to reflect selected time periods

---

## Contact

For questions or feedback, please contact CATRes Diversions Project:

Jasmine Siyu Wu (jsiyuwu@upenn.edu)
Jing Xu (jing-xu@berkeley.edu)
Jun Luu (jjluu@upenn.edu)

