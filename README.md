# Emotion Concepts — Cross-Model Dashboard

Rendered, self-contained results dashboard for a multi-model replication of
**Sofroniew et al., "Emotion Concepts and their Function in a Large Language Model"**
(Anthropic, 2026; the paper studied Claude Sonnet 4.5).

Open **`index.html`** (it redirects to the landing page). From there pick a model to see its
results, or open the cross-model analysis.

## Contents
- `emotions/session_dashboard.html` — landing (model selector).
- `emotions/session_dashboard_cross.html` — cross-model analysis (Part A · characterization).
- `emotions/session_dashboard_<model>.html` — per-model pages: Gemma-4 (31B / E4B / 26B-A4B),
  Qwen3 (8B / 32B), Llama-3.1 (8B / 70B), Llama-3.3 (70B).
- `blackmail/`, `reward_hacking/` — two Part-B de-risk reports linked from the per-model pages.

Every page is self-contained: all CSS/JS is inline and figures are base64-embedded, so there are
no external assets to load. This repository contains only the rendered dashboard — not the
generating pipeline, data, or checkpoints.
