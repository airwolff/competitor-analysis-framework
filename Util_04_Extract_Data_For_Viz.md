**[PROMPT START]**

**Role:** Act as a meticulous **Data Extraction Assistant** tasked with identifying and structuring specific quantitative data points from a completed Competitive Intelligence report for visualization purposes.

**Objective:** Scan the provided CI report file and extract key numerical and categorical data relevant for creating charts and graphs. Present this data in a clear, structured format (primarily Markdown lists/tables) suitable for easy copy-pasting into external visualization tools.

**Input:**

* **Please process the attached file containing the final, complete CI report.**
    *(This file should contain the report after all stages (1-4) of facts and analysis summaries have been integrated, likely the output from Util_02 run after Stage 4 analysis)*

**Data Extraction Task:**

Carefully review the **entire attached Input Report file** and extract the following specific data points. If a category of data is not present or marked as "[Information Not Found]" in the report, state that clearly for the corresponding section below.

1.  **Funding Rounds:**
    * Extract Date, Round Name (Seed, Series A, etc.), Amount Raised, and Lead Investor(s) for each round mentioned.
    * Present as a Markdown table or a clearly structured list.

2.  **Total Funding:**
    * State the total funding amount reported.

3.  **Revenue Estimates:**
    * Extract Date/Period and the corresponding Estimated Revenue figure for each estimate mentioned.
    * Present as a Markdown table or list.

4.  **Team Size:**
    * Extract the approximate team size figure(s) mentioned. If multiple points in time are given, include dates if available.

5.  **User/Patron Count:**
    * Extract the key figures for user/patron counts (e.g., Monthly Active Patrons, Total Creators). Include dates/timeframes if specified.

6.  **Site Traffic:**
    * Extract key website traffic estimates (e.g., monthly visits). Include dates/timeframes if specified.

7.  **User Demographics (if available):**
    * Extract key demographic breakdowns (e.g., Age Group percentages, Gender percentages, Top Geography percentages).
    * Present as Markdown lists or a table.

8.  **Social Media Following:**
    * Extract Platform Name and Follower Count for each social media channel listed.
    * Present as a Markdown table or list.

9.  **Mobile App Ratings (if available):**
    * Extract Platform (iOS/Android) and Average Rating.

10. **SWOT Summary Points:**
    * List the key bullet points under Strengths.
    * List the key bullet points under Weaknesses.
    * List the key bullet points under Opportunities.
    * List the key bullet points under Threats.

**Output Format:**

* Present the extracted data clearly under headings corresponding to points 1-10 above.
* Use Markdown tables or bulleted/numbered lists for structured data (like funding rounds, revenue estimates, demographics, social following, SWOT points).
* For single data points (like Total Funding, Team Size), state them clearly.
* If data for a section is unavailable in the input report, explicitly state "[Data Not Found in Report]".
* **Do NOT include** analysis, commentary, or the original surrounding text from the report – only the extracted data points in the requested structured format.

**[PROMPT END]**
