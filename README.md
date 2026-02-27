# x-post-summarizer-2026

This repository summarizes a public figure's 2026 X posts using AI.

## Analyzed Account
- Handle: @llm_wizard

## Project Overview
This project was built using a LangGraph agent with GitHub MCP tools for repository operations and the X API v2 for retrieving posts.

## Replication Instructions
To replicate this process:

1. Set up your X API Bearer Token as an environment variable:

```bash
export X_BEARER_TOKEN='your_bearer_token_here'
```

2. Install the required Python dependencies:

```bash
pip install requests
```

3. Run the search script to fetch recent posts:

```bash
python x_search.py <X_handle>
```
Replace `<X_handle>` with the desired account handle.

4. Review the generated `posts.json` file and use the summary and metadata files as references.

---

This setup allows you to analyze and summarize X posts programmatically using AI and automation tools.
