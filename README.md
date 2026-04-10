# ArangoML Research Reports

Interactive research reports and experiment results, served via GitHub Pages.

🔗 **Browse reports: [arangoml.github.io/research-reports](https://arangoml.github.io/research-reports/)**

## Reports

### Retrieval Evaluation

- **[Dense vs Token-Level Retrieval](https://arangoml.github.io/research-reports/retrieval-eval/embedding-comparison/)** — Comparing 14 embedding models across two multi-hop QA datasets (MuSiQue + MultiHop-RAG)
- **[Vector Index vs Brute Force](https://arangoml.github.io/research-reports/retrieval-eval/vector-index-tuning/)** — ArangoDB APPROX_NEAR_COSINE accuracy loss and timing analysis

## Structure

```
research-reports/
├── index.html                              # Landing page
├── retrieval-eval/
│   ├── embedding-comparison/index.html     # Dense vs token-level report
│   └── vector-index-tuning/index.html      # Vector index report
└── README.md
```

Reports are self-contained HTML files with embedded Plotly charts. No server needed — GitHub Pages serves them directly.
