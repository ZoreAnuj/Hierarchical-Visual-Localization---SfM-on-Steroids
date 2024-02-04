# Hierarchical-Visual-Localization---SfM-on-Steroids

Pipeline:

Collected Outdoor Env dataset for SOTA 6-DoF visual localization by leveraging image retrieval & feature matching.
Predicted Local feature matches with SuperGlue (Detector ↦ GNN with Sinkhorn Algorithm-based Optimal Matching)
Triangulate SfM models with COLMAP ↦ Locates Database Images for each Query Image ↦ Query Image Matching.
Employed Hierarchical Feature Network for Estimating local & global features for localization (Recall 75.7% Daytime)



https://github.com/ZoreAnuj/Hierarchical-Visual-Localization---SfM-on-Steroids/assets/95142805/13beed13-f5ad-4883-b035-6d56a8a284e6

