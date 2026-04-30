# RADC Depression Classification Submission Package

This package is a reviewer-facing companion to the original repository. It is intended to make the project easier to evaluate without modifying the source notebooks.

## Contents
- `requirements.txt` for the main Python dependencies used in the notebooks.
- `DATA_AVAILABILITY.md` describing what data can be shared.
- `KNOWLEDGE_BASE_PROVENANCE.md` documenting the curated knowledge base.
- `REPRODUCIBILITY.md` with the minimum execution notes needed by reviewers.
- `CITATION.cff` for citation metadata.

## Notes for submission
- The original notebooks remain unchanged in the repository root.
- The E-DAIC dataset is not redistributed here because of licensing restrictions.
- The knowledge base in `knowledge_base/knowledge_base.jsonl` is curated by the authors.
- Several notebooks contain environment-specific Colab paths and outputs from prior runs; reviewers should treat the root notebooks as the working versions used during development.

