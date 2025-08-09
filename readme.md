# Paper List for AutoML & LLM

<!-- omit in toc -->

## Contents
- [Paper List for AutoML \& LLM](#paper-list-for-automl--llm)
  - [Contents](#contents)
  - [Introduction](#introduction)
    - [Keywords Convention](#keywords-convention)
  - [Papers](#papers)
    - [Survey](#survey)
    - [System](#system)
      - [Search Space Compression](#search-space-compression)
      - [FE](#fe)
    - [BO](#bo)

## Introduction

This is a paper list (working in progress) about **AutoML and LLM**


### Keywords Convention

![](https://img.shields.io/badge/MetaICL-DCE7F1) abbreviation

![](https://img.shields.io/badge/MetaTraining-D8D0E1) main feature

![](https://img.shields.io/badge/NeurIPS2025-FAEFCA) conference

## Papers

### Survey

1. **AutoML in the Age of Large Language Models: Current Challenges, Future Opportunities and Risks.** ![](https://img.shields.io/badge/survey-DCE7F1), ![](https://img.shields.io/badge/arxiv2023-FAEFCA), 2023.06
   *Alexander Tornede, Difan Deng, Theresa Eimer, Joseph Giovanelli, Aditya Mohan, Tim Ruhkopf, Sarah Segel, Daphne Theodorakopoulos, Tanja Tornede, Henning Wachsmuth, Marius Lindauer*.  [[pdf](https://arxiv.org/abs/2306.08107)]


### System
1. **AutoKaggle: A Multi-Agent Framework for Autonomous Data Science Competitions.** ![](https://img.shields.io/badge/AutoKaggle-DCE7F1), ![](https://img.shields.io/badge/arxiv2024-FAEFCA), 2024.11
   *Ziming Li, Qianbo Zang, David Ma, Jiawei Guo, Tuney Zheng, Minghao Liu, Xinyao Niu, Yue Wang, Jian Yang, Jiaheng Liu, Wanjun Zhong, Wangchunshu Zhou, Wenhao Huang, Ge Zhang*. [[pdf](https://arxiv.org/abs/2410.20424)], [[project](https://github.com/multimodal-art-projection/AutoKaggle)]


#### Search Space Compression
1. **Design Principle Transfer in Neural Architecture Search via Large Language Models** ![](https://img.shields.io/badge/LAPT-DCE7F1), ![](https://img.shields.io/badge/AAAI2025-FAEFCA)
   *Xun Zhou, Xingyu Wu, Liang Feng, Zhichao Lu, Kay Chen Tan* [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/34463)]

#### FE
1. **Large Language Models for Automated Data Science: Introducing CAAFE for Context-Aware Automated Feature Engineering.** ![](https://img.shields.io/badge/CAAFE-DCE7F1), ![](https://img.shields.io/badge/NeurIPS2023-FAEFCA)
    *Noah Hollmann, Samuel Müller, Frank Hutter.* [[pdf](https://proceedings.neurips.cc/paper_files/paper/2023/hash/8c2df4c35cdbee764ebb9e9d0acd5197-Abstract-Conference.html)], [[project](https://github.com/noahho/CAAFE)]

   
### BO
1. **Position: Leverage Foundational Models for Black-Box Optimization.** ![](https://img.shields.io/badge/position-DCE7F1),![](https://img.shields.io/badge/ICML2024-FAEFCA)*Xingyou Song, Yingtao Tian, Robert Tjarko Lange, Chansoo Lee, Yujin Tang, Yutian Chen.* [[pdf](https://arxiv.org/abs/2405.03547)]
2. **Large Language Models as Optimizers.** ![](https://img.shields.io/badge/OPRO-DCE7F1),![](https://img.shields.io/badge/ICLR2024-FAEFCA)*Chengrun Yang, Xuezhi Wang, Yifeng Lu, Hanxiao Liu, Quoc V. Le, Denny Zhou, Xinyun Chen (Google DeepMind).*[[pdf](https://arxiv.org/abs/2309.03409)],[[project](https://github.com/google-deepmind/opro)]
3. **Large Language Models to Enhance Bayesian Optimization.** ![](https://img.shields.io/badge/LLAMBO-DCE7F1),![](https://img.shields.io/badge/ICLR2024-FAEFCA)*Tennison Liu, Nicolás Astorga, Nabeel Seedat, Mihaela van der Schaar.* [[pdf](https://arxiv.org/abs/2402.03921)],[[project](https://github.com/tennisonliu/LLAMBO)]
4. **𝙻𝙻𝙸𝙽𝙱𝙾: Trustworthy LLM-in-the-Loop Bayesian Optimization.** ![](https://img.shields.io/badge/LLINBO-DCE7F1),![](https://img.shields.io/badge/arxiv2025-FAEFCA)*Chih-Yu Chang, Milad Azvar, Chinedum Okwudire, Raed Al Kontar.* [[pdf](https://arxiv.org/abs/2505.14756)],[[project](https://github.com/UMDataScienceLab/LLM-in-the-Loop-BO)]
5. **Searching For Optimal Solutions With LLMs Via Baysian Optimization.** ![](https://img.shields.io/badge/BOPRO-DCE7F1),![](https://img.shields.io/badge/ICLR2025-FAEFCA)*Dhruv Agarwal, Manoj Ghuhan Arivazhagan, Rajarshi Das, Sandesh Swamy, Sopan Khosla, Rashmi Gangadharaiah.*[[pdf](https://openreview.net/forum?id=aVfDrl7xDV)]
6.  **A Sober Look at LLMs for Material Discovery-Are They Actually Good for Bayesian Optimization Over Molecules?** ![](https://img.shields.io/badge/lapeft_bayesopt-DCE7F1),![](https://img.shields.io/badge/ICML2024-FAEFCA)*Agustinus Kristiadi, Felix Strieth-Kalthoff, Marta Skreta, Pascal Poupart, Alán Aspuru-Guzik, Geoff Pleiss.* [[pdf](https://arxiv.org/abs/2402.05015)],[[project](https://github.com/wiseodd/lapeft-bayesopt)]
7. **Language-Based Bayesian Optimization Research Assistant (BORA).** ![](https://img.shields.io/badge/BORA-DCE7F1),![](https://img.shields.io/badge/arxiv2025-FAEFCA)*Abdoulatif Cissé, Xenophon Evangelopoulos, Vladimir V. Gusev, Andrew I. Cooper.*[[pdf](https://arxiv.org/abs/2501.16224)],[[project](https://anonymous.4open.science/r/bora-the-explorer)]
8. **Reasoning BO: Enhancing Bayesian Optimization with Long-Context Reasoning Power of LLMs.**![](https://img.shields.io/badge/ReasoningBO-DCE7F1),![](https://img.shields.io/badge/arxiv2025-FAEFCA)*Zhuo Yang, Lingli Ge, Dong Han, Tianfan Fu, Yuqiang Li.*[[pdf](https://arxiv.org/abs/2505.12833)],[[project](https://anonymous.4open.science/r/Reasoning-BO/)]
9. **Large Scale Multi-Task Bayesian Optimization with Large Language Models.**![](https://img.shields.io/badge/BOIT-DCE7F1),![](https://img.shields.io/badge/arxiv2025-FAEFCA)*Yimeng Zeng, Natalie Maus, Haydn Thomas Jones, Jeffrey Tao, Fangping Wan, Marcelo Der Torossian Torres, Cesar de la Fuente-Nunez, Ryan Marcus, Osbert Bastani, Jacob R. Gardner.*[[pdf](https://arxiv.org/abs/2503.08131)]
10. **Evolve Cost-aware Acquisition Functions Using Large Language Models.** ![](https://img.shields.io/badge/EvolCAF-DCE7F1),![](https://img.shields.io/badge/arxiv2024-FAEFCA)*Yiming Yao, Fei Liu, Ji Cheng, Qingfu Zhang.* [[pdf](https://arxiv.org/abs/2404.16906)],[[project](https://github.com/FeiLiu36/EoH)]
11. **FunBO:Discovering Acquisition Functions for Bayesian Optimization with FunSearch.**![](https://img.shields.io/badge/FunBO-DCE7F1),![](https://img.shields.io/badge/ICML2025-FAEFCA)*Virginia Aglietti, Ira Ktena, Jessica Schrouff, Eleni Sgouritsa, Francisco J. R. Ruiz, Alan Malek, Alexis Bellot, Silvia Chiappa.*[[pdf](https://arxiv.org/abs/2406.04824)]
12. **Active Learning with LLMs for Partially Observed and Cost-Aware Scenarios.** ![](https://img.shields.io/badge/&mu;POCA-DCE7F1),![](https://img.shields.io/badge/NeurIPS2024-FAEFCA)*Yiming Yao, Fei Liu, Ji Cheng, Qingfu Zhang.*[[pdf](https://arxiv.org/abs/2404.16906)],[[project](https://github.com/vanderschaarlab/POCA)]
