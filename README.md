# Berlin Park Accessibility Analysis

This project analyzes the spatial distribution, accessibility, and equity of public parks across Berlin using geospatial data at two administrative levels:

- **District level** (Bezirk)
- **Sub-district level** (Ortsteil)

We focus on three main aspects of urban green space:

---

## 1. Park Availability

**Objective:** Measure how many parks exist in each district and sub-district.

- We perform a spatial join between park polygons and administrative boundaries.
- The total number of parks is counted and compared across all areas.
- Helps identify which areas are over- or under-served by public parks.

---

## 2. Park Area per Capita

**Objective:** Assess equity in green space by calculating park area available per resident.

- Park area is summed per area (in square meters).
- Divided by population to compute per capita access.
- Highlights spatial inequities between districts and sub-districts.

---

## 3.  Accessibility (800m Buffer)

**Objective:** Estimate how much of each area falls within an 800-meter walking distance to a park.

- Parks are buffered by 800 meters.
- We calculate what proportion of each area's surface is covered by these buffers.
- Gives a measure of functional access to green spaces.

---

## Data Sources  
- Berlin administrative boundaries (districts and sub-districts)  
- Public park polygons from Berlin Open Data Portal  
- Population estimates for 2024 from [Statistik Berlin Brandenburg](https://www.statistik-berlin-brandenburg.de)



##  Key Findings

This project analyzes the distribution, size, and accessibility of public parks across Berlin’s districts and sub-districts using 2024 population data.  
It highlights spatial inequalities in green space availability and park access to inform urban planning.  
Interactive maps and detailed reports are included to support decision-making for equitable park development.


## Outputs

- Interactive maps [Maps/berlin_park_map.html](Maps/berlin_park_map.html)
- Full results summary: [results_summary.md](Results/report.md)



