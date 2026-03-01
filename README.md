# NCJunctionTransit-R153
Clean, includes project name and fleet identifier
# NCJunctionTransit-R153 🚇

![R153 Fleet](https://img.shields.io/badge/Fleet-R153-ffb703?style=for-the-badge&labelColor=003566)
![Cars Delivered](https://img.shields.io/badge/Cars%20Delivered-1%2C658-006633?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-009688?style=for-the-badge)
![Last Updated](https://img.shields.io/badge/Last%20Updated-March%202026-8B1E3F?style=for-the-badge)

**We bring fiction to reality on your PCs.** NCJunctionTransit presents a detailed, living document tracking the fictional Kawasaki R153 subway car fleet for the New York City Subway (B Division) and Staten Island Railway.

![NCJunctionTransit Header](https://via.placeholder.com/1200x300/001d3d/ffb703?text=NCJunctionTransit+-+R153+Fleet+Tracker)

---

## 📋 Table of Contents
- [Overview](#overview)
- [Fleet Types](#fleet-types)
- [Current Status (March 2026)](#current-status-march-2026)
- [Recent Events](#recent-events)
- [Repository Contents](#repository-contents)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

---

## 📌 Overview

The **R153** is a massive, multi-type order of subway cars from **Kawasaki Rail Car Manufacturing**, designed to replace older rolling stock (R44s, R68s) across the NYC Subway and Staten Island Railway. This repository tracks every detail of the fictional fleet:

- **Builder:** Kawasaki Rail Car Manufacturing
- **Built At:** Kobe & Hyuga, Japan; Lincoln, NE; Yonkers, NY
- **Traction Systems:** Alstom OptONIX 2100, Siemens SiTRAC, Hitachi Electric
- **Configurations:** 4-car, 5-car, 8-car, and 10-car trains
- **Total Fleet Size (Projected):** 5,400+ cars

---

## 🚆 Fleet Types

| Type | Description | Numbers | Traction | Lines |
|------|-------------|---------|----------|-------|
| **R153S** | Staten Island Railway | 200-274 | Alstom OptONIX | SIR |
| **R153A** | Standard B Division | 2400-3499, 3500-4607, 5040-5439 | Alstom / Siemens / Hitachi | A, B, C, D, G, J, M, N, Q, W |
| **R153T** | Open-Gangway Variant | 3040-3059, 4610-5039 | Alstom / Hitachi | D Line (primary), testing |
| **R153B** | Future Order | 5350-5527 | Siemens SIC-VVVF | C, L, B, G, N, Q, W |

---

## 📊 Current Status (as of March 1, 2026)

### Delivery Progress

| Order Type | Total Cars | Delivered | Remaining | Completion |
|------------|------------|-----------|-----------|------------|
| R153S Base Order | 75 | 75 | 0 | **100%** |
| R153A Batch 1 (OO1) | 650 | 390 | 260 | 60% |
| R153A Batch 1 Base | 430 | 430 | 0 | **100%** |
| R153A Batch 2 (Siemens) | 350 | 270 | 80 | 77% |
| R153A 4-Car (ENY/Pitkin) | 220 | 220 | 0 | **100%** |
| R153T Batch 1 | 240 | 50 | 190 | 21% |
| R153A Batch 3 | 160 | 0 | 160 | 0% |
| **TOTAL** | **2,125** | **1,435** | **690** | **67.5%** |

### Active Line Assignments

| Line | Primary Yards | Fleet Types | Cars Assigned |
|------|---------------|-------------|---------------|
| **A** | Pitkin Yard | R153A Batch 1 OO1, Batch 2 Siemens | 300+ |
| **B** | Coney Island | R153A Batch 1 Base, Batch 2 Siemens, R153T | 450+ |
| **C** | Pitkin Yard | R153A Batch 1 Base (4-Car), Batch 2 Siemens | 200+ |
| **D** | Concourse | R153A Batch 1 OO1, Batch 1 Base, Batch 2 Siemens | 70 (growing) |
| **G** | Coney Island | R153A Batch 1 OO1, Batch 2 Siemens | 140+ |
| **J/M** | East New York | R153A 4-Car Base | 120 |
| **N/Q/W** | Coney Island | R153A Batch 1 Base, Batch 2 Siemens | 300+ |
| **SIR** | Clifton | R153S | 75 |

---

## 🔥 Recent Events

### February 27-28, 2026 - R153A 2640-2644 Fire Incident

| Detail | Information |
|--------|-------------|
| **Time** | February 27, 2026 - 10:24 PM |
| **Location** | Hoyt-Schermerhorn Streets (G Line) |
| **Train** | R153A 2640-2644 (5-car set) |
| **Affected Car** | 2644 (fifth coach) |
| **Cause** | Underfloor electrical arcing (preliminary) |
| **Injuries** | 0 |
| **Service Impact** | 1 hr 21 min suspension |
| **Restoration** | February 28, 2026 - 9:57 AM |

### February 28, 2026 - New Deliveries

| Set | Type | Destination | Cars |
|-----|------|-------------|------|
| 2770-2779 | R153A Alstom | Pitkin Yard | 20 |
| 3760-3769 | R153A Siemens | Concourse Yard | 20 |

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `index.html` | Main HTML page with interactive fleet tracker |
| `style.css` | Styling for the fleet tracker interface |
| `script.js` | JavaScript for tab switching and interactivity |
| `fleet-data.json` | Complete R153 fleet database (deliveries, assignments) |
| `incident-log.md` | Detailed incident reports |
| `timeline-2025-2026.md` | Full delivery and service timeline |
| `assets/` | Images, icons, and graphics |

---

## 🖥️ How to Use

### View Online
Visit [https://ncjunctiontransit.github.io/NCJunctionTransit-R153](https://ncjunctiontransit.github.io/NCJunctionTransit-R153)

### Run Locally
```bash
git clone https://github.com/NCJunctionTransit/NCJunctionTransit-R153.git
cd NCJunctionTransit-R153
open index.html
