# olit-guide
Olit is an AI research assistant built directly into the Galaxy platform. It allows researchers to analyze data, run tools, build charts, and document experiments using plain language.

---

## 1. What Olit Does
Galaxy contains hundreds of scientific tools and settings. Olit simplifies this experience:
* You describe your analysis goal in ordinary words.
* Olit identifies the appropriate tools and prepares their inputs.
* Olit submits the jobs to Galaxy and tracks their progress.
* Olit documents your entire workflow into a permanent scientific report.

---

## 2. Where It Runs
* **Directly in Your Web Browser:** Olit requires no software installation and no dedicated background servers. It opens as a side panel next to your active dataset.
* **Uses Your Existing Login:** Because it runs in your current browser window, it works with your active Galaxy account automatically.
* **Privacy by Default:** If you provide your own key for an external AI model, it stays inside your browser tab and is never stored on Galaxy servers.
* **Preserved Conversations:** Your chat history is saved in your browser's local storage, meaning refreshing the page does not erase your work.

---

## 3. How It Works: Plan First, Run Second
Olit is built on the principle that the researcher remains in full control:
1. **Step-by-Step Plan:** When you request an analysis, Olit outlines a clear plan listing each tool and the settings it intends to use.
2. **User Review:** You can inspect the proposal, request adjustments, or approve it.
3. **Execution on Approval:** Olit only launches Galaxy jobs after you explicitly approve the plan.
4. **Progress Tracking:** Olit monitors running jobs in the background and informs you when the results are ready.

---

## 4. Key Capabilities
* **Running Galaxy Tools:** Searches the platform, selects tools, and runs them on your datasets.
* **Running Community Workflows:** Finds and executes peer-reviewed pipelines from the scientific community.
* **Fast Local Math:** Performs lightweight calculations directly in your browser without waiting in server queues.
* **Importing Public Data:** Looks up public sequence repositories by study number and downloads raw files straight into your history.
* **Consulting Official Tutorials:** Searches official Galaxy training materials to follow verified scientific protocols.
* **History Management:** Groups, renames, and tags datasets to keep large projects organized.
* **Data Lineage:** Traces the history of any output file and displays its creation steps as an interactive flowchart.

---

## 5. Visualizations and Charts
* **Built-in Galaxy Viewers:** Opens dedicated platform viewers (such as genome browsers or 3D molecular viewers) with your data pre-loaded.
* **Custom Charts on Demand:** Generates interactive bar charts, scatter plots, and heatmaps from tabular data directly in the side panel.
* **Save or Preview:** Allows you to preview a chart temporarily or save it permanently as a shareable link in your Galaxy account.
* **Scientific Integrity:** If a chart requires a new calculation, Olit runs a real Galaxy tool to produce the data first, ensuring all results remain reproducible.

---

## 6. Built-in Guidebooks
Instead of guessing platform rules, Olit consults official, built-in guidebooks:
* **Specific Knowledge:** Individual guidebooks cover topics such as chart design, data structuring, and lab record keeping.
* **Consulted on Demand:** Olit only loads a guidebook when a matching task begins.
* **Verified Rules:** All guidebooks are verified and locked into the software package in advance to ensure consistent and reliable behavior.

---

## 7. Automatic Lab Records
Chat conversations can easily be closed or lost. To protect your work, Olit maintains a permanent Galaxy Page for every project:
* **The Plan:** Records the approved goals and parameters.
* **The Execution:** Logs the exact tools used, marking each completed step with a checkmark.
* **The Output:** Embeds generated charts and figures directly into the document alongside written interpretations.
* **A Shareable Deliverable:** Leaves behind a complete, shareable, and verifiable scientific notebook at the end of every session.

---

## 8. Safety and Governance
* **Destructive Action Warnings:** If an operation would permanently delete data or cancel a workflow, Olit stops and asks for your confirmation first.
* **No Fabricated Results:** Olit does not simulate data processing. All computations are performed by real Galaxy tools with full provenance tracking.
