**[PROMPT START]**

**Role:** Act as a **Senior Competitive Intelligence Analyst** tasked with creating a concise executive summary by extracting the most critical insights from a completed, detailed CI report.

**Objective:** Review the provided comprehensive CI report (containing both facts and integrated analysis) and distill the absolute essential findings, conclusions, and strategic implications into a brief, high-level summary document suitable for stakeholders needing a quick overview.

**Input:**

<<< --- PASTE THE FINAL, COMPLETE CI REPORT HERE --- >>>
*(This should be the report after all stages (1-4) of facts and analysis summaries have been integrated, likely the output from Util_02 run after Stage 4 analysis)*

**Extraction Task:**

Read through the **entire Input Report**, paying close attention to the **Analysis Summary** sections for Stages 1, 2, and 3, as well as the **SWOT Analysis** and **Strategic Implications** sections in Stage 4. Perform the following extraction:

1.  **Identify Core Conclusions:** For *each* major analysis point within the report (e.g., Financial Health Implications, Overall Product Coherence, Market Positioning Analysis, SWOT points, Strategic Implications), identify and extract the **single most important takeaway, conclusion, or assessment** presented. Rephrase slightly for conciseness if necessary, but prioritize extracting the core message accurately.
2.  **Synthesize Key Strengths & Weaknesses:** From the SWOT analysis and earlier synthesis points, identify the top 2-3 most impactful **Strengths** and top 2-3 most critical **Weaknesses**.
3.  **Synthesize Key Opportunities & Threats:** From the SWOT analysis and future outlook sections, identify the top 2-3 most significant external **Opportunities** and top 2-3 most pressing **Threats**.
4.  **Identify Overarching Strategic Picture:** Based on the overall analysis (especially Stage 3 & 4), extract a 1-2 sentence summary of the competitor's apparent core strategy or market position.

**Output Format:**

* Create a **new, concise Markdown document** titled: `Executive Summary: [Competitor Name] Key Takeaways` (extract the competitor name from the input report).
* Organize the extracted points logically under clear headings (e.g., `Key Financial Takeaways`, `Product & Technology Highlights`, `Market Position & Strategy`, `Core Strengths`, `Critical Weaknesses`, `Major Opportunities`, `Significant Threats`, `Overall Strategic Assessment`).
* Use bullet points for lists of takeaways, strengths, weaknesses, etc.
* **Focus entirely on brevity and impact.** Each point should represent a critical insight.
* **Do NOT** include detailed factual data (use conclusions drawn from the data), introductory/conversational text, or sections from the original report not containing key analysis conclusions. The goal is a high-level summary, not a slightly shorter version of the full report.

**[PROMPT END]**
