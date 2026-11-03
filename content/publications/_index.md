---
title: "Publications"
hidemeta: true
description: "Emma Huang's research publications."
---

<p class="research-subtitle"><em>* / ** denote equal contribution. Representative papers are shown below.</em></p>

<table class="publication-table">
<tbody>
<tr class="publication-row">
<td class="publication-thumb">
<a href="https://arxiv.org/abs/2607.26337" target="_blank" rel="noopener">
<img src="/reeling_grasp.png" alt="Reeling It In" loading="lazy" />
</a>
</td>
<td class="publication-details">
<a href="https://arxiv.org/abs/2607.26337" target="_blank" rel="noopener" class="papertitle">
Reeling It In: Flexible Needle Pick Up via Thread Manipulation for Autonomous Suturing
</a>
<div class="authors">
<strong>Emma Huang</strong>, Zih-Yun Chiu, Neelay Joglekar, Shanglei Liu, Michael C. Yip
</div>
<div class="venue">
<em>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</em>, 2026
</div>
<p class="paper-explanation">
Suture-needle pickup is necessary for autonomous suturing, as a needle can be unexpectedly dropped or strategically released to adjust the grasping configuration. Current methods for autonomous needle pickup typically guide a robot to move straight toward the needle and grasp it, limited to conditions where the needle is observable and directly approachable. In addition, grasping the needle lying on tissue can lead to the robot pinching nearby tissue or the needle jumping around due to its slippery surface, posing potential safety issues. This work proposes an autonomous framework that uses a suture thread as an assistive tool for indirect needle pickup, avoiding unnecessary tool-tissue contact and enabling pickup even when the needle is occluded or inaccessible. The framework spans the entire workflow, including thread and tissue reconstruction, safe grasp-point selection, stable thread lifting, and bimanual thread-following until securing needle grasping. The robot policies account for visual uncertainty to maximize robustness in real-world environments. We evaluate the proposed framework on a da Vinci Research Kit under various real-world conditions. The results demonstrate robust performance even with a challenging thread configuration or a non-approachable needle, closing the gap in applying autonomous robot policies to unstructured suturing environments.
</p>
</td>
</tr>

<tr class="publication-row">
<td class="publication-thumb">
<a href="https://arxiv.org/abs/2610.30452" target="_blank" rel="noopener">
<img src="/CT_coverfig.png" alt="Autonomous Needle Insertion Via CT Bore Robotic Arm" loading="lazy" />
</a>
</td>
<td class="publication-details">
<a href="https://arxiv.org/abs/2610.30452" target="_blank" rel="noopener" class="papertitle">
Integrated Respiratory Sensing and Gated Control for Autonomous Needle Insertion Via CT Bore Robotic Arm
</a>
<div class="authors">
<strong>Emma Huang*</strong>, Moira Bohley*, Krishna Jamakhandi**, Rebecca Fellbaum**, Sophia Tang, Sean Tutton, Albert Hsiao, Alexander Norbash, Changwei Chen, Derek Chen, Ananya Rao, Lizzie Peiros, Michael C. Yip
<span class="author-note">(* / ** denote equal contribution)</span>
</div>
<div class="venue">
<em>Under review for ICRA 2027</em>, 2026
</div>
<p class="paper-explanation">
Currently, CT-guided lung biopsy is a highly manual procedure requiring patient breath-holding, iterative manual needle insertions, and repeated CT confirmation scans to accurately target a tumor. Automating this process within the CT bore—without relying on manual needle placement or patient breath-holding—has the potential to reduce procedure time, patient discomfort, and radiation exposure. In this work, we present an integrated sensing and control system capable of performing a gated needle insertion within the CT bore. The experiments demonstrate the system's ability to track and predict patient breath cycles, perform autonomous respiratory-gated needle insertions, and detect anomalies within the breathing cycle.
</p>
</td>
</tr>

<tr class="publication-row">
<td class="publication-thumb">
<a href="https://arxiv.org/abs/2610.30694" target="_blank" rel="noopener">
<img src="/live_showcase.png" alt="Live Thread Reconstruction" loading="lazy" />
</a>
</td>
<td class="publication-details">
<a href="https://arxiv.org/abs/2610.30694" target="_blank" rel="noopener" class="papertitle">
Live Thread Reconstruction for Autonomous Manipulation
</a>
<div class="authors">
<strong>Emma Huang</strong>, Omar Hernandez, Zih-Yun Chiu, Michael Yip
</div>
<div class="venue">
<em>IROS DOM-R3 Workshop</em>, 2026
</div>
<p class="paper-explanation">
Autonomous robotic surgery has drawn increased attention in recent years due to its potential to relieve surgeons of time-consuming, mentally straining, and tedious tasks, particularly during prolonged operations. One suitable task for automation is suturing, which involves tracking the thread as it deforms during needle retrieval, de-tangling, knot tightening, and other tasks. Unlike rigid-object manipulation, deformable thread manipulation has no fixed pose to track and effectively infinite degrees of freedom, making its configuration difficult to predict and requiring the thread's state to be re-estimated rather than assumed. At the same time, thread manipulations involve sequential motions that depend on past and current thread contact points, which must be accurately and continuously tracked. This paper presents an image-to-manipulation pipeline that concurrently generates live thread reconstruction while conducting safe and optimized sequential manipulations to achieve long-horizon tasks.
</p>
</td>
</tr>

<tr class="publication-row">
<td class="publication-thumb">
<a href="/papers/paper4/">
<img src="/real_cover.png" alt="Real-time Thread Reconstruction" loading="lazy" />
</a>
</td>
<td class="publication-details">
<a href="/papers/paper4/" class="papertitle">
Real-time Thread Reconstruction for Autonomous Suture Thread and Needle Manipulation
</a>
<div class="authors">
<strong>Emma Huang</strong>, Omar Hernandez, Zakai Liang, Zih-Yun Chiu, Michael Yip
</div>
<div class="venue">
<em>Under review for IEEE Robotics and Automation Letters (RA-L)</em>, 2026
</div>
<p class="paper-explanation">
Autonomous robotic surgery requires robust tracking of deformable suture threads during sequential manipulation tasks such as needle retrieval, de-tangling, and knot tightening. This work presents an autonomous thread reconstruction framework that builds upon prior work with autonomous segmentation, keypoint ordering, and real-time tracking to drive manipulation strategies for needle pick up, thread untangling, and tightening. The thread reconstruction remains consistent through common surgical manipulations while handling tool occlusions and self-intersections causing ambiguity, demonstrating a 25.8% improvement in needle pick up trials and an 88.9% average task completion success rate.
</p>
</td>
</tr>
</tbody>
</table>