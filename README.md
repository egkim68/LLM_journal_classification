# LLM Journal Classification for LIS

This project classifies 273 Library and Information Science journals into 85 Scopus ASJC categories using four LLMs (Claude 3 Haiku, GPT-4o Mini, Gemini 2.0 Flash Lite, DeepSeek Chat).

## How to Use
1. Collect journal titles and scope statements from [Scimago](https://www.scimagojr.com/) and save as `data/lis_journals_info.csv` (columns: `Title`, `Scope`).
2. Install python dependencies
3. Run a script, e.g.:
   python classify_claude.py
4. Outputs are saved in `data/`.
