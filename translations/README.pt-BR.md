# AI-Similarity-Limits-Framework

**Objective similarity thresholds for generative AI and deepfake regulation**

Subjetividade judicial + IA = caos.  
Este framework substitui critérios vagos como "reconhecibilidade" ou "aparência real" por **limites objetivos mensuráveis** de similaridade.

### Framework Original (v0.1)

- **Similaridade < 70%**: Livre – considerado "pessoa genérica"
- **Similaridade 70-85%**: Permitido com alerta obrigatório
- **Similaridade 85-95%**: Exige consentimento explícito da pessoa similar
- **Similaridade > 95%**: Considerado violação grave (crime em contextos de dano), salvo autorização expressa

### Por que este projeto existe?

Atualmente, juízes decidem casos de deepfake baseados em testemunhos emocionais e percepções subjetivas. Este repositório busca construir um padrão técnico aberto, revisável por pares e globalmente adaptável para reduzir essa subjetividade.

### Métricas Técnicas Principais
- Face Embeddings (ArcFace / CosFace)
- Voice Embeddings
- Métricas Perceptuais (LPIPS, SSIM)
- FID + outras

O framework é **iterativo** e reconhece limitações (incluindo ataques adversariais).

### Como Participar
Não importa sua formação. Precisamos de:
- Engenheiros de IA e Computer Vision
- Advogados e especialistas em regulação
- Formuladores de políticas
- Pesquisadores éticos
- Cidadãos preocupados

**Contribuições são bem-vindas via Issues e Pull Requests.**

### Traduções
- [English](README.md)
- [Português Brasileiro](translations/README.pt-BR.md)
- [Mandarim Simplificado](translations/README.zh-CN.md)

### Próximos Passos
- Versão 0.1 → Discussão comunitária
- Versão 1.0 → Submissão para ITU/ISO, OECD.AI, UNESCO, Council of Europe, C2PA e outros órgãos

---

**Este é um projeto open-source neutro e técnico.**  
Não representa nenhuma empresa ou governo.

**Autores iniciais**: Comunidade (você + Grok + DeepSeek + contribuidores)

---

**Licença**: [CC BY-SA 4.0](LICENSE) (documentos) + MIT (código)
