**Prompt:**

Act as an experienced Competitive Intelligence Analyst focused on **finalizing a Competitive Intelligence (CI) report** for presentation to startup founders and potential investors.

Your task is to take a **previously populated draft** of the CI report (which includes inline citations, likely in formats like `[Short Source Name](URL)`, `(Short Source Name)`, or `[source: X]`) and clean it up for final presentation according to the rigorous, step-by-step process outlined below.

**Input:**

Please process the attached file with:

**Rigorous Step-by-Step Finalization Process:**

1.  **Initial Scan & Identify Citations:**
    * Perform an initial read-through of the *entire* input draft report body (Stages 1-4, including all subsections).
    * Create a temporary, comprehensive internal list of the *exact text and format* of **every single inline source citation** found in the body text (e.g., `[Source Name A](URL_A)`, `(Source Name B)`, `[source: 1]`). List duplicates if they appear multiple times; the goal is to capture *all* citation instances first.

2.  **Clean the Report Body (Remove Citations):**
    * Go back to the beginning of the report body.
    * Systematically go through the text. For each piece of text that matches an entry in the temporary list of citations created in Step 1, **completely remove that citation** from the body text.
    * Ensure that only the factual statements, surrounding punctuation, and original formatting (like bolding, lists, headers) remain, creating a clean and readable narrative. Do not alter or rephrase the factual content itself.

3.  **Identify *Unique* Cited Sources:**
    * From the temporary list of **all** citation instances created in Step 1, create a new list containing only the **unique** citations. This is the definitive list of sources that were actually used in the report body.

4.  **Curate the Final Source List:**
    * Go to the "SOURCES" section at the very end of the input draft report.
    * For each source entry listed in this "SOURCES" section, check if it exists in the list of **unique** cited sources created in Step 3.
    * **Construct the FINAL "SOURCES" section for the output report by including ONLY those entries from the input's "SOURCES" list that were successfully matched against the unique cited sources list from Step 3.**
    * **Remove** any source entries from the input's "SOURCES" list that were *not* found in the unique cited sources list from Step 3.
    * Maintain the original Markdown formatting (e.g., `[Descriptive Source Text](URL)` or `(Source Name or Description)`) for the sources that ARE included in the final list.

5.  **Final Output Assembly:**
    * Assemble the final report, ensuring it features:
        * The main report body (Stages 1-4) with **no inline citations**, as processed in Step 2.
        * The curated "SOURCES" section containing **only** the unique sources that were actually cited in the original draft, as curated in Step 4.
        * All other content, structure, and analysis placeholders from the original draft are preserved.

**Output:**

Provide the finalized **CI Report**, processed according to the rigorous, step-by-step finalization process. The output should feature:
* The main report body (Stages 1-4) with **no inline citations**.
* A "SOURCES" section containing **only** the unique sources that were actually cited in the original draft, with unused sources removed, maintaining their original formatting.
