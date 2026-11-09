# Francisco Rezzonico — Data & Analytics Portfolio

Personal portfolio website for Francisco Agustín Rezzonico, a data analyst and MS in Business Analytics & AI candidate at American University.

**Live site:** [franciscorezzonico.github.io](https://franciscorezzonico.github.io/)

## About

This portfolio combines my interests in sports analytics, data analysis, and AI through an interactive 3D locker room. Each locker represents part of my professional story: my background, selected projects, education, work experience, skills, or contact information.

Visitors can browse the room, open a locker, and read its details in an expandable content panel. A Text Version provides an alternative way to explore the portfolio without navigating the 3D scene.

## Features

- Interactive 3D locker-room scene with numbered jerseys, sports equipment, and environmental details.
- Separate lockers for About Me, Projects, Education, Experience, Skills, and Contact.
- Front and angled browsing views, with additional views while inspecting a locker.
- Expandable details panels for project summaries, education, experience, and skills.
- Responsive navigation with desktop section controls and a Section menu on narrow screens.
- Keyboard, scrolling, pointer, and touch navigation.
- HIDE/show controls for the interface.
- A Text Version and a fallback view when the interactive scene cannot initialize.
- A résumé download hosted alongside the website.

## Featured projects

### American University Basketball Expected Points Dashboard

An R Shiny dashboard developed for American University's men's basketball coaching staff to explore team- and player-specific expected points by shot zone, shot type, and defensive contest level. The project includes foul-adjusted predictions, weighted KPIs, configurable inclusion rules, and limited-sample warnings. Its published demo uses fictitious player names and data to protect privacy.

### European Football Transfer Market Analysis

Analysis of 70,006 European football transfer records using R, Quarto, and Tableau. The project examines long-run transfer-fee inflation and the relationships between fees, leagues, player ages, and positions through quadratic and OLS regression models and an interactive dashboard.

### Spotify Music Market Analysis

Exploratory analysis of 9,227 Spotify tracks using R, ggplot2, and Plotly, examining how genre, artist release history, song duration, and speechiness relate to track popularity.

### Manhattan Private-Room Pricing Analysis

A reproducible R and Quarto workflow analyzing private-room listings across five Manhattan neighborhoods. The project includes exploratory visualizations, multiple linear regression, model diagnostics, and an interactive 3D Plotly chart.

### EV CAFV Eligibility Analysis

Statistical analysis of 103,032 Washington State EV registrations using descriptive statistics, a chi-square test of independence, Cramér's V, and data visualizations to examine differences in Clean Alternative Fuel Vehicle eligibility across manufacturers.

## Skills presented

- Programming languages: Python, R, SQL, and Stata.
- Markup & typesetting: R Markdown and LaTeX.
- Libraries & frameworks: Pandas, NumPy, Scikit-learn, tidyverse, and ggplot2.
- Tools & platforms: Power BI, Tableau, Git / GitHub, Google Cloud Run, Jupyter, VS Code, Claude Code, and MCP.
- Spoken languages: Spanish — Native; English — C2.

## Website technologies

- HTML5 and CSS3.
- JavaScript and ES modules.
- Three.js, using its WebGPU renderer with a WebGL2 fallback where supported.
- Procedural geometry, canvas-generated textures, and custom scene lighting.
- Google Fonts: Cormorant Garamond, DM Mono, and Outfit.
- GitHub Pages for static hosting.

Three.js modules and Google Fonts are loaded from external services. An internet connection is therefore needed for the intended interactive experience.

## Local preview

No build step is required. Clone the repository:

```bash
git clone https://github.com/franciscorezzonico/franciscorezzonico.github.io.git
cd franciscorezzonico.github.io
```

Serve the repository through a local HTTP server rather than opening the HTML directly as a local file. For example, with Python installed:

```bash
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in a modern browser.

Graphics support varies by browser and device. If the interactive view does not initialize, use the Text Version or the fallback view.

## Navigation

- Browse lockers with scrolling, dragging/swiping, the bottom arrow controls, or the keyboard's left and right arrow keys.
- On desktop, use the section navigation to jump between sections. On narrow screens, use the Section menu.
- Select a locker, then select it again to open it.
- Use Read details or select the open locker to view its content panel.
- Use Back to the Lockers to return to browsing.
- Use the view controls to switch between front and angled views.
- Use HIDE or the H key to hide or show the interface.
- Use Text Version to switch to the traditional portfolio layout.

## Repository structure

```text
.
├── index.html          # Portfolio markup, styling, data, and scene logic
├── assets/
│   └── resume.pdf      # Résumé PDF maintained in the repository
├── README.md           # Project documentation
└── .gitignore          # Excluded local files and folders
```

## Contact

- [LinkedIn](https://www.linkedin.com/in/franciscoarezzonico/)
- [GitHub](https://github.com/franciscorezzonico)

## License

© 2026 Francisco Agustín Rezzonico. All rights reserved.

Unless otherwise stated, the original website code and content are provided for portfolio-viewing purposes. Please do not reproduce, redistribute, or reuse them without permission.

Third-party libraries, fonts, and other third-party materials remain subject to their respective licenses.