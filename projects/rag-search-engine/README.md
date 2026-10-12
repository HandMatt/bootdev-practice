## RAG Search Engine (Boot.dev Course)

This repository contains a small search engine project built while following the Boot.dev course on Retrieval-Augmented Generation (RAG). It currently includes a simple keyword-based movie search CLI.

## Installation

1. **Create and activate a virtual environment** (recommended), or use your preferred Python environment.
2. **Install dependencies** (if you're using `uv`, from the project root run):

```bash
uv sync
```

3. Ensure the `data/movies.json` file exists (it is ignored by git, so you may need to download or recreate it from the course materials).

## Running the CLI

From the project root, run the keyword search CLI with:

```bash
python -m cli.keyword_search_cli search "your query here"
```

For example:

```bash
python -m cli.keyword_search_cli search "Narnia"
```

This will search the movies dataset and print matching titles ranked by a simple keyword/BM25-based search.

## Notes

- This project is primarily educational, following the Boot.dev RAG course structure.
- The `data/` directory (including `movies.json`) is ignored by git so that large datasets and course-specific files are not committed.

