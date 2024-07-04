# DotaMath: Decomposition of Thought with Code Assistance and Self-correction for Mathematical Reasoning

*Chengpeng Li, Guanting Dong, Mingfeng Xue, Ru Peng, Xiang Wang, Dayiheng Liu*

University of Science and Technology of China

Qwen, Alibaba Inc.

---



<p>
📃 <a href="">ArXiv Paper</a>
  •
📚 <a href="">Dataset</a>
</p>




![image](https://github.com/dongguanting/DotaMath/assets/60767110/92339cd7-80a0-4db7-b6d5-40a0f98c12d1)


⭐ **We will release the templates, and codes soon. Thanks for your attention!**

## Introduction
Large language models (LLMs) have made impressive progress in handling simple math problems, yet they still struggle with more challenging and complex mathematical tasks. In this paper, we introduce a series of LLMs that employs the Decomposition of thought with code assistance and self-correction for mathematical reasoning, dubbed as DotaMath. DotaMath models tackle complex mathematical tasks by decomposing them into simpler logical subtasks, leveraging code to solve these subtasks, obtaining fine-grained feedback from the code interpreter, and engaging in self-reflection and correction. By annotating diverse interactive tool-use trajectories and employing query evolution on GSM8K and MATH datasets, we generate an instruction fine-tuning dataset called DotaMathQA with 574K query-response pairs. We train a series of base LLMs using imitation learning on DotaMathQA, resulting in DotaMath
models that achieve the remarkable performance compared to open-source LLMs across various in-domain and out-of-domain benchmarks. Notably, DotaMath-deepseek-7B showcases an outstanding performance of 64.8% on the competitive MATH dataset and 86.7% on GSM8K. Besides, DotaMath-deepseek-7B maintains strong competitiveness on a series
of in-domain and out-of-domain benchmarks (Avg. 80.1%). Looking forward, we anticipate that the DotaMath paradigm will open new pathways for addressing intricate mathematical problems.

## Citation
