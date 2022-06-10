# Adversarial Representation Teaching with Perturbation-agnostic Student-Teacher Structure for Semi-supervised Learning
ImageNet experimental results with aversarial representation teaching (ART)

## Classification error rate on the ImageNet
### ImageNet 10% semi-supervised learning (SSL) results
Cartegories | Methods | Backbone | 10%
|---|---|---|---|
| Label Propagation: | MPL| ResNet50 | 22.3
| Representation Learning: | BYOL | ResNet-200x2 | 22.3
| | SimCLR | ResNet-50x4 | 25.6
| | SimCLRv2 | ResNet-152x3, SK | 19.1
| | PAWS | ResNet-50x4 | 21.0
| | ART-56 epochs | ResNet-50x4 | 36.9

### Update history
Epochs | 1%  | 10% | date
---|---|---|---|
5     | -   | 53.6 | 2022-05-29
30    | -   | 39.3 | 2022-05-29
56    | -   | 36.9 | 2022-06-08

We will upload the code as soon as possible.
