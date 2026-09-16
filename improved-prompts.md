# Improved Prompts Used in Research

These prompts show the evolution toward more specific, structured, and effective queries as the research progressed.

## Improved Prompts with Better Structure

1. **Fraud Detection Focus**
   - Basic: "Tell me about AI in banking fraud detection"
   - Improved: "Act as a financial risk analyst. Analyze three specific AI-based fraud detection systems implemented by Indian banks (HDFC, ICICI, SBI) since 2022. For each system, provide: a) Technology used (ML models, neural networks, etc.), b) Measurable results (reduction in fraud %, cost savings), c) Implementation challenges faced, d) Real transaction volume statistics. Cite sources from bank annual reports, RBI publications, or reputable financial news."
   - Used with: Claude (for analysis) + Perplexity (for source finding)
   - Improvement: Specific banks, timeframe, required elements, and source types specified

2. **Customer Service AI Applications**
   - Basic: "How do banks use AI for customer service?"
   - Improved: "As a banking industry consultant, compare AI-powered customer service solutions (chatbots, voice assistants, recommendation engines) deployed by HDFC Bank's Eva, ICICI Bank's iPal, and SBI's SIA. Include: a) Natural language processing capabilities, b) Transaction types handled, c) Customer satisfaction metrics before/after implementation, d) Integration with core banking systems, e) Limitations and handoff procedures to human agents. Use only 2023-2024 sources."
   - Used with: Claude for comparative analysis, Gemini for exploring nuances
   - Improvement: Specific products named, comparative framework, measurable metrics, time-bound

3. **Credit Risk Assessment**
   - Basic: "AI for credit risk assessment in banks"
   - Improved: "Evaluate the implementation of machine learning models for credit risk assessment in retail lending by major Indian banks. Focus on: a) Alternative data sources used (utility payments, mobile usage, etc.), b) Model performance metrics (AUC scores, default prediction accuracy), c) Regulatory compliance with RBI guidelines, d) Impact on loan approval rates for underserved segments, e) Bias mitigation strategies employed. Reference specific pilot programs or full-scale implementations from 2022-2024."
   - Used with: Perplexity for finding specific programs, Claude for regulatory analysis
   - Improvement: Specific technical and regulatory focus, measurable outcomes

4. **Implementation Challenges**
   - Basic: "Challenges of AI in banking"
   - Improved: "Identify and analyze the top 5 challenges faced by Indian banks when scaling AI from pilot to enterprise-wide implementation, particularly for fraud detection systems. For each challenge, provide: a) Specific examples from bank implementations, b) Strategies used to overcome them, c) Cost implications, d) Timeline for resolution, e) Lessons learned that could benefit other banks. Draw from interviews with bank technology leaders, industry reports, and regulatory discussions."
   - Used with: Claude for synthesis, Perplexity for finding expert opinions
   - Improvement: Actionable framework with examples and solutions

## Prompt Engineering Techniques Applied

1. **Role Specification**: Beginning prompts with "Act as a [expert role]" to get domain-specific perspectives
2. **Structured Output Requirements**: Specifying exact information needed in bullet points or numbered lists
3. **Time Boundaries**: Limiting information to recent implementations (2022-2024)
4. **Source Specification**: Requesting information from particular types of sources (annual reports, RBI docs)
5. **Comparative Framework**: Asking for comparisons between specific entities (banks, products)
6. **Metric Focus**: Demanding quantitative results and measurable outcomes
7. **Constraint Setting**: Specifying geographical or sectoral boundaries (Indian banks only)