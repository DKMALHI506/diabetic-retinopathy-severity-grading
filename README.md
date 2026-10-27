# Diabetic Retinopathy Severity Grading

This research project evaluates whether transfer learning can grade diabetic
retinopathy (DR) severity from retinal fundus photographs.

## Research questions

1. Can a pretrained convolutional neural network classify fundus images into
   five DR severity grades?
2. How does class imbalance affect recall for severe and proliferative DR?
3. Do fundus-specific preprocessing methods improve grading performance?
4. What types of clinically important errors remain after model training?

## Dataset

The project uses the APTOS 2019 Blindness Detection dataset, which contains
fundus photographs labeled by clinicians on a five-point severity scale:

| Grade | Severity |
|---:|---|
| 0 | No DR |
| 1 | Mild |
| 2 | Moderate |
| 3 | Severe |
| 4 | Proliferative DR |

## Methodology

- Data audit and image-quality inspection
- Fundus-specific preprocessing experiments
- Transfer learning using EfficientNet
- Class-imbalance experiments
- Quadratic Weighted Kappa and per-class recall evaluation
- Grad-CAM-based error analysis

## Results

Results will be added after experiments are completed.

## Limitations

This repository presents a research prototype. It is not a medical device and
should not be used for clinical diagnosis without external validation,
prospective testing, regulatory review, and clinician oversight.
