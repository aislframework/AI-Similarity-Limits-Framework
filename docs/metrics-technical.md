# Technical Metrics

## Why Multiple Metrics?

No single metric is sufficient to capture all dimensions of similarity. We use a **multi-metric composite approach**.

### Primary Metrics

1. **Face Embeddings (ArcFace / CosFace)**
   - Measures identity similarity
   - Most robust for facial recognition
   - Recommended minimum: Cosine similarity

2. **Voice Embeddings**
   - Uses models such as Wav2Vec2, ECAPA-TDNN or Resemblyzer
   - Critical for audio deepfakes

3. **Perceptual Metrics (LPIPS + SSIM)**
   - LPIPS: Better aligned with human visual perception
   - SSIM: Structural similarity

4. **FID (Fréchet Inception Distance)**
   - Evaluates distribution-level quality and realism

## Normalization Method

- Use **percentile-based scoring** instead of raw values
- Example: 85% similarity = being in the 85th percentile of intra-class similarity distribution for that individual
- Final score: Weighted average of normalized metrics (weights to be defined by community)

## Modalities

- **Phase 1**: Face + Voice
- **Phase 2**: Full body, gestures, and long-form video
- **Phase 3**: Behavioral and contextual consistency

## Known Limitations

- Adversarial attacks can reduce metric scores while maintaining human perception
- Bias in datasets (performance varies across ethnicities, ages, and genders)
- Solution: Iterative improvement + hybrid approach (metrics + human review in borderline cases)

This document will evolve as new research and benchmarks emerge.
