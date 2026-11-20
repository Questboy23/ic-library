# ic-library

Shared, public library for ic. It holds only public data, named by SHA-256: zstd dictionaries,
piece indexes (`.caibx`) and pieces of openly licensed public files. No code, no keys, no private data.

Assets live in Releases. Check every download against the release's `SHA256SUMS-open`.

## library-v1-open contents and sources
- Open-source Python packages from PyPI and the requests, flask and click repositories (each tar carries its own license).
- Open-source release binaries and source of jq, ripgrep and fd from GitHub releases.
- Open datasets: datasets/*, owid/co2-data, seaborn-data, plotly datasets, pandas test files.
- Enron email corpus (public record, via Hugging Face corbt/enron-emails).
- zstd dictionaries trained only on the files above (.tar, .gz, .csv, .mbox).

arXiv papers, Wikimedia Commons photos, music and video are left out: their licenses restrict
redistribution or require attribution per file.
