# WebScraperAI

A powerful, AI-powered web scraping tool built with Python, featuring sentiment analysis, summarization, and flexible scraping options. Uses IPRoyal proxies for reliable scraping and a sleek GUI with Tkinter.

## Features
- **Proxy Configuration**: Customizable proxy settings with IPRoyal SOCKS5 support.
- **Batch URL Processing**: Scrape multiple URLs in one go.
- **AI Analysis**: Sentiment analysis and summarization powered by Hugging Face Transformers.
- **Flexible Scraping**: Select multiple content types (e.g., headings, paragraphs) with descriptive checkboxes.
- **Export Options**: Save scraped data as TXT, CSV, or JSON.
- **Progress Indicator**: Visual feedback with a progress bar.
- **Error Logging**: Detailed logs saved to a file for debugging.

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ghubgsns/webscraperAI.git
   cd webscraperAI
   ```
2. **Install Dependencies**:
   ```bash
   pip install requests requests[socks] beautifulsoup4 transformers torch fake_useragent pandas
   ```
3. **Run the App**:
   ```bash
   python web-scraper-ai.py
   ```

## Usage
- Enter proxy details (get yours from [IPRoyal](https://iproyal.com/?r=IproyalR)).
- Input URLs (one per line) in the text box.
- Click "Analyze & Scrape" to fetch, analyze, and select content.
- Choose content types with checkboxes and export format, then hit "Scrape Selected".

## Version History
- **v1.0 (Initial Release)** - 03/04/2025
  - Basic scraping with IPRoyal proxy support.
  - Sentiment and summarization using default Transformers models.
- **v1.1** - 03/06/2025
  - Added GUI with Tkinter.
  - Fixed proxy URL parsing and token length errors.
- **v1.2** - 03/08/2025
  - Batch URL processing, progress bar, and export options (TXT, CSV, JSON).
  - Added error logging to file.
- **v1.3 (Current)** - 03/10/2025
  - Proxy config UI, descriptive checkboxes for multi-select scraping.
  - IPRoyal referral link button.

## Get Proxies
For reliable scraping, use IPRoyal proxies.[IPRoyal Proxy](https://iproyal.com/?r=IproyalR).

## Contributing
Feel free to fork, submit PRs, or open issues on [GitHub](https://github.com/ghubgsns/webscraperAI).

## License
MIT License - see [LICENSE](LICENSE) file.
