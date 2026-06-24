# Papers & Works in Xie Saining (谢赛宁) × Zhang Xiaojun (张小珺) Interview

**Episode:** 《张小珺Jùn｜商业访谈录》#133 — "对谢赛宁的7小时马拉松访谈" · Feb 2026, Brooklyn · 6h45m · his first interview
**Video:** https://www.bilibili.com/video/BV1tew5zVEDf/ · **Audio:** https://www.xiaoyuzhoufm.com/episode/69b77577f8b8079bfa8eb837

> **Method:** Extracted from the verbatim Podwise transcript (4,926 segments), scanned and read in context. Timestamps `[h:mm:ss]` mark where each work is named — jump there in the video. ASR garbles some English terms; decoded names are flagged.

---

## Tier 1 — Papers he explicitly calls GREAT (代表作)

At **2:19:47–2:22:34** he says there are *"大概二十篇…二十二三篇 paper"* (~20–25 papers) that "deeply shaped deep learning and AI," adds *"那我一篇都没有"* ("I have not a single one of those"), then names them off — warning *"我可能数不全"* ("I can't list them all"). So this is **his partial enumeration of the canon**, not his own work.

| # | Paper | URL | At |
|---|---|---|---|
| 1 | LeNet | http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf | 2:21:40 |
| 2 | AlexNet | https://proceedings.neurips.cc/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html | 2:21:40 |
| 3 | ImageNet | https://ieeexplore.ieee.org/document/5206848 | 2:21:40 |
| 4 | ResNet | https://arxiv.org/abs/1512.03385 | 2:21:40 |
| 5 | R-CNN / Fast R-CNN (detection) | https://arxiv.org/abs/1311.2524 | 2:21:40 |
| 6 | Transformer (Attention Is All You Need) | https://arxiv.org/abs/1706.03762 | 2:22:02 |
| 7 | **Attention paper** — *garbled "Tension Solution Unit"* (see note) | https://arxiv.org/abs/1409.0473 | ~2:22:04 |
| 8 | GPT-3 | https://arxiv.org/abs/2005.14165 | 2:22:02 |
| 9 | BERT | https://arxiv.org/abs/1810.04805 | 2:22:02 |
| 10 | CLIP | https://arxiv.org/abs/2103.00020 | 2:22:02 |
| 11 | ViT (Vision Transformer) — *said as "VIP", then reclarified* | https://arxiv.org/abs/2010.11929 | 2:22:14 |
| 12 | GAN | https://arxiv.org/abs/1406.2661 | 2:22:14 |
| 13 | NeRF | https://arxiv.org/abs/2003.08934 | 2:22:25 |
| 14 | 3D Gaussian Splatting | https://arxiv.org/abs/2308.04079 | 2:22:25 |
| 15 | Diffusion Models / DDPM | https://arxiv.org/abs/2006.11239 | 2:21:09 |
| 16 | Stable Diffusion / LDM | https://arxiv.org/abs/2112.10752 | 3:07:38 |

**16 identifiable** (≈ his "twenty-something" estimate). He explicitly keeps his own work OUT of this tier — when asked "DiT 不算吗?" he answers *"算 0.25"* (only a quarter, 2:20:41).

### Notes on the two ASR-garbled names
- **#11 "VIP" = ViT.** Certain. ASR spells it "VIT" correctly at 2:58:26, 3:03:53, 3:04:00; here it mangled the acronym and he immediately said "Vision Transformer." Duplicate, not a separate paper.
- **#7 "Tension Solution Unit" = an attention paper.** "Tension" = **attention** is proven by this ASR's habit of writing self-attention as "software attention" / "Software Tension" (2:58:30, 2:58:45). As he lists Transformer separately at #6, the most likely intent is the original attention paper — **Bahdanau, Cho & Bengio 2014, "Neural Machine Translation by Jointly Learning to Align and Translate"** (linked above). ⚠️ Not 100% — confirm by ear at **~2:22:04–2:22:06**.

---

## Tier 2 — His own / co-authored work he DISCUSSES (he does not self-rate as "great")

| Work | URL | At |
|---|---|---|
| Deeply-Supervised Nets (DSN) | https://arxiv.org/abs/1409.5185 | 0:48:53, 3:36:27, 4:01:39 |
| HED (Holistically-Nested Edge Detection) | https://arxiv.org/abs/1504.06375 | 0:48:28, 3:36:27 |
| ResNeXt | https://arxiv.org/abs/1611.05431 | 1:00:39, 1:02:31 |
| DiT (Diffusion Transformers) — self-rated "0.25" | https://arxiv.org/abs/2212.09748 | 2:20:41, 3:00:29, 3:59:30 |
| SiT (Scalable Interpolant Transformers) | https://arxiv.org/abs/2401.08740 | 3:15:25 |
| MoCo (Momentum Contrast) | https://arxiv.org/abs/1911.05722 | 2:25:59, 2:26:45, 6:03:29 |
| MAE (Masked Autoencoders) | https://arxiv.org/abs/2111.06377 | 2:26:45, 6:03:29 |
| Cambrian-1 (multimodal LLM) | https://arxiv.org/abs/2406.16860 | 3:15:51, 4:02:13 |
| REPA (Representation Alignment) | https://arxiv.org/abs/2410.06940 | 4:01:06 |
| Representation Autoencoder (RAE) — 2025, follow-on to REPA | https://arxiv.org/a/xie_s_1.html | 4:02:48 |

*MoCo & MAE are Kaiming He–led, Xie is co-author. RAE arXiv ID not verified — link goes to his arXiv author page; title is "Representation Autoencoder."*

---

## Tier 3 — Other works / systems / tools referenced

**RL & world-model lineage**
| Work | URL | At |
|---|---|---|
| Dyna (Sutton 1991, model-based RL) | https://dl.acm.org/doi/10.1145/122344.122377 | 4:15:20 |
| The Bitter Lesson (Sutton 2019 essay) | http://www.incompleteideas.net/IncIdeas/BitterLesson.html | 4:10:33, 4:39:00 |
| JEPA (LeCun, *A Path Towards Autonomous Machine Intelligence*) + a recent "The JEPA" paper | https://openreview.net/forum?id=BZ5a1r-kVsf | 6:03:10–6:05:36 |
| Genie (DeepMind world model) | https://arxiv.org/abs/2402.15391 | 4:26:52 |
| U-Net (what DiT replaced) | https://arxiv.org/abs/1505.04597 | 3:04:00 |
| CPC (Contrastive Predictive Coding) | https://arxiv.org/abs/1807.03748 | 2:00:27 |
| Mask R-CNN / Focal Loss (Ross Girshick's line — mentioned, not in Tier 1) | https://arxiv.org/abs/1703.06870 · https://arxiv.org/abs/1708.02002 | 2:34:49–56 |

**Contemporary systems / tools name-dropped**
- Sora (OpenAI; cites his DiT) — https://openai.com/sora — 3:10:10, 3:59:30
- SeeDance (ByteDance) — 4:06:18
- Nano Banana (Google Gemini image) — 2:17:56
- Gemini / ChatGPT (GPT series) — 2:17:56, 4:00:09
- A video-diffusion model, name garbled (likely Google **Veo**) — 4:26:52
- PyTorch — https://pytorch.org — 0:42:03

**Concepts / awards (not papers)**
- Neural Architecture Search (NAS) — reflected on critically — 1:13:52
- Scaling Law — 4:10:33
- Marr Prize nomination (his PhD paper) — 0:50:29

*Cultural references (not academic): 《金刚经》 Diamond Sutra (on research taste); 《万神殿》 Pantheon, TV series by Ken Liu 刘宇坤.*
