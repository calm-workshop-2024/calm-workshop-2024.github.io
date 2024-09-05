---
title: "About"
---

## About the workshop

The remarkable capabilities and accessibility of recent large models, also known as “foundation models,” have sparked significant interest and excitement in the research community and beyond. In particular, large pre-trained generative models have demonstrated remarkable competencies in understanding and generating human-like text despite being trained on largely unstructured data using relatively simple self-supervised learning objectives. This raises the question: (A) *Why do such large models work so well?*

The impressive performance, sometimes even exceeding human experts, across a wide variety of benchmarks, together with the incorporation of multiple modalities such as images, text, and audio, makes these large models particularly versatile decision-making systems. However, the increased adoption of these models is not without challenges. The increasing size and complexity of these “black box” models raises concerns about their trustworthiness and reliability. For real-world applications, where distribution shifts are pervasive and sufficient high-quality data may be difficult or expensive to collect, it is crucial to systematically verify and enhance the robustness and generalization capabilities of these models. This is especially pertinent in safety-critical domains, such as healthcare and policy-making. Consequently, we must consider: (B) *Under what circumstances can we trust these large models and how can this be improved?*

Enter causality: a systematic framework to formalize “why?” and “how?” questions much like (A) or (B) and develop principled tools to address them. Causal inference is a powerful approach to describe a system’s behavior under interventions and reason over counterfactual scenarios. By relying on stable causal relationships, instead of potentially spurious statistical correlations, causal models can transparently elucidate a system’s behavior and enable performance guarantees beyond the training distribution, which is crucial for high-risk applications. However, translating the rigorous theoretical tools of causality into practical methods, especially in the large-scale regime with heterogeneous unstructured data as in large models, remains a notable challenge, despite the growing attention by the community.

With the striking potential of causality and the enormous interest in tackling the many open questions about understanding and improving large models on the other, we propose a workshop that aims to explore the many exciting synergies between causality and large models. Specifically, we identify four main directions to cover in our workshop:

* Causality in large models: Assessing the causal knowledge captured by large models and their (causal) reasoning abilities.

* Causality for large models: Applying ideas from causality to augment and improve large models.

* Causality with large models: Leveraging large models to improve causal inference and discovery.

* Causality of large models: Investigating the causal structure of how large models work and how to make them more interpretable and controllable.

We would like to acknowledge that a related workshop, [Are Large Language Models Simply Causal Parrots?](https://llmcp.cause-lab.net/llmcp), held at AAAI 2024, shared some of our objectives.

## Selected References

The following is a non-exhaustive list of selected references related to the topics of the workshop, compiled before announcing the call for papers.

You can see the list of references also in this public Zotero [library](https://www.zotero.org/groups/5650152/causality_and_large_models_-_neurips2024).


[1] Xiaoyu Liu, Paiheng Xu, Junda Wu, Jiaxin Yuan, Yifan Yang, Yuhang Zhou, Fuxiao Liu, Tianrui Guan, Haoliang Wang, Tong Yu, Julian McAuley, Wei Ai, and Furong Huang. Large Language Models and Causal Inference in Collaboration: A Comprehensive Survey, March 2024.

[2] Linying Yang, Oscar Clivio, Vik Shirvaikar, and Fabian Falck. A critical review of causal inference benchmarks for large language models. In AAAI 2024 Workshop on”Are Large Language Models Simply Causal Parrots?”, 2023.

[3] Usman Anwar, Abulhair Saparov, Javier Rando, Daniel Paleka, Miles Turpin, Peter Hase, Ekdeep Singh Lubana, Erik Jenner, Stephen Casper, Oliver Sourbut, et al. Foundational challenges in assuring alignment and safety of large language models. arXiv preprint arXiv:2404.09932, 2024.

[4] Zhijing Jin, Yuen Chen, Felix Leeb, Luigi Gresele, Ojasv Kamal, Zhiheng Lyu, Kevin Blin, Fernando Gonzalez Adauto, Max Kleiman-Weiner, Mrinmaya Sachan, et al. CLadder: A benchmark to assess causal reasoning capabilities of language models. Advances in Neural Information Processing Systems, 36, 2024.

[5] Tejas Kasetty, Divyat Mahajan, Gintare Karolina Dziugaite, Alexandre Drouin, and Dhanya Sridhar. Evaluating interventional reasoning capabilities of large language models. arXiv preprint arXiv:2404.05545, 2024.

[6] Kiho Park, Yo Joong Choe, and Victor Veitch. The linear representation hypothesis and the geometry of large language models. arXiv preprint arXiv:2311.03658, 2023.

[7] Atticus Geiger, Zhengxuan Wu, Christopher Potts, Thomas Icard, and Noah Good- man. Finding alignments between interpretable causal variables and distributed neural representations. In Causal Learning and Reasoning, pages 160–187. PMLR, 2024.

[8] Allen Nie, Yuhui Zhang, Atharva Shailesh Amdekar, Chris Piech, Tatsunori B Hashimoto, and Tobias Gerstenberg. MoCa: Measuring human-language model alignment on causal and moral judgment tasks. Advances in Neural Information Processing Systems, 36, 2024.

[9] Matej Zečević, Moritz Willig, Devendra Singh Dhami, and Kristian Kersting. Causal parrots: Large language models may talk causality but are not causal. arXiv preprint arXiv:2308.13067, 2023.

[10] Aniket Vashishtha, Abbavaram Gowtham Reddy, Abhinav Kumar, Saketh Bachu, Vineeth N Balasubramanian, and Amit Sharma. Causal inference using LLM-guided discovery. arXiv preprint arXiv:2310.15117, 2023.

[11] Patrik Reizinger, Szilvia Ujváry, Anna Mészáros, Anna Kerekes, Wieland Brendel, and Ferenc Huszár. Understanding LLMs requires more than statistical generalization. arXiv preprint arXiv:2405.01964, 2024.

[12] Moritz Willig, Matej Zečević, Devendra Singh Dhami, and Kristian Kersting. Can foundation models talk causality? arXiv preprint arXiv:2206.10591, 2022.

[13] Kevin Xia, Kai-Zhan Lee, Yoshua Bengio, and Elias Bareinboim. The causal-neural connection: Expressiveness, learnability, and inference. Advances in Neural Information Processing Systems, 34:10823–10836, 2021.

[14] Alexander D’Amour, Katherine Heller, Dan Moldovan, Ben Adlam, Babak Alipanahi, Alex Beutel, Christina Chen, Jonathan Deaton, Jacob Eisenstein, Matthew D Hoffman, et al. Underspecification presents challenges for credibility in modern machine learning. Journal of Machine Learning Research, 23(226):1–61, 2022.

[15] Stephanie Long, Alexandre Piché, Valentina Zantedeschi, Tibor Schuster, and Alexandre Drouin. Causal discovery with language models as imperfect experts. arXiv preprint arXiv:2307.02390, 2023.

[16] Goutham Rajendran, Simon Buchholz, Bryon Aragam, Bernhard Schölkopf, and Pradeep Ravikumar. Learning interpretable concepts: Unifying causal representation learning and foundation models. arXiv preprint arXiv:2402.09236, 2024.

[17] Yibo Jiang, Goutham Rajendran, Pradeep Ravikumar, Bryon Aragam, and Victor Veitch. On the origins of linear representations in large language models. arXiv preprint arXiv:2403.03867, 2024.

[18] Zihao Wang, Lin Gui, Jeffrey Negrea, and Victor Veitch. Concept algebra for (score- based) text-controlled generative models. Advances in Neural Information Processing Systems, 36, 2024.

[19] Sharut Gupta, Stefanie Jegelka, David Lopez-Paz, and Kartik Ahuja. Context is environment. In The Twelfth International Conference on Learning Representations, 2024. URL https://openreview.net/forum?id=8VPWfqtQMX.

[20] Andrew Kyle Lampinen, Stephanie C.Y. Chan, Ishita Dasgupta, Andrew Joo Hun Nam, and Jane X Wang. Passive learning of active causal strategies in agents and language models. In Thirty-seventh Conference on Neural Information Processing Systems, 2023. URL https://openreview.net/forum?id=BRpi8YAfac.

[21] Zhengxuan Wu, Atticus Geiger, Thomas Icard, Christopher Potts, and Noah Goodman. Interpretability at scale: Identifying causal mechanisms in alpaca. Advances in Neural Information Processing Systems, 36, 2024.

[22] Emre Kıcıman, Robert Ness, Amit Sharma, and Chenhao Tan. Causal reasoning and large language models: Opening a new frontier for causality. arXiv preprint arXiv:2305.00050, 2023.

[23] Francesco Montagna, Max Cairney-Leeming, Dhanya Sridhar, and Francesco Lo- catello. Demystifying amortized causal discovery with transformers. arXiv preprint arXiv:2405.16924, 2024.

[24] Imant Daunhawer, Alice Bizeul, Emanuele Palumbo, Alexander Marx, and Julia E Vogt. Identifiability results for multimodal contrastive learning. In The Eleventh International Conference on Learning Representations, 2023. URL https://openreview.net/forum? id=U_2kuqoTcB.

[25] Pedro Sanchez and Sotirios A. Tsaftaris. Diffusion causal models for counterfactual estimation. In First Conference on Causal Learning and Reasoning, 2022. URL https://openreview.net/forum?id=LAAZLZIMN-o.

[26] Yushu Pan and Elias Bareinboim. Counterfactual image editing. arXiv preprint arXiv:2403.09683, 2024.

[27] Jingling Li, Zeyu Tang, Xiaoyu Liu, Peter Spirtes, Kun Zhang, Liu Leqi, and Yang Liu. Steering LLMs towards unbiased responses: A causality-guided debiasing framework. In ICLR 2024 Workshop on Reliable and Responsible Foundation Models.

[28] Ahmed Abdulaal, adamos hadjivasiliou, Nina Montana-Brown, Tiantian He, Ayodeji Ijishakin, Ivana Drobnjak, Daniel C. Castro, and Daniel C. Alexander. Causal modelling agents: Causal graph discovery through synergising metadata- and data-driven reasoning. In The Twelfth International Conference on Learning Representations, 2024. URL https://openreview.net/forum?id=pAoqRlTBtY.

[29] Jonathan Richens and Tom Everitt. Robust agents learn causal world models. In The Twelfth International Conference on Learning Representations, 2024. URL https: //openreview.net/forum?id=pOoKI3ouv1.

[30] Amir Feder, Yoav Wald, Claudia Shi, Suchi Saria, and David Blei. Causal-structure driven augmentations for text OOD generalization. Advances in Neural Information Processing Systems, 36, 2024.