# MobileViT

## Overview

This is a PyTorch implementation of MobileViT specified in "[MobileViT: Light-weight, General-purpose, and Mobile-friendly Vision Transformer](https://arxiv.org/abs/2110.02178)", arXiv 2021.

![img](https://user-images.githubusercontent.com/67839539/136470152-2573529e-1a24-4494-821d-70eb4647a51d.png)


## Usage

```python
import torch
from mobilevit import mobilevit_xxs

net = mobilevit_xxs()
img = torch.randn(1, 3, 256, 256)
out = net(img)
```

## Citation

```bibtex
@article{mehta2021mobilevit,
  title={MobileViT: Light-weight, General-purpose, and Mobile-friendly Vision Transformer},
  author={Mehta, Sachin and Rastegari, Mohammad},
  journal={arXiv preprint arXiv:2110.02178},
  year={2021}
}
```

## Credits

Code adapted from [MobileNetV2](https://github.com/tonylins/pytorch-mobilenet-v2) and [ViT](https://github.com/lucidrains/vit-pytorch).
