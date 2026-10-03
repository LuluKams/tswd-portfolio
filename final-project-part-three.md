# Final Project Part III: Final Deliverable & Behind-the-Scenes Evolution

[← Back to Portfolio Home](README.md) | [View Part I: Proposal](final-project-part-one.md) | [View Part II: Wireframes & Research](final-project-part-two.md)

---

## 1. Final Deliverable Links

* **Live Interactive Data Story (Shorthand):** [Shielded Inside, Endangered Outside](https://carnegiemellon.shorthandstories.com/shielded-inside-endangered-outside/index.html)
* **Tableau Public Worksheet:** [Pedestrian vs Occupant Divergence](https://public.tableau.com/)
* **Project Documentation Repository:** [tswd-portfolio](https://github.com/lulukams/tswd-portfolio)

---

## 2. Story Summary & Executive Overview

"Shielded Inside, Endangered Outside" investigates a stark paradox in American transit safety: over the past decade, advancements in structural automotive passenger protection have made modern car cabins safer than ever, while individuals walking outside those cabins face historic levels of danger. Between 2010 and 2022, U.S. pedestrian fatalities surged by nearly 75%, while occupant deaths rose by less than 15%.

This scrollytelling project moves beyond conventional victim-blaming narratives to examine the systemic drivers behind this divergence. Through a multi-tiered narrative arc, the story investigates how federal fuel economy carve-outs accelerated a domestic shift from low-slung sedans to heavy, blunt-front SUVs and trucks. It details the biomechanics of impact geometry, links crash severity to arterial design deficiencies, and presents federal policy and complete-streets interventions necessary to reverse this trend.

---

## 3. Audience Analysis & Design Evolution

### Target Audience & Persona Framing
The core audience for this project encompasses two distinct groups:
1. **Civic Advocates & Transportation Planners:** Professionals seeking data-backed rigor to advocate for pedestrian-scale lighting and roadway retrofits.
2. **Everyday Motorists & SUV Owners:** Drivers who value personal and family cabin safety but may be unaware of front-end blind zones and exterior kinematic impact profiles.

### User Research Insights & Iterative Adjustments
Feedback gathered during Part II wireframe testing directly shaped the final deliverable:
* **Indexing Clarification:** Reviewers initially questioned whether Figure 1 represented raw fatalities or percentage changes. In response, the Y-axis was clearly re-labeled as `% Change from 2010 Baseline`, and contextual callouts showing absolute counts (4,302 in 2010 to 7,522 in 2022) were added to ground the scale.
* **Neutral, Systemic Framing:** User feedback indicated that blaming vehicle purchasers provoked defensive reactions. The narrative was intentionally shifted from consumer culpability toward systemic vehicle safety regulations (NHTSA NCAP crashworthiness tests) and automotive design incentives.
* **Elevating Built-Environment Context:** Peer critique highlighted that focusing solely on vehicle height overlooked infrastructural factors. Section 4 was expanded with Figure 3 to emphasize that over 76% of fatal crashes happen in low light and nearly 70% where sidewalks are absent.

---

## 4. Design Decisions & Platform Execution

### Platform & Layout Selection
Shorthand was chosen as the delivery medium to create a distraction-free, responsive scrollytelling narrative. The long-form scroll format allows the reader to follow the sequential structure outlined in Scott Berinato's *Good Charts*, moving deliberately from the macroscopic trend to the anatomical impact mechanism, and concluding with municipal solutions.

### Visual Styling & Accessibility
* **Color Hierarchy:** A cohesive color palette was used across all visual assets. Deep navy (`#3182bd`) signifies the pedestrian baseline trend, muted slate grey represents occupant baseline stability, and high-contrast alert orange/red (`#de2d26`) isolates elevated hazard categories.
* **Typography & Responsive Scaling:** All charts include high-contrast annotations, clear axis labels, and descriptive captions. Media assets were uploaded with dedicated desktop and mobile breakpoints alongside comprehensive screen-reader alt text.

---

## 5. References & Academic Attribution

### Primary Data Sources
* **National Highway Traffic Safety Administration (NHTSA).** (2023). *Fatality Analysis Reporting System (FARS) Microdata: Person Auxiliary Dataset*. U.S. Department of Transportation.
* **Insurance Institute for Highway Safety (IIHS).** (2022). *Vehicle Front-End Geometry, Point-of-Contact Dynamics, and Pedestrian Injury Severity*.
* **Governors Highway Safety Association (GHSA).** (2023). *Pedestrian Traffic Fatalities by State: Annual Trend Report*.

### Literature & Frameworks
* **Berinato, Scott.** (2023). *Good Charts: The HBR Guide to Making Smarter, More Persuasive Data Visualizations*. Harvard Business Review Press.

### Generative AI Disclosure
In compliance with course academic integrity guidelines, Generative AI (Google Gemini) was utilized in the following capacities:
* Programmatically generating high-fidelity draft charts (Figures 2 and 3) based on curated federal research parameters.
* Refining narrative structure, section phrasing, and interview synthesis clarity.
* Structuring Markdown scaffolding for portfolio documentation. Figure 1 was developed and published directly by the author using Tableau Public.

