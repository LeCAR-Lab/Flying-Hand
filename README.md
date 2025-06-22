<h1 align="center">
  <br>
  Flying Hand: End-Effector-Centric Framework for Versatile Aerial Manipulation Teleoperation and Policy Learning
  <br>
</h1>

<p align="center">
  <a href="https://lecar-lab.github.io/flying_hand/">Project Page</a> •
  <a href="https://arxiv.org/abs/2504.10334">arXiv</a> •
  <a href="https://lecar-lab.github.io/flying_hand/#video">Video</a> •
  <a href="#citation">BibTeX</a>
</p>

<p align="center">
  <img src="./assets/flying_hand_teaser.gif" width="70%">
</p>



**Flying Hand** enables aerial robots to perform complex long horizon manipulation tasks—such as turning a valve or changing a lightbulb—through a unified, end-effector-centric control and learning framework. This system supports both expert teleoperation and autonomous policy learning.

---

## Abstract

Aerial manipulation has recently attracted increasing interest from both industry and academia. Previous approaches have demonstrated success in various specific tasks. However, their hardware design and control frameworks are often tightly coupled with task specifications, limiting the development of cross-task and cross-platform algorithms. Inspired by the success of robot learning in tabletop manipulation, we propose a unified aerial manipulation framework with an end-effector-centric interface that decouples high-level platform agnostic decision-making from task-agnostic low-level control. Our framework consists of a fully-actuated hexarotor with a 4-DoF robotic arm, an end-effector-centric whole-body model predictive controller, and a high-level policy. The high-precision end-effector controller enables efficient and intuitive aerial teleoperation for versatile tasks and facilitates the development of imitation learning policies. Real-world experiments show that the proposed framework significantly improves end-effector tracking accuracy, and can handle multiple aerial teleoperation and imitation learning tasks, including writing, peg-in-hole, pick and place, changing light bulbs, etc. We believe the proposed framework provides one way to standardize and unify aerial manipulation into the general manipulation community and to advance the field.

---

## TODO
Opensource list:
- [] hardware design
- [] mujoco simulation
- [] MPC controller

---

## Citation

If you find our work useful, please cite us:

```bibtex
@misc{he2025flyinghandendeffectorcentricframework,
  title={Flying Hand: End-Effector-Centric Framework for Versatile Aerial Manipulation Teleoperation and Policy Learning}, 
  author={Guanqi He and Xiaofeng Guo and Luyi Tang and Yuanhang Zhang and Mohammadreza Mousaei and Jiahe Xu and Junyi Geng and Sebastian Scherer and Guanya Shi},
  year={2025},
  eprint={2504.10334},
  archivePrefix={arXiv},
  primaryClass={cs.RO},
  url={https://arxiv.org/abs/2504.10334}
}
