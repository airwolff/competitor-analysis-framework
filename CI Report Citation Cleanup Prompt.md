**Prompt:**

Act as an experienced Competitive Intelligence Analyst focused on **finalizing a Competitive Intelligence (CI) report** for presentation to startup founders and potential investors.

Your task is to take a **previously populated draft** of the CI report (which includes inline citations) and clean it up for final presentation according to the instructions below.

**Input:**

Please process the attached file: `[Filename of the populated DRAFT CI Report]`

**Finalization Instructions:**

1.  **Remove Inline Citations:**
    * Go through the entire body of the report (Stages 1-4, including all subsections).
    * Identify and **completely remove** all inline source citations. These citations will typically be in formats like `[Descriptive Source Text](URL)` or `(Source Name or Description)`.
    * Ensure that only the factual statements remain in the body text, creating a clean and readable narrative.

2.  **Curate the Final Source List:**
    * **Identify Used Sources:** Before removing them (or concurrently), scan the entire input draft to identify every *unique* source that was actually cited inline.
    * **Clean the "SOURCES" Section:** Go to the "SOURCES" section at the end of the report.
    * Ensure this section contains **only** the unique sources that were identified as being cited inline in the draft report body.
    * **Remove Unused Sources:** Delete any source entries from the "SOURCES" list that were *not* actually cited anywhere in the body of the input draft.
    * **Maintain Formatting:** Preserve the original formatting for the sources listed (e.g., `[Descriptive Source Text](URL)` or `(Source Name or Description)`).

3.  **Preserve Content:**
    * Do not alter the factual content, analysis placeholders, or structure of the report itself, other than removing the inline citations as specified.

**Output:**

Provide the finalized **CI Report**, processed according to all instructions. The output should feature:
* The main report body (Stages 1-4) with **no inline citations**.
* A "SOURCES" section containing **only** the sources that were actually cited in the original draft, with unused sources removed.

---
*(The CI Report Template structure itself is omitted here, as the input is assumed to be an already populated version of that template)*
---