<h1 align="center">🤗🤗🤗 Awesome-LVLM-Safety 🤗🤗🤗</h1>

<p align="center"><em>Curated list of Large Vision-Language Model Safety resources, aligned with our work:</em><br><strong>A Survey of Safety on Large Vision-Language Models: Attacks, Defenses and Evaluations</strong></p>

<p align="center">
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome Badge"></a>
    <img src="https://badges.toozhao.com/badges/01JM4JCV43N3ARA3BC25QSBH0S/blue.svg" alt="Custom Badge" />
    <a href="https://creativecommons.org/licenses/by-nc/4.0/"><img src="https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg" alt="License Badge"></a>
    <a href="https://github.com/XuankunRong/Awesome-LVLM-Safety"><img src="https://img.shields.io/github/stars/XuankunRong/Awesome-LVLM-Safety?style=social" alt="GitHub stars"></a>
</p>

<h2> 📜 Table of Contents </h2>

- [Awesome Paper](#awesome-papers)
  - [Attacks](#attacks)
  - [Defenses](#defenses)
  - [Evaluations](#evaluations)
- [Contact](#contact)
- [Citation](#citation)

<h2 id="awesome-papers"> 👑 Awesome Papers </h2>

<h3 id="attacks"> <img src="assets/attack.png" alt="Icon" width="20" style="vertical-align:middle"/> Attacks </h3>

* **[2023.05.26]** **[On Evaluating Adversarial Robustness of Large Vision-Language Models](https://arxiv.org/abs/2305.16934)**
  * Yunqing Zhao, Tianyu Pang, Chao Du, Xiao Yang, Chongxuan Li, Ngai-Man Cheung, Min Lin
  * Singapore University of Technology and Design, Sea AI Lab, Tsinghua University, Renmin University of China
  * [NeurIPS'23]

* **[2023.06.22] [Visual Adversarial Examples Jailbreak Aligned Large Language Models](https://arxiv.org/abs/2306.13213)** [![GitHub stars](https://img.shields.io/github/stars/unispac/visual-adversarial-examples-jailbreak-large-language-models?style=social)](https://github.com/unispac/visual-adversarial-examples-jailbreak-large-language-models)
  * Xiangyu Qi, Kaixuan Huang, Ashwinee Panda, Peter Henderson, Mengdi Wang, Prateek Mittal
  * Princeton University, Stanford University
  * [AAAI'24 Oral]
* **[2023.07.19]** **[Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs](https://arxiv.org/abs/2307.10490)** [![GitHub stars](https://img.shields.io/github/stars/ebagdasa/multimodal_injection?style=social)](https://github.com/ebagdasa/multimodal_injection)
  * Eugene Bagdasaryan, Tsung-Yin Hsieh, Ben Nassi, Vitaly Shmatikov
  * Cornell Tech
  * [arXiv'23]
* **[2023.07.26]** **[Jailbreak in pieces: Compositional Adversarial Attacks on Multi-Modal Language Models](https://arxiv.org/abs/2307.14539)**
  * Erfan Shayegani, Yue Dong, Nael Abu-Ghazaleh
  * University of California, Riverside
  * [ICLR'24]

* **[2023.08.23]** **[On the Adversarial Robustness of Multi-Modal Foundation Models](https://arxiv.org/abs/2308.10741)**
  * Christian Schlarmann, Matthias Hein
  * University of Tübingen
  * [ICCV'23 AROW]

* **[2023.09.01]** **[Image Hijacks: Adversarial Images can Control Generative Models at Runtime](https://arxiv.org/abs/2309.00236)**
  * Luke Bailey, Euan Ong, Stuart Russell, Scott Emmons
  * Harvard University, Cambridge University , University of California, Berkeley
  * [ICML'24]

* **[2023.09.20]** **[How Robust is Google's Bard to Adversarial Image Attacks?](https://arxiv.org/abs/2309.11751)**
  * Yinpeng Dong, Huanran Chen, Jiawei Chen, Zhengwei Fang, Xiao Yang, Yichi Zhang, Yu Tian, Hang Su, Jun Zhu
  * Tsinghua University, RealAI
  * [NeurIPS'23 Workshop]

* **[2023.11.09]** **[FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts](https://arxiv.org/abs/2311.05608)**
  * Yichen Gong, Delong Ran, Jinyuan Liu, Conglei Wang, Tianshuo Cong, Anyu Wang, Sisi Duan, Xiaoyun Wang
  * Tsinghua University, Carnegie Mellon University, Zhongguancun Laboratory, National Financial Cryptography Research Center, Shandong Institute of Blockchain, Shandong University
  * [AAAI'25]

* **[2023.12.04]** **[InstructTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models](https://arxiv.org/abs/2312.01886)**
  * Xunguang Wang, Zhenlan Ji, Pingchuan Ma, Zongjie Li, Shuai Wang
  * The Hong Kong University of Science and Technology
  * [arXiv'23]

* **[2024.01.20]** **[Inducing High Energy-Latency of Large Vision-Language Models with Verbose Images](https://arxiv.org/abs/2401.11170)**
  * Kuofeng Gao, Yang Bai, Jindong Gu, Shu-Tao Xia, Philip Torr, Zhifeng Li, Wei Liu
  * Tsinghua University, Tencent Technology (Beijing) Co.Ltd, University of Oxford, Tencent Data Platform,  Peng Cheng Laboratory
  * [ICLR'24]

* **[2024.02.01]** **[Vision-LLMs Can Fool Themselves with Self-Generated Typographic Attacks](https://arxiv.org/abs/2402.00626)**
  * Maan Qraitem, Nazia Tasnim, Piotr Teterwak, Kate Saenko, Bryan A. Plummer
  * Boston University
  * [NeurIPS'24]

* **[2024.02.03]** **[Jailbreaking Attack against Multimodal Large Language Model](https://arxiv.org/abs/2402.02309)**
  * Zhenxing Niu, Haodong Ren, Xinbo Gao, Gang Hua, Rong Jin
  * Xidian University, Wormpex AI Research, Meta
  * [arXiv'24]

* **[2024.02.05]** **[Shadowcast: Stealthy Data Poisoning Attacks Against Vision-Language Models](https://arxiv.org/abs/2402.06659)**
  * Yuancheng Xu, Jiarui Yao, Manli Shu, Yanchao Sun, Zichu Wu, Ning Yu, Tom Goldstein, Furong Huang
  * University of Maryland, University of Illinois Urbana-Champaign, Salesforce Research, Apple, University of Waterloo,  Netflix Eyeline Studios
  * [NeurIPS'24]

* **[2024.02.13]** **[Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast](https://arxiv.org/abs/2402.08567)**
  * Xiangming Gu, Xiaosen Zheng, Tianyu Pang, Chao Du, Qian Liu, Ye Wang, Jing Jiang, Min Lin
  * Sea AI Lab, National University of Singapore, Singapore Management University
  * [ICML'24]

* **[2024.02.13]** **[Test-Time Backdoor Attacks on Multimodal Large Language Models](https://arxiv.org/abs/2402.08577)**
  * Dong Lu, Tianyu Pang, Chao Du, Qian Liu, Xianjun Yang, Min Lin
  * Southern University of Science and Technology, Sea AI Lab, University of California
  * [arXiv'24]

* **[2024.02.20]** **[The Wolf Within: Covert Injection of Malice into MLLM Societies via An MLLM Operative](https://arxiv.org/abs/2402.14859)**
  * Zhen Tan, Chengshuai Zhao, Raha Moraffah, Yifan Li, Yu Kong, Tianlong Chen, Huan Liu
  * Arizona State University, Michigan State University, University of North Carolina at Chapel Hill, MIT, Harvard University
  * [arXiv'24]

* **[2024.02.21]** **[VL-Trojan: Multimodal Instruction Backdoor Attacks against Autoregressive Visual Language Models](https://arxiv.org/abs/2402.13851)**
  * Jiawei Liang, Siyuan Liang, Man Luo, Aishan Liu, Dongchen Han, Ee-Chien Chang, Xiaochun Cao
  * [arXiv'24]

* **[2024.02.22]** **[Stop Reasoning! When Multimodal LLM with Chain-of-Thought Reasoning Meets Adversarial Image](https://arxiv.org/abs/2402.14899)**
  * Zefeng Wang, Zhen Han, Shuo Chen, Fan Xue, Zifeng Ding, Xun Xiao, Volker Tresp, Philip Torr, Jindong Gu
  * Technical University of Munich, LMU Munich, Huawei Technologies, University of Oxford
  * [COLM'24]

* **[2024.03.05]** **[ImgTrojan: Jailbreaking Vision-Language Models with ONE Image](https://arxiv.org/abs/2403.02910)**
  * Xijia Tao, Shuai Zhong, Lei Li, Qi Liu, Lingpeng Kong
  * The University of Hong Kong
  * [arXiv'24]

* **[2024.03.14]** **[Images are Achilles' Heel of Alignment: Exploiting Visual Vulnerabilities for Jailbreaking Multimodal Large Language Models](https://arxiv.org/abs/2403.09792)**
  * Yifan Li, Hangyu Guo, Kun Zhou, Wayne Xin Zhao, Ji-Rong Wen
  * Renmin University of China, Beijing Key Laboratory of Big Data Management and Analysis Methods
  * [ECCV'24]

* **[2024.03.14]** **[An Image Is Worth 1000 Lies: Adversarial Transferability across Prompts on Vision-Language Models](https://arxiv.org/abs/2403.09766)**
  * Haochen Luo, Jindong Gu, Fengyuan Liu, Philip Torr
  * University of Oxford
  * [ICLR'24]

* **[2024.04.19]** **[Physical Backdoor Attack can Jeopardize Driving with Vision-Large-Language Models](https://arxiv.org/abs/2404.12916)**
  * Zhenyang Ni, Rui Ye, Yuxi Wei, Zhen Xiang, Yanfeng Wang, Siheng Chen
  * Shanghai Jiao Tong University, University of Illinois Urbana-Champaign, Shanghai AI Laboratory, Multi-Agent Governance & Intelligence Crew (MAGIC)
  * [ICML'24 Workshop]

* **[2024.05.16]** **[Adversarial Robustness for Visual Grounding of Multimodal Large Language Models](https://arxiv.org/abs/2405.09981)**
  * Kuofeng Gao, Yang Bai, Jiawang Bai, Yong Yang, Shu-Tao Xia
  * Tsinghua University, Tencent Security Platform, Peng Cheng Laboratory
  * [ICLR'24 Workshop]

* **[2024.05.25]** **[Visual-RolePlay: Universal Jailbreak Attack on MultiModal Large Language Models via Role-playing Image](https://arxiv.org/abs/2405.20773)**
  * Siyuan Ma, Weidi Luo, Yu Wang, Xiaogeng Liu
  * University of Wisconsin–Madison, The Ohio State University, Peking University
  * [arXiv'24]

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

* **[2024.06.27]** **[Revisiting Backdoor Attacks against Large Vision-Language Models](https://arxiv.org/abs/2406.18844)**
  * Siyuan Liang, Jiawei Liang, Tianyu Pang, Chao Du, Aishan Liu, Mingli Zhu, Xiaochun Cao, Dacheng Tao
  * National University of Singapore, Shenzhen Campus of Sun Yat-sen University, Sea AI lab, Independent Researchers, The Chinese University of Hong Kong, Shenzhen, Nanyang Technological University
  * [arXiv'24]

* **[2024.07.01]** **[Image-to-Text Logic Jailbreak: Your Imagination can Help You Do Anything](https://arxiv.org/abs/2407.02534)**
  * Xiaotian Zou, Ke Li, Yongkang Chen
  * University of Exeter, Nanjing University of Aeronautics and Astronautics
  * [arXiv'24]

* **[2024.09.28]** **[TrojVLM: Backdoor Attack Against Vision Language Models](https://arxiv.org/abs/2409.19232)**
  * Weimin Lyu, Lu Pang, Tengfei Ma, Haibin Ling, Chao Chen
  * Stony Brook University
  * [ECCV'24]

* **[2024.10.02]** **[Backdooring Vision-Language Models with Out-Of-Distribution Data](https://arxiv.org/abs/2410.01264)**
  * Weimin Lyu, Jiachen Yao, Saumya Gupta, Lu Pang, Tao Sun, Lingjie Yi, Lijie Hu, Haibin Ling, Chao Chen
  * Stony Brook University, King Abdullah University of Science and Technology
  * [ICLR'25]


* **[2024.10.09]** **[Break the Visual Perception: Adversarial Attacks Targeting Encoded Visual Tokens of Large Vision-Language Models](https://arxiv.org/abs/2410.06699)**
  * Yubo Wang, Chaohu Liu, Yanqiu Qu, Haoyu Cao, Deqiang Jiang, Linli Xu
  * University of Science and Technology of China, Tencent YouTu Lab
  * [MM'24]
* **[2024.10.29]** **[IDEATOR: Jailbreaking Large Vision-Language Models Using Themselves](https://arxiv.org/abs/2411.00827v2)**
  * Ruofan Wang, Bo Wang, Xiaosen Wang, Xingjun Ma, Yu-Gang Jiang
  * Fudan University, Huawei Technologies Ltd.
  * [arXiv'24]
* **[2024.11.01]** **[Replace-then-Perturb: Targeted Adversarial Attacks With Visual Reasoning for Vision-Language Models](https://arxiv.org/abs/2411.00898v1)**
  * Jonggyu Jang, Hyeonsu Lyu, Jungyeon Koh, Hyun Jong Yang
  * Seoul National University, Pohang University of Science and Technology
  * [arXIv'24]

* **[2024.12.01]** **[Jailbreak Large Vision-Language Models Through Multi-Modal Linkage](https://arxiv.org/abs/2412.00473v4)**
  * Yu Wang, Xiaofei Zhou, Yichen Wang, Geyuan Zhang, Tianxing He
  * University of Chinese Academy of Sciences, Tsinghua University, Shanghai Qi Zhi Institute, University of Chicago
  * [arXiv'24]
* **[2024.12.08]** **[Heuristic-Induced Multimodal Risk Distribution Jailbreak Attack for Multimodal Large Language Models](https://arxiv.org/abs/2412.05934)**
  * Ma Teng, Jia Xiaojun, Duan Ranjie, Li Xinfeng, Huang Yihao, Chu Zhixuan, Liu Yang, Ren Wenqi
  * Sun Yat-Sen University, Nanyang Technological University, Alibaba Group, Zhejiang University
  * [arXiv'24]

<h3 id="defenses"> <img src="assets/defense.png" alt="Icon" width="18" style="vertical-align:middle"/> Defenses </h3>

* **[2023.11.16]** **[DRESS: Instructing Large Vision-Language Models to Align and Interact with Humans via Natural Language Feedback](https://arxiv.org/abs/2311.10081)**
  * Yangyi Chen, Karan Sikka, Michael Cogswell, Heng Ji, Ajay Divakaran
  * SRI International, University of Illinois Urbana-Champaign
  * [CVPR'24]
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
* **[2024.07.31]** **[Cross-modality Information Check for Detecting Jailbreaking in Multimodal Large Language Models](https://arxiv.org/abs/2407.21659v4)**
  * Yue Xu, Xiuyuan Qi, Zhan Qin, Wenjie Wang
  * ShanghaiTech University, Zhejiang University
  * [EMNLP'24]
* **[2024.08.17]** **[BaThe: Defense against the Jailbreak Attack in Multimodal Large Language Models by Treating Harmful Instruction as Backdoor Trigger](https://arxiv.org/abs/2408.09093)**
  * Yulin Chen, Haoran Li, Yirui Zhang, Zihao Zheng, Yangqiu Song, Bryan Hooi
  * National University of Singapore, Hong Kong University of Science and Technology, Harbin Institute of Technology, Shenzhen
  * [arXiv'24]
* **[2024.09.11]** **[Sim-CLIP+: Securing Vision-Language Models with a Robust Encoder Against Jailbreak and Adversarial Attacks](https://arxiv.org/abs/2409.07353)**
  * Md Zarif Hossain, Ahmed Imteaj
  * Southern Illinois University, Security, Privacy and Intelligence for Edge Devices Laboratory
  * [arXiv'24]
* **[2024.09.17]** **[CoCA: Regaining Safety-awareness of Multimodal Large Language Models with Constitutional Calibration](https://arxiv.org/abs/2409.11365)**
  * Jiahui Gao, Renjie Pi, Tianyang Han, Han Wu, Lanqing Hong, Lingpeng Kong, Xin Jiang, Zhenguo Li
  * Noah’s Ark Lab, The Hong Kong University of Science and Technology, The Hong Kong Polytechnic University, The University of Hong Kong
  * [COLM'24]
* **[2024.10.09]** **[ETA: Evaluating Then Aligning Safety of Vision Language Models at Inference Time](https://arxiv.org/abs/2410.06625)**
  * Yi Ding, Bolian Li, Ruqi Zhang
  * Purdue University
  * [ICLR'25]
* **[2024.10.11]** **[Unraveling and Mitigating Safety Alignment Degradation of Vision-Language Models](https://arxiv.org/abs/2410.09047)**
  * Qin Liu, Chao Shang, Ling Liu, Nikolaos Pappas, Jie Ma, Neha Anna John, Srikanth Doss, Lluis Marquez, Miguel Ballesteros, Yassine Benajiba
  * University of California, Davis, AWS AI Labs
  * [arXiv'24]
* **[2024.10.16]** **[Cross-Modal Safety Mechanism Transfer in Large Vision-Language Models](https://arxiv.org/abs/2410.12662)**
  * Shicheng Xu, Liang Pang, Yunchang Zhu, Huawei Shen, Xueqi Cheng
  * Institute of Computing Technology
  * [ICLR'25]
* **[2024.10.28]** **[BlueSuffix: Reinforced Blue Teaming for Vision-Language Models Against Jailbreak Attacks](https://arxiv.org/abs/2410.20971)**
  * Yunhan Zhao, Xiang Zheng, Lin Luo, Yige Li, Xingjun Ma, Yu-Gang Jiang
  * Fudan University, City University of Hong Kong, Singapore Management University
  * [ICLR'25]
* **[2024.10.30]** **[Effective and Efficient Adversarial Detection for Vision-Language Models via A Single Vector](https://arxiv.org/abs/2410.22888)**
  * Youcheng Huang, Fengbin Zhu, Jingkun Tang, Pan Zhou, Wenqiang Lei, Jiancheng Lv, Tat-Seng Chua
  * Sichuan University, National University of Singapore, Singapore Management University
  * [arXiv'24]
* **[2024.11.03]** **[UniGuard: Towards Universal Safety Guardrails for Jailbreak Attacks on Multimodal Large Language Models](https://arxiv.org/abs/2411.01703)**
  * Sejoon Oh, Yiqiao Jin, Megha Sharma, Donghyun Kim, Eric Ma, Gaurav Verma, Srijan Kumar
  * Netflix, Georgia Institute of Technology
  * [arXiv'24]
* **[2024.11.23]** **[Steering Away from Harm: An Adaptive Approach to Defending Vision Language Model Against Jailbreaks](https://arxiv.org/abs/2411.16721)**
  * Han Wang, Gang Wang, Huan Zhang
  * University of Illinois Urbana-Champaign
  * [arXiv'24]
* **[2024.11.27]** **[Immune: Improving Safety Against Jailbreaks in Multi-modal LLMs via Inference-Time Alignment](https://arxiv.org/abs/2411.18688)**
  * Soumya Suvra Ghosal, Souradip Chakraborty, Vaibhav Singh, Tianrui Guan, Mengdi Wang, Ahmad Beirami, Furong Huang, Alvaro Velasquez, Dinesh Manocha, Amrit Singh Bedi
  * University of Maryland, Indian Institute of Technology Bombay, Princeton University, University of Colorado Boulder, University of Central Florida
  * [arXiv'24]
* **[2024.12.17]** **[Defending LVLMs Against Vision Attacks through Partial-Perception Supervision](https://arxiv.org/abs/2412.12722)**
  * Qi Zhou, Tianlin Li, Qing Guo, Dongxia Wang, Yun Lin, Yang Liu, Jin Song Dong
  * Zhejiang University, Nanyang Technological University, A*STAR, Shanghai Jiao Tong University, National University of Singapore
  * [arXiv'24]

<h3 id="evaluations"> <img src="assets/evaluation.png" alt="Icon" width="27" style="vertical-align:middle"/> Evaluations </h3>

* **[2023.11.27]** **[How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs](https://arxiv.org/abs/2311.16101)**
  * Haoqin Tu, Chenhang Cui, Zijun Wang, Yiyang Zhou, Bingchen Zhao, Junlin Han, Wangchunshu Zhou, Huaxiu Yao, Cihang Xie
  * UC Santa Cruz, UNC-Chapel Hill, University of Edinburgh , University of Oxford, AIWaves Inc.
  * [ECCV'24]
* **[2023.11.29]** **[MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models](https://arxiv.org/abs/2311.17600)**
  * Xin Liu, Yichen Zhu, Jindong Gu, Yunshi Lan, Chao Yang, Yu Qiao
  * Shanghai AI Laboratory, East China Normal University, Midea Group, University of Oxford
  * [ECCV'24]
* **[2024.01.23]** **[Red Teaming Visual Language Models](https://arxiv.org/abs/2401.12915)**
  * Mukai Li, Lei Li, Yuwei Yin, Masood Ahmed, Zhenguang Liu, Qi Liu
  * The University of Hong Kong, Zhejiang University
  * [ACL'24]
* **[2024.02.29]** **[Unveiling Typographic Deceptions: Insights of the Typographic Vulnerability in Large Vision-Language Model](https://arxiv.org/abs/2402.19150)**
  * Hao Cheng, Erjia Xiao, Jindong Gu, Le Yang, Jinhao Duan, Jize Zhang, Jiahang Cao, Kaidi Xu, Renjing Xu
  * The Hong Kong University of Science and Technology (Guangzhou), University of Oxford, Xi’an Jiaotong University, Drexel University, The Hong Kong University of Science and Technology
  * [ECCV'24]
* **[2024.03.14]** **[AVIBench: Towards Evaluating the Robustness of Large Vision-Language Model on Adversarial Visual-Instructions](https://arxiv.org/abs/2403.09346)**
  * Hao Zhang, Wenqi Shao, Hong Liu, Yongqiang Ma, Ping Luo, Yu Qiao, Nanning Zheng, Kaipeng Zhang
  * Xi’an Jiaotong University, Shanghai Artificial Intelligence Laboratory, Osaka University
  * [arXiv'24]
* **[2024.04.03]** **[JailBreakV-28K: A Benchmark for Assessing the Robustness of MultiModal Large Language Models against Jailbreak Attacks](https://arxiv.org/abs/2404.03027)**
  * Weidi Luo, Siyuan Ma, Xiaogeng Liu, Xiaoyu Guo, Chaowei Xiao
  * The Ohio State University, Peking University, University of Wisconsin-Madison
  * [COLM'24]
* **[2024.04.04]** **[Red Teaming GPT-4V: Are GPT-4V Safe Against Uni/Multi-Modal Jailbreak Attacks?](https://arxiv.org/abs/2404.03411)**
  * Shuo Chen, Zhen Han, Bailan He, Zifeng Ding, Wenqian Yu, Philip Torr, Volker Tresp, Jindong Gu
  * LMU Munich, University of Oxford, Siemens AG, Munich Center for Machine Learning (MCML), Wuhan University
  * [ICLR'24]
* **[2024.06.11]** **[MultiTrust: A Comprehensive Benchmark Towards Trustworthy Multimodal Large Language Models](https://arxiv.org/abs/2406.07057)**
  * Yichi Zhang, Yao Huang, Yitong Sun, Chang Liu, Zhe Zhao, Zhengwei Fang, Yifan Wang, Huanran Chen, Xiao Yang, Xingxing Wei, Hang Su, Yinpeng Dong, Jun Zhu
  * Tsinghua University,  Beihang University, Shanghai Jiao Tong University, RealAI, Pazhou Lab (Huangpu)
  * [NeurIPS'24]
* **[2024.06.11]** **[MLLMGuard: A Multi-dimensional Safety Evaluation Suite for Multimodal Large Language Models](https://arxiv.org/abs/2406.07594)**
  * Tianle Gu, Zeyang Zhou, Kexin Huang, Dandan Liang, Yixu Wang, Haiquan Zhao, Yuanqi Yao, Xingge Qiao, Keqing Wang, Yujiu Yang, Yan Teng, Yu Qiao, Yingchun Wang
  * Tsinghua Shenzhen International Graduate School, Shanghai Artificial Intelligence Laboratory
  * [NeurIPS'24]
* **[2024.06.21]** **[Cross-Modality Safety Alignment](https://arxiv.org/abs/2406.15279)**
  * Siyin Wang, Xingsong Ye, Qinyuan Cheng, Junwen Duan, Shimin Li, Jinlan Fu, Xipeng Qiu, Xuanjing Huang
  * Fudan University, National University of Singapore, Shanghai AI Laboratory
  * [NAACL'25]
* **[2024.06.22]** **[MOSSBench: Is Your Multimodal Language Model Oversensitive to Safe Queries?](https://arxiv.org/abs/2406.17806)**
  * Xirui Li, Hengguang Zhou, Ruochen Wang, Tianyi Zhou, Minhao Cheng, Cho-Jui Hsieh
  * University of California, LA,  University of Maryland, Pennsylvania State University
  * [ICLR'25]
* **[2024.07.21]** **[Arondight: Red Teaming Large Vision Language Models with Auto-generated Multi-modal Jailbreak Prompts](https://arxiv.org/abs/2407.15050)**
  * Yi Liu, Chengjun Cai, Xiaoli Zhang, Xingliang Yuan, Cong Wang
  * City University of Hong Kong, University of Science and Technology, The University of Melbourne
  * [MM'24]
* **[2024.08.15]** **[MMJ-Bench: A Comprehensive Study on Jailbreak Attacks and Defenses for Multimodal Large Language Models](https://arxiv.org/abs/2408.08464)**
  * Fenghua Weng, Yue Xu, Chengyan Fu, Wenjie Wang
  * ShanghaiTech University
  * [arXiv'24]
* **[2024.10.08]** **[Multimodal Situational Safety](https://arxiv.org/abs/2410.06172)**
  * Kaiwen Zhou, Chengzhi Liu, Xuandong Zhao, Anderson Compalas, Dawn Song, Xin Eric Wang
  * University of California, Santa Cruz, University of California, Berkeley
  * [ICLR'25]
* **[2024.10.24]** **[SafeBench: A Safety Evaluation Framework for Multimodal Large Language Models](https://arxiv.org/abs/2410.18927)**
  * Zonghao Ying, Aishan Liu, Siyuan Liang, Lei Huang, Jinyang Guo, Wenbo Zhou, Xianglong Liu, Dacheng Tao
  * Beihang University, National University of Singapore, Zhongguancun Laboratory, Hefei Comprehensive National Science Center, University of Science and Technology of China, Nanyang Technological University, Singapore
  * [arXiv'24]

<h2 id="contact"> 👋 Contact </h2> 

This repository is currently maintained by [Xuankun Rong](https://xuankunrong.github.io/) 👨‍💻. If you have any questions, concerns, or suggestions regarding the contents of this repository or the resources shared here, feel free to reach out! I'm more than happy to assist you with any inquiries or help you navigate through the materials. Please don't hesitate to send an email to me at [xuankun.rong@gmail.com](mailto:xuankun.rong@gmail.com) 📧, and I will get back to you as soon as possible. Let's keep improving the LVLM Safety community together! 🚀

Looking forward to hearing from you! 😊

<h2 id="citation"> 🥳 Citation </h2>

Please kindly cite these papers in your publications if it helps your research:

```

```
