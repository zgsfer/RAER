# DK-CLIP: Domain Knowledge Enhanced CLIP for Dynamic Facial Expression Recognition

This repository provides the official implementation of the paper:

**"DK-CLIP: Domain Knowledge Enhanced CLIP for Dynamic Facial Expression Recognition"**  
📍 *Accepted to [Conference/Journal Name]*  
🔗 [Paper Link (arXiv or conference)](https://arxiv.org/abs/xxxx.xxxxx)

## 🔍 Overview

**DK-CLIP** introduces a CLIP-based framework that integrates domain knowledge from dynamic facial expression recognition (DFER), including temporal correlations and facial action units (AUs). It addresses two major challenges in DFER:

- Noise interference from irrelevant or low-intensity frames  
- Limited annotated training data

Key components:

- Hierarchical video encoder with short- and long-term temporal modeling  
- AU-enhanced semantic text prompts  
- Class-aware consistency regularization for robust learning

## 📦 Datasets

We evaluate DK-CLIP on the following in-the-wild DFER datasets:

- [DFEW](https://github.com/whdeng-ustc/DFEW)
- [FERV39K](https://github.com/ZhiwenShao/FERV39K)
- [MAFW](https://github.com/ZhiwenShao/MAFW)

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- PyTorch ≥ 1.10
- CUDA-compatible GPU

### Installation

```bash
git clone https://github.com/liliupeng28/DK-CLIP.git
cd DK-CLIP
pip install -r requirements.txt
