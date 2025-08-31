# BrightData Research Assistant 🤖🌐

An AI-powered research assistant bot built with n8n and Bright Data's Verified Node to deliver real-time, comprehensive research results by scraping and summarizing web data.

---

## What It Does

BrightData Research Assistant ([@BrightDataResearch_bot](https://t.me/BrightDataResearch_bot)) automatically listens for user queries via Telegram, fetches relevant and up-to-date information using BrightData’s web scraping capabilities combined with Perplexity AI and Google Gemini, then summarizes the results and delivers actionable research answers directly in chat.

---

## Features

- Real-time web data scraping with Bright Data Verified Node  
- Advanced search integration with Perplexity AI  
- Natural language processing and summarization using Google Gemini  
- Modular workflow built and automated through n8n  
- Telegram bot interface for seamless user interaction  
- Robust snapshot management and error handling  

---

## How To Use

1. Deploy the n8n workflow.  
2. Configure credentials for Telegram, Bright Data, Perplexity, and Google Gemini APIs.  
3. Start the Telegram bot by interacting with @BrightDataResearch_bot.  
4. Send research queries via Telegram chat and receive summarized responses.

---

## Workflow Breakdown

- **Telegram Bot Trigger:** Listens for incoming messages.  
- **Send Welcome & Acknowledgment:** Provides user prompts and status updates.  
- **BrightData Scraper Node:** Initiates target web scraping for queries.  
- **Snapshot Status & Download:** Polls and retrieves scraped data once ready.  
- **Readable Data Extractor & Summarizer:** Cleans, extracts, and distills valuable insights from raw data.  
- **Telegram Response Generator:** Sends back concise research summaries to user chat.

---

## Installation & Setup

- Import the [BrightData-Research-Assistant.json](link-to-your-json) into your n8n instance.  
- Update all credentials with valid API keys and Telegram bot tokens.  
- Adjust timeout and rate limits according to your account quotas.

---

## Technologies Used

- [n8n](https://n8n.io/) - Workflow automation  
- [Bright Data](https://brightdata.com/) - Web scraping infrastructure  
- [Perplexity AI](https://www.perplexity.ai/) - Advanced search API  
- [Google Gemini](https://developers.google.com/ai) - Language model for summarization  
- Telegram Bot API for chat interface

---

## Contributing

Contributions and suggestions are welcome! Feel free to open issues or submit pull requests.

---

## License

[MIT License](LICENSE) (or specify your preferred license)

---

## Author

Developed by 👨‍💻 Nikhil Raikwar  
🌐 [https://dev.to/nikhilraikwar](https://dev.to/nikhilraikwar)  
🌍 [https://nikhilraikwar.vercel.app](https://nikhilraikwar.vercel.app)  
Telegram: [@BrightDataResearch_bot](https://t.me/BrightDataResearch_bot)

---

*Powered by the synergy of real-time data and AI intelligence.*

