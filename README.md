[**English**](README.md) | [**中文**](README.zh-CN.md)

# RTMol: Rethinking Molecule-text Alignment in a Round-trip View

[![AAAI 2026](https://img.shields.io/badge/AAAI-2026-blue.svg)]()
[![arXiv](https://img.shields.io/badge/arXiv-2511.12135-b31b1b.svg)](https://arxiv.org/abs/2511.12135)

**Appendix**:[appendix](assets/Appendix.pdf)

---

### Abstract

Aligning molecular sequence representations (e.g., SMILES notations) with textual descriptions is critical for applications spanning drug discovery, materials design, and automated chemical literature analysis. Existing methodologies typically treat molecular captioning (molecule-to-text) and text-based molecular design (text-to-molecule) as separate tasks, which leads to three key limitations:

1.  **Wrong Metric:** Conventional metrics (e.g., BLEU) prioritize linguistic fluency over chemical accuracy.
2.  **Low-quality Dataset:** Training datasets frequently contain chemically ambiguous or incomplete narratives.
3.  **Lack of Bidirectional Mapping:** Independent optimization of generation directions leads to bidirectional inconsistency.

To address these issues, we propose **RTMol**, a bidirectional alignment framework that unifies molecular captioning and text-to-SMILES generation through self-supervised **round-trip learning**. Experiments demonstrate that RTMol enhances bidirectional alignment performance by up to **47%** across various LLMs.

### Framework: Round-Trip Alignment

The core idea of RTMol is to use a single LLM to serve two complementary roles: a **Captioner** and a **Generator**. We enforce consistency through a round-trip training process.

![RTMol Framework](assets/framework.png)

### Code

**Coming Soon**

We are cleaning and annotating the codebase and will release it shortly. Stay tuned!

### How to Cite

If you find our work useful in your research, please cite our paper:

```bibtex
@inproceedings{}