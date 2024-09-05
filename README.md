# End-to-End Path Planning using Stitched Surround View Images and 2D Object Bounding Boxes

Liguo Zhou, Zhuting Xue, Huaming Liu, Alois Knoll

Autonomous driving technologies promise to revolutionize the way we navigate, offering safer and more efficient transportation solutions. Particularly, end-to-end autonomous driving systems, which process inputs directly into waypoints or steering commands, represent a significant advancement in this field. This article presents a novel approach to end-to-end autonomous driving that leverages vision and Transformer-based technologies to navigate. Our method incorporates dual Transformer encoders, one for images and another for past states, enabling nuanced interpretations of spatial and temporal elements. The integration of a Vision Transformer as the image encoder enhances visual processing capabilities, critical for autonomous navigation. We further advanced our model by integrating object detection model for superior object detection, enriching the ability of the model for improved situational awareness and collision avoidance. Innovations such as gated cross attention in the decoder refine attention mechanisms, enhancing focus on relevant scenarios during driving. Validated on the large-scale nuScenes dataset, our model demonstrates substantial improvements over existing methods in L2 loss and collision rates, affirming the effectiveness of our design in real-world conditions.

https://github.com/zhouliguo/research/blob/master/e2epathplanning.pdf

# Residual Coordinate Chain Prediction for Autonomous Driving Path Planning

Liguo Zhou, Jiacheng Zhang, Tongtong Xie, Yirui Zhou, Alois Knoll

```
@article{zhou2024residual,
  title={Residual Chain Prediction for Autonomous Driving Path Planning},
  author={Zhou, Liguo and Zhou, Yirui and Liu, Huaming and Knoll, Alois},
  journal={arXiv preprint arXiv:2404.05423},
  year={2024}
}
```