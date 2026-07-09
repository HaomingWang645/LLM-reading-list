The most intuitive thought is that current vlm perform bad in spatial reasoing because in their pretraining data most just annotate the semantic, data with 3d spatial annotation is rare. this indicates that spatial reasoning can be solved if we have enough spatial vqa data to train the model. to solve the data scarcity, many exisitng works developed pipeline to automatically generate spatial vqa data for model fine-tuning

(automatic label.png)

although this method can improve the performance, an interesting finding is that spatial reasoning capability seems to emerge/scale significantly slower than other capability (scale-training data.jpg)

there could be a lot of reasoning behind this finding. for example, vqa data is a weak signal as the qa provide very little spatial information compared with the detailed geometry of the scene shown in the video so that the model overly focus on the text or even find some shorcuts from the text instead of reasoning from the visual inputs

reading:
SpatialVLM: Endowing Vision-Language
Models with Spatial Reasoning Capabilities (https://arxiv.org/pdf/2401.12168)
Cambrian-S: Towards Spatial Supersensing in Video (https://arxiv.org/abs/2511.04670)
Learning to Localize Objects Improves Spatial Reasoning in Visual-LLMs (https://arxiv.org/pdf/2404.07449)
Scaling Spatial Intelligence with Multimodal Foundation Models (https://arxiv.org/pdf/2511.13719)
How Far are VLMs from Visual Spatial
Intelligence? A Benchmark-Driven Perspective (https://arxiv.org/pdf/2509.18905)
Visual Spatial Tuning (https://arxiv.org/pdf/2511.05491)