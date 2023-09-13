# PVTrack
## Efficient 3D Human Tracking with Point-Video Transformer for Quadruped Robots in Complex Environment

In this work, a Point-Video-based Transformer Tracking model (PVTrack) is presented for quadruped robots. It is the first 3D tracking work that jointly incorporates the LIDAR modality and RGB-video modality together and achieves dual information complementarity. Moreover, PVTrack proposes a hierarchical Self and Cross Attention strategy for the encoder to overcome dynamic environments by capturing more target-aware information through a two-branch paradigm adaptively. Considering the violent shaking on robots and rugged terrains, a lateral human-ware proposal network is designed together with an anti-shake speed prediction module. It alleviates the disturbance caused by complex scenes as well as the particularity of the robot platform itself.

# Framework

# Visualization

# Citation
If you find PTTR useful, please consider citing
```
@inproceedings{PVTrack,
  title={Efficient 3D Human Tracking with Point-Video Transformer for Quadruped Robots in Complex Environment},
  author={XinShuo, Liu Yong},
  booktitle={2024 IEEE International Conference on Robotics and Automation (ICRA)},
  year={2024}
}
```
# Acknowledgement
This repo builds on top of [PTTR](https://github.com/Jasonkks/PTTR), pytorch implementation of [Point-MAE](https://github.com/Pang-Yatian/Point-MAE), and [MobileFormer](https://github.com/AAboys/MobileFormer). We wish to thank their contributions.
