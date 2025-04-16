**Prompt:**

Act as an experienced Competitive Intelligence Analyst focused *solely on verifying, refining, and structuring factual research data* for a CI report intended for startup founders and potential investors.

Your task is to take the provided raw research findings, rigorously edit them for factual accuracy and objectivity according to the instructions below, and then populate the provided CI Report Template with the refined information, ensuring correct formatting and citation.

**Input:**

Please process the attached file: `[Filename of the attached research document]`

**Editing & Structuring Instructions:**

1.  **Verification & Precision:**
    * Ensure every factual statement placed into the template (e.g., founding date, funding amount, feature description, market share estimate, key personnel, pricing details, target audience description) is precise and directly supported by a verifiable source citation found within the input research.
    * Scrutinize claims for accuracy based on common knowledge and the provided context within the input research.

2.  **Citation:**
    * Verify that every factual claim included in the final output has an associated citation from the input research.
    * When populating the template, replace the `(Source Reference)` placeholder after each factual detail with the corresponding citation.
    * Format citations as clickable Markdown links `[Source Name](URL)` whenever a verifiable URL is available in the input's source list.
    * If a specific URL cannot be found for a cited source in the input, format the citation as plain text `(Source Name)`.
    * **Crucially: Do not include any factual statement in the output template if it lacks a verifiable source or citation in the input research.**

3.  **Handling Information Gaps:**
    * If the input research indicates that specific information required by the template structure was sought but not found, explicitly state this gap in the relevant template field using neutral language (e.g., "Specific team size not disclosed in verifiable sources," "Technology stack details unverified," "Market share data not publicly available"). Do not leave fields blank if the information was sought but unavailable; state the gap.

4.  **Strict Objectivity (No Analysis):**
    * Ensure the output populated into the template contains *only* objective, verifiable facts as reported by sources in the input.
    * **Remove ALL analysis, interpretation, opinions, or subjective/evaluative language** found in the input research (e.g., remove words like 'good', 'poor', 'impressive', 'limited', 'strong', 'weak', 'significant', 'crucial', 'valuable', 'essential' unless directly quoting a cited source from the input). The goal is pure factual reporting within the template structure.

5.  **Clarity & Conciseness:**
    * Ensure the factual language used in the template is clear, concise, and professional. Avoid jargon where possible unless it's standard industry terminology defined by the sources.

6.  **Structure & Formatting (Apply to Template Population):**
    * Map the refined factual information from the input research to the corresponding sections and fields within the CI Report Template below.
    * Adhere to the inherent structure of the template.
    * Apply section-specific formatting guidance when populating the template:
        * **Company Overview Facts:** Keep factual and concise. The 'Brief product/service description' should be a factual, descriptive paragraph.
        * **Financial and Investment Details:** Format primarily as factual lists or figures (use bullet points). Use standard phrases for unavailable data.
        * **Team Composition Facts:** Use factual lists for names, roles, and key experience points (use bullet points).
        * **Products/Services Facts:** Use descriptive paragraphs for core offerings/tech summaries. Use bullet points for listing specific, distinct features, capabilities, or *reported* user/artist complaints (verbatim if possible, or summarized factually based on input sources).
        * **Target Audience Facts:** Use clear descriptive paragraphs based on source findings.
        * **Pricing & Business Model Facts:** Use clear descriptions. Use bullet points or tables for detailing pricing tiers or commission structures if the input provides structured data.
        * **Market Positioning & Messaging Facts:** Use descriptive paragraphs for reported positioning/messaging. Use bullet points for listing specific differentiators or value propositions *as stated by the competitor or sources in the input*.
        * **Marketing and Growth Strategy Facts:** Use descriptive paragraphs for reported strategy. Use bullet points for listing key channels, specific campaigns, or partnerships *as reported in the input*.
        * **Analysis Summaries & SWOT:** Leave the "Analysis Summary," "Strategic Implications," "Strategic Recommendations," and "SWOT Analysis" sections blank or with their original placeholder text. Your task is *only* to populate the factual sections (Stages 1-3 data points, factual SWOT points if explicitly stated as such *with sources* in the input).

**Output:**

Provide the completed **CI Report Template** below, populated *only* with the refined, objective, and properly cited factual information extracted and processed from the input research according to all instructions. Ensure no analysis or opinion remains in the populated fields, and all `(Source Reference)` placeholders are replaced with actual citations (`[Source Name](URL)` or `(Source Name)`).

---

## CI Report Template

***Note:** Throughout this template, `(Source Reference)` serves as a placeholder instruction. It indicates where you should insert the actual citation or link (e.g., using `[Name](URL)` format) for the information provided immediately before it. It is not meant to be a clickable link itself in the final document.*

## **Competitor Name:** [Specify Name]

## Stage 1: Competitor Profile & Business Fundamentals

### Company Overview:

* **Founding date and headquarters:** [Detail] (Source Reference)
* **Core mission or tagline:** [Detail] (Source Reference)
* **Brief product/service description:** [Detail, noting features for established artists if mentioned] (Source Reference)

### Financial and Investment Details:

* **Funding Rounds:**
    * Current funding rounds (seed, Series A, etc.): [List] (Source Reference)
* **Major investors (VC firms, angel investors):** [List] (Source Reference)
* **Total funding to date:** [Amount or 'Total funding not publicly available'] (Source Reference)
* **Revenue estimates:** [Amount/Range or 'Revenue estimates not publicly available'] (Source Reference)

### Team Composition and Leadership:

* **Founders and/or CEO background:** [Key points, including music industry experience/ventures] (Source Reference)
* **Key Functional Leadership (Product, Eng, Marketing, Sales, etc.):** [Leaders and relevant industry/domain experience] (Source Reference)
* **Music Industry Credibility & Connections:** [Specific connections, roles, achievements for founders/key team] (Source Reference)
* **Key executives or marquee names:** [List C-suite/recognized execs] (Source Reference)
* **Approximate team size:** [Number or 'Approximate team size unknown'] (Source Reference)

### Fan/Artist Base & Platform Use:

* **Target fan/user demographics:** [Describe primary target users/fans] (Source Reference)
* **Target artist/user demographics:** [Describe primary target users/artists, noting emerging vs. established focus] (Source Reference)
* **Notable Artists on Platform / Partnerships:** [List specific examples of well-known/established artists, how they use the platform (sales, exclusives, promo, etc.)] (Source Reference)
* **Approximate user count or site traffic:** [Estimates or 'User count/site traffic data not publicly available'] (Source Reference)

### Key Business Metrics:

* **Engagement rates (e.g., monthly active users):** [Rates or 'Engagement rate data not publicly available'] (Source Reference)
* **Revenue sources and breakdown:** [Description or 'Revenue source/breakdown information not publicly available'] (Source Reference)
* **Social media presence and following:** [Platforms and follower counts, note artist interactions] (Source Reference)

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
* User complaints or requested improvements (Top 3-5, last 12 mos): [List] (Source Reference)

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
* Artist complaints or requested improvements (Top 3-5, last 12 mos): [List] (Source Reference)
* Features highlighted in testimonials/case studies: [List] (Source Reference)

### Technology Infrastructure:

* Platform architecture (if known): [Description] (Source Reference)
* Technology aspects highlighted as Differentiators/Limitations: [List] (Source Reference)
* Mobile capabilities and app ratings: [Availability and ratings] (Source Reference)
* API offerings and third-party integrations: [List] (Source Reference)
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

* Features described as Innovative/Differentiating: [List features] (Source Reference)

### Information Gaps: \\

* [List points where information/URL was confirmed as not found]

### **Stage 2 Analysis Summary:** (Placeholder for post-verification analysis) \\

* User Interface/Experience Assessment
* Analysis of User/Artist Complaints
* Analysis of Value Drivers
* Technology Competitiveness Assessment
* Pricing Model Competitiveness Assessment
* Onboarding Ease Assessment (User/Fan & Artist)
* Support Quality Assessment (User/Fan & Artist)
* Innovation/Differentiation Assessment
* Overall Product Coherence & Competitiveness

## Stage 3: Market Position & Competitive Strategy

### Market Positioning:

* Stated market differentiators: [Identify company's stated differentiators] (Source Reference)
* Stated Positioning vs. Key Rivals: [How they differentiate from specific competitors] (Source Reference)
* Primary value propositions: [To users and creators] (Source Reference)
* Brand identity and public perception findings: [Stated identity vs. public view] (Source Reference)
* Target market segments: [Define primary segments] (Source Reference)

### Adoption & User Base:

* *(Note: Detailed artist info moved to Stage 1)*
* Notable Labels/Industry Partners: [List labels, publishers, distributors, etc. with reasons for use] (Source Reference)
* Overall Artist/Label Profile Data: [Data/summaries indicating typical user profile] (Source Reference)
* Case Studies & Testimonials: [Summarize or link to official examples] (Source Reference)

### Competitive Landscape:

* Direct and indirect competitors: [List main competitors] (Source Reference)
* Relative market share: [Estimates or 'Market share data not publicly available'] (Source Reference)

### Marketing and Growth Strategy:

* Key marketing campaigns or initiatives: [Describe recent campaigns] (Source Reference)
* Core Marketing Messaging & Angles: [List primary messages, themes, pain points/benefits mentioned] (Source Reference)
* Strategic partnerships and alliances: [List significant formal deals] (Source Reference)
* Recent product expansions or pivots: [Detail significant changes] (Source Reference)
* International expansion efforts: [Describe efforts and target regions] (Source Reference)
* Growth trajectory relative to the industry: [Report findings compared to industry] (Source Reference)

### Regulatory Approach:

* Compliance with music licensing requirements: [Report stated approach] (Source Reference)
* Copyright protection mechanisms: [Describe mechanisms employed] (Source Reference)
* Regional adaptations to local regulations: [Detail known adaptations] (Source Reference)

### Future Outlook:

* Announced roadmap items: [List publicly announced plans] (Source Reference)
* Data related to potential pivots or expansions: [Findings on hiring, M&A, stated directions] (Source Reference)
* Data about potential vulnerabilities: [Findings from all stages indicating risks] (Source Reference)

### Information Gaps:

* [List points where information/URL was confirmed as not found]

### **Stage 3 Analysis Summary:** (Placeholder for post-verification analysis) \\

* Market Positioning Analysis (Brand, User Base Profile)
* Competitive Landscape Analysis (Strengths/Weaknesses Synthesis)
* Marketing and Growth Strategy Analysis (Messaging, Trajectory)
* Regulatory Approach Analysis
* Future Outlook Analysis (Potential Pivots, Scenarios, Vulnerabilities)
* Overall Strategic Assessment

## Stage 4: SWOT Analysis & Strategic Recommendations

### **SWOT Analysis:** (Derived strictly from verified context)

* Strengths: [List internal advantages] (Source Reference)
* Weaknesses: [List internal limitations] (Source Reference)
* Opportunities: [List external factors - market trends, competitor weaknesses] (Source Reference)
* Threats: [List external factors - market trends, competitor strengths, regulations] (Source Reference)

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

---