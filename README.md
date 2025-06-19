# Artificial-Intelligence-Hub
A curated collection of top resources covering various aspects of Artificial Intelligence. Being curated by [Sandip Palit](https://www.linkedin.com/in/sandip-palit/) during his AI learning journey, this repo offers a structured path to help learners and enthusiasts navigate the vast world of AI with clarity.

---

## Table of Contents

- [You Only Look Once](#you-only-look-once)

---

## You Only Look Once

### Research Articles

* [**You Only Look Once: Unified, Real-Time Object Detection**](https://arxiv.org/pdf/1506.02640)  ⭐

  This paper framed object detection as a regression problem to bounding boxes and class probabilities.
It built a single CNN that simultaneously predicts multiple boxes and classes in one pass.
It introduced YOLO, which runs at 45 FPS in real time but struggled with localization of small objects.
The model achieved 88% top-5 accuracy on ImageNet 2012 validation after one week of training.
At test time, box confidences were computed by multiplying conditional class probabilities and IoU.

* [**YOLOv3: An Incremental Improvement**](https://arxiv.org/pdf/1804.02767)

  This paper followed YOLO9000 and introduced anchor boxes with dimension clusters.
It redesigned class prediction using binary cross-entropy with independent logistic classifiers.
YOLOv3 predicted at 3 different scales using a Feature Pyramid Network–like architecture.
The new backbone combined Darknet-19 with residual network principles for improved accuracy.
At 320x320, YOLOv3 achieved 28.2 mAP and 22 ms inference speed, balancing speed and accuracy.

* [**YOLOv4: Optimal Speed and Accuracy of Object Detection**](https://arxiv.org/pdf/2004.10934)

  This paper optimized object detection for fast production speed and parallel computation.
It used CSPDarknet53 as backbone, SPP & PAN as neck, YOLOv3 head with many BoF & BoS tricks.
Training tricks included CutMix, Mosaic, DropBlock, CIoU-loss, and cosine LR scheduling.
Self-Adversarial Training (SAT) was used to improve robustness against input perturbations.
Hyperparameters were fine-tuned using genetic algorithms, achieving state-of-the-art results.

* [**YOLOv6: A Single-Stage Object Detection Framework for Industrial Applications**](https://arxiv.org/pdf/2209.02976)

  This paper redesigned network scales from small to large, optimized for industrial scenarios.
It used self-distillation for classification and regression tasks for better learning efficiency.
Advanced techniques for label assignment, losses, and data augmentation were selectively applied.
RepOptimizer-based quantization and channel-wise distillation improved speed and accuracy.
It achieved 43.3% COCO AP and 869 FPS throughput at batch size 32, excelling in fast inference.

* [**A Comprehensive Review of YOLO Architectures in Computer Vision: From YOLOv1 to YOLOv8 and YOLO-NAS**](https://arxiv.org/pdf/2304.00501)  ⭐

  This paper reviewed YOLO evolution from YOLOv1 to YOLO-NAS, detailing architectural changes.
YOLOv1 unified detection as a single-stage grid-based regression with SxS outputs.
YOLOv2 added batch norm, anchor boxes, dimension clusters, multi-scale training, and passthrough layers.
YOLOv3 introduced better backbones (Darknet-53), multi-scale predictions, and objectness scores.
YOLOv4-v8 brought advanced training techniques, novel losses, PAN necks, CSP blocks, SAT, and SOTA results.


---

**Kindly star this repository and share it with your friends.**
_If you have any questions or feedback, please contact me on [LinkedIn](https://www.linkedin.com/in/sandip-palit/)._
