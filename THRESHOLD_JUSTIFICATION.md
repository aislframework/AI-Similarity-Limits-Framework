# Threshold Justification

## Why 70%, 85% and 95%?

These thresholds are **initial proposals** based on current scientific literature in face recognition, perceptual psychology, and deepfake detection. They are not arbitrary.

### Proposed Thresholds Rationale

- **< 70%**: Below most practical false acceptance rates (FAR) in modern face recognition systems. At this level, the generated content is generally perceived as a generic or fictional person.

- **70-85%**: Corresponds to the range where similarity becomes noticeable to humans, but still has significant room for creative freedom. This is the "gray zone" that requires transparency.

- **85-95%**: High similarity zone. At this level, studies show strong risk of identity confusion. Requires consent to protect right of publicity and personality rights.

- **> 95%**: Very high similarity — approaching "digital replica" territory. In this range, the risk of harm (fraud, defamation, non-consensual intimate imagery) increases dramatically.

## Basis

- Face recognition literature (ArcFace, CosFace papers)
- Perceptual studies using LPIPS and human evaluation
- Deepfake detection benchmarks (2024-2026)
- False Acceptance Rate (FAR) and False Rejection Rate (FRR) curves

These numbers will be refined through community debate and new empirical data.
