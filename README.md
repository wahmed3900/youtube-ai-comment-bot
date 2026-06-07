# YouTube AI Comment Bot

[![CI/CD Pipeline](https://github.com/wahmed3900/youtube-ai-comment-bot/actions/workflows/deploy.yml/badge.svg)](https://github.com/wahmed3900/youtube-ai-comment-bot/actions/workflows/deploy.yml)
[![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/)

AI-powered bot that automatically replies to YouTube comments using DeepSeek API. Detects genuine questions, filters spam, and generates natural responses.

## 🚀 Features

- 🔍 **Smart Detection** - Identifies genuine questions vs spam
- 🤖 **AI-Powered Replies** - Uses DeepSeek API (10x cheaper than OpenAI)
- 📊 **Real-time Dashboard** - Monitor bot activity on Render.com
- 🐳 **Docker Ready** - Run locally with docker-compose
- ✅ **Tested** - Unit tests for spam detection and API endpoints
- 🔄 **CI/CD Pipeline** - Automated testing and deployment via GitHub Actions

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Backend | Python 3.11, Flask |
| APIs | YouTube Data API v3, DeepSeek API |
| Database | PostgreSQL |
| Caching | Redis |
| Container | Docker, docker-compose |
| Deployment | Render.com |
| CI/CD | GitHub Actions |
| Testing | pytest, coverage |

## 📦 Quick Start

### Prerequisites
- Python 3.11+
- Docker (optional)
- YouTube API key
- DeepSeek API key

### Local Development

```bash
# Clone the repository
git clone https://github.com/wahmed3900/youtube-ai-comment-bot.git
cd youtube-ai-comment-bot

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your API keys

# Run the bot
python app.py
