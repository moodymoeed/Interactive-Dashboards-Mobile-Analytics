# Visual Analytics & Dashboard Design: Gestalt & Bertin Principles

**Author:** Moeed ur Rehman

**Course/Project:** DSA301 Project 2 - Interactive Dashboards & Mobile Analytics  

## Overview
This repository contains the code, data, and design rationale for a two-part data visualization project focusing on the application of **Gestalt principles** and **Jacques Bertin's visual variables**. 

The project is divided into two distinct mediums: a desktop-optimized web dashboard (AI-Generated) and a mobile-optimized application prototype (D3.js/Vanilla JS).

---

## Part 1: Japan Inbound Immigration Dashboard
**Goal:** Analyze and redesign an AI-generated dashboard to improve usability and data-to-ink ratio.

* **Data:** Japan Immigration Statistics by Nationality (Kaggle)
* **Process:**

    1. Generated an initial baseline dashboard using an LLM (Claude Sonnet 4.6)
    2. Critiqued the baseline using Gestalt principles (Proximity, Figure/Ground) and Bertin's visual encodings (Color, Position).
    3. Formulated a revised prompt to enforce semantic color matching (Similarity), logical layout grouping (Enclosure), and reduction of visual clutter.
* **Location:** `Part1_Japan_Immigration/` folder. Screenshots of the transformation are documented in the submitted PDF.

---

## Part 2: Whoop Health Dataset Mobile App
**Goal:** Design and implement a mobile-first analytics interface for highly granular physiological data.

* **Data:** Whoop Fitness Dataset (Kaggle)
* **Process:**

  1. **Data Analysis:** Filtered the 100k+ row dataset down to the most critical glanceable metrics for a mobile user (Recovery Score, Day Strain, Sleep Performance).
  2. **Conceptual Sketches:** Designed three distinct mobile views (Daily Readiness, Sleep Architecture, Weekly Trends) using strict spatial positioning and color encodings.
  3. **D3.js Implementation:** Programmed a fully functional, tabbed mobile prototype in a single HTML file.
* **Technical Implementation:** The prototype uses Vanilla JavaScript for tab routing and **D3.js** for rendering SVG charts (Circular Arc gauges, Stacked Horizontal Bars, and Composed Line/Bar charts).
* **Location:** The playable code is located at `Part2_Whoop_App/whoop_mobile_app.html`.

## How to Run the Mobile Prototype
1. Navigate to the `Part2_Whoop_App/` directory.
2. Download or clone the `whoop_mobile_app.html` file.
3. Double-click the file to open it in any modern web browser (Chrome, Safari, Edge). No local server is required.
