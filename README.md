# 4D-UMAP identity clustering — interactive demo

A self-contained, dependency-free WebGL visualization (three.js) of identity-embedding
clusters under a 4D-UMAP projection. Each cluster is a distinct tracked entity; the
animation sweeps the fourth UMAP dimension. Hover a point for its entity label.

**Live demo:** https://serge-tochilov.github.io/umap-4d-identity-demo/

Pipeline: per-entity image embeddings → HDBSCAN clustering → 4D-UMAP projection.
Single HTML file, no build step, no network calls (three.js inlined).
