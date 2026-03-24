# Static-composition-data-analysis
Itagaki-Egozcue-Unified-Pipeline (V1.2.2): The Terminal Solution for Static CoDA. Integrating Itagaki's Absolute Basis Recovery with Egozcue's ILR Geometry. Overcoming Pearson's Spurious Correlation and Aitchison's Closure via Poisson-Aitchison-Ohta Triple Metrics.
# Itagaki-Egozcue-Unified-Pipeline (V1.2.2) 🚀
**Absolute-Scale Reconstruction & Orthonormal Geometric Mapping for Compositional Data**

Developed by **Tatsuki Itagaki**, this framework marks the **"Terminal Station"** for Static Compositional Data Analysis (CoDA). It merges the physical reality of **Absolute Basis Recovery** with the mathematical purity of **Egozcue's ILR (Isometric Log-Ratio) Transformation**.

## ⚖️ Scientific Philosophy
> "Compositional data (percentages) are a prison. To see the true 'Storm in the Teacup' (Absolute Mass), we must recover the lost Basis. By merging Basis Scaling with Orthonormal Geometry, we finally see the truth—not as a ratio, but as a physical entity."

## 🛠 Key Features
- **Itagaki Basis Scaling**: Reconstructs absolute total mass from relative abundance using the **Poisson-Aitchison-Ohta Triple Metric**.
- **Egozcue ILR Mapping**: Projects the recovered absolute data into an orthonormal Euclidean space, eliminating the "Closure" constraint.
- **AS-PCA (Absolute-Scale PCA)**: Performs Principal Component Analysis in the absolute dimension. Samples are separated by **True Physical Mass**, not just relative proportions.
- **Chaos Guard**: Automatically detects system collapse (Chaos Index > 0.7) and prevents physically meaningless interpretations.
- **Pure Base R**: Zero dependencies. Designed for reproducibility and academic integrity.

## 📊 Why This is the "Terminal Solution"
This pipeline utilizes 100% of the available information in static compositional data:
1. **Physical Limit**: Poisson Noise Floor (Minimum Variance).
2. **Geometric Limit**: Aitchison Simplex (Structural Entropy).
3. **Statistical Limit**: Ohta's CV-Asymmetry (Inferential Leverage).

## 🚀 Quick Start (English Code)

```R
# 1. Prepare your proportion matrix (Dataset)
# 2. Run Diagnosis & Basis Estimation
res_v8 <- diagnose_chaos_v8(Dataset)

# 3. Recover Absolute Geometry
abs_geo <- recover_absolute_basis(Dataset, res_v8)

# 4. Map to Orthonormal ILR Space
final_coords <- apply_itagaki_ilr(abs_geo)

# 5. Result: Absolute-Scale PCA
pca_res <- prcomp(final_coords)
plot(pca_res$x[,1:2], main="Absolute-Scale PCA (Itagaki-Egozcue Pipeline)")

📜 License
MIT License - Copyright (c) 2026 Tatsuki Itagaki
🎓 Academic Citation & Credits
This research is the original work of Tatsuki Itagaki. Please cite the following for any academic usage:
Methodology & Implementation (Unified Pipeline):
Itagaki, T. (2026). Deciphering Compositional Chaos Identifying Invariant Anchors and System Perturbations using Physics, Geometry, and Statistics.
DOI: 10.13140/RG.2.2.21953.93284
ResearchGate Method Page
Theoretical Foundation (CoDA Geometry):
Egozcue, J. J., et al. (2003). Isometric Logratio Transformations for Compositional Data Analysis.
Mathematical Anchor (CV Asymmetry):
Ohta, T. (2011). DOI: 10.1007/s11004-011-9332-y
Author: Tatsuki Itagaki
Copyright (c) 2026 Tatsuki Itagaki. All rights reserved.
"Even if it is an inconvenient truth, convey it as it is." — Tatsuki Itagaki

