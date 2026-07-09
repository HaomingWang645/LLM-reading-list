introductory text: current sota vlm can achieve near-human capability in semantic understand (you may already feeled that in your daily life), but for understanding the 3d spatial information (e.g. geomery of objects, objects relative locations and movements), which is intuitive for human, is difficult for vlm. (performance gap.jpg)

to quantify the model's spatial capability, the standard way to construct benchmark data is to formulate different spatial tasks into VQA (ask the model to ask a numerical or multi-choice question give image/video inputs) (spatial tasks vsibench)

example: results in vsi-bench (vsi_results.png) both open-source and closed sourced model evovle rapiadly but spatial reasoning is still an unsolved problem for them

reading:
VSI-bench: https://arxiv.org/pdf/2603.05591
omini-spatial: https://arxiv.org/pdf/2506.03135
MMSI-bench: https://arxiv.org/pdf/2505.23764