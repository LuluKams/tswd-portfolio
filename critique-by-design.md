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

<div class='tableauPlaceholder' id='viz1789616837282' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wo&#47;WorldsDeadliestAnimalsRedesign&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='WorldsDeadliestAnimalsRedesign&#47;Dashboard1' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wo&#47;WorldsDeadliestAnimalsRedesign&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1789616837282');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='1000px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='850px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='1000px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='850px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.minHeight='800px';vizElement.style.maxHeight=(divElement.offsetWidth*1.77)+'px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>



---

## Sources & AI Disclosure
* **Data Sources:** *Our World in Data*, IHME Global Burden of Disease, World Health Organization (WHO), UNODC.
* **Design Frameworks:** Stephen Few's Data Visualization Effectiveness Profile.
* **Generative AI Usage:** Generative AI (Google Gemini) was utilized during the development of this project as a design thinking collaborator and technical reference. Specifically, AI was used to help brainstorm layout architectures for handling multi-order-of-magnitude discrepancies, refine qualitative color palette assignments, troubleshoot Tableau Web Authoring axis formatting, and assist in drafting structural Markdown scaffolding for documentation.
