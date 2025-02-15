# 🤗🤗🤗 Awesome LVLM Safety [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License](https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/) [![GitHub stars](https://img.shields.io/github/stars/XuankunRong/Awesome-LVLM-Safety?style=social)](https://github.com/XuankunRong/Awesome-LVLM-Safety)

> Curated list of Large Vision-Language Model Safety resources, aligned with our survey:
> **A Survey of Safety on Large Vision-Language Models: Attacks, Defenses and Evaluations**

## 📜 Table of Contents

<details>
<summary>Click to expand</summary>

- [Attacks](#attacks)
- [Defenses](#defenses)
- [Evaluations](#evaluations)

</details>

<h2> <img src="assets/attack.png" alt="Icon" width="20" style="vertical-align:middle"/> Attacks </h2>

* **[2023.05.26]** On Evaluating Adversarial Robustness of Large Vision-Language Models **(NeurIPS'23)** [[Paper](https://arxiv.org/abs/2305.16934)] zhao2024evaluating
* **[2023.06.22] [Visual Adversarial Examples Jailbreak Aligned Large Language Models](https://arxiv.org/abs/2306.13213)** [![GitHub stars](https://img.shields.io/github/stars/unispac/visual-adversarial-examples-jailbreak-large-language-models?style=social)](https://github.com/unispac/visual-adversarial-examples-jailbreak-large-language-models)
  * Xiangyu Qi, Kaixuan Huang, Ashwinee Panda, Peter Henderson, Mengdi Wang, Prateek Mittal
  * Princeton University, Stanford University
  * [AAAI'24 Oral]
* **[2023.07.19]** **[Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs](https://arxiv.org/abs/2307.10490)** [![GitHub stars](https://img.shields.io/github/stars/ebagdasa/multimodal_injection?style=social)](https://github.com/ebagdasa/multimodal_injection)
  * Eugene Bagdasaryan, Tsung-Yin Hsieh, Ben Nassi, Vitaly Shmatikov
  * Cornell Tech
  * [arXiv'23]
* **[2023.07.26]** Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models **(ICLR'24)** [[Paper](https://arxiv.org/abs/2307.14539)] shayegani2023jailbreak
* **[2023.08.23]** **[On the Adversarial Robustness of Multi-Modal Foundation Models](https://arxiv.org/abs/2308.10741)**
  * Christian Schlarmann, Matthias Hein
  * University of Tübingen
  * [ICCV'23 AROW]

* **[2023.09.01]** **[Image Hijacks: Adversarial Images can Control Generative Models at Runtime](https://arxiv.org/abs/2309.00236)** [[Code](https://github.com/euanong/image-hijacks)]
  * Luke Bailey, Euan Ong, Stuart Russell, Scott Emmons
  * Harvard University, Cambridge University , University of California, Berkeley
  * [ICML'24]

* **[2023.09.20]** How Robust is Google's Bard to Adversarial Image Attacks? **(NeurIPS'23 Workshop)** [[Paper](https://arxiv.org/abs/2309.11751)] [[Code](https://github.com/thu-ml/attack-bard)] dong2023robust
* **[2023.11.09]** FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts **(arXiv'23)** [[Paper](https://arxiv.org/abs/2311.05608)] [[Code](https://github.com/thuccslab/figstep)] gong2023figstep
* **[2023.12.04]** InstructTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models [[Paper](https://arxiv.org/abs/2312.01886)]
* **[2024.01.20]** **[Inducing High Energy-Latency of Large Vision-Language Models with Verbose Images](https://arxiv.org/abs/2401.11170)**
  * Kuofeng Gao, Yang Bai, Jindong Gu, Shu-Tao Xia, Philip Torr, Zhifeng Li, Wei Liu
  * Tsinghua University, Tencent Technology (Beijing) Co.Ltd, University of Oxford, Tencent Data Platform,  Peng Cheng Laboratory
  * [ICLR'24]

* **[2024.02.01]** Vision-LLMs Can Fool Themselves with Self-Generated Typographic Attacks **(NeurIPS’24)** [[Paper](https://arxiv.org/abs/2402.00626)] qraitem2024vision
* **[2024.02.03]** Jailbreaking Attack against Multimodal Large Language Model **(arXiv’24)** [[Paper](https://arxiv.org/abs/2402.02309)] niu2024jailbreaking 也是用了多个encoder，放在一起提一嘴
* **[2024.02.05]** Shadowcast: Stealthy Data Poisoning Attacks Against Vision-Language Models **(NeurIPS’24)** [[Paper](https://arxiv.org/abs/2402.06659)] xu2024shadowcast 这个是，只poison一小类图片，如trump、biden之类的
* **[2024.02.13]** Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast **(ICML’24)** [[Paper](https://arxiv.org/abs/2402.08567)] gu2024agent
* **[2024.02.13]** **[Test-Time Backdoor Attacks on Multimodal Large Language Models](https://arxiv.org/abs/2402.08577)**
  * Dong Lu, Tianyu Pang, Chao Du, Qian Liu, Xianjun Yang, Min Lin
  * Southern University of Science and Technology, Sea AI Lab, University of California
  * [arXiv'24]

* **[2024.02.20]** The Wolf Within: Covert Injection of Malice into MLLM Societies via An MLLM Operative **(arXiv’24)** [[Paper](https://arxiv.org/abs/2402.14859)] tan2024wolf
* **[2024.02.21]** VL-Trojan: Multimodal Instruction Backdoor Attacks against Autoregressive Visual Language Models **(arXiv’24)** [[Paper](https://arxiv.org/abs/2402.13851)] liang2024vl 这个是生成一个noise加到任何的图片中作为trigger，然后可以实现hidden backdoor
* **[2024.02.22]** **[Stop Reasoning! When Multimodal LLM with Chain-of-Thought Reasoning Meets Adversarial Image](https://arxiv.org/abs/2402.14899)**
  * Zefeng Wang, Zhen Han, Shuo Chen, Fan Xue, Zifeng Ding, Xun Xiao, Volker Tresp, Philip Torr, Jindong Gu
  * Technical University of Munich, LMU Munich, Huawei Technologies, University of Oxford
  * [COLM'24]

* **[2024.03.05]** ImgTrojan: Jailbreaking Vision-Language Models with ONE Image **(arXiv’24)** [[Paper](https://arxiv.org/abs/2403.02910)]
* **[2024.03.14]** **[Images are Achilles' Heel of Alignment: Exploiting Visual Vulnerabilities for Jailbreaking Multimodal Large Language Models](https://arxiv.org/abs/2403.09792)**
  * Yifan Li, Hangyu Guo, Kun Zhou, Wayne Xin Zhao, Ji-Rong Wen
  * Renmin University of China, Beijing Key Laboratory of Big Data Management and Analysis Methods
  * [ECCV'24]

* **[2024.03.14]** **[An Image Is Worth 1000 Lies: Adversarial Transferability across Prompts on Vision-Language Models](https://arxiv.org/abs/2403.09766)**
  * Haochen Luo, Jindong Gu, Fengyuan Liu, Philip Torr
  * University of Oxford
  * [ICLR'24]

* **[2024.04.19]** Physical Backdoor Attack can Jeopardize Driving with Vision-Large-Language Models **(arXiv’24)** [[Paper](https://arxiv.org/abs/2404.12916)] ni2024physical
* **[2024.05.16]** **[Adversarial Robustness for Visual Grounding of Multimodal Large Language Models](https://arxiv.org/abs/2405.09981)**
  * Kuofeng Gao, Yang Bai, Jiawang Bai, Yong Yang, Shu-Tao Xia
  * Tsinghua University, Tencent Security Platform, Peng Cheng Laboratory
  * [ICLR'24 Workshop]

* **[2024.05.25]** Visual-RolePlay: Universal Jailbreak Attack on MultiModal Large Language Models via Role-playing Image Character **(arXiv’24)** [[Paper](https://arxiv.org/abs/2405.20773)] ma2024visual
* **[2024.05.28]** **[White-box Multimodal Jailbreaks Against Large Vision-Language Models](https://arxiv.org/abs/2405.17894)**
  * Ruofan Wang, Xingjun Ma, Hanxu Zhou, Chuanjun Ji, Guangnan Ye, Yu-Gang Jiang
  * Fudan University, Shanghai Jiaotong University
  * [MM'24]

* **[2024.06.06]** **[Jailbreak Vision Language Models via Bi-Modal Adversarial Prompt](https://arxiv.org/abs/2406.04031)**
  * Zonghao Ying, Aishan Liu, Tianyuan Zhang, Zhengmin Yu, Siyuan Liang, Xianglong Liu, Dacheng Tao
  * Beihang University, Fudan University, National University of Singapore, Nanyang Technological University
  * [arXiv'24]

* **[2024.06.19]** **[Enhancing Cross-Prompt Transferability in Vision-Language Models through Contextual Injection of Target Tokens](https://arxiv.org/abs/2406.13294)**
  * Xikang Yang, Xuehai Tang, Fuqing Zhu, Jizhong Han, Songlin Hu
  * University of Chinese Academy of Sciences
  * [arXiv'24]

* **[2024.06.27]** Revisiting Backdoor Attacks against Large Vision-Language Models **(arXiv’24)** [[Paper](https://arxiv.org/abs/2406.18844)] liang2024revisiting
* **[2024.07.01]** Image-to-Text Logic Jailbreak: Your Imagination can Help You Do Anything **(arXiv’24)** [[Paper](https://arxiv.org/abs/2407.02534)] zou2024image
* **[2024.09.28]** TrojVLM: Backdoor Attack Against Vision Language Models **(ECCV’24) [**[Paper](https://arxiv.org/abs/2409.19232)] lyu2024trojvlm
* **[2024.10.02]** Backdooring Vision-Language Models with Out-Of-Distribution Data **(arXiv’24)** [[Paper](https://arxiv.org/abs/2410.01264)] lyu2024backdooring

* **[2024.10.09]** Break the Visual Perception: Adversarial Attacks Targeting Encoded Visual Tokens of Large Vision-Language Models **(MM’24)** [[Paper](https://arxiv.org/abs/2410.06699)] wang2024break
* **[2024.10.29]** IDEATOR: Jailbreaking Large Vision-Language Models Using Themselves **(arXiv’24)** [[Paper](https://arxiv.org/abs/2411.00827v2)] wang2024ideator
* **[2024.11.01]** **[Replace-then-Perturb: Targeted Adversarial Attacks With Visual Reasoning for Vision-Language Models](https://arxiv.org/abs/2411.00898v1)**
  * Jonggyu Jang, Hyeonsu Lyu, Jungyeon Koh, Hyun Jong Yang
  * Seoul National University, Pohang University of Science and Technology
  * [arXIv'24]

* **[2024.12.01]** Jailbreak Large Vision-Language Models Through Multi-Modal Linkage **(arXiv’24) [**[Paper](https://arxiv.org/abs/2412.00473v2)] wang2024jailbreak
* **[2024.12.08]** Heuristic-Induced Multimodal Risk Distribution Jailbreak Attack for Multimodal Large Language Models **(arXiv’24)** [[Paper](https://arxiv.org/abs/2412.05934)] teng2024heuristic

<h2> <img src="assets/defense.png" alt="Icon" width="18" style="vertical-align:middle"/> Defenses </h2>

* **[2023.12.17]** **[JailGuard: A Universal Detection Framework for LLM Prompt-based Attacks](https://arxiv.org/abs/2312.10766v3)**
  * Xiaoyu Zhang, Cen Zhang, Tianlin Li, Yihao Huang, Xiaojun Jia, Ming Hu, Jie Zhang, Yang Liu, Shiqing Ma, Chao Shen
  * Xi’an Jiaotong University, Nanyang Technological University, University of Massachusetts
  * [arXiv'23]
* **[2024.01.05]** **[MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance](https://arxiv.org/abs/2401.02906)**
  * Renjie Pi, Tianyang Han, Jianshu Zhang, Yueqi Xie, Rui Pan, Qing Lian, Hanze Dong, Jipeng Zhang, Tong Zhang
  * The Hong Kong University of Science and Technology, University of Illinois at Urbana-Champaign, The Hong Kong Polytechnic University
  * [EMNLP'24]
* **[2024.01.20]** **[InferAligner: Inference-Time Alignment for Harmlessness through Cross-Model Guidance](https://arxiv.org/abs/2401.11206)**
  * Pengyu Wang, Dong Zhang, Linyang Li, Chenkun Tan, Xinghao Wang, Ke Ren, Botian Jiang, Xipeng Qiu
  * Fudan University
  * [EMNLP'24]
* **[2024.02.03]** **[Safety Fine-Tuning at (Almost) No Cost: A Baseline for Vision Large Language Models](https://arxiv.org/abs/2402.02207)**
  * Yongshuo Zong, Ondrej Bohdal, Tingyang Yu, Yongxin Yang, Timothy Hospedales
  * University of Einburgh, EPFL
  * [ICML'24]
* **[2024.02.19]** **[Robust CLIP: Unsupervised Adversarial Fine-Tuning of Vision Embeddings for Robust Large Vision-Language Models](https://arxiv.org/abs/2402.12336)**
  * Christian Schlarmann, Naman Deep Singh, Francesco Croce, Matthias Hein
  * Tübingen AI Center, University of Tübingen, EPFL
  * [ICML'24]
* **[2024.03.14]** **[Eyes Closed, Safety On: Protecting Multimodal LLMs via Image-to-Text Transformation](https://arxiv.org/abs/2403.09572)**
  * Yunhao Gou, Kai Chen, Zhili Liu, Lanqing Hong, Hang Xu, Zhenguo Li, Dit-Yan Yeung, James T. Kwok, Yu Zhang
  * Southern University of Science and Technology, Hong Kong University of Science and Technology, Huawei Noah’s Ark Lab
  * [ECCV'24]
* **[2024.03.14**] **[AdaShield: Safeguarding Multimodal Large Language Models from Structure-based Attack via Adaptive Shield Prompting](https://arxiv.org/abs/2403.09513)**
  * Yu Wang, Xiaogeng Liu, Yu Li, Muhao Chen, Chaowei Xiao
  * Peking University, University of Wisconsin–Madison, International Digital Economy Academy, University of California, Davis
  * [ECCV'24]
* **[2024.05.17]** **[Safeguarding Vision-Language Models Against Patched Visual Prompt Injectors](https://arxiv.org/abs/2405.10529)**
  * Jiachen Sun, Changsheng Wang, Jiongxiao Wang, Yiwei Zhang, Chaowei Xiao
  * University of Michigan Ann arbor, University of Wisconsin Madison, Michigan State University
  * [arXiv'24]
* **[2024.05.21]** **[Single Image Unlearning: Efficient Machine Unlearning in Multimodal Large Language Models](https://arxiv.org/abs/2405.12523)**
  * Jiaqi Li, Qianshan Wei, Chuanyi Zhang, Guilin Qi, Miaozeng Du, Yongrui Chen, Sheng Bi
  * Southeast University, Hohai University
  * [NeurIPS'24]
* **[2024.05.22]** **[Safety Alignment for Vision Language Models](https://arxiv.org/abs/2405.13581)**
  * Zhendong Liu, Yuanbi Nie, Yingshui Tan, Xiangyu Yue, Qiushi Cui, Chongjun Wang, Xiaoyong Zhu, Bo Zheng
  * Nanjing University, Chongqing University, Alibaba Group, Chinese University of Hong Kong
  * [arXiv'24]
* **[2024.05.27]** **[Cross-Modal Safety Alignment: Is textual unlearning all you need?](https://arxiv.org/abs/2406.02575)**
  * Trishna Chakraborty, Erfan Shayegani, Zikui Cai, Nael Abu-Ghazaleh, M. Salman Asif, Yue Dong, Amit K. Roy-Chowdhury, Chengyu Song
  * University of California, Riverside
  * [EMNLP'24 Findings]
* **[2024.06.07]** **[LLavaGuard: VLM-based Safeguards for Vision Dataset Curation and Safety Assessment](https://arxiv.org/abs/2406.05113)**
  * Lukas Helff, Felix Friedrich, Manuel Brack, Kristian Kersting, Patrick Schramowski
  * Technical University of Darmstadt, hessian.AI, DFKI, Centre for Cognitive Science, Ontocord
  * [arXiv'24]
* **[2024.06.13]** **[MirrorCheck: Efficient Adversarial Defense for Vision-Language Models](https://arxiv.org/abs/2406.09250)**
  * Samar Fares, Klea Ziu, Toluwani Aremu, Nikita Durasov, Martin Takáč, Pascal Fua, Karthik Nandakumar, Ivan Laptev
  * Mohamed bin Zayed University of Artificial Intelligence, EPFL
  * [arXiv'24]
* **[2024.06.17]** **[SPA-VL: A Comprehensive Safety Preference Alignment Dataset for Vision Language Model](https://arxiv.org/abs/2406.12030)**
  * Yongting Zhang, Lu Chen, Guodong Zheng, Yifeng Gao, Rui Zheng, Jinlan Fu, Zhenfei Yin, Senjie Jin, Yu Qiao, Xuanjing Huang, Feng Zhao, Tao Gui, Jing Shao
  * University of Science and Technology of China, Fudan University, Shanghai Artificial Intelligence Laboratory
  * [arXiv'24]
* **[2024.07.20]** **[Sim-CLIP: Unsupervised Siamese Adversarial Fine-Tuning for Robust and Semantically-Rich Vision-Language Models](https://arxiv.org/abs/2407.14971v2)**
  * Md Zarif Hossain, Ahmed Imteaj
  * Southern Illinois University, Security, Privacy and Intelligence for Edge Devices Laboratory
  * [arXiv'24]
* **[2024.07.31]** Cross-modality Information Check for Detecting Jailbreaking in Multimodal Large Language Models **(EMNLP’24)** [[Paper](https://arxiv.org/abs/2407.21659v4)] xu2024cross
  * 
* **[2024.08.17]** BaThe: Defense against the Jailbreak Attack in Multimodal Large Language Models by Treating Harmful Instruction as Backdoor Trigger **(arXiv’24)** [[Paper](https://arxiv.org/abs/2408.09093)] chen2024bathe data processing
* **[2024.09.11]** Sim-CLIP+: Securing Vision-Language Models with a Robust Encoder Against Jailbreak and Adversarial Attacks **(arXIv’24)** [[Paper](https://arxiv.org/abs/2409.07353)]
* **[2024.09.17]** CoCA: Regaining Safety-awareness of Multimodal Large Language Models with Constitutional Calibration **(COLM’24)** [[Paper](https://arxiv.org/abs/2409.11365)] gao2024coca
* **[2024.10.09]** ETA: Evaluating Then Aligning Safety of Vision Language Models at Inference Time (arXiv’24) [[Paper](https://arxiv.org/abs/2410.06625)] ICLR ding2024eta
* **[2024.10.11]** Unraveling and Mitigating Safety Alignment Degradation of Vision-Language Models **(arXiv’24)** [[Paper](https://arxiv.org/abs/2410.09047)] ICLR liu2024unraveling
* **[2024.10.16]** Cross-Modal Safety Mechanism Transfer in Large Vision-Language Models **(arXiv’24)** [[Paper](https://arxiv.org/abs/2410.12662)] ICLR data processing xu2024crosssafety
* **[2024.10.28]** BlueSuffix: Reinforced Blue Teaming for Vision-Language Models Against Jailbreak Attacks **(arXiv’24)** [[Paper](https://arxiv.org/abs/2410.20971)] zhao2024bluesuffix
* **[2024.10.30]** Effective and Efficient Adversarial Detection for Vision-Language Models via A Single Vector **(arXiv’24)** [[Paper](https://arxiv.org/abs/2410.22888)] ICLR撤稿huang2024effective
* **[2024.11.03]** UniGuard: Towards Universal Safety Guardrails for Jailbreak Attacks on Multimodal Large Language Models **(arXiv’24)** [[Paper](https://arxiv.org/abs/2411.01703)] ARR oh2024uniguard
* **[2023.11.16]** DRESS: Instructing Large Vision-Language Models to Align and Interact with Humans via Natural Language Feedback **(CVPR’24)** [[Paper](https://arxiv.org/abs/2311.10081)] 用NLF来safety alignment chen2024dress
* **[2024.11.23]** Steering Away from Harm: An Adaptive Approach to Defending Vision Language Model Against Jailbreaks **(arXiv’24)** [[Paper](https://arxiv.org/abs/2411.16721)] CVPR wang2024steering
* **[2024.11.27]** Immune: Improving Safety Against Jailbreaks in Multi-modal LLMs via Inference-Time Alignment **(arXiv’24)** [[Paper](https://arxiv.org/abs/2411.18688)] CVPR ghosal2024immune
* **[2024.12.17]** Defending LVLMs Against Vision Attacks through Partial-Perception Supervision (arXiv’24) [[Papar](https://arxiv.org/abs/2412.12722)]

<h2> <img src="assets/evaluation.png" alt="Icon" width="27" style="vertical-align:middle"/> Evaluations </h2>

* **[2023.11.27]** How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs **(ECCV’24)** [[Paper](https://arxiv.org/abs/2311.16101)] tu2023many
* **[2023.11.29]** MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models **(ECCV’24)** [[Paper](https://arxiv.org/abs/2311.17600)] liu2023query
* **[2024.01.23]** Red Teaming Visual Language Models **(ACL’24)** [[Paper](https://arxiv.org/abs/2401.12915)] li2024red
* **[2024.02.29]** Unveiling Typographic Deceptions: Insights of the Typographic Vulnerability in Large Vision-Language Model **(ECCV’24)** [[Paper](https://arxiv.org/abs/2402.19150)] cheng2024typographic
* **[2024.03.14]** AVIBench: Towards Evaluating the Robustness of Large Vision-Language Model on Adversarial Visual-Instructions **(arXiv’24)** [[Paper](https://arxiv.org/abs/2403.09346)] zhang2024avibench
* **[2024.04.03]** JailBreakV-28K: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks **(COLM’24)** [[Paper](https://arxiv.org/abs/2404.03027)] luo2024jailbreakv
* **[2024.04.04]** Red Teaming GPT-4V: Are GPT-4V Safe Against Uni/Multi-Modal Jailbreak Attacks? **(ICLR’24)** [[Paper](https://arxiv.org/abs/2404.03411)] chen2024red
* **[2024.06.11]** MultiTrust: A Comprehensive Benchmark Towards Trustworthy Multimodal Large Language Models **(NeurIPS’24)** [[Paper](https://arxiv.org/pdf/2406.07057)] zhang2024benchmarking
* **[2024.06.11]** MLLMGuard: A Multi-dimensional Safety Evaluation Suite for Multimodal Large Language Models **(NeurIPS’24)** [[Paper](https://arxiv.org/abs/2406.07594)] gu2024mllmguard
* **[2024.06.21]** Cross-Modality Safety Alignment **(arXiv’24)** [[Paper](https://arxiv.org/abs/2406.15279)] wang2024cross
* **[2024.06.22]** MOSSBench: Is Your Multimodal Language Model Oversensitive to Safe Queries? **(arXiv’24)** [[Paper](https://arxiv.org/abs/2406.17806)] li2024mossbench
* **[2024.07.21]** Arondight: Red Teaming Large Vision Language Models with Auto-generated Multi-modal Jailbreak Prompts **(MM’24)** [[Paper](https://arxiv.org/abs/2407.15050)] liu2024arondight
* **[2024.08.15]** MMJ-Bench: A Comprehensive Study on Jailbreak Attacks and Defenses for Multimodal Large Language Models **(arXiv’24)** [[Paper](https://arxiv.org/abs/2408.08464)] weng2024textit
* **[2024.10.08]** Multimodal Situational Safety **(arXiv’24)** [[Paper](https://arxiv.org/abs/2410.06172)] MSSBench zhou2024multimodal
* **[2024.10.24]** SafeBench: A Safety Evaluation Framework for Multimodal Large Language Models **(arXIv’24)** [[Paper](https://arxiv.org/abs/2410.18927)] ying2024safebench
