# Intelligent FAQ Retrieval Website

A standalone recreation of the FAQ Retrieval website shown in the supplied Base44 screenshots.

## Features

- Natural-language FAQ search
- Inverted-index candidate retrieval
- TF-IDF scoring
- Levenshtein fuzzy matching
- Synonym/semantic matching
- Hybrid ranking
- Top-K results
- Category and source filters
- Scoring display
- Search analytics
- Method distribution
- Admin FAQ CRUD
- Dark mode
- Browser localStorage persistence
- Optional Java DSA implementation in `dsa/`

## Run

### Easiest
Double-click `index.html`.

### Recommended in VS Code
Install the "Live Server" extension, then right-click `index.html` and choose:
`Open with Live Server`

No npm installation is required.

## DSA

`dsa/FAQRetrievalDSA.java` contains a standalone Java implementation of the core algorithms:
- HashMap
- HashSet
- Inverted Index
- TF-IDF
- Levenshtein Dynamic Programming
- Fuzzy Matching
- Semantic/Synonym Matching
- PriorityQueue Top-K retrieval
- Sorting
- Analytics
- CRUD

## Important

This is a functional recreation based on the UI, feature descriptions, and FAQ data visible in the supplied Base44 screenshots. It is not a dump/export of Base44's private source code.
