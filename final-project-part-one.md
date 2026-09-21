# Final Project Part I: Proposal & Story Architecture

## The Invisible Crisis: The Surge in U.S. Pedestrian Fatalities in the SUV Era

---

## 1. High-Level Project Summary

Over the past two decades, passenger vehicle cabins have become safer than at any point in automotive history. Advances in reinforced steel safety cages, crumple zones, and multi-angle airbag systems have steadily protected vehicle occupants during collisions. However, this private safety sanctuary coincided with an alarming public health failure outside the vehicle: pedestrian fatalities across the United States increased by over 70% between 2010 and 2022, climbing to more than 7,400 annual deaths. 

This project investigates the physical, environmental, and consumer dynamics driving this divergence. While popular media narratives often frame pedestrian collisions as individual behavioral lapses, citing smartphone distraction or pedestrian jaywalking—the empirical crash record demonstrates that this spike directly corresponds to a fundamental transformation of the American passenger vehicle fleet. As consumer preferences shifted overwhelmingly toward heavier, taller light trucks and full-size SUVs with blunt, high-profile front hoods, crash impact physics changed catastrophically for vulnerable road users. By contextualizing federal crash records, vehicle dimensional changes, and roadway infrastructure disparities, this visual data story aims to steer the conversation toward systemic solutions: federal pedestrian-safety vehicle regulations, vehicle hood geometry standards, and pedestrian-priority street design.

---

## 2. Project Structure & Story Arc

In alignment with Scott Berinato's Good Charts (Chapter 8: Story Structure), this narrative unfolds using a deliberate five-stage narrative arc:

* **Setup (The Divergence):** The general public assumes roads are safer due to modern in-car tech, but pedestrian fatalities are rapidly climbing while occupant fatalities fall.
* **Rising Action (Fleet Shift):** Exploring the consumer shift from sedans to heavy SUVs/pickups, tracking curb weight growth and hood heights.
* **Climax (The Geometry of Impact):** Analyzing the biomechanics of impact,how blunt SUV grilles strike vital organs directly and carry a fatal risk multiplier compared to lower sedan bumpers.
* **Falling Action (The Infrastructure Gap):** Examining compounding 2023 crash environment factors (75%+ occurring at night, missing crosswalks and sidewalks on arterial roads).
* **Resolution (Redesigning Survival):** Actionable policy and design levers (federal vehicle hood standards, nighttime automatic emergency braking, and urban traffic calming).

### One-Sentence Story Summary:
While modern vehicle design has engineered unprecedented safety for drivers, the unchecked growth of heavy, tall-front SUVs has exported fatal risk onto pedestrians, a public health crisis that demands regulatory and physical design intervention.

### User Stories & Target Audiences:
* **The Concerned Urban Resident / Commuter:** "As a pedestrian and transit user, I want to understand whether roads are truly getting more dangerous for people walking, so that I can advocate for traffic calming and safer street design in my neighborhood."
* **The Transportation Planner / Policymaker:** "As a civic leader or safety analyst, I need empirical evidence connecting vehicle front-end design and roadway lighting to vulnerable road user fatalities, so that I can justify lower arterial speed limits and infrastructure funding."

### Detailed Narrative Progression:
1. **The Setup (The Divergence):**
   * The Assumption: Most people assume roads are universally safer today because vehicles have advanced sensors, cameras, and crash-test ratings.
   * The Reality: A dual-line comparison illustrating that while occupant fatalities plateaued or dropped relative to miles driven, pedestrian and cyclist fatalities surged by more than 70% after 2010.
2. **The Rising Action (The Transformation of the American Fleet):**
   * How sedans and station wagons were replaced by light trucks and SUVs, which now constitute over 50% of the domestic passenger vehicle fleet.
   * Tracking curb weight increases and the rising height of vehicle grilles over the last decade.
3. **The Climax (The Geometry of Impact):**
   * The biomechanics of impact: A sedan bumper strikes an adult below the center of gravity (knees/tibia), rolling the body onto the softer hood. A full-sized SUV or pickup grille strikes directly at chest, torso, and head level, thrusting the pedestrian downward into the path of the wheels.
   * Crash severity statistics showing that SUVs are significantly more lethal to pedestrians at urban speeds than passenger cars.
4. **The Falling Action (Environmental & Equity Compounding Factors):**
   * Analyzing 2023 crash conditions: over 75% of fatal pedestrian crashes occur after dusk, heavily concentrated on arterial multi-lane roads lacking continuous sidewalks, mid-block crosswalks, or pedestrian-scale lighting.
   * How these fatalities disproportionately impact lower-income neighborhoods where roadway infrastructure investments have lagged.
5. **The Resolution (Designing for Survival):**
   * Actionable policy and design levers:
     1. Updating federal New Car Assessment Program (NCAP) standards to penalize aggressive, blunt hood heights.
     2. Mandating standard automatic emergency braking (AEB) calibrated for dark conditions and pedestrian silhouettes.
     3. Implementing traffic calming: daylighting street corners, pedestrian refuge islands, and reduced arterial speed limits.

---

## 3. Initial Sketches

The following sketches outline the planned sequence of charts and the visual hierarchy of the story:

📄 [Download / View Initial Sketches (PDF)](sketch_part1.pdf)

### Visualization Plan:
* **Chart 1: Divergence Trend (Line Chart):** Comparing the trajectories of vehicle occupant deaths versus pedestrian deaths from 2010 to 2023 to expose the diverging safety trends.
* **Chart 2: Grille Profile vs. Injury Severity (Annotated Bar / Diagram):** Visualizing the striking vehicle profile and the corresponding fatality multiplier between sedans and light trucks/SUVs.
* **Chart 3: Crash Environment Breakdown (Stacked Distribution / Donut Charts):** Isolating light conditions (daylight vs. dark/unlit) and sidewalk presence from the 2023 FARS data.
* **Chart 4: Speed and Survivability Matrix (Risk Curve):** Illustrating pedestrian survival probabilities across 20 mph, 30 mph, and 40 mph impact speeds.

---

## 4. The Data

### Primary Data Sources & Attribution
This project uses verified, primary open data provided by federal transportation safety agencies:
1. **National Highway Traffic Safety Administration (NHTSA) / Data.gov:**
   * **Dataset:** Fatality Analysis Reporting System (FARS) Final Release - Person Auxiliary File (PER_AUX), maintained by the USDOT Bureau of Transportation Statistics (BTS) and NHTSA.
   * **Attributes Used:** Crash year (YEAR), person type (A_PTYPE: Pedestrians = 3), injury severity (A_PERINJ: Fatal = 1), age demographics, and seating/location factors across 93,406 total recorded traffic incidents.
   * **Official Source Link:** https://catalog.data.gov/dataset/fatality-analysis-reporting-system-fars-final-release-person-auxiliary-file
2. **Governors Highway Safety Association (GHSA):**
   * **Reports:** Annual Pedestrian Traffic Fatalities by State statistical benchmarks tracking multi-year historical trends, striking vehicle body types, and roadway lighting attributes.
   * **Official Resource Link:** https://www.ghsa.org/resource-hub/pedestrian-traffic-fatalities
3. **Insurance Institute for Highway Safety (IIHS):**
   * **Research Publications:** Empirical studies quantifying pedestrian crash outcomes relative to front-end vehicle dimensions, hood heights, and vehicle curb weights.
   * **Official Resource Link:** https://www.iihs.org/

### Working Data Access
A working extract containing person-level FARS microdata has been uploaded to the public portfolio repository:
* **Public Repository Dataset Link:** [Download fars_person_auxiliary_2023.csv](fars_person_auxiliary_2023.csv)
* **Direct Raw Link:** https://github.com/lulukams/tswd-portfolio/blob/main/fars_person_auxiliary_2023.csv

---

## 5. Method and Medium

The final project will be executed as an interactive, digital-first data story:
* **Interactive Data Visualizations:** Designed and published via **Tableau Public**, allowing readers to hover for exact values, filter by vehicle type, and explore trends interactively.
* **Narrative Platform:** The story will be structured using **Shorthand** (or directly integrated into **GitHub Pages** as a clean, responsive scrollytelling webpage) to guide readers through text, diagrams, and interactive charts in a unified visual flow.
* **Diagrams & Visual Cues:** Vector illustrations explaining bumper impact mechanics and hood profiles will be designed to support the quantitative charts.

---

## Sources & AI Disclosure

### References
* National Highway Traffic Safety Administration. (2023). Fatality Analysis Reporting System (FARS) Final Release: Person Auxiliary File. U.S. Department of Transportation.
* Governors Highway Safety Association. (2023). Pedestrian Traffic Fatalities by State: 2022 Preliminary Data.
* Berinato, S. (2023). Good Charts: The HBR Guide to Making Smarter, More Persuasive Data Visualizations. Harvard Business Review Press.

### Generative AI Usage
Generative AI (Google Gemini) was utilized during the development of Part I as a design thinking collaborator and technical research assistant. Specifically:
* **Topic Selection & Framing:** AI assisted in evaluating and narrowing down proposed topics against the assignment criteria to focus on the intersection of vehicle geometry and pedestrian mortality.
* **Story Architecture:** AI helped structure the five-stage story arc and audience user stories aligned with Scott Berinato's Good Charts (Chapter 8).
* **Data Inspection:** Python code via Google Gemini was utilized to parse the 93,406-row FARS CSV (PER_AUX), verifying column definitions (A_PTYPE = 3 for pedestrians, A_PERINJ = 1 for fatalities) and confirming data integrity.
* **Markdown Scaffolding:** AI assisted in drafting the structural Markdown scaffolding to ensure alignment with all rubric requirements.
