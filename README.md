# AI Financial Market Intelligence Automation

An end-to-end **AI-powered financial market intelligence system built with n8n**.

The workflow automatically collects financial news from multiple sources, removes duplicate stories, analyzes market relevance using AI, performs additional web and social intelligence research, generates professional financial insights and stores structured results in Google Sheets.

## What the Workflow Does

Financial News Sources
↓
RSS Aggregation
↓
Merge & Deduplication
↓
AI Market Analysis
↓
Importance Scoring
↓
Web Research
↓
LinkedIn & X Intelligence
↓
Financial Research Analysis
↓
Professional Market Briefing
↓
LinkedIn Content Generation
↓
X Content Generation
↓
Google Sheets Database

## Key Features

- Multi-source financial news aggregation
- Automatic duplicate removal
- AI-based news classification
- 0–100 importance scoring
- Bullish / Bearish / Neutral / Unclear market-impact classification
- Automated web research
- LinkedIn and X industry-intelligence collection
- Fact and narrative analysis
- Investor relevance analysis
- Professional financial briefing generation
- LinkedIn post generation
- X post generation
- Structured Google Sheets output
- Batch processing to manage API usage

## AI Analysis

Each financial article is processed into structured intelligence including:

- Category
- Importance score
- Market impact
- Key points
- Professional summary
- Investor relevance
- Content potential
- Content angle

Higher-priority stories can then move through deeper research and intelligence processing.

## Research Layer

The workflow combines the original financial story with additional web research and available social/industry intelligence.

The research layer is designed to identify:

- Confirmed facts
- Additional context
- Conflicting information
- Market significance
- Affected entities
- Investor implications
- Industry sentiment
- Dominant narratives
- Consensus and contrarian viewpoints
- Emerging trends

## Automated Content Generation

Research output is transformed into:

**Professional Financial Briefing**

A structured market-intelligence report designed for finance professionals.

**LinkedIn Content**

Professional finance-focused posts built from the research output.

**X Content**

Concise market insights designed to stay within the platform's character limit.

## Technology

- n8n
- AI / LLM Agents
- OpenRouter
- Tavily
- JavaScript
- RSS
- HTTP APIs
- Google Sheets
- JSON processing

## Reliability & Error Handling

During development, the workflow was tested and debugged against issues including:

- API rate limits
- LLM quota limitations
- Invalid/malformed JSON
- Duplicate articles
- Data filtering problems
- Workflow routing issues
- Partial executions
- External API failures

## Potential Business Applications

The architecture can be adapted for:

- Investment research
- Market intelligence
- Competitor intelligence
- Industry monitoring
- News monitoring
- Research automation
- AI content research
- Executive intelligence
- Lead intelligence

## Workflow Preview

Workflow screenshots and output examples will be added to this repository.

## 🔐 Security

The public workflow version does not contain production API keys, authentication tokens or private credentials.

## 📌 Project Status

**Working prototype — successfully tested end-to-end with structured Google Sheets output.**
