## FinAgent - Agentic Finance Demo

A lightweight, multi-agent system that combines real-time web search with live stock data to answer finance queries.

## 🚀 Features

- **Web Search Agent**  
  Fetches headlines, snippets, and source links via DuckDuckGo.  
- **Finance Agent**  
  Retrieves stock prices, historical data, and analyst recommendations using `yfinance`.  
- **Team Lead Agent**  
  Coordinates both agents to answer higher-level queries, merges outputs, and streams them as Markdown.

## 🔍 How It Works
**WebSearch Agent** 

Uses DuckDuckGo’s HTML interface to scrape top 3 results.

**Finance Agent** 

Wraps yfinance.Ticker to fetch .info, .history(), and .recommendations.

**TeamLeadAgent** 

Prompts LLM to call search() and quote() tools, stitches responses, and streams in markdown.

## ⚙️ Prerequisites

- Python 3.10+  
- DuckDuckGo (no key required)  
- Yahoo Finance (no key required)
## DEMO 
![image](https://github.com/user-attachments/assets/ef09fee6-734f-4ae2-96e5-51a9933460ff)
