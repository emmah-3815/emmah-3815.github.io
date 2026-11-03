---
title: "Reeling It In: Flexible Needle Pick Up via Thread Manipulation for Autonomous Suturing" 
date: 2026-07-01
tags: ["robotics","autonomous suturing","surgical robotics","thread manipulation","computer vision"]
author: ["Emma Huang","Zih-Yun Chiu","Neelay Joglekar","Shanglei Liu","Michael C. Yip"]
description: "This paper presents a method for flexible needle pick up via thread manipulation for autonomous suturing. Published at IEEE/RSJ IROS, 2026." 
summary: "Image to robot motion pipeline for autonomous needle pick up: SAM segmentation → point cloud reconstruction (RAFT-stereo) → 3D B-Spline fitting → intersection/reliability calculations → grasping goal selection → robot motion planning. 61% full pipeline success, 91% reconstruction success." 
cover:
    image: "paper1.png"
    alt: "Flexible Needle Pick Up via Thread Manipulation"
    relative: true
editPost:
    URL: "https://arxiv.org/abs/2607.26337"
    Text: "IEEE/RSJ IROS 2026"

---

---

##### Download

+ [Paper](paper1.pdf)
+ [arXiv](https://arxiv.org/abs/2607.26337)

---

##### Abstract

Image to robot motion pipeline written in Python and C++ on the da Vinci Research Kit (dVRK): SAM segmentation → point cloud reconstruction (RAFT-stereo) → 3D B-Spline fitting → Open3D integration → intersection/reliability calculations → dependency aware grasping goal selection → robot motion planning. Achieved 61% full pipeline success and 91% reconstruction success. Accepted to IROS 2026.

---

##### Citation

Huang, Emma, Zih-Yun Chiu, Neelay Joglekar, Shanglei Liu, and Michael C. Yip. 2026. "Reeling It In: Flexible Needle Pick Up via Thread Manipulation for Autonomous Suturing." *IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*.

```latex
@article{huang2026reelinginflexibleneedle,
      title={Reeling It In: Flexible Needle Pick Up via Thread Manipulation for Autonomous Suturing}, 
      author={Emma Huang and Zih-Yun Chiu and Neelay Joglekar and Shanglei Liu and Michael C. Yip},
      year={2026},
      journal={IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
      url={https://arxiv.org/abs/2607.26337},
}
```

---

##### Related material

+ [Presentation slides](presentation1.pdf)
