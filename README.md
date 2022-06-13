# Adversarial Representation Teaching with Perturbation-agnostic Student-Teacher Structure for Semi-supervised Learning
ImageNet experimental results with aversarial representation teaching (ART)

## Classification error rate (%) on the ImageNet
### ImageNet 10% semi-supervised learning (SSL) results
Cartegories | Methods | Backbone | 1% | 10%
|---|---|---|---|---|
| Label Propagation: | [MPL](https://arxiv.org/abs/2003.10580) | ResNet-50 | - |22.3
| Representation Learning: | [BYOL](https://arxiv.org/abs/2006.07733) | ResNet-200x2 | - | 22.3
| | [SimCLR](https://arxiv.org/abs/2002.05709) | ResNet-50x4 | - | 25.6
| | [SimCLRv2](https://arxiv.org/abs/2006.10029) | ResNet-152x3, SK | - | 19.1
| | [PAWS](https://arxiv.org/abs/2104.13963) | ResNet-50x4 | - | 21.0
| | ART-56 epochs | ResNet-50x4 | - | 36.9

### Update history
Epochs | 1%  | 10% | date
---|---|---|---|
5     | -   | 53.6 | 2022-05-29
30    | -   | 39.3 | 2022-05-29
56    | -   | 36.9 | 2022-06-08
60    | -   | 35.1 | 2022-06-12

We will upload the code as soon as possible.
