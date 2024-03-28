<div align="center" style="font-family: charter;">

<h1>Can 3D Vision-Language Models Truly Understand Natural Language?</h1>

<!-- <p>tl;dr: We build a platform that enables agents to scalably interact with the real-world in a virtual yet realistic environment.</p> -->
<div>
    <a href="https://github.com/VincentDENGP" target="_blank">Weipeng Deng</a><sup>1</sup>,</span>
    <a href="https://dingry.github.io/" target="_blank">Runyu Ding</a><sup>1</sup>,</span>
    <a href="https://jihanyang.github.io/" target="_blank">Jihan Yang</a><sup>1</sup>,</span>
    <a href="https://github.com/jliu-ac" target="_blank">Jiahui Liu</a><sup>1</sup>,</span>
    Yijiang Li<sup>2</sup>,</span>
    <div></div>
    <a href="https://xjqi.github.io/" target="_blank">Xiaojuan Qi</a><sup>1</sup>,</span>  
    Edith Ngai<sup>1</sup>,</span>
</div>

<div>
    <sup>1</sup>The University of Hong Kong&emsp;
    <sup>2</sup>Johns Hopkins University
</div>

[arXiv](https://arxiv.org/abs/2403.14760)

<img src="docs/resources/teaser.png" width="100%"/>

****
### Abstract
</div>

Rapid advancements in 3D vision-language (3D-VL) tasks have opened up new avenues for human interaction with embodied agents or robots using natural language. Despite this progress, we find a notable limitation: existing 3D-VL models exhibit sensitivity to the styles of language input, struggling to understand sentences with the same semantic meaning but written in different variants. This observation raises a critical question: **Can 3D vision-language models truly understand natural language?** To test the language understandability of 3D-VL models, we first propose a language robustness task for systematically assessing 3D-VL models across various tasks, benchmarking their performance when presented with different language style variants. Importantly, these variants are commonly encountered in applications requiring direct interaction with humans, such as embodied robotics, given the diversity and unpredictability of human language. We propose a 3D Language Robustness Dataset, designed based on the characteristics of human language, to facilitate the systematic study of robustness. Our comprehensive evaluation uncovers a significant drop in the performance of all existing models across various 3D-VL tasks. Even the state-of-the-art 3D-LLM fails to understand some variants of the same sentences. Further in-depth analysis suggests that the existing models have a fragile and biased fusion module, which stems from the low diversity of the existing dataset. Finally, we propose a training-free module driven by LLM, which improves language robustness. Dataset will be available.

****

### Release Checklist
- [ ] Datasets 
- [ ] Tools for building the datasets
  - [ ] Prompts
  - [ ] Codes
- [ ] Install & Deployment guideline

****

We will release the datasets first in the near future and providing you with more details later to assist in building your own dataset.
Please stay tuned...