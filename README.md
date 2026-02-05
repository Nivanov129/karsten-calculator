# ⚡ Karsten Mana Calculator

MTG Mana Source Calculator based on Frank Karsten's formula.

## 🌐 Live Demo

**GitHub Pages:** https://nivanov129.github.io/karsten-calculator/

## 📖 What is this?

A web-based calculator that analyzes your Magic: The Gathering decklist and recommends how many colored mana sources you need for consistent gameplay, based on **Frank Karsten's mathematical analysis**.

### Key Features

- ✅ Analyzes 40, 60, and 99 card decks (Limited/Constructed/Commander)
- ✅ Uses Scryfall API to fetch card data
- ✅ Calculates required sources based on Karsten's tables
- ✅ Visual color-coded recommendations (✓ ok, ⚠️ low, ❌ critical)
- ✅ No build step - pure HTML/CSS/JS

## 🎮 How to Use

1. Select your deck format (40/60/99 cards)
2. Paste your decklist in the text area
   - Format: `4 Lightning Bolt` or `1x Thoughtseize`
3. Click **Analyze Decklist**
4. Review recommendations for each color

## 📊 The Formula

Based on [Frank Karsten's article](https://www.channelfireball.com/article/frank-analysis-how-many-colored-mana-sources-do-you-need-to-consistently-cast-your-spells/8a1e), which uses hypergeometric distribution to calculate 90% probability of having the right mana.

**Examples (60-card deck):**
- **Thoughtseize** ({B} on T1): Need 14 black sources
- **Lightning Bolt** ({R} on T1): Need 14 red sources  
- **Supreme Verdict** ({W}{W}{U}{U} on T4): Need 18 white AND 18 blue
- **Boros Reckoner** ({R/W}{R/W}{R/W} on T3): Need 22 sources

## 🛠️ Tech Stack

- Pure HTML/CSS/JavaScript (no framework)
- TailwindCSS via CDN
- Scryfall API for card data
- GitHub Pages for hosting

## 📝 License

MIT

## 🙏 Credits

- **Frank Karsten** for the original mathematical analysis
- **Scryfall** for the card database API
- Russian translation of the article: [TopDeck.ru](https://topdeck.ru/forums/topic/104891-перевод-статьи-фрэнка-карстена-how-many-colored-mana-sources-do-you-need-to-consistently-cast-your-spells/)

---

Made with ⚡ for MTG players
