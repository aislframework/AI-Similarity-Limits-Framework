# Adversarial Attacks and Limitations

## Known Challenge

It is possible to create adversarial examples that reduce the measured similarity score in metrics (ArcFace, LPIPS, etc.) while still appearing highly similar to humans.

## Our Position

- We openly acknowledge this limitation.
- The framework is **not** intended to be a perfect technical defense, but a **better alternative** to pure subjectivity.
- Recommended approach: **Hybrid system** (objective metrics + human review in borderline or contested cases).

## Mitigation Strategies

- Use multiple metrics in ensemble
- Periodic re-evaluation of thresholds
- Require provenance metadata (C2PA)
- Maintain transparency about confidence scores
