# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a flashcard deck repository for the Repetio spaced repetition learning app. It contains educational content in CSV format covering topics like cloud computing (AWS, Azure), history, philosophy, and sports.

## Structure

- `index.csv` - Master index of all available decks with metadata (filename, version, description, category, subcategory, URL, language)
- `decks/` - Production-ready flashcard decks in CSV format
- `ai/` - Work-in-progress or AI-generated deck drafts

## Flashcard Deck Format

Each deck is a CSV file with two columns:
- `front` - The question or prompt
- `back` - The answer

Example:
```csv
front,back
What is AWS?,A cloud computing platform offering on-demand IT resources
```

## Index Entry Format

When adding a new deck, create an entry in `index.csv` with these fields:
- `filename` - Name of the CSV file
- `version` - Semantic version (e.g., 1.0)
- `description` - Human-readable deck name
- `category` - Main category (Technology, History, Philosophy, Sports)
- `subcategory1` - First-level subcategory
- `subcategory2` - Second-level subcategory
- `url` - Raw GitHub URL to the deck file
- `language` - Language code (e.g., "en")

The URL pattern is: `https://raw.githubusercontent.com/lucaspellucci/repetio_decks/refs/heads/main/decks/{filename}`
