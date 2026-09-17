# Visualizing Risk: Microscopic Vectors vs. Cinematic Predators

## Step 1: The Original Data Visualization
The original visualization analyzed animal-related human fatalities using data from *Our World in Data*. I selected this visualization because the popular perception of deadly animals is heavily skewed by cultural media and cinematic depictions of apex predators like sharks and lions, rather than the public health reality of insect-borne pathogens.

[Link to Original Visualization on Our World in Data](https://ourworldindata.org/)

---

## Step 2: Critique Method & Initial Insights
Using Stephen Few's Data Visualization Effectiveness Profile, I evaluated the original chart's capacity to communicate relative risk:
* **The Scale Problem:** Placing mosquitoes (~760,000 deaths) on the same single linear scale as sharks (~6 deaths) completely flattened apex predators against the baseline, making them visually indistinguishable from zero.
* **Mechanism Ambiguity:** The chart listed animals alphabetically or by raw count without distinguishing *how* the deaths occurred (pathogen transmission vs. envenomation vs. direct physical attacks).

---

## Step 3: Wireframes & Initial Sketches
To resolve the scale compression, I developed an initial sketch featuring a two-panel split layout:
* **Panel 1 (Global Macro Impact):** A linear scale (0 to 800,000) focusing on high-magnitude vectors and direct human conflict.
* **Panel 2 (Magnified View: Feared Predators):** A focused inset scale isolating feared predators.
* **Color Encoding:** Blue for pathogen/parasite vectors, orange for biological venom, and red for direct physical trauma.

View or download the complete initial design sketch:
📄 **[Download / View Initial Design Sketch (PDF)](sketch.pdf)**

<iframe src="sketch.pdf" width="100%" height="550px"></iframe>

---

## Step 4: User Feedback & Revisions
I conducted user feedback sessions with two peers (Interviewee C and Interviewee I):
* **Scale Separation:** Both users appreciated the separate inset panel, noting it immediately clarified how insignificant shark and lion attacks are relative to insect-borne illnesses.
* **Clarity of Mechanism:** One user pointed out that dogs should be grouped with disease vectors rather than physical trauma, as dog-related human fatalities are overwhelmingly driven by rabies transmission.
* **Modifications Applied:** I aligned the color coding so dogs, snails, and mosquitoes share the pathogen vector palette, and clarified the axis titles with explicit scale notes.

---

## Step 5: The Final Solution

### Design Transition Note
During the initial sketching phase, I estimated apex predator counts based on general figures (placing Crocodiles at the top of the magnified view). When transitioning to Tableau and connecting the official dataset extract, the reported figures placed Lions higher (300) than Crocodiles (150). Rather than forcing the visual to match the initial sketch, I let the underlying data drive the sorting order while preserving the two-panel magnified architecture and trauma color coding.

### Final Interactive Dashboard

<iframe src="https://public.tableau.com/views/WorldsDeadliestAnimalsRedesign/Dashboard1?:showVizHome=no&:embed=true" width="100%" height="750" frameborder="0"></iframe>



---

## Sources & AI Disclosure
* **Data Sources:** *Our World in Data*, IHME Global Burden of Disease, World Health Organization (WHO), UNODC.
* **Design Frameworks:** Stephen Few's Data Visualization Effectiveness Profile.
* **Generative AI Usage:** Generative AI (Google Gemini) was utilized during the development of this project as a design thinking collaborator and technical reference. Specifically, AI was used to help brainstorm layout architectures for handling multi-order-of-magnitude discrepancies, refine qualitative color palette assignments, troubleshoot Tableau Web Authoring axis formatting, and assist in drafting structural Markdown scaffolding for documentation.
