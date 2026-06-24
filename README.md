# 🧭 World over Words — The Paper Canon of Saining Xie

> *"Training world models over word models."* — Saining Xie (谢赛宁), founding manifesto of AMI Labs

![papers](https://img.shields.io/badge/papers_mapped-34-blue)
![great](https://img.shields.io/badge/he_calls_great-16-gold)
![interview](https://img.shields.io/badge/source-6h45m_interview-red)
![method](https://img.shields.io/badge/built_from-verbatim_transcript-brightgreen)
![license](https://img.shields.io/badge/license-CC_BY_4.0-lightgrey)

A curated, **timestamped** map of every research paper, model, and system mentioned by **Saining Xie (谢赛宁)** — co-founder & Chief Scientist of **AMI Labs** (with Yann LeCun) — during his **first-ever interview**: a 6-hour-45-minute marathon conversation with podcaster **Zhang Xiaojun (张小珺)**, recorded in Brooklyn after the 2026 Spring Festival.

The centerpiece is a moment around **2:21:40** where Xie tries to name the *"~20–25 papers that deeply shaped deep learning and AI"* — the works he considers genuine 代表作 (masterpieces) — while insisting *"那我一篇都没有"* ("I don't have a single one of those"). This repo reconstructs that canon, separates it cleanly from his own work, and even **decodes the names the auto-transcription garbled**.

---

## 🎬 Watch / Listen

| Format | Link |
|---|---|
| 📺 Video (Bilibili) | https://www.bilibili.com/video/BV1tew5zVEDf/ |
| 🎧 Audio (小宇宙 / Xiaoyuzhou) | https://www.xiaoyuzhoufm.com/episode/69b77577f8b8079bfa8eb837 |
| 🎧 Apple Podcasts (ep. 133) | https://podcasts.apple.com/cn/podcast/id1634356920?i=1000755501308 |
| 📝 Text version (official) | 《对话谢赛宁：逃出硅谷！》 — WeChat 公众号 "语言即世界 language is world" |

All timestamps `[h:mm:ss]` below point into the video so you can jump straight to each mention.

---

## 📑 Contents
- [Tier 1 — Papers he calls GREAT](#tier-1--papers-he-explicitly-calls-great-代表作)
- [🔍 Decoding the garbled names](#-decoding-the-garbled-names)
- [Tier 2 — His own work he discusses](#tier-2--his-own--co-authored-work-he-discusses)
- [Tier 3 — Other works & systems referenced](#tier-3--other-works--systems-referenced)
- [How this list was built](#-how-this-list-was-built)
- [Features](#-features)

---

## Tier 1 — Papers he explicitly calls GREAT (代表作)

His own spontaneous enumeration of the deep-learning canon (*"我可能数不全"* — "I can't list them all"). He pointedly keeps **his own** work out of this tier: asked *"DiT 不算吗?"* he answers *"算 0.25"* — only a quarter.

| # | Paper | One-line intro | Link | At |
|---|---|---|---|---|
| 1 | **LeNet** (LeCun et al., 1998) | The original convolutional network, trained by backprop for digit recognition. | [pdf](http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf) | 2:21:40 |
| 2 | **AlexNet** (Krizhevsky, Sutskever, Hinton, 2012) | The ImageNet-2012 winner that ignited the deep-learning era. | [NeurIPS](https://proceedings.neurips.cc/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html) | 2:21:40 |
| 3 | **ImageNet** (Deng … Fei-Fei, 2009) | The million-image labeled benchmark that made deep vision possible. | [IEEE](https://ieeexplore.ieee.org/document/5206848) | 2:21:40 |
| 4 | **ResNet** (He et al., 2016) | Residual connections that let networks go 100+ layers deep. | [arXiv](https://arxiv.org/abs/1512.03385) | 2:21:40 |
| 5 | **R-CNN / Fast R-CNN** (Girshick et al., 2014–15) | Brought CNNs to object detection; start of the detection lineage. | [arXiv](https://arxiv.org/abs/1311.2524) | 2:21:40 |
| 6 | **Transformer** — *Attention Is All You Need* (Vaswani et al., 2017) | The attention-only architecture behind almost all modern AI. | [arXiv](https://arxiv.org/abs/1706.03762) | 2:22:02 |
| 7 | **Attention** (Bahdanau et al., 2014) ⚠️ *garbled — see below* | Introduced the attention mechanism for sequence models. | [arXiv](https://arxiv.org/abs/1409.0473) | ~2:22:04 |
| 8 | **GPT-3** (Brown et al., 2020) | Showed large language models are few-shot learners. | [arXiv](https://arxiv.org/abs/2005.14165) | 2:22:02 |
| 9 | **BERT** (Devlin et al., 2018) | Bidirectional masked-language pretraining that swept NLP. | [arXiv](https://arxiv.org/abs/1810.04805) | 2:22:02 |
| 10 | **CLIP** (Radford et al., 2021) | Learned vision from natural-language supervision. | [arXiv](https://arxiv.org/abs/2103.00020) | 2:22:02 |
| 11 | **ViT** — Vision Transformer (Dosovitskiy et al., 2020) ⚠️ *said "VIP"* | Pure Transformers beat CNNs on images at scale. | [arXiv](https://arxiv.org/abs/2010.11929) | 2:22:14 |
| 12 | **GAN** (Goodfellow et al., 2014) | Generative adversarial nets; launched modern image generation. | [arXiv](https://arxiv.org/abs/1406.2661) | 2:22:14 |
| 13 | **NeRF** (Mildenhall et al., 2020) | Neural radiance fields for photorealistic 3D reconstruction. | [arXiv](https://arxiv.org/abs/2003.08934) | 2:22:25 |
| 14 | **3D Gaussian Splatting** (Kerbl et al., 2023) | Real-time, high-quality 3D reconstruction; NeRF's faster successor. | [arXiv](https://arxiv.org/abs/2308.04079) | 2:22:25 |
| 15 | **Diffusion / DDPM** (Ho, Jain, Abbeel, 2020) | Denoising diffusion; the engine of modern image/video generation. | [arXiv](https://arxiv.org/abs/2006.11239) | 2:21:09 |
| 16 | **Stable Diffusion / LDM** (Rombach et al., 2022) | Latent diffusion that made high-res generation efficient and open. | [arXiv](https://arxiv.org/abs/2112.10752) | 3:07:38 |

---

## 🔍 Decoding the garbled names

The interview is Chinese with English terms sprinkled in, and the auto-transcription mangled two paper names. Both are decoded here with evidence:

- **"VIP" (2:22:14) → ViT.** *Certain.* The same transcript spells it **"VIT"** correctly at 2:58:26, 3:03:53 and 3:04:00. Here it garbled the acronym, and Xie immediately reclarifies "Vision Transformer." So it's a duplicate — not a separate paper.
- **"Tension Solution Unit" (~2:22:04) → an attention paper.** *High confidence on "attention", medium on the exact paper.* This transcript reliably renders **self-attention as "software attention" / "Software Tension"** (2:58:30, 2:58:45) — so **"Tension" = attention**. Because Xie lists *Transformer* separately at #6, the best fit is the original attention paper, **Bahdanau, Cho & Bengio 2014**. ⚠️ Confirm by ear at **~2:22:04–2:22:06**; PRs welcome.

---

## Tier 2 — His own / co-authored work he discusses

Discussed in depth across the interview, but **he does not place these in the "great" tier** (he explicitly rates DiT at "0.25").

| Work | One-line intro | Link | At |
|---|---|---|---|
| **Deeply-Supervised Nets (DSN)** (2015) | Auxiliary losses at intermediate layers — "deep supervision." | [arXiv](https://arxiv.org/abs/1409.5185) | 0:48:53 |
| **HED** (2015) | Holistically-nested edge detection; his proud PhD work. | [arXiv](https://arxiv.org/abs/1504.06375) | 0:48:28 |
| **ResNeXt** (2017) | Grouped/"cardinality" transformations — the next-gen ResNet (Kaiming named it). | [arXiv](https://arxiv.org/abs/1611.05431) | 1:00:39 |
| **DiT** (2023) — *self-rated "0.25"* | Diffusion Transformers; replaced U-Net, basis for Sora. | [arXiv](https://arxiv.org/abs/2212.09748) | 2:20:41 |
| **SiT** (2024) | Interpolant / flow-matching generalization of DiT. | [arXiv](https://arxiv.org/abs/2401.08740) | 3:15:25 |
| **MoCo** (2020) | Momentum contrast; first strong self-supervised vision results (Kaiming-led). | [arXiv](https://arxiv.org/abs/1911.05722) | 2:25:59 |
| **MAE** (2022) | Masked autoencoders; BERT-style masking for images (Kaiming-led). | [arXiv](https://arxiv.org/abs/2111.06377) | 2:26:45 |
| **Cambrian-1** (2024) | Vision-centric multimodal LLM. | [arXiv](https://arxiv.org/abs/2406.16860) | 3:15:51 |
| **REPA** (2025) | Align a diffusion model's internal features with a self-supervised model → trains far faster. | [arXiv](https://arxiv.org/abs/2410.06940) | 4:01:06 |
| **RAE — Representation Autoencoder** (2025) | Use a strong representation as the generative model's autoencoder. | [arXiv (author)](https://arxiv.org/a/xie_s_1.html) | 4:02:48 |

*MoCo & MAE are Kaiming He–led; Xie is a co-author. RAE's exact arXiv ID is unverified — link goes to his arXiv author page.*

---

## Tier 3 — Other works & systems referenced

**RL & world-model lineage**
| Work | Link | At |
|---|---|---|
| Dyna (Sutton, 1991) — model-based RL; reactive vs. model-based "System 1/2" | [ACM](https://dl.acm.org/doi/10.1145/122344.122377) | 4:15:20 |
| The Bitter Lesson (Sutton, 2019 essay) — Xie: *"LLMs are anti–Bitter Lesson"* | [essay](http://www.incompleteideas.net/IncIdeas/BitterLesson.html) | 4:10:33 |
| JEPA (LeCun) — *A Path Towards Autonomous Machine Intelligence*; "from doubting JEPA, to understanding it, to becoming it" | [paper](https://openreview.net/forum?id=BZ5a1r-kVsf) | 6:03:10 |
| Genie (DeepMind) — interactive world model | [arXiv](https://arxiv.org/abs/2402.15391) | 4:26:52 |
| U-Net — the architecture DiT replaced | [arXiv](https://arxiv.org/abs/1505.04597) | 3:04:00 |
| CPC — Contrastive Predictive Coding | [arXiv](https://arxiv.org/abs/1807.03748) | 2:00:27 |
| Mask R-CNN / Focal Loss (Ross Girshick's line; mentioned, not in Tier 1) | [Mask](https://arxiv.org/abs/1703.06870) · [Focal](https://arxiv.org/abs/1708.02002) | 2:34:49 |

**Contemporary systems / tools name-dropped**
Sora ([openai.com/sora](https://openai.com/sora), cites his DiT) · SeeDance · Nano Banana · Gemini / ChatGPT · a video model likely Veo · PyTorch ([pytorch.org](https://pytorch.org))

**Concepts / awards (not papers)**
Neural Architecture Search (NAS, reflected on critically, 1:13:52) · Scaling Law (4:10:33) · Marr Prize nomination for his PhD paper (0:50:29)

*Cultural references: 《金刚经》 Diamond Sutra (on research taste); 《万神殿》 Pantheon, TV series by Ken Liu 刘宇坤.*

---

## 🛠 How this list was built

1. Pulled the **full verbatim transcript** — **4,926 timestamped segments** — of the episode.
2. Scanned every segment for model / paper / architecture names, then read each hit in context.
3. Profiled the transcription's failure modes (e.g. *self-attention → "software attention"*, *inductive bias → "index bias"*) to **decode garbled names**.
4. Separated three tiers: **(1)** papers Xie himself calls great, **(2)** his own work, **(3)** everything else referenced.

This matters because online recaps were wrong: they listed **ConvNeXt** and **V-JEPA** as mentioned, but those names **never appear** in the actual audio (0 hits) — they were imported from his CV. The verbatim transcript fixes that.

## ✨ Features

- ✅ **Every paper** with an official / arXiv link and the **exact timestamp** to jump to in the video.
- ✅ **Three tiers** — clearly separates "papers he calls *great*" from "his own work" from "merely referenced."
- ✅ **Garbled-name forensics** — decoded with evidence, with the precise second to verify by ear.
- ✅ Built from the **complete transcript**, not from secondhand summaries.

---

## Credits & License

Compiled by **He Chaoyue (何超越)**. Interview by **Zhang Xiaojun (张小珺)** with **Saining Xie (谢赛宁)**.
Content licensed **CC BY 4.0**. This is an unofficial fan-made study aid; all rights to the interview belong to its creators.

> Spotted a paper I missed, or can confirm the garbled name at ~2:22:04? **Open an issue or PR.**
