# 📚 Repetio Decks

Open-source flashcard decks for the [Repetio](https://repetioapp.com) spaced repetition app.

## What's Inside

**179 decks** across **60 topics** in **3 languages** (English, Portuguese, Spanish).

### Categories

| Category | Topics |
|----------|--------|
| 🖥️ **Technology** | AWS Basics, Azure Fundamentals, AI-900, AZ-900, AWS AI Practitioner, AWS↔Azure |
| 📜 **History** | World Wars, Cold War, Middle Ages, Industrial Revolution, Ancient Civilizations, Famous Explorers |
| 🔬 **Science** | Physics, Chemistry, Biology, Astronomy, Quantum Physics, Space Exploration, Human Body |
| 🧠 **Philosophy** | Stoicism, Existentialism, Ethics, Logic |
| 🏆 **Sports** | FIFA World Cup, F1, Olympics, Tennis, Basketball |
| 🎬 **Pop Culture** | Movies by decade (1950s–2010s), Music by decade (1950s–2010s), Classic Video Games |
| 🌍 **Geography** | World Capitals, Countries, Demographics |
| 🧬 **Psychology** | Psychology, Cognitive Biases |
| 🍽️ **Food** | World Cuisine, Cocktails |
| 📖 **Culture** | Greek Mythology, Norse Mythology, Literature, Art History, Architectural Wonders, Famous Scientists, Inventions & Inventors |
| 🗣️ **Languages** | Travel English↔Portuguese |

### Languages

Each deck is available in:
- 🇬🇧 English (`_en` or no suffix)
- 🇧🇷 Portuguese (`_pt`)
- 🇪🇸 Spanish (`_es`)

## Deck Format

Simple CSV with two columns — `front` (question) and `back` (answer):

```csv
"front","back"
"What is AWS?","A cloud computing platform offering on-demand IT resources"
```

## How to Use

1. Download any deck from the `decks/` folder
2. Import into [Repetio](https://repetioapp.com) or any flashcard app that supports CSV
3. Start learning with spaced repetition!

### Direct Links

All decks are accessible via raw GitHub URLs:
```
https://raw.githubusercontent.com/lucaspellucci/repetio_decks/refs/heads/main/decks/{filename}
```

The full index with metadata is in [`index.csv`](index.csv).

## Contributing

PRs welcome! Each deck should:
- Use CSV format with `"front"` and `"back"` headers
- Wrap all fields in double quotes
- Include ~30 cards per deck
- Provide all 3 language versions (EN/PT/ES)

## License

These decks are free to use for personal learning.
