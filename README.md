# 🕷️ Web Scraping AI Agent

**Intelligent web scraping powered by AI** — Extract structured data from any website using natural language prompts instead of complex parsing code. Built on **ScrapeGraph AI**, this agent transforms web scraping into a simple, conversational process.

---

## 🎯 Overview

This project provides two powerful implementations for AI-driven web scraping:

| Implementation | Type | Best For |
|---|---|---|
| **Local AI Scraper** | Open-source library | Development, privacy, cost-conscious users |
| **Cloud SDK** | Managed API service | Production, scale, advanced features |

Choose the version that fits your needs, or use both depending on your project requirements.

---

## 📂 Project Structure

```
web_scrapping_ai_agent/
├── ai_scrapper.py              # Streamlit app using OpenAI GPT-4o
├── local_ai_scrapper.py        # Streamlit app using local models
├── requirements.txt            # Project dependencies

```

---

## ⚡ Quick Start

### Option 1: Local AI Scraper (Recommended for starters)

```bash
# Install dependencies
pip install -r requirements.txt

# Set your OpenAI API key
export OPENAI_API_KEY='your-api-key-here'

# Run the web interface
streamlit run ai_scrapper.py

# Or for local LLM models (requires Ollama)
streamlit run local_ai_scrapper.py
```

### Option 2: Cloud SDK

```bash
# Navigate to SDK directory
cd scrapegraph_ai_sdk/

# Install dependencies
pip install -r requirements.txt

# Set your ScrapeGraph AI API key
export SGAI_API_KEY='your-api-key-here'

# Run quick demo
python quickstart.py
```

---

## ✨ Features

### 🏠 Local AI Scraper
- **Natural Language Interface**: Describe what you want to extract in plain English
- **Flexible Models**: Choose between GPT-4o or local LLM models (via Ollama)
- **Web UI**: User-friendly Streamlit interface
- **Privacy-First**: All processing happens locally (with local models)
- **Free to Use**: No cloud costs when using local LLMs

### ☁️ Cloud SDK
- **Production-Ready**: Managed, scalable infrastructure
- **Advanced Features**: SmartScraper, SearchScraper, SmartCrawler, Markdownify
- **No Setup Needed**: Just API key, instant access
- **Batch Processing**: Handle large-scale scraping jobs
- **Scheduled Jobs**: Automate recurring scraping tasks
- **Always Updated**: Latest features and improvements

---

## 🔄 How It Works

### Local Scraper Workflow
```
1. User enters URL + natural language prompt
   ↓
2. App initializes ScrapeGraph AI with your LLM
   ↓
3. Website is fetched and parsed
   ↓
4. AI extracts structured data based on your prompt
   ↓
5. Results displayed in Streamlit UI
```

### Cloud SDK Workflow
```
1. Define scraping request (URL, prompt, schema)
   ↓
2. Send to ScrapeGraph AI API
   ↓
3. Cloud processes the request optimally
   ↓
4. Receive structured JSON response
   ↓
5. Use data in your application
```


## 🛠️ Technical Details

### Local Scraper
- **Framework**: Streamlit
- **LLM Options**: OpenAI GPT-4o or Ollama (local)
- **Scraping Engine**: ScrapeGraph AI library
- **Data Parsing**: AI-powered extraction

### Cloud SDK
- **API Client**: Official ScrapeGraph AI SDK
- **Processing**: Cloud-based with global infrastructure
- **Response Format**: JSON, Markdown, or custom schema
- **Rate Limits**: Depends on your plan

---

## 📊 Comparison Matrix

| Aspect | Local Scraper | Cloud SDK |
|--------|---------------|-----------|
| **Setup Time** | 5 minutes | 2 minutes |
| **Cost** | OpenAI charges only | Pay-per-request |
| **Processing Speed** | Depends on hardware | Optimized & fast |
| **Data Privacy** | Local models = full privacy | Data sent to cloud |
| **Scalability** | Limited by hardware | Unlimited |
| **Advanced Features** | SmartScraper only | All features |
| **Maintenance** | Manual updates | Fully managed |
| **Best For** | Learning, development | Production, scale |

---


## 📚 Resources

- **ScrapeGraph AI GitHub**: [VinciGit00/Scrapegraph-ai](https://github.com/VinciGit00/Scrapegraph-ai)
- **Official Documentation**: [docs.scrapegraphai.com](https://docs.scrapegraphai.com)
- **Cloud SDK Details**: [scrapegraph_ai_sdk/README.md](scrapegraph_ai_sdk/README.md)
- **Ollama Documentation**: [ollama.ai](https://ollama.ai)

---

---


