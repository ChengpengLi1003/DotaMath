 # <div align="center"> 🔥DotaMath: Decomposition of Thought with Code Assistance and Self-correction for Mathematical Reasoning <div>

<p align="center">
 
**Chengpeng Li, Guanting Dong, Mingfeng Xue, Ru Peng, Xiang Wang, Dayiheng Liu**

University of Science and Technology of China

Qwen, Alibaba Inc.

</p align="center">


<p align="center">
📃 <a href="https://arxiv.org/pdf/2407.04078">ArXiv Paper</a>  • 🤗 <a href="https://huggingface.co/datasets/dongguanting/DotamathQA">Dataset (Huggingface)</a>  • 📚 <a href="https://drive.google.com/drive/folders/1Hwey6ovYU2ERVox76e-3JTsJBe_PHOl6?usp=sharing">Dataset (Google drive)</a>
</p align="center">

---

If you find this work helpful for your research, please kindly cite it.


```bibtex
@article{li2024dotamath,
  author       = {Chengpeng Li and
                  Guanting Dong and
                  Mingfeng Xue and
                  Ru Peng and
                  Xiang Wang and
                  Dayiheng Liu},
  title        = {DotaMath: Decomposition of Thought with Code Assistance and Self-correction
                  for Mathematical Reasoning},
  journal      = {CoRR},
  volume       = {abs/2407.04078},
  year         = {2024},
  url          = {https://doi.org/10.48550/arXiv.2407.04078},
  doi          = {10.48550/ARXIV.2407.04078},
  eprinttype    = {arXiv},
  eprint       = {2407.04078},
  timestamp    = {Wed, 07 Aug 2024 21:29:45 +0200},
  biburl       = {https://dblp.org/rec/journals/corr/abs-2407-04078.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```
---

## 💥 News

- [12/2024] 🔥 We released our ***DotaMathQA*** dataset! Download [🤗 DotaMathQA (huggingface)](https://huggingface.co/datasets/dongguanting/DotamathQA)  [📚 DotaMathQA (google drive)](https://drive.google.com/drive/folders/1Hwey6ovYU2ERVox76e-3JTsJBe_PHOl6?usp=sharing) here. 
- [07/2024] 🔥 We introduce ***DotaMath***, a series of LLMs that employs the Decomposition of thought with code assistance and self-correction for mathematical reasoning. Check out the [paper](https://arxiv.org/pdf/2407.04078). 



## Introduction
Large language models (LLMs) have made significant strides in solving simple math problems but still struggle with complex tasks. This paper presents DotaMath, a series of LLMs that utilize thought decomposition, code assistance, and self-correction for mathematical reasoning. DotaMath tackles complex problems by breaking them down into simpler subtasks, using code to solve these subtasks, receiving detailed feedback from the code interpreter, and engaging in self-reflection. By annotating diverse interactive tool-use trajectories and applying query evolution on the GSM8K and MATH datasets, we create an instruction fine-tuning dataset called DotaMathQA, consisting of 574K query-response pairs. We train several base LLMs using imitation learning on DotaMathQA, resulting in models that outperform open-source LLMs on various benchmarks. Notably, DotaMath-deepseek-7B achieves 64.8% on the MATH dataset and 86.7% on GSM8K, maintaining strong competitiveness across multiple benchmarks (Avg. 80.1%). We believe the DotaMath paradigm will pave the way for tackling intricate mathematical problems.

## Overall Framework
![image](https://github.com/dongguanting/DotaMath/assets/60767110/b47403d4-1367-46be-9c13-c465160195a3)
![image](https://github.com/dongguanting/DotaMath/assets/60767110/5c6b9396-875a-489b-adfe-d95d68b038f7)

## Main Result
![image](https://github.com/dongguanting/DotaMath/assets/60767110/cccfb95c-8cb5-44eb-8088-5602873295ee)




