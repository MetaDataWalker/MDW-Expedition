# Long-Distance Human Locomotion Dataset

**Subtitle:** Long-Horizon Egocentric Navigation Under Resource Constraints

---

## Overview

This repository documents a long-term egocentric dataset capturing **long-distance human locomotion** across varied terrain, weather, and environments.

The dataset supports research into **long-horizon egocentric navigation under real-world resource constraints**, including limited battery, water, fatigue, terrain variability, and environmental conditions.

The focus is on **measurable human movement over extended time horizons**, not storytelling or travel documentation.

---

## Research Task

> Given an egocentric view of the environment and current resource state, predict how a human will physically move next over the following hours.

Predicted outcomes include distance, duration, stop vs continue, terrain transitions, and resource consumption.

---

## Dataset Structure

- ~365 days approximately of data collection  
- 3 fixed segments per day (morning, midday, late afternoon)  
- ~1,095 segments  
- ~730 long-horizon prediction windows  

---

## Capture Protocol (Summary)

For each segment:
- GPS screenshot at start and end  
- Battery percentage and water level captured at start and end  
- 30–90s forward-facing egocentric video  
- No talking, narration, music, or edits  

Ground truth is derived from the difference between consecutive segments.

---

## Human Annotations

Optional contextual logs are recorded after each segment (e.g. terrain, weather, fatigue, notes).  
These provide human context and are **not** the prediction target.

---

## Scope

**Included:** movement, location, time, terrain, resource state  
**Excluded:** intentions, plans, emotions, narration  

---

## Intended Use

Research into long-horizon navigation, human movement forecasting, and resource-constrained locomotion.

Not intended for entertainment content or short-horizon action recognition.

Contact:
fieldwalk.data@gmail.com
