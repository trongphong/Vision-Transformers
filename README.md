# Vision Transformers Models
## ViT Classification models (ViT)
As the transformer architecture in Nlp, the same architecture was appiled to images by creating small patches of the images and treating them as token. ViT decomposes each image into a sequence of token (non-overlapping patches) with a fixed length and the applies multiple standard Transformer layers, consisting of Multi-head Self Attention and Position-wise Feed-forward module to model global relations for classification. [Link HunggingFace](https://huggingface.co/docs/transformers/tasks/image_classification)
## Swin Transformers models for multi-label classification
Swin transformer architecture optimizers for latency and performance using a shifted window approach which reduces the number of operation required. Swin is considered a hierarchical backbone for computer vision. Swin can be used for tasks like image classification.
## Convolutional Vision Transformer (CvT)
CvT employs all the benefits of CNN: local receptive fields, shared weights and spatial subsampling along with shift, distortion invariance while keeping merits of Transformers: dynamic attention, global  context fusion,  and better generalization. Furthermore, due to buoilt-in local context structure introduced by convolutions, CvT no longer requires a position embedding, giving it a potential advantage for adaption to a wide rang of vision tasks requiring variable input resolution.
## DEtection Transformers
DETR simplifies the detector by using an encode-decoder transformer after the feature extraction backbone to directly predict bounding boxes in parallet, requiring minimal post-processing.
