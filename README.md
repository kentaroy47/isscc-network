# ISSCC 2026 Author Network

Interactive co-authorship network visualization for ISSCC 2026 papers.

## Live Demo

https://kentaroy47.github.io/isscc-network/

## Features

- **Interactive Graph**: Force-directed network layout with D3.js
- **Node**: Authors (size = number of papers, color = session)
- **Edge**: Co-authorship relationship
- **Search**: Find authors by name
- **Filters**: Filter by session or minimum paper count
- **Details Panel**: Click on a node to see author's papers and co-authors
- **Navigation**: Drag nodes, zoom, hover to highlight connections

## Data

Source: ISSCC 2026 Advance Program

## Local Development

```bash
python -m http.server 8080
```

Then open http://localhost:8080
