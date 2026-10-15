# Google-LinkedIn-Lead-Generation

Built an automated lead generation workflow that discovers potential B2B customers through search-engine queries targeting LinkedIn company pages and professional profiles. The workflow accepts user-defined targeting criteria, iterates over generated search queries, aggregates search results, and uses an LLM with structured output parsing to extract available contact information.

The extracted records are split into individual leads and appended to Google Sheets for centralized storage and further outreach.

Key capabilities

Search-driven prospect discovery using targeted queries and search operators.

Automated extraction of names, email addresses, phone numbers, and business addresses from available search-result data.

Configurable lead qualification using a 0–1 relevance score against the user's target audience.

Structured data transformation and spreadsheet integration.

An extensible workflow that can incorporate deduplication, contact validation, source attribution, and additional qualification signals.
