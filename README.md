# TAP-Track: Generalizable Spacecraft Pose Tracking by Tracking Any Points

## 📝 Abstract

Recent learning-based spacecraft pose tracking methods have demonstrated impressive improvement in estimation accuracy and potential scalability to a complex space environment. However, most of them still rely on the detection of discriminative keypoints on a known 3-D model, limiting the generalization to unknown spacecraft. To this end, we propose, to the best of our knowledge, the first generalizable spacecraft pose tracking method. Instead of requiring a known model, we only assume the existence of at least one planar structure, for example, solar panels, which holds for most satellites in general scenes. Additionally, the proposed method tracks any points on the plane across multiframe followed by a re-projection error minimization, rather than detecting keypoints between image pairs, allowing robust capture of "long-term" temporal information among frames even for textureless surfaces without sufficient keypoints. Moreover, we also constructed the first large-scale dataset, G-SPET, for generalizable spacecraft pose estimation and tracking. It covers 174 satellites with diverse structures and rich annotations, increasing the number of targets in previous datasets by almost two orders of magnitude. Extensive evaluations on the proposed dataset have demonstrated the superiority of our method over state-of-the-art (SoTA) methods.

## 📦 Dataset: G-SPET

We construct **G-SPET**, the first large-scale dataset for generalizable spacecraft pose estimation and tracking. It covers **174 satellites** with diverse structures and rich annotations.

**To request access to the G-SPET dataset and TAP-Track python code, please contact us via email:**

📧 **Email:** [yatingliu@mail.nwpu.edu.cn]



## 📖 Citation

If you find this work useful in your research, please consider citing:

```bibtex
@article{liu2025tap,
  title={TAP-Track: Generalizable spacecraft pose tracking by tracking any points},
  author={Liu, Yating and Qi, Zhaoshuai and Chen, Pulin and Fan, Huilin and Zhu, Yu and Yang, Jiaqi and Zhang, Yanning},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  volume={63},
  pages={1--13},
  year={2025},
  publisher={IEEE}
}
