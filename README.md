# Awesome BERT and computer vision
Curated list of methods using images along with a BERT model.
This list is ordered by submission month to arXiv. Feel free to PR new papers.
All images are on courtesy of the paper corresponding to their paragraph.

## [ViLBERT](https://arxiv.org/abs/1908.02265)
Published at NeurIPS 2019.

![ViLBERT](images/vilbert1.png)

Co-attention between two parallel streams. New form of co-attention mechanism that operates on Transformer as seen below.

![ViLBERT](images/vilbert2.png)

## [VisualBERT](https://arxiv.org/abs/1908.03557)

![VisualBERT](images/visualbert.png)

Append to word tokens the ROI features.

## [B2T2](https://arxiv.org/abs/1908.05054)
Published at EMNLP 2019.

![B2T2](images/b2t2.png)

1) Late fusion: ONE image is injected with a gating mechanism on the BERT hidden states. 2) Early fusion: ROI are injected between word tokens 


## [Unicoder-VL](https://arxiv.org/abs/1908.06066)
Published at AAAI 2020

![Unicoder VL](images/unicoder.png)

## [LXMERT](https://arxiv.org/abs/1908.07490)
Published at EMNLP 2019

![LXMERT](images/lxmert.png)


## [VL-BERT](https://arxiv.org/abs/1908.08530)
Published at EMNLP 2019

![VL-BERT](images/vlbert.png)

Visual feature provided at each token

## [Unified-VLP](https://arxiv.org/abs/1909.11059)
Published at AAAI 2020

![Unified-VLP](images/UNIFIED_VLP.png)




## [UniTER](https://arxiv.org/abs/1909.11740)
Published at EMNLP 2019

![UniTER](images/uniter.png)

Word region alignment + Image-text maching

## [12-in-1](https://arxiv.org/abs/1912.02315)
Published at EMNLP 2019

Same model as ViLBERT with multi-task learning on several tasks and datasets.

## [ImageBERT](https://arxiv.org/pdf/2001.07966.pdf)
![ImageBERT](images/imagebert.png)

Prepend tokens with ROI + position of the ROI

## [Oscar](https://arxiv.org/abs/2004.06165)
Published at EMNLP 2019

![Oscar](images/oscar.png)

Object tags are used as an anchor between caption and image regions. Trained with:

1. Masked Token Loss
2. Contrastive loss, actually BCE, to measure similarity between image/caption




