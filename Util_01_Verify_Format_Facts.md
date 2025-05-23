**[PROMPT START]**

Act as an experienced Competitive Intelligence Analyst focused *solely on extracting, verifying, refining, and structuring objective factual research data* for the initial, fact-based layer of a CI report. **This output is intended for internal factual review and verification purposes, hence the detailed inline citations are required.**

Your task is to take the provided raw research findings, rigorously process them according to the instructions below, and then populate the provided CI Report Template with the refined, objective factual information, ensuring correct formatting and explicit citation for every fact included.

**Input:**

Please process the attached file:

**Editing & Structuring Instructions:**

**Before populating any field in the template, perform the following step-by-step verification and extraction process for EACH potential piece of factual information identified in the input related to that field:**

1.  **Identify Factual Claim:** Pinpoint a specific statement in the input research that appears to be a factual claim relevant to the current template field.
2.  **Locate Source:** Look immediately around that factual claim in the input text for its corresponding source citation (e.g., `[source: 5]`, `(Requires Source URL)`, or similar indicator linked to a source list).
3.  **Verify Source & URL:** Find that source entry in the input research's 'Source List' or equivalent section. Check if it includes a verifiable URL.
4.  **Validate Objectivity:** Confirm the statement is purely objective fact, free from analysis or opinion.
5.  **Extract & Format:** If steps 1-4 are successful (claim found, cited, source verified with URL, objective), extract the precise factual statement and proceed to format it for the template field.
6.  **Cite Correctly (INLINE CLICKABLE LINK REQUIRED):** Immediately after the extracted factual statement, **insert the citation formatted as a clickable Markdown link `[Short Source Name](URL)` using a concise name and the verified URL from the input's source list.** If a URL is *not* available for a verified source, use plain text `(Short Source Name)`. **This inline, clickable format is essential for verification.**
7.  **Handle Unverifiable Claims:** If ANY of steps 2, 3, or 4 fail (no citation, source missing, no URL, subjective language), DO NOT include that factual claim in the output template.
8.  **Handle Information Gaps:** If the template requires information that was explicitly sought but stated as "`[Information Not Found]`" in the input research, state this gap neutrally (e.g., "`[Information Not Found]`") in the relevant field.

**(Continue with original detailed instructions, which now refine the steps above):**

* **Verification & Precision:** Ensure every factual statement placed into the template... is precise and directly supported by a verifiable source citation found within the input research... Scrutinize claims for accuracy...
* **Citation:** Verify that every factual claim included... has an associated citation... When populating the template, replace the `(Source Reference)` placeholder... **format citations as clickable Markdown links `[Short Source Name](URL)` inline after the fact.** If a specific URL cannot be found... format the citation as plain text `(Short Source Name)` inline... Do not include any factual statement... if it lacks a verifiable source or citation... **The primary output format for citations in the template body MUST be the inline clickable Markdown link or plain text citation.**
* **Handling Information Gaps:** If the input research indicates... explicitly state this gap (`[Information Not Found]`) in the relevant template field... Do not leave fields blank...
* **Strict Objectivity (No Analysis):** Ensure the output... contains *only* objective, verifiable facts... Remove ALL analysis, interpretation, opinions, or subjective/evaluative language...
* **Clarity & Conciseness:** Ensure the factual language... is clear, concise, and professional...
* **Structure & Formatting (Apply to Template Population):**
    * Map the refined factual information from the input research to the corresponding sections and fields within the CI Report Template below.
    * Adhere to the inherent structure of the template.
    * Apply section-specific formatting guidance when populating the template.
    * **Populating Bulleted Placeholders:** For template fields that now use nested bullet points under a main point (e.g., 'Founders and/or CEO background:', 'Major investors:', 'Notable Artists:', 'User complaints:', 'Key marketing campaigns:', 'SWOT Strengths/Weaknesses/Opportunities/Threats', etc.), extract each distinct factual point related to that field from the raw research and populate it as a separate bullet point under the main heading in the template, ensuring each bullet point has its own citation immediately following it.
    * Leave the "Analysis Summary," "Strategic Implications," "Strategic Recommendations," and the *analysis within* "SWOT Analysis" sections blank or with their original placeholder text.

**Output:**

Provide the completed **CI Report Template** below, populated *only* with the refined, objective, and properly cited factual information extracted and processed from the input research according to all instructions, including the step-by-step verification process. Ensure no analysis or opinion remains in the populated fields, and all `(Source Reference)` placeholders are replaced with actual citations (`[Short Source Name](URL)` or `(Short Source Name)` as determined by source availability) **placed immediately after the corresponding factual statement.**

---

## CI Report Template

***Note:** This template is populated with verified factual data for internal review. Full analysis and strategic recommendations will be added in a subsequent step.*

## **Competitor Name:** [Specify Name - Extract from Input if possible, otherwise leave placeholder]

## Stage 1: Competitor Profile & Business Fundamentals

### Company Overview:

* **Founding date and headquarters:** [Detail] (Source Reference)
* **Core mission or tagline:** [Detail] (Source Reference)
* **Brief product/service description:** [Detail, noting features for established artists if mentioned] (Source Reference)

### Financial and Investment Details:

* **Funding Rounds:**
    * Current funding rounds (seed, Series A, etc.):
        * [List each round] (Source Reference)
* **Major investors (VC firms, angel investors):**
    * [List investors] (Source Reference)
* **Total funding to date:** [Amount or 'Total funding not publicly available'] (Source Reference)
* **Revenue estimates:** [Amount/Range or 'Revenue estimates not publicly available'] (Source Reference)

### Team Composition and Leadership:

* **Founders and/or CEO background:**
    * [Key point 1, including music industry experience/ventures] (Source Reference)
    * [Key point 2] (Source Reference)
    * ...
* **Key Functional Leadership (Product, Eng, Marketing, Sales, etc.):**
    * [Leader Name, Role, relevant industry/domain experience] (Source Reference)
    * [Leader Name, Role, relevant industry/domain experience] (Source Reference)
    * ...
* **Music Industry Credibility & Connections:**
    * [Specific connection/role/achievement 1 for founders/key team] (Source Reference)
    * [Specific connection/role/achievement 2] (Source Reference)
    * ...
* **Key executives or marquee names:**
    * [List C-suite/recognized execs] (Source Reference)
    * ...
* **Approximate team size:** [Number or 'Approximate team size unknown'] (Source Reference)

### Fan/Artist Base & Platform Use:

* **Target fan/user demographics:** [Describe primary target users/fans] (Source Reference)
* **Target artist/user demographics:** [Describe primary target users/artists, noting emerging vs. established focus] (Source Reference)
* **Notable Artists on Platform / Partnerships:**
    * [Specific example 1: Artist Name, how they use platform] (Source Reference)
    * [Specific example 2: Artist Name, how they use platform] (Source Reference)
    * ...
* **Approximate user count or site traffic:** [Estimates or 'User count/site traffic data not publicly available'] (Source Reference)

### Key Business Metrics:

* **Engagement rates (e.g., monthly active users):** [Rates or 'Engagement rate data not publicly available'] (Source Reference)
* **Revenue sources and breakdown:** [Description or 'Revenue source/breakdown information not publicly available'] (Source Reference)
* **Social media presence and following:**
    * [Platform: Follower count, note artist interactions] (Source Reference)
    * [Platform: Follower count, note artist interactions] (Source Reference)
    * ...

### Information Gaps:

* [List points where information/URL was confirmed as not found]

### **Stage 1 Analysis Summary:** (Placeholder for post-verification analysis)

* Founders and/or CEO Background Summary
* Key Functional Leadership Background Summary
* Social Media Presence Summary
* Financial Health Implications

## Stage 2: Product & Feature Analysis

### Features for Fans:

* **Music purchasing and consumption options:** [Description] (Source Reference)
* **Merchandise purchasing capabilities:** [Description] (Source Reference)
* **Event ticket purchasing system:** [Details] (Source Reference)
* **Subscription options for exclusive content:** [Explanation] (Source Reference)
* Direct artist interaction mechanisms: [Description] (Source Reference)
* Community features and forums: [Details] (Source Reference)
* Mobile app functionality: [Summary] (Source Reference)
* User interface and experience aspects: [Key aspects mentioned] (Source Reference)
* **User complaints or requested improvements (Top 3-5, last 12 mos):**
    * [Complaint 1] (Source Reference)
    * [Complaint 2] (Source Reference)
    * ...

### Features for Artists:

* Content uploading and management tools: [Description] (Source Reference)
* Pricing control and flexibility: [Explanation] (Source Reference)
* Merchandise creation and management: [Details] (Source Reference)
* Fan engagement and communication tools: [Description] (Source Reference)
* Analytics dashboards and reporting: [Details] (Source Reference)
* Subscription tier management: [Explanation] (Source Reference)
* Event organization capabilities: [Description] (Source Reference)
* Payment processing and payout systems: [Details] (Source Reference)
* Rights management features: [Description] (Source Reference)
* **Artist complaints or requested improvements (Top 3-5, last 12 mos):**
    * [Complaint 1] (Source Reference)
    * [Complaint 2] (Source Reference)
    * ...
* **Features highlighted in testimonials/case studies:**
    * [Feature 1] (Source Reference)
    * [Feature 2] (Source Reference)
    * ...

### Technology Infrastructure:

* Platform architecture (if known): [Description] (Source Reference)
* **Technology aspects highlighted as Differentiators/Limitations:**
    * [Aspect 1] (Source Reference)
    * [Aspect 2] (Source Reference)
    * ...
* Mobile capabilities and app ratings: [Availability and ratings] (Source Reference)
* **API offerings and third-party integrations:**
    * [Integration 1] (Source Reference)
    * [Integration 2] (Source Reference)
    * ...
* Performance and reliability factors: [Report known factors] (Source Reference)

### Pricing Model:

* Detailed breakdown of pricing tiers: [Breakdown for artists/creators] (Source Reference)
* Commission structures for artists: [Explanation] (Source Reference)

### User/Fan Onboarding:

* Onboarding process overview: [Steps for new user/fan] (Source Reference)

### Artist Onboarding:

* Onboarding process overview: [Steps for new artist] (Source Reference)

### User/Fan Support & Documentation:

* Available support channels: [List options] (Source Reference)
* User support feedback: [Specific feedback points, if available] (Source Reference)

### Artist Support & Documentation:

* Available support channels: [List options for artists] (Source Reference)
* Artist support feedback: [Specific feedback points, if available] (Source Reference)

### Innovative/Differentiating Features:

* **Features described as Innovative/Differentiating:**
    * [Feature 1] (Source Reference)
    * [Feature 2] (Source Reference)
    * ...

### Information Gaps: \

* [List points where information/URL was confirmed as not found]

### **Stage 2 Analysis Summary:** (Placeholder for post-verification analysis) \

* User Interface/Experience Assessment
* Analysis of User/Artist Complaints
* Analysis of Value Drivers
* Technology Competitiveness Assessment
* Pricing Model Competitiveness Assessment
* Onboarding Ease Assessment (User/Fan & Artist)
* Support Quality Assessment (User/Fan & Artist)
* Innovation/ Differentiation Assessment
* Overall Product Coherence & Competitiveness

## Stage 3: Market Position & Competitive Strategy

### Market Positioning:

* **Stated market differentiators:**
    * [Differentiator 1] (Source Reference)
    * [Differentiator 2] (Source Reference)
    * ...
* **Stated Positioning vs. Key Rivals:** [How they differentiate from specific competitors] (Source Reference)
* **Primary value propositions:**
    * [To users] (Source Reference)
    * [To creators] (Source Reference)
* Brand identity and public perception findings: [Stated identity vs. public view] (Source Reference)
* Target market segments: [Define primary segments] (Source Reference)

### Adoption & User Base:

* *(Note: Detailed artist info moved to Stage 1)*
* **Notable Labels/Industry Partners:**
    * [Partner 1, reason for use] (Source Reference)
    * [Partner 2, reason for use] (Source Reference)
    * ...
* Overall Artist/Label Profile Data: [Data/summaries indicating typical user profile] (Source Reference)
* Case Studies & Testimonials: [Summarize or link to official examples] (Source Reference)

### Competitive Landscape:

* **Direct and indirect competitors:**
    * [Competitor 1] (Source Reference)
    * [Competitor 2] (Source Reference)
    * ...
* Relative market share: [Estimates or 'Market share data not publicly available'] (Source Reference)

### Marketing and Growth Strategy:

* **Key marketing campaigns or initiatives:**
    * [Campaign 1] (Source Reference)
    * [Campaign 2] (Source Reference)
    * ...
* **Core Marketing Messaging & Angles:**
    * [Message/Angle 1] (Source Reference)
    * [Message/Angle 2] (Source Reference)
    * ...
* **Strategic partnerships and alliances:**
    * [Partnership 1] (Source Reference)
    * [Partnership 2] (Source Reference)
    * ...
* **Recent product expansions or pivots:**
    * [Change 1] (Source Reference)
    * [Change 2] (Source Reference)
    * ...
* International expansion efforts: [Describe efforts and target regions] (Source Reference)
* Growth trajectory relative to the industry: [Report findings compared to industry] (Source Reference)

### Regulatory Approach:

* Compliance with music licensing requirements: [Report stated approach] (Source Reference)
* Copyright protection mechanisms: [Describe mechanisms employed] (Source Reference)
* Regional adaptations to local regulations: [Detail known adaptations] (Source Reference)

### Future Outlook:

* **Announced roadmap items:**
    * [Item 1] (Source Reference)
    * [Item 2] (Source Reference)
    * ...
* **Data related to potential pivots or expansions:**
    * [Finding 1 from hiring, M&A, stated directions] (Source Reference)
    * [Finding 2] (Source Reference)
    * ...
* **Data about potential vulnerabilities:**
    * [Finding 1 indicating risks from all stages] (Source Reference)
    * [Finding 2] (Source Reference)
    * ...

### Information Gaps:

* [List points where information/URL was confirmed as not found]

### **Stage 3 Analysis Summary:** (Placeholder for post-verification analysis) \

* Market Positioning Analysis (Brand, User Base Profile)
* Competitive Landscape Analysis (Strengths/Weaknesses Synthesis)
* Marketing and Growth Strategy Analysis (Messaging, Trajectory)
* Regulatory Approach Analysis
* Future Outlook Analysis (Potential Pivots, Scenarios, Vulnerabilities)
* Overall Strategic Assessment

## Stage 4: SWOT Analysis & Strategic Recommendations

### **SWOT Analysis:** (Derived strictly from verified context)

* **Strengths:**
    * [List internal advantages] (Source Reference)
    * ...
* **Weaknesses:**
    * [List internal limitations] (Source Reference)
    * ...
* **Opportunities:**
    * [List external factors - market trends, competitor weaknesses] (Source Reference)
    * ...
* **Threats:**
    * [List external factors - market trends, competitor strengths, regulations] (Source Reference)
    * ...

### **Strategic Implications:** (Placeholder for post-verification analysis)

* Analyze how strengths translate to advantages
* Analyze how weaknesses create vulnerabilities
* Analyze opportunities they might capture
* Analyze threats posing the greatest risk

### **Strategic Recommendations:** (Placeholder for post-verification analysis)

* Differentiating strategies for our company (based on competitor Weaknesses)
* Leveraging Opportunities against the competitor
* Defensive measures against competitor Strengths
* Likely competitive responses from [Competitor Name]
* Potential 'White Space' Opportunities
* Monitoring priorities moving forward

### Information Gaps:

* [List points where lack of information impacts SWOT/Recommendations]

**SOURCES:**
* [Source Name](Full URL if available)
* ... (List all unique sources cited inline, derived from the input research's source list)

**[PROMPT END]**
