# Visual representation learning

| Title | Motivation | Method | Conclusion | Application | Year | Limitation | Comment |
| - | - | - | - | - | - | - | - |
| A Simple Framework for Contrastive Learning of Visual Representations [[Paper]](https://arxiv.org/pdf/2002.05709.pdf) | Simply recently proposed contrastive self-supervised learning algorithms without specialized architectures of a memory bank. | Input, Data augmentation, Base encoder, Projection head, Contrastive loss | 1) Composition of data augmentation plays a critical role. 2) Introducing a learnable transformation (projection head) substantially improves the quality of learned representations. 3) Contrastive learning benefits from larger batch sizes and more training steps compared with supervised learning. | Image classification | 2020 | | A very useful blog to explain the paper at [[here]](https://amitness.com/2020/03/illustrated-simclr/)
| Momentum contrast for unsupervised visual representation learning [[Paper]](https://arxiv.org/pdf/1911.05722.pdf)| 
