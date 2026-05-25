# AI-Similarity-Limits-Framework

**Objective similarity thresholds for generative AI and deepfake regulation**

Subjectivity in courts + AI = chaos.  
This framework replaces vague criteria such as "recognizability" or "appears authentic" with **measurable objective thresholds** of similarity.

### Original Framework (v0.1)

- **Similarity < 70%**: Free — considered "generic person"
- **Similarity 70-85%**: Allowed with mandatory disclaimer
- **Similarity 85-95%**: Requires explicit consent from the similar person
- **Similarity > 95%**: Considered serious violation (potential crime in harmful contexts), except with explicit authorization

### Why does this project exist?

Currently, judges decide deepfake cases based on emotional testimonies and subjective perceptions. This repository aims to build an open, peer-reviewed, and globally adaptable technical standard to reduce this subjectivity.

### Main Technical Metrics
- Face Embeddings (ArcFace / CosFace)
- Voice Embeddings
- Perceptual Metrics (LPIPS, SSIM)
- FID and others

The framework is **iterative** and acknowledges its limitations (including adversarial attacks).

### How to Participate
Background doesn't matter. We need:
- AI & Computer Vision Engineers
- Lawyers and regulatory experts
- Policymakers
- Ethics researchers
- Concerned citizens

**Contributions are welcome via Issues and Pull Requests.**

### Translations
- [English](README.md)
- [Português Brasileiro](translations/README.pt-BR.md)
- [翻译成简体中文](translations/README.zh-CN.md)

### Next Steps
- Version 0.1 → Community discussion
- Version 1.0 → Submission to ITU/ISO, OECD.AI, UNESCO, Council of Europe, C2PA and other organizations

---

**This is a neutral and technical open-source project.**  
It does not represent any company or government.

**Initial authors**: Community (you + Grok + DeepSeek + contributors)

---

**License**: [CC BY-SA 4.0](LICENSE) (documents) + MIT (code)
