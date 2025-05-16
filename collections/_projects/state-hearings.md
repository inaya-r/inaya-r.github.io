---
layout: project
title: "State Legislative Hearings Dashboard"
description: "This interactive dashboard visualizes over a decade’s worth of U.S. state legislative hearing transcripts to uncover trends in transparency, access, and civic engagement."
date: 2024-12-18
weight: 1
thumbnail: "/assets/images/state_hearings/state-leg-dashboard.png"
image: "/assets/images/gen/projects/project-1-2.webp"
categories: ["R", "Shiny", "Civic Tech", "Data Visualization"]
client: "UWB Faculty"
role: "Data Analyst & R Shiny Developer"
gallery:
  - image: "/assets/images/state_hearings/state-leg-p1.png"
  - image: "/assets/images/state_hearings/state-leg-p2.png"
gallery_limit: 2
---

This interactive dashboard visualizes over a decade’s worth of U.S. state legislative hearing transcripts to uncover trends in transparency, access, and civic engagement.

---

### Key Features

- **Interactive Filters** for state, year, and archive type (e.g., agendas, minutes, transcripts)
- **Visual Summaries** of hearing availability by state and over time
- **Searchable Tables** of metadata for quick comparison
- **GPT Summaries** (experimental): uses OpenAI API to summarize state hearing access

---

### 🔍 Project Goals

This dashboard was built to:
- Help journalists, researchers, and advocates assess how accessible legislative records are across states
- Identify gaps in public documentation (e.g., missing transcripts or outdated archives)
- Highlight patterns in open government practices

---

### 📁 Data & Methods

- Data scraped from state legislative websites and standardized for dashboard use
- Cleaned using `tidyverse`, analyzed with `dplyr`, and visualized with `ggplot2`
- Built entirely in R with `shiny` for interactive deployment

---

### 🌐 View the Live Dashboard

👉 [Launch Dashboard](https://inaya-r.shinyapps.io/StateHearings_Dashboard/)

---

*Note: All data used in this project was manually collected from publicly accessible state legislature websites. This dashboard was created solely for educational purposes and does not use or expose any private or restricted information.*

---