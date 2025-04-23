# Stage 1: Competitor Profile & Business Fundamentals

## Stage 1 Research Prompt

**[PROMPT START]**

**Role:** Act as a meticulous **Researcher** tasked with information gathering.

**Objective:** Create a foundational profile of **Competitor Name**. Focus on information and developments from the last 2-3 years where applicable.

**Research Guidance:**
* Search thoroughly for each required point.
* **Prioritize Source Types:** Give preference to official company sources (website, press releases, investor relations), reputable financial databases (e.g., Crunchbase, Pitchbook, SEC filings if public), and major news outlets.
* **Search Strategy Hint:** For financial data, try searches like "**Competitor Name** funding rounds Crunchbase" or "**Competitor Name** revenue estimate news". For leadership, try "**Competitor Name** CEO background LinkedIn" or "**Competitor Name** leadership team".
* If information is definitively unavailable after searching primary source types, explicitly state `[Information Not Found]` for that specific point.
* Report *only* the factual findings based on your research. Do not include analysis or interpretation in this output. Ensure all findings requiring a source URL have one appended.

**Required Information and Structure:**

**Stage 1: Competitor Profile & Business Fundamentals**

**Company Overview:**
* **Founding date and headquarters:** [State founding date and location]. (Requires Source URL)
* **Core mission or tagline:** [State mission/tagline]. (Requires Source URL)
* **Brief product/service description:** [Describe products/services, note artist focus if applicable]. (Requires Source URL)

**Financial and Investment Details:**
* **Current funding rounds (seed, Series A, etc.):** [List rounds]. (Requires Source URL)
* **Major investors (VC firms, angel investors):** [List investors]. (Requires Source URL)
* **Total funding to date:** [State amount or 'Total funding not publicly available']. (Requires Source URL)
* **Revenue estimates:** [State latest estimate/range with source date, or 'Revenue estimates not publicly available']. (Requires Source URL)

**Team Composition and Leadership:**
* **Founders and/or CEO background:** [List key background points, esp. music industry experience]. (Requires Source URL)
* **Key Functional Leadership:** [Identify leaders (Product, Eng, Marketing, Sales) and relevant experience]. (Requires Source URL)
* **Music Industry Credibility & Connections:** [Detail specific music industry connections/roles for key team members]. (Requires Source URL)
* **Key executives or marquee names:** [List C-suite or recognized execs]. (Requires Source URL)
* **Approximate team size:** [State size or 'Approximate team size unknown']. (Requires Source URL)

**Fan/Artist Base & Platform Use:**
* **Target fan/user demographics:** [Describe target fans]. (Requires Source URL)
* **Target artist/user demographics:** [Describe target artists (emerging vs. established?)]. (Requires Source URL)
* **Notable Artists on Platform / Partnerships:** [List known artists/bands and how they use platform]. (Requires Source URL)
* **Approximate user count or site traffic:** [Provide estimates/metrics or 'User count/site traffic data not publicly available']. (Requires Source URL)

**Key Business Metrics:**
* **Engagement rates (e.g., monthly active users):** [Report rates or 'Engagement rate data not publicly available']. (Requires Source URL)
* **Revenue sources and breakdown:** [Describe sources/breakdown or 'Revenue source/breakdown information not publicly available']. (Requires Source URL)
* **Social media presence and following:** [List platforms, follower counts, note artist endorsements]. (Requires Source URL)

**Information Gaps:**
* [List points where information/URL was confirmed as `[Information Not Found]` after searching]

**Source List:**
* [List all Source URLs used]

**[PROMPT END]**

---

## Stage 1 Analysis Prompt

**[PROMPT START]**

**Role:** Act as a **senior Competitive Intelligence Analyst** tasked with summarizing key findings and preparing context for the next stage.

**Input Data:**
<<< --- PASTE THE CLEANED FACTUAL OUTPUT (FROM UTIL_02) FOR STAGE 1 HERE --- >>>
*(This input should be the structured report containing verified facts but WITHOUT inline citations)*

**Analysis Task:** Based **strictly** on the verified factual points provided in the Input Data above for `[Competitor Name]`, perform the following:

**Part 1: Generate Concise Summaries & Assessments (Internal Process)**
* *Internally perform reasoning and self-critique for each point below, but DO NOT include the reasoning/critique steps in the final summary text.*

1.  **Founders and/or CEO Background Summary:** Synthesize the *relevant* background, focusing on pertinent experience. Explicitly note key music industry experience or previous ventures.
2.  **Key Functional Leadership Background Summary:** Briefly summarize the *relevant* industry/domain experience for each identified leader pertinent to their function. Note significant gaps if information was not found.
3.  **Social Media Presence Summary:** Characterize their overall social media footprint (platforms, scale).
4.  **Financial Health Implications:** Assess the competitor's likely financial position (e.g., well-funded, bootstrapping, reliant on next round) and potential implications for strategic flexibility/aggression, citing supporting evidence from the Input Data.

**Part 2: Prepare Context for Next Stage**
* Based *only* on the verified input data and the analysis performed, extract or copy the following specific items and format them clearly.
<<< --- START CONTEXT BLOCK FOR STAGE 2 --- >>>
**CONTEXT FOR STAGE 2:**
* **Core mission or tagline:** [Extract from input data]
* **Brief product/service description:** [Extract from input data]
* **Target fan/user demographics:** [Extract from input data]
* **Target artist/user demographics:** [Extract from input data]
* **Summary of Financial Health Implications:** [Copy the assessment generated in Part 1, Section 4 above]
<<< --- END CONTEXT BLOCK FOR STAGE 2 --- >>>

**Output Instructions:**
* **Provide ONLY the following two items in this specific order:**
    1.  **Generated Stage 1 Analysis:** Present the analysis summaries generated in Part 1 under the heading `### Stage 1 Analysis Summary:`, maintaining the bullet point structure for the individual summaries.
    2.  **Context Block:** Provide the complete `CONTEXT FOR STAGE 2` block prepared in Part 2.
* **DO NOT include:** Any introductory sentences, headings like "Part 1" or "Part 2", reasoning steps, self-critiques, repetitions of the input factual data, or any other conversational text in your final output.

**[PROMPT END]**

---
*(Post-Stage Human Task: Review the generated analysis summaries and context block. Manually integrate the verified analysis summaries into your main report file under the appropriate heading. Verify and copy the context block for the next stage.)*