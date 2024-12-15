## Supplementary Materials
Supplementary Materials for paper: **Stealthy and Effective Physical Adversarial Attacks in Autonomous Driving**

There are three videos:
- Human Vision.mp4 : We used video shot at a shutter speed of 1/30s to **simulate the human eye's perception** of our attack, and it's clear to see that our adversarial video is **almost invisible for human**, showing **strong stealthy**.
- Camera Vision.mp4 : We used video shot at a shutter speed of 1/90s to simulate the perception of a camera in an autonomous driving scenario, at high shutter settings, **adversarial samples embedded in the video can be observed** to influence the decision of the autopilot system. In this video, you can also see two phenomena, **rainbow effect and screen distortion**, which we mentioned in the simulation projection. In addition, this video was fed into well trained YOLOv5 network, and **the predictions show an ultra-high ASR for our targeted attack**.
- Move_Camera.mp4 : Consistent with the setup employed in Camera Vision.mp4, this time we **change the position and angle of the camera relative to the traffic sign**, and the predictions of YOLOv5 demonstrate the **robustness and effectiveness** of our attack.

## Code
Our implementation with codes is available upon request or acceptance.

## Cite
```
@article{journals/tifs/2024.3422920,
  author       = {Man Zhou and
                  Wenyu Zhou and
                  Jie Huang and
                  Junhui Yang and
                  Minxin Du and
                  Qi Li},
  title        = {Stealthy and Effective Physical Adversarial Attacks in Autonomous
                  Driving},
  journal      = {{IEEE} Trans. Inf. Forensics Secur.},
  year         = {2024},
  url          = {https://doi.org/10.1109/TIFS.2024.3422920}
}
```
