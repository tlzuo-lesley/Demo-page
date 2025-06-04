# XEmoRAG: Cross-Lingual Emotion Transfer with Controllable Intensity

This repository contains the demo page for our paper **"XEmoRAG: Cross-Lingual Emotion Transfer with Controllable Intensity Using Retrieval-Augmented Generation"**.

## Project Overview

XEmoRAG is a novel framework for cross-lingual emotion transfer in speech synthesis, specifically focusing on transferring emotions from Chinese to Thai in a zero-shot setting. Our approach uses retrieval-augmented generation to guide emotional expression and incorporates flow-matching for natural prosody and timbre blending.

Key features:
- Zero-shot emotion transfer without parallel emotional data
- Controllable emotion intensity (weak/normal/strong)
- Language-agnostic emotional embedding extraction
- Natural prosody preservation through flow-matching

## Demo Contents

The demo page showcases three main aspects of our work:

### 1. Cross-Lingual Emotion Comparison
Compares emotional speech synthesis results between XEmoRAG and baseline models (Typhoon, DelightfulTTS) in Chinese-to-Thai transfer. Each example shows:
- Chinese reference audio
- Emotionally matched Thai audio
- Synthesized outputs from different systems

### 2. Emotion Intensity Control
Demonstrates XEmoRAG's ability to control emotion intensity at three levels:
- Weak
- Normal 
- Strong

### 3. Flow Matching for Natural Prosody
Compares the original X-Codec2 approach with our flow-matching module on:
- Naturalness
- Expressiveness
- Timbre blending

## How to Use the Demo

1. Navigate through the different comparison sections
2. Click the play button on any audio sample to listen
3. Compare the emotional quality between different systems
4. Observe the intensity variations in the controllable examples

## Citation

If you find this work useful, please cite our paper:

```bibtex
@inproceedings{xemorag2024,
  title={XEmoRAG: Cross-Lingual Emotion Transfer with Controllable Intensity Using Retrieval-Augmented Generation},
  author={Author Names},
  booktitle={Conference Name},
  year={2024}
}
