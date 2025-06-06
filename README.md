# 🎯 Mitigating Social Bias in Large Language Models: A Multi-Objective Approach within a Multi-Agent Framework  

## 📌 Poster  
![d8fe00c3f24b69dfb3d6efa7ff235474](https://github.com/user-attachments/assets/e9f873fd-d277-4c49-a033-4e987a97a895)  

This repository accompanies the paper **"Mitigating Social Bias in Large Language Models: A Multi-Objective Approach within a Multi-Agent Framework"**, which has been accepted at **AAAI 2025** as **oral presentation**🎉.

## 📝 Paper 
**[Read the Paper Here](https://ojs.aaai.org/index.php/AAAI/article/view/34748)**   

## 🚀 Code Availability  
MOMA relies on few-shot examples to perform context intervention, a key mechanism in our framework. To support reproducibility and downstream application, we have released a representative set of processed samples from MOMA 🧠, which can serve as few-shot inputs for LLMs to learn from and adapt their behaviors.

While the full codebase is under preparation, we are currently focusing on an extended journal version 📚 and preparing for another conference deadline ⏳. Additionally, the lead author is actively preparing for PhD/MPhil applications, which may cause some delay.

For any technical details or collaboration inquiries, feel free to contact the authors via email at:
xuzhj33 [at] mail2 [dot] sysu [dot] edu [dot] cn ✉️

We appreciate your understanding, interest, and support!

## 📖 Citation  
If you find our work helpful, please consider citing:  

```bibtex
@article{Xu_Chen_Tang_Li_Hu_Chu_Ren_Zheng_Lu_2025, title={Mitigating Social Bias in Large Language Models: A Multi-Objective Approach Within a Multi-Agent Framework}, volume={39}, url={https://ojs.aaai.org/index.php/AAAI/article/view/34748}, DOI={10.1609/aaai.v39i24.34748}, abstractNote={Natural language processing (NLP) has seen remarkable advancements with the development of large language models (LLMs). Despite these advancements, LLMs often produce socially biased outputs. Recent studies have mainly addressed this problem by prompting LLMs to behave ethically, but this approach results in unacceptable performance degradation. In this paper, we propose a multi-objective approach within a multi-agent framework (MOMA) to mitigate social bias in LLMs without significantly compromising their performance. The key idea of MOMA involves deploying multiple agents to perform causal interventions on bias-related contents of the input questions, breaking the shortcut connection between these contents and the corresponding answers. Unlike traditional debiasing techniques leading to performance degradation, MOMA substantially reduces bias while maintaining accuracy in downstream tasks. Our experiments conducted in two datasets and two models demonstrate that MOMA reduces bias scores by up to 87.7%, with only a marginal performance degradation of up to 6.8% in the BBQ dataset. Additionally, it significantly enhances the multi-objective metric icat in the StereoSet dataset by up to 58.1%.}, number={24}, journal={Proceedings of the AAAI Conference on Artificial Intelligence}, author={Xu, Zhenjie and Chen, Wenqing and Tang, Yi and Li, Xuanying and Hu, Cheng and Chu, Zhixuan and Ren, Kui and Zheng, Zibin and Lu, Zhichao}, year={2025}, month={Apr.}, pages={25579-25587} }
```
