# Hierarchical-Visual-Localization---SfM-on-Steroids

This Jupyter Notebook covers 6 DoF Visual Localization.

## Prerequisites
- Familiarity with Python and PyTorch.
- Basic understanding of SfM and Localization.

## How to Use
- Ensure PyTorch is installed in your environment.
- Follow the notebook step-by-step to understand implementation details.
- Execute the code cells to train the model.

## Pipeline:

- Collected Outdoor Env dataset for SOTA 6-DoF visual localization by leveraging image retrieval & feature matching.
- Predicted Local feature matches with SuperGlue (Detector ↦ GNN with Sinkhorn Algorithm-based Optimal Matching)
- Triangulate SfM models with COLMAP ↦ Locates Database Images for each Query Image ↦ Query Image Matching.
- Employed Hierarchical Feature Network for Estimating local & global features for localization (Recall 75.7% Daytime)

## Reference

https://github.com/cvg/Hierarchical-Localization

## Results

https://github.com/ZoreAnuj/Hierarchical-Visual-Localization---SfM-on-Steroids/assets/95142805/13beed13-f5ad-4883-b035-6d56a8a284e6

