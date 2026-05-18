# PCDP-Deblur

**Processing-Condition Degradation Prior-Guided Deblurring for High-Speed Rotational Imaging of Involute Surfaces**

This repository is the official resource page for the manuscript:

> 渐开线曲面高速旋转成像的工况退化先验引导去模糊方法

## Overview

PCDP-Deblur is designed for deblurring high-speed rotational images of involute metallic surfaces. The method combines:

- **ArilDF**, a lightweight direction-aware restoration backbone for near-horizontal motion degradation.
- **AnisoFreqPSNRLoss**, a PSNR-based training objective with horizontal-biased frequency supervision.
- **PKICL**, a lightweight processing-condition prior injection module that maps rotation-speed-related metadata into bounded pseudo-kernel weights and stage residual modulation.

The goal is to improve restoration quality while maintaining low inference latency for industrial visual inspection workflows, including high-throughput manufacturing quality control, online gear-surface monitoring, and remanufacturing damage assessment.

## Release Status

The manuscript is currently under preparation/submission. Full resources will be released after paper acceptance.

Planned release items include:

- Training and inference code.
- Dataset access instructions and split/index files.
- Trained model checkpoints.
- Evaluation scripts for PSNR, SSIM, and inference speed.
- Configuration files for ablation and transfer experiments.

## Citation

The citation will be added after the manuscript is accepted.

```bibtex
@article{pcdp_deblur,
  title  = {Processing-Condition Degradation Prior-Guided Deblurring for High-Speed Rotational Imaging of Involute Surfaces},
  author = {To be updated},
  journal = {To be updated},
  year   = {2026}
}
```

## Contact

Issues and questions can be submitted through this GitHub repository after the resources are released.

