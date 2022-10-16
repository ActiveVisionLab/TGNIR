---
layout: index
title: "Towards Generalising Neural Implicit Representations"
---

<iframe src="assets/presentation.mp4" frameborder="0" allowfullscreen></iframe>


## Abstract
Neural implicit representations have shown substantial improvements in efficiently storing 3D data, when
compared to conventional formats.
However, the focus of existing work has mainly been on storage and subsequent reconstruction.
In this work, we show that training neural representations for reconstruction tasks alongside
conventional tasks can produce more general encodings that admit equal quality reconstructions to single
task training, whilst improving results on conventional tasks when compared to single task encodings.
We reformulate the semantic segmentation task, creating a more representative task for implicit
representation contexts, and through multi-task experiments on reconstruction, classification, and
segmentation, show our approach learns feature rich encodings that admit equal performance for each
task.
Further, through hold-out experiments, we show that adding semantic supervision when training implicit
encoders can significantly improve performance on later unseen tasks, without requiring encoder
retraining.

## Code

The code will be released soon.

## Paper
A copy of the paper can be found [here](assets/paper.pdf)

## Citation

BiBTeX:

```
@article{howard2021lalaloc,
  title={LaLaLoc: Latent Layout Localisation in Dynamic, Unvisited Environments},
  author={Howard-Jenkins, Henry and Ruiz-Sarmiento, Jose-Raul and Prisacariu, Victor Adrian},
  booktitle={Proceedings of the IEEE International Conference on Computer Vision},
  pages={},
  year={2021}
}
```