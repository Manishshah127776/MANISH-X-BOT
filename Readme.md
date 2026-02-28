# Telegram Multi-Feature Bot

## 🤖 Developed by MANI XTECH

A powerful Telegram bot with 200+ features including fast downloader, utilities, games, converters, and much more!

## ✨ Features

### 📥 Fast Downloader
- YouTube videos & audio
- Instagram posts & reels
- Facebook videos
- TikTok videos
- Twitter/X videos
- Pinterest images
- Reddit videos

### 📝 Text Tools
- Word/character counter
- Text reverser
- Case converter
- Email/phone extractor
- URL extractor
- Password generator
- QR code generator

### 🧮 Math Tools
- Basic calculator
- Scientific calculator
- Unit converter
- Currency converter
- Age calculator
- BMI calculator
- Percentage calculator

### 🎮 Games
- Dice roller
- Coin flip
- Rock Paper Scissors
- Number guessing
- Word guessing
- Trivia quiz
- Fortune teller

### 🔧 Utilities
- File info
- Hash generator
- Base64 encode/decode
- JSON formatter
- Color converter
- And much more!

## 🚀 Deployment

### Local Deployment
1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Set your bot token in `.env` file
4. Run: `python bot/main.py`

### GitHub Actions Deployment
1. Fork this repository
2. Add secrets in GitHub:
   - `BOT_TOKEN`: Your bot token from @BotFather
3. Push to main branch to trigger deployment

### Docker Deployment
```bash
docker build -t mani-xtech-bot .
docker run -e BOT_TOKEN=your_token mani-xtech-bot
