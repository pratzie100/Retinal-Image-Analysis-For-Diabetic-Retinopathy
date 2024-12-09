# Retinal Image Analysis for Diabetic Retinopathy Detection

## Project Overview

- Applied machine learning, deep learning, and transfer learning on APTOS 2019 Blindness Detection Dataset.

## Dataset Details

- Dataset taken from Kaggle (APTOS Blindness Detection Dataset).
- Consists of 3,662 eye fundus images.

## Model and Performance

- A CNN classifier based on the DenseNet121 network (trained for ImageNet) performed best.
- Achieved an accuracy of 79% for 5-class severity classification.

## Image Preprocessing

- Image preprocessing was done using CLAHE (Contrast Limited Adaptive Histogram Equalization).
- CLAHE enhances the contrast of local regions in the image.
- Improves visibility of important features like blood vessels and lesions without over-amplifying noise.

## Benefits of CLAHE

- Prepares images for more accurate machine learning and deep learning analysis.
