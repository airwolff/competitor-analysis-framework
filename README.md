# README: Stakeholder Summary Prompt (`Util_05_Extract_Key_Takeaways.md`)

## Purpose

This utility prompt (`Util_05_Extract_Key_Takeaways.md`) serves a specific, crucial function within the larger Competitive Analysis Prompt Suite: **generating a concise executive summary tailored for stakeholders.**

While the main workflow produces a detailed, verifiable report suitable for deep analysis, stakeholders (like founders, investors, board members, or team leads) often require a much shorter, high-impact overview focusing only on the most critical findings and strategic implications.

This prompt takes the final, comprehensive CI report (after all research and analysis stages are complete) and extracts the absolute essential takeaways, presenting them in a standalone summary document.

## Workflow Placement

* **When to Use:** This prompt is designed to be run **once**, at the very **end** of the main CI workflow, after the Stage 4 Analysis has been completed and integrated into the main report document.
* **Input:** It requires the **final, complete CI report file** (containing all facts and integrated analysis summaries from Stages 1-4) as input, typically provided as an attached file.
* **Output:** It produces a **new, separate Markdown document** containing only the extracted key takeaways, formatted as an executive summary.

## Key Benefits for Stakeholders

* **Brevity:** Delivers the most important information without requiring stakeholders to read the lengthy detailed report.
* **Focus:** Highlights critical strengths, weaknesses, opportunities, threats, and strategic conclusions.
* **Efficiency:** Saves valuable stakeholder time while ensuring they grasp the core competitive insights.
* **Consistency:** Extracts conclusions directly from the final, verified analysis, ensuring alignment with the detailed report.

## Usage

1.  Complete the full competitive analysis workflow (Stages 1-4, including iterative use of `Util_01` and `Util_02`, and manual integration of analysis summaries).
2.  Ensure you have the final, complete CI report document saved.
3.  Open the `Util_05_Extract_Key_Takeaways.md` prompt file.
4.  Copy the prompt text into your AI assistant.
5.  **Attach the final CI report document** as input when prompted.
6.  Run the prompt.
7.  Review the generated "Executive Summary: [Competitor Name] Key Takeaways" document for accuracy and impact before sharing with stakeholders.

This prompt acts as the final step in translating the detailed analytical work into a format suitable for high-level strategic discussion and decision-making.
