# PCDP-Net

**Processing-Condition Prior-Guided Restoration of Motion-Degraded Gear Surface in High-Speed Rotational Imaging**

This repository currently serves as a pre-release project page for the processing-condition degradation prior-guided restoration method for degraded gear-surface images acquired under high-speed rotation.

> Code, trained models, and dataset access will be released after the paper is accepted.

## What This Project Addresses

High-speed rotational imaging is useful for industrial inspection because it can support gear-surface quality assessment, online monitoring, and remanufacturing evaluation without relying on slow static imaging. In practice, captured tooth-surface images often contain near-horizontal motion blur, metallic reflection changes, weak scratch textures, and trajectory disturbances caused by noisy dynamic processing conditions.

PCDP-Deblur is designed to restore such images by combining visual restoration with lightweight processing-condition prior information. The goal is to improve deblurring reliability while keeping the method suitable for industrial visual inspection workflows.

## Method Overview

The method studies three cooperating design elements:

- **ILDFA**: an involute-surface lightweight direction-factorized architecture for row-oriented feature extraction, directional feature decoupling, and horizontal output correction.
- **PCPIM**: a processing-condition prior injection module that converts a blur-intensity prior into bounded, image-conditioned, stage-aware restoration guidance.
- **HBF-PSNRLoss**: a training objective that complements spatial reconstruction supervision with frequency-domain emphasis on horizontal degradation patterns.

Together, ILDFA and PCPIM form the restoration network, while HBF-PSNRLoss is used during training to encourage recovery of horizontal degradation patterns.

## Planned Release

The repository is currently a pre-release resource page. After paper acceptance, the following resources are planned:

- Training and inference code.
- Configuration files for reproduction.
- Trained model checkpoints.
- Evaluation scripts for PSNR, SSIM, and inference time.
- Dataset access instructions through the final release link.
- Dataset split files and metadata format documentation.

No runnable code, checkpoints, or dataset files are included in this repository before the formal release.

## Dataset Access

Dataset access will be provided after the paper is accepted. The released documentation will include the image-pair organization, processing-condition prior format, and train/test split information.

## Citation

The citation will be updated after the paper is accepted.

```bibtex
@article{pcdp_deblur,
  title  = {Processing-Condition Degradation Prior-Guided Deblurring for High-Speed Rotational Imaging of Involute Surfaces},
  author = {To be updated},
  journal = {To be updated},
  year   = {2026}
}
```

## Contact

For questions about the project, please use the issue tracker after the resource release.
