# Prompt Templates Repository

## Overview

This repository contains a collection of structured prompts designed for various analytical and research tasks, primarily leveraging Large Language Models (LLMs) and AI tools. The initial focus is on detailed competitive intelligence analysis, along with utility prompts for editing and verifying AI-generated content.

## Current Contents

This repository currently includes the following key components:

1.  **Multi-Stage Competitive Intelligence (CI) Analysis Workflow (`Phase 1-Competitor Analysis Prompts V2.md`)**:
    * A comprehensive set of prompts designed to guide AI through a multi-stage CI process.
    * **Stages:** Covers Business Fundamentals, Product/Feature Analysis, Market Position/Strategy, and SWOT/Recommendations.
    * **Roles:** Defines distinct 'Researcher' (fact-gathering) and 'Analyst' (interpretation, synthesis) roles for the AI at different stages.
    * **Context Handling:** Includes specific instructions for passing verified context between stages.
    * **Verification:** Emphasizes the critical human verification steps required after each AI-driven stage.
    * **Addendum:** Includes a specific prompt for researching artist connections.

2.  **Utility Prompts:**
    * **Factual Research Editing (`Prompt-Edit Factual Research.md`)**: A prompt to guide an AI acting as a CI Analyst to refine draft research findings, focusing on verification, citation, objectivity (removing analysis), and clarity.
    * **Claim Verification (`Prompt-Verification.md`)**: A prompt for an AI fact-checker to verify claims within a document using web search and report findings in a structured table.
    * **Analysis Content Editing (`Prompt-Edit Analysis Content.md`)**: A prompt for an AI acting as a senior CI Analyst to review and refine draft analysis content, ensuring it's logically derived from verified facts, insightful, and maintains an appropriate analytical tone.

## Usage

These prompts are designed to be copied and used with capable AI models.

* **Placeholders:** Remember to replace placeholders like `[Competitor Name]` with specific details.
* **Context:** Pay close attention to the instructions regarding pasting verified context from previous stages, especially in the multi-stage CI workflow.
* **Human Oversight:** The prompts, particularly the CI workflow, explicitly rely on human review, verification, and strategic judgment at multiple points. The utility prompts are designed to assist in this process.
* **Adaptation:** Feel free to adapt these templates for your specific needs and AI models.

## Future Plans

This repository is expected to grow over time with the addition of new prompts for different tasks and domains.
