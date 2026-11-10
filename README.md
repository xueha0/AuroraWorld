# AuroraWorld: Structured 4D World Modeling for Exo-to-Ego Video Generation in Robot Manipulation

**Hao Xue** · **Peng-Fei Zhang** · **Ying Cheng** · **Lanyun Zhu** · **Lei Zhu** · **Heng Tao Shen**

📄 **Paper:** [arXiv](https://arxiv.org/abs/2611.00177) · [PDF](https://arxiv.org/pdf/2611.00177)

---

## Overview

This repository is the official project repository for **"AuroraWorld: Structured 4D World Modeling for Exo-to-Ego Video Generation in Robot Manipulation"**.

**AuroraWorld** is a structured 4D world model that synthesizes egocentric (wrist-camera) manipulation videos from sparse exocentric observations.

It models the underlying embodied world through three complementary components: **spatial geometry**, **motion-stabilized temporal anchors**, and **robot motion trajectories**. These components guide video generation through sparse keyframe conditioning and **spatial-motion-aware structured noise initialization**, improving geometric consistency, temporal coherence, and the fidelity of robot-object interactions.

Experiments on **DROID**, **RLBench**, and the real-world **ARX X5** robot demonstrate improvements in exo-to-ego video generation and downstream visuomotor policy learning, highlighting AuroraWorld's potential as a data engine for robot manipulation.

## Status

🚧 **Code and usage instructions will be released soon.**

## Citation

If you find this work useful, please consider citing:

```bibtex
@article{xue2026auroraworld,
  title={AuroraWorld: Structured 4D World Modeling for Exo-to-Ego Video Generation in Robot Manipulation},
  author={Xue, Hao and Zhang, Peng-Fei and Cheng, Ying and Zhu, Lanyun and Zhu, Lei and Shen, Heng Tao},
  journal={arXiv preprint arXiv:2611.00177},
  year={2026}
}
```
