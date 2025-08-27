# wikipediaDictionary
 Wikipedia-based Dictionary Tool

# Wikipedia Dictionary

A lightweight, bilingual dictionary-style web app powered by the Wikipedia API.  
Users can enter a word in one language, browse candidate entries with short summaries,  and then view the corresponding entry in another language.

## Features (Planned for v0.1)
- Two-column interface (source language on the left, target language on the right).
- Each language has a input box on the top, and a candidate list box below.
- Search for a term in the source language and see candidate matches with summaries.
- Select a candidate to automatically fetch and display the equivalent entry in the target language.
- Clickable links to full Wikipedia articles for more details.

## Goals
- Provide a clean, dictionary-like UI.
- Keep implementation simple: frontend-focused with minimal setup.
- Use the Wikipedia REST API for summaries and cross-language links.

## Future Enhancements
- Handle multiple candidates and disambiguation pages.
- Add support for more languages beyond the initial pair.
- Explore LLM-based post-processing to shorten or polish summaries.