# A Comprehensive Survey on Pedestrian Attribute Recognition 
> **Pedestrian attribute recognition: A survey**. Xiao Wang, Shaofei Zheng, Rui Yang, Aihua Zheng, Zhe Chen, Jin Tang, and Bin Luo (2022). Pattern Recognition, 121, 108220.

![Illustration of PAR](https://github.com/wangxiao5791509/Pedestrian-Attribute-Recognition-Paper-List/blob/master/person-attribute-recognition.png)


![Illustration of PAR](https://github.com/wangxiao5791509/Pedestrian-Attribute-Recognition-Paper-List/blob/master/PETA_rap_results.jpg) 
Performance comparison on the PETA and RAP datasets from 2014 to 2020. We can find that the baseline method CNN-SVM is outperformed by recent deep learning based PAR approaches significantly on both large scale benchmark datasets.  Interestingly, we can also find that the accuracy of current deep learning based methods is comparable, and there is no significant improvements of current methods (in 2020) compared with deep PAR algorithms proposed several years ago. So, what's next if the deep learning based PAR algorithms achieve its bottleneck? 










## Update Log：


#### :fire: [Dec-20-2023] We maintain an open source PAR toolkit at [[OpenPAR](https://github.com/Event-AHU/OpenPAR)]

#### :fire: [Sep-14-2023] Pedestrian Attribute Recognition and Person Retrieval Challenge at WACV-2024 [[Homepage](https://chalearnlap.cvc.uab.cat/challenge/57/description/)] 

#### :fire: [July-03-2023] PAR on Paper with Code: [[Link](https://paperswithcode.com/task/pedestrian-attribute-recognition)]

#### :fire: [Submission Deadline: June 30th, 2023] PAR CONTEST at 20th International Conference on Computer Analysis of Images and Patterns - CAIP 2023 👇
* [PAR CONTEST 2023](https://mivia.unisa.it/par2023/) 

#### :fire: [October-14-2022] Pedestrian Attribute Recognition and Attributed-based Person Retrieval Challenge at WACV! 👇
* [WACV'23 Pedestrian Attribute Recognition and Attributed-based Person Retrieval Challenge](https://chalearnlap.cvc.uab.cat/challenge/52/description/) | **Data  available!** 

#### :fire: [July-31-2021] Our paper is finally accepted by journal **Pattern Recognition**! The journal version is slightly different from our arxiv version. 

#### :fire: Welcome to our **WeChat group** for further discussion, please scan this [code](https://github.com/wangxiao5791509/Pedestrian-Attribute-Recognition-Paper-List/blob/master/QQ%E5%9B%BE%E7%89%8720190117165910.png) Or scan this to add my [wechat](https://github.com/wangxiao5791509/Pedestrian-Attribute-Recognition-Paper-List/blob/master/mywechat.jpg) [Please tell me your Name + School/Company].  

#### :fire: If you find more related papers about person attribute recognition, please email me: wangxiaocvpr@foxmail.com 


Please consider citing this paper, if you find this survey useful for your research. 
[[arXiv paper](https://arxiv.org/pdf/1901.07474.pdf)]  
[[PR Version](https://www.sciencedirect.com/science/article/pii/S0031320321004015)] 

~~~
@article{wang2021pedestrian,
  title={Pedestrian attribute recognition: A survey},
  author={Wang, Xiao and Zheng, Shaofei and Yang, Rui and Zheng, Aihua and Chen, Zhe and Tang, Jin and Luo, Bin},
  journal={Pattern Recognition},
  pages={108220},
  year={2021},
  publisher={Elsevier}
}
~~~

![Structure of Survey](https://github.com/wangxiao5791509/Pedestrian-Attribute-Recognition-Paper-List/blob/master/structure.png)
![Papers of Survey](https://github.com/wangxiao5791509/Pedestrian-Attribute-Recognition-Paper-List/blob/master/review-of-par-papers.png)
![Overview_Benchmark](https://github.com/wangxiao5791509/Pedestrian-Attribute-Recognition-Paper-List/blob/master/overview-benchmark.png)



## Dataset:
1. PETA Dataset: http://mmlab.ie.cuhk.edu.hk/projects/PETA.html
2. RAP Dataset: http://rap.idealtest.org/
3. PA-100K Dataset: https://drive.google.com/drive/folders/0B5_Ra3JsEOyOUlhKM0VPZ1ZWR2M
4. WIDER Attribute Dataset: http://mmlab.ie.cuhk.edu.hk/projects/WIDERAttribute.html
5. Database of Human Attributes (HAT): [[Project](https://jurie.users.greyc.fr/datasets/hat.html)] [[Dataset](https://jurie.users.greyc.fr/datasets/hatdb.tar)]
6. Market-1501_Attribute: https://github.com/vana77/Market-1501_Attribute
7. DukeMTMC-Attribute: https://github.com/vana77/DukeMTMC-attribute
8. Clothing Attributes Dataset: https://purl.stanford.edu/tb980qz1002
9. Parse27k Dataset: https://www.vision.rwth-aachen.de/page/parse27k
10. RAP 2.0 Dataset: https://drive.google.com/file/d/1hoPIB5NJKf3YGMvLFZnIYG5JDcZTxHph/view
11. CRP Dataset: http://www.vision.caltech.edu/~dhall/projects/CRP/
12. APis dataset: http://www.cbsr.ia.ac.cn/english/APiS-1.0-Database.html. (Failed)
13. Berkeley-Attributes of People dataset: https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/shape/poselets/
14. Deepfashion dataset: http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html
15. Video-Based PAR dataset: https://github.com/yuange250/MARS-Attribute 
16. UAV-Human (CVPR 2021): https://github.com/SUTDCV/UAV-Human 
17. UPAR: [[Paper](https://arxiv.org/pdf/2209.02522.pdf)] [[WACV2023-Challenge](https://chalearnlap.cvc.uab.cat/challenge/52/description/)] [[Homepage](https://chalearnlap.cvc.uab.cat/dataset/44/description/)] [[GitHub](https://github.com/speckean/upar_challenge)] 
18. CelebV-HQ: A Large-Scale Video Facial Attributes Dataset 
[[Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136670641.pdf)]
[[Project](https://celebv-hq.github.io/)]







## Related Survey Papers and Tutorial: 
1. Zheng, X., Guo, Y., Huang, H., Li, Y., & He, R. (2020). A Survey of Deep Facial Attribute Analysis. International Journal of Computer Vision, 1-33. [Paper](https://arxiv.org/abs/1812.10265) 

2. Human Parsing: Huang, Lili, Jiefeng Peng, Ruimao Zhang, Guanbin Li, and Liang Lin. "Learning deep representations for semantic image parsing: a comprehensive overview." Frontiers of Computer Science 12, no. 5 (2018): 840-857. [Paper](https://arxiv.org/abs/1810.04377) 

3. Awesome Imbalanced Learning [[GitHub](https://github.com/ZhiningLiu1998/awesome-imbalanced-learning#surveys)] 

4. Person Search Paper List [[Github]](https://github.com/wangxiao5791509/Person-Search-Paper-List)

5. Human Attribute Recognition: A Comprehensive Survey, Yaghoubi, E., Khezeli, F., Borza, D., Kumar, S. A., Neves, J., & Proença, H. (2020). [[Paper](https://www.preprints.org/manuscript/202007.0055/download/final_file)] 

6. **监控场景中的行人属性识别研究综述**, 贾健, 陈晓棠, 黄凯奇, 计算机学报，
[[Paper](http://cjc.ict.ac.cn/online/onlinepaper/jj-202286141700.pdf)] 




## Recommended Code:

* [**OpenPAR**] An open-source framework for Pedestrian Attribute Recognition, based on PyTorch [[Link](https://github.com/Event-AHU/OpenPAR)]

* **A Simple Visual-Textual Baseline for Pedestrian Attribute Recognition**, Xinhua Cheng;Mengxi Jia;Qian Wang;Jian Zhang, IEEE TCSVT-2022
[[Paper](https://ieeexplore.ieee.org/document/9782406)] [[Code](https://github.com/cxh0519/VTB)]

* **Label2Label: A Language Modeling Framework for Multi-Attribute Learning**, Wanhua Li, Zhexuan Cao, Jianjiang Feng, Jie Zhou, Jiwen Lu, 	ECCV 2022 
[[Paper](https://arxiv.org/abs/2207.08677)] [[Code](https://github.com/Li-Wanhua/Label2Label)] 

* Rethinking of Pedestrian Attribute Recognition: A Reliable Evaluation under Zero-Shot Pedestrian Identity Setting： https://github.com/valencebond/Rethinking_of_PAR

* A solid and strong baseline of pedestrian attribute recognition: https://github.com/aajinjin/Strong_Baseline_of_Pedestrian_Attribute_Recognition

* A baseline model ( pytorch implementation ) for person attribute recognition task, training and testing on Market1501-attribute and 
DukeMTMC-reID-attribute dataset. https://github.com/hyk1996/Person-Attribute-Recognition-MarketDuke

* DeepMAR from "Multi-attribute learning for pedestrian attribute recognition": https://github.com/kyu-sz/DeepMAR_deploy

* Multi-attribute Learning for Pedestrian Attribute Recognition in Surveillance Scenarios, Dangwei Li and Xiaotang Chen and Kaiqi Huang, ACPR 2015: https://github.com/dangweili/pedestrian-attribute-recognition-pytorch

* Multi-label Image Recognition by Recurrently Discovering Attentional Regions (Pytorch implementation): https://github.com/James-Yip/AttentionImageClass

* A Richly Annotated Pedestrian Dataset for Person Retrieval in Real Surveillance Scenarios: Li, Dangwei and Zhang, Zhang and Chen, Xiaotang and Huang, Kaiqi, IEEE Transactions on Image Processing 2019: https://github.com/dangweili/RAP

* PatchIt (BMVC-2016): https://github.com/psudowe/patchit

* PANDA (CVOR-2014): https://github.com/facebookarchive/pose-aligned-deep-networks

* HydraPlus-Net (ICCV-2017): https://github.com/xh-liu/HydraPlus-Net

* WPAL-network (BMVC-2014) https://github.com/YangZhou1994/WPAL-network

* Deep Imbalanced Attribute Classification using Visual Attention Aggregation (ECCV-2018): https://github.com/cvcode18/imbalanced_learning

* Sarfraz, M. Saquib, et al. "Deep view-sensitive pedestrian attribute inference in an end-to-end model." arXiv preprint arXiv:1707.06089 (2017). https://github.com/asc-kit/vespa 









## The paper list of person attribute recognition: 



### Year-2024 


* **Distributionally Generative Augmentation for Fair Facial Attribute Classification**, Fengda Zhang, Qianpei He, Kun Kuang, Jiashuo Liu, Long Chen, Chao Wu, Jun Xiao, Hanwang Zhang
  [[Paper](https://arxiv.org/abs/2403.06606)]
  [[Code](https://github.com/heqianpei/DiGA)] 

* **Attribute-Guided Pedestrian Retrieval: Bridging Person Re-ID with Internal Attribute Variability**, Yan Huang, Zhang Zhang, Qiang Wu, Yi Zhong, Liang Wang
  [[Paper]()]

* [ICML 2024] **Pedestrian Attribute Recognition as Label-balanced Multi-label Learning**, arXiv:2405.04858, 
  Yibo Zhou, Hai-Miao Hu, Yirong Xiang, Xiaokang Zhang, Haotian Wu
  [[Paper](https://arxiv.org/abs/2405.04858)] 
  [[Code](https://github.com/SDret/Pedestrian-Attribute-Recognition-as-Label-balanced-Multi-label-Learning)] 

* **Spatio-Temporal Side Tuning Pre-trained Foundation Models for Video-based Pedestrian Attribute Recognition**, arXiv:2404.17929, 
  Xiao Wang, Qian Zhu, Jiandong Jin, Jun Zhu, Futian Wang, Bo Jiang, Yaowei Wang, Yonghong Tian 
  [[Paper](https://arxiv.org/abs/2404.17929)] 
  [[Code](https://github.com/Event-AHU/OpenPAR)] 
  
* **Private Attribute Inference from Images with Vision-Language Models**, arXiv:2404.10618, 
  Batuhan Tömekçe, Mark Vero, Robin Staab, Martin Vechev
  [[Paper](https://arxiv.org/abs/2404.10618)]
  [[Code](https://github.com/eth-sri/privacy-inference-multimodal)] 
 
* **CLEAR: Cross-Transformers with Pre-trained Language Model is All you need for Person Attribute Recognition and Retrieval**,
  Doanh C. Bui, Thinh V. Le, Hung Ba Ngo, Tae Jong Choi
  [[Paper](https://arxiv.org/abs/2403.06119)] 

* [CVPR-2024] **Learning Group Activity Features Through Person Attribute Prediction**, Chihiro Nakatani, Hiroaki Kawashima, Norimichi Ukita
  [[Paper](https://arxiv.org/abs/2403.02753)]
  [[Code](https://github.com/chihina/GAFL-CVPR2024)] 

* **Deep Learning for Multi-Label Learning: A Comprehensive Survey**, Adane Nega Tarekegn, Mohib Ullah, Faouzi Alaya Cheikh
  [[Paper](https://arxiv.org/abs/2401.16549)] 

* [AAAI-2024] **Object Attribute Matters in Visual Question Answering**, Peize Li, Qingyi Si, Peng Fu, Zheng Lin, Yan Wang
  [[Paper](https://arxiv.org/pdf/2401.09442.pdf)]

* [AAAI-2024] **Selective and Orthogonal Feature Activation for Pedestrian Attribute Recognition** Junyi Wu; Yan Huang; Min Gao; Yuzhen Niu; Mingjing Yang; Zhipeng Gao; Jianqiang Zhao 

* [AAAI-2024] **Multi-Prompts Learning with Cross-Modal Alignment for Attribute-based Person Re-Identification**, Yajing Zhai1,2*, Yawen Zeng1*, Zhiyong Huang, Zheng Qin1†, Xin Jin2†, Da Cao 
  [[Paper](https://arxiv.org/pdf/2312.16797.pdf)]
  [[Code](https://github.com/zyj20/MPReID)]

* **Masked Attribute Description Embedding for Cloth-Changing Person Re-identification**, Chunlei Peng, Boyu Wang, Decheng Liu, Nannan Wang, Ruimin Hu, Xinbo Gao
  [[Paper](https://arxiv.org/pdf/2401.05646.pdf)]
  [[Code](https://github.com/moon-wh/MADE)]

* Thakare, Kamalakar Vijay, et al. "**Let's Observe Them Over Time: An Improved Pedestrian Attribute Recognition Approach**." Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision. 2024.
  [[Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Thakare_Lets_Observe_Them_Over_Time_An_Improved_Pedestrian_Attribute_Recognition_WACV_2024_paper.pdf)]

* Bui, Doanh C., Thinh V. Le, and Ba Hung Ngo. "**C2T-Net: Channel-Aware Cross-Fused Transformer-Style Networks for Pedestrian Attribute Recognition**." Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision. 2024.
  [[Paper](https://openaccess.thecvf.com/content/WACV2024W/RWS/papers/Bui_C2T-Net_Channel-Aware_Cross-Fused_Transformer-Style_Networks_for_Pedestrian_Attribute_Recognition_WACVW_2024_paper.pdf)]
  [[Code](https://github.com/caodoanh2001/upar_challenge)]

* Wu, Peishu, et al. "**KD-PAR: A knowledge distillation-based pedestrian attribute recognition model with multi-label mixed feature learning network**." Expert Systems with Applications 237 (2024): 121305.
  [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0957417423018079)]

* Cormier, Mickael, et al. "**UPAR Challenge 2024: Pedestrian Attribute Recognition and Attribute-Based Person Retrieval-Dataset, Design, and Results.**" Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision. 2024.
  [[Paper](https://openaccess.thecvf.com/content/WACV2024W/RWS/papers/Cormier_UPAR_Challenge_2024_Pedestrian_Attribute_Recognition_and_Attribute-Based_Person_Retrieval_WACVW_2024_paper.pdf)]
  [[Code](https://github.com/speckean/upar_challenge)]



### Year-2023 

* **"Evaluation of a Visual Question Answering Architecture for Pedestrian Attribute Recognition."** Castrillón-Santana, Modesto, et al.  International Conference on Computer Analysis of Images and Patterns. Cham: Springer Nature Switzerland, 2023.
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-44237-7_2)]

* **"PAR Contest 2023: pedestrian attributes recognition with multi-task learning."** Greco, Antonio, and Bruno Vento. International Conference on Computer Analysis of Images and Patterns. Cham: Springer Nature Switzerland, 2023.
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-44237-7_1)]
  [[Project Page](https://mivia.unisa.it/par2023/)] 

* Song, Xu, et al. "**Gait Attribute Recognition: A New Benchmark for Learning Richer Attributes from Human Gait Patterns.**" IEEE Transactions on Information Forensics and Security (2023).
  [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10262050)] 

* Wu, Junyi, et al. "**Exponential information bottleneck theory against intra-attribute variations for pedestrian attribute recognition.**" IEEE Transactions on Information Forensics and Security (2023).
  [[Paper](https://ieeexplore.ieee.org/abstract/document/10238746)] 
 
* [Book-Chapter] **"Facial Attribute Analysis."** Handbook of Face Recognition. Wan, Jun, Zichang Tan, and Ajian Liu. Cham: Springer International Publishing, 2023. 171-207.
  [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43567-6_6)]

* [ACM MCCA] "**Pedestrian Attribute Recognition via Spatio-Temporal Relationship Learning for Visual Surveillance.**" Liu, Zhenyu, Da Li, Xinyu Zhang, Zhang Zhang, Peng Zhang, Caifeng Shan, and Jungong Han. ACM Transactions on Multimedia Computing, Communications and Applications (2023).
[[Paper](https://dl.acm.org/doi/pdf/10.1145/3632624)]


* [arXiv-2023] **Pedestrian Attribute Recognition via CLIP based Prompt Vision-Language Fusion**, Xiao Wang, Jiandong Jin, Chenglong Li, Jin Tang, Cheng Zhang, Wei Wang
[[arXiv](https://arxiv.org/abs/2312.10692)]
[[Code](https://github.com/Event-AHU/OpenPAR)]

* [PR-2023] **SSPNet: Scale and spatial priors guided generalizable and interpretable pedestrian attribute recognition**, Jifeng Shena, Teng Guo, Xin Zuo, Heng Fan, Wankou Yang 
  [[Paper](https://arxiv.org/pdf/2312.06049.pdf)]
  [[Code](https://github.com/guotengg/SSPNet)] 
 
* [arXiv-2023] **Hulk: A Universal Knowledge Translator for Human-Centric Tasks**， Yizhou Wang*, Yixuan Wu*, Shixiang Tang, Weizhen He, Xun Guo, Feng Zhu, Lei Bai, Rui Zhao, Jian Wu, Tong He, Wanli Ouyang,
  [[Paper](https://arxiv.org/pdf/2312.01697.pdf)]
  [[Code](https://github.com/OpenGVLab/HumanBench)] 

* [arXiv-2023] **SequencePAR: Understanding Pedestrian Attributes via A Sequence Generation Paradigm**, Jiandong Jin, Xiao Wang*, Chenglong Li, Lili Huang, Jin Tang,
  [[Paper](https://arxiv.org/abs/2312.01640)]
  [[Code](https://github.com/Event-AHU/OpenPAR)] 

* [arXiv-2023] **LogicNet: A Logical Consistency Embedded Face Attribute Learning Network**, Haiyu Wu, Sicong Tian, Huayu Li, Kevin W. Bowyer
  [[Paper](https://arxiv.org/pdf/2311.11208.pdf)]

* **[NeurIPS 2023]** "**Learning to Parameterize Visual Attributes for Open-set Fine-grained Retrieval.**" Wang, Shijie, Jianlong Chang, Haojie Li, Zhihui Wang, Wanli Ouyang, and Qi Tian.  In Thirty-seventh Conference on Neural Information Processing Systems. 2023. [[Paper](https://openreview.net/pdf?id=SaII5qMgKH)] 

* **[NeurIPS 2023] HAP: Structure-Aware Masked Image Modeling for Human-Centric Perception**, [[Homepage](https://zhangxinyu-xyz.github.io/hap.github.io/)] [[Github](https://github.com/junkunyuan/HAP)]

* **[ICCV-2023] Interaction-aware Joint Attention Estimation Using People Attributes**, Chihiro Nakatani, Hiroaki Kawashima, Norimichi Ukita, [[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Nakatani_Interaction-aware_Joint_Attention_Estimation_Using_People_Attributes_ICCV_2023_paper.pdf)] [[Code](https://github.com/chihina/)] 

* **AttMOT: Improving Multiple-Object Tracking by Introducing Auxiliary Pedestrian Attributes**, Yunhao Li, Zhen Xiao, Lin Yang, Dan Meng, Xin Zhou, Heng Fan, Libo Zhang,
[[Paper](https://arxiv.org/pdf/2308.07537.pdf)] 
 
* **Attribute-Image Person Re-identification via Modal-Consistent Metric Learning.** Zhu, J., Liu, L., Zhan, Y. et al.  Int J Comput Vis (2023). https://doi.org/10.1007/s11263-023-01841-7
[[Paper](https://link.springer.com/article/10.1007/s11263-023-01841-7#citeas)] 

* **"Identity-Aware Contrastive Knowledge Distillation for Facial Attribute Recognition."** Chen, Si, Xueyan Zhu, Yan Yan, Shunzhi Zhu, Shao-Zi Li, and Da-Han Wang.  IEEE Transactions on Circuits and Systems for Video Technology (2023).
[[IEEE](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10064142)]  

* **"Learning Weak Semantics by Feature Graph for Attribute-Based Person Search."** Peng, Qiyang, Lingxiao Yang, Xiaohua Xie, and Jianhuang Lai. IEEE Transactions on Image Processing 32 (2023): 2580-2592.
[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10113879)] 

* **Learning Attribute and Class-Specific Representation Duet for Fine-grained Fashion Analysis**,  Yang Jiao, Yan Gao, Jingjing Meng, Jin Shang, Yi Sun
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Jiao_Learning_Attribute_and_Class-Specific_Representation_Duet_for_Fine-Grained_Fashion_Analysis_CVPR_2023_paper.pdf)] 

* **"A novel self-boosting dual-branch model for pedestrian attribute recognition."** Cao, Yilu, Yuchun Fang, Yaofang Zhang, Xiaoyu Hou, Kunlin Zhang, and Wei Huang.  Signal Processing: Image Communication 115 (2023): 116961.
[[Paper](https://www.sciencedirect.com/science/article/pii/S0923596523000437)]

* **Towards Unified Text-based Person Retrieval: A Large-scale Multi-Attribute and Language Search Benchmark**, Shuyu Yang, Yinan Zhou, Yaxiong Wang, Yujiao Wu, Li Zhu, Zhedong Zheng 
[[Paper](https://arxiv.org/pdf/2306.02898.pdf)]

* **"Incremental Pedestrian Attribute Recognition via Dual Uncertainty-Aware Pseudo-Labeling."** Li, Da, Zhang Zhang, Caifeng Shan, and Liang Wang.  IEEE Transactions on Information Forensics and Security (2023).
[[Paper](https://ieeexplore.ieee.org/abstract/document/10106077)]

* **On Adversarial Robustness of Demographic Fairness in Face Attribute Recognition**, Huimin Zeng, Zhenrui Yue, Lanyu Shang, Yang Zhang, Dong Wang, IJCAI-2023  
[[Paper]()] 

* **A Solution to Co-occurrence Bias: Attributes Disentanglement via Mutual Information Minimization for Pedestrian Attribute Recognition**, Yibo Zhou, Hai-Miao Hu, Jinzuo Yu, Zhenbo Xu, Weiqing Lu, Yuran Cao, IJCAI-2023 [[Paper](https://arxiv.org/pdf/2307.15252.pdf)] 

* **PLIP: Language-Image Pre-training for Person Representation Learning**, Jialong Zuo Changqian Yu Nong Sang Changxin Gao, 
[[Paper](https://arxiv.org/pdf/2305.08386.pdf)] 
[[Code](https://github.com/Zplusdragon/PLIP)]

* **Beyond Appearance: a Semantic Controllable Self-Supervised Learning Framework for Human-Centric Visual Tasks**, Weihua Chen, Xianzhe Xu, Jian Jia, Hao luo, Yaohua Wang, Fan Wang, Rong Jin, Xiuyu Sun, CVPR-2023 
[[Paper](https://arxiv.org/pdf/2303.17602.pdf)] 
[[Code](https://github.com/tinyvision/SOLIDER)] 

* **Learning CLIP Guided Visual-Text Fusion Transformer for Video-based Pedestrian Attribute Recognition**, Jun Zhu, Jiandong Jin, Zihan Yang, Xiaohao Wu, Xiao Wang, CVPR-2023 Workshop@NFVLR (New Frontiers in Visual Language Reasoning: Compositionality, Prompts and Causality). 
[[Paper](https://arxiv.org/abs/2304.10091)]
[[Code](https://github.com/Event-AHU/VTF_PAR)]

* "**PARFormer: Transformer-based Multi-Task Network for Pedestrian Attribute Recognition.**" Fan, Xinwen, Yukang Zhang, Yang Lu, and Hanzi Wang.  IEEE Transactions on Circuits and Systems for Video Technology (2023).
[[arXiv](https://arxiv.org/pdf/2304.07230.pdf)] 
[[IEEE](https://ieeexplore.ieee.org/abstract/document/10148996)] 
[[Code](https://github.com/xwf199/PARFormer)] 

* **Learning Transferable Pedestrian Representation from Multimodal Information Supervision**, Liping Bao, Longhui Wei, Xiaoyu Qiu, Wengang Zhou, Houqiang Li, Qi Tian  [[Paper](https://arxiv.org/pdf/2304.05554.pdf)]

* **UPAR Challenge: Pedestrian Attribute Recognition and Attribute-Based Person Retrieval--Dataset, Design, and Results.** In Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (pp. 166-175). Cormier, M., Specker, A., Junior, J., Jacques, C. S., Florin, L., Metzler, J., ... & Beyerer, J. (2023). 
[[Paper](https://openaccess.thecvf.com/content/WACV2023W/RWS/papers/Cormier_UPAR_Challenge_Pedestrian_Attribute_Recognition_and_Attribute-Based_Person_Retrieval_--_WACVW_2023_paper.pdf)]

* **Orientation-Aware Pedestrian Attribute Recognition based on Graph Convolution Network.** Lu, W. Q., Hu, H. M., Yu, J., Zhou, Y., & Wang, H. (2023).  IEEE Transactions on Multimedia. [[Paper](https://ieeexplore.ieee.org/abstract/document/10078344)]

* **[MM ’23]** **POAR: Towards Open-World Pedestrian Attribute Recognition**, Yue Zhang, Suchen Wang, Shichao Kan, Zhenyu Weng, Yigang Cen, Yap-peng Tan, 
[[arXiv](https://arxiv.org/pdf/2303.14643.pdf)] 


* **HumanBench: Towards General Human-centric Perception with Projector Assisted Pretraining**, Shixiang Tang, Cheng Chen, Qingsong Xie, Meilin Chen, Yizhou Wang, Yuanzheng Ci, Lei Bai, Feng Zhu, Haiyang Yang, Li Yi, Rui Zhao, Wanli Ouyang, CVPR-2023 
[[Paper](https://arxiv.org/pdf/2303.05675.pdf)] 
[[Code](https://github.com/OpenGVLab/HumanBench)]

* **Exploring Attribute Localization and Correlation for Pedestrian Attribute Recognition**[J]. Weng, Dunfang and Tan, Zichang and Fang, Liwei and Guo, Guodong.  Neurocomputing, 2023. 
[[Paper](https://www.sciencedirect.com/science/article/pii/S0925231223001583)] 

* **Diverse features discovery transformer for pedestrian attribute recognition**[J]. Zheng, Aihua and Wang, Huimin and Wang, Jiaxiang and Huang, Huaibo and He, Ran and Hussain, Amir.  Engineering Applications of Artificial Intelligence, 2023, 119: 105708. 
[[Paper](https://www.sciencedirect.com/science/article/pii/S0952197622006984)]


### Year-2022 

* "**YinYang-Net: Complementing Face and Body Information for Wild Gender Recognition**." Roxo, Tiago, and Hugo Proença.  IEEE Access 10 (2022): 28122-28132.
[[arXiv](https://arxiv.org/pdf/2107.06847v2.pdf)]
[[IEEE](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9730882)]
[[Code](https://github.com/Tiago-Roxo/YinYang-Net)] 

* **FairGRAPE: Fairness-aware GRAdient Pruning mEthod for Face Attribute Classification**, Xiaofeng Lin , Seungbae Kim , and Jungseock Joo, 
[[Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136730414.pdf)] 
[[Code](https://github.com/Bernardo1998/FairGRAPE)]

* **Improving Closed and Open-Vocabulary Attribute Prediction using Transformers**, Khoi Pham et al. 
[[Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136850199.pdf)] 
[[Project Page](https://vkhoi.github.io/TAP/)]

* **OvarNet: Towards Open-vocabulary Object Attribute Recognition**, Keyan Chen, et al. 
[[Paper](https://arxiv.org/pdf/2301.09506.pdf)] 
[[Project](https://kyanchen.github.io/OvarNet)] 
[[Code](https://github.com/KyanChen/OvarNet)]

* **Dual-Branch Self-attention Network for Pedestrian Attribute Recognition**. Liu, Z., Zhang, Z., Li, D., Zhang, P., & Shan, C. (2022).  Pattern Recognition Letters.  [[Paper](https://www.sciencedirect.com/science/article/pii/S0167865522002963)]

* **Correlation Graph Convolutional Network for Pedestrian Attribute Recognition,** H. Fan, H. -M. Hu, S. Liu, W. Lu and S. Pu,  in IEEE Transactions on Multimedia, vol. 24, pp. 49-60, 2022, doi: 10.1109/TMM.2020.3045286. [[Paper](https://ieeexplore.ieee.org/document/9296283)]

* **UPAR: Unified Pedestrian Attribute Recognition and Person Retrieval**, Andreas Specker, Mickael Cormier, Jurgen Beyerer, In Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision, pp. 981-990. 2023. 
[[Paper](https://openaccess.thecvf.com/content/WACV2023/papers/Specker_UPAR_Unified_Pedestrian_Attribute_Recognition_and_Person_Retrieval_WACV_2023_paper.pdf)] 
[[Dataset](https://github.com/speckean/upar_dataset)]


* **Label2Label: A Language Modeling Framework for Multi-Attribute Learning**, Wanhua Li, Zhexuan Cao, Jianjiang Feng, Jie Zhou, Jiwen Lu, 	ECCV 2022 
[[Paper](https://arxiv.org/abs/2207.08677)] [[Code](https://github.com/Li-Wanhua/Label2Label)]

* "**Feature Fusion with Non-local for Pedestrian Attribute Recognition**." Lv, Jiping, et al.  2022 2nd International Conference on Bioinformatics and Intelligent Computing. 2022. [[Paper](https://dl.acm.org/doi/abs/10.1145/3523286.3524581)] 

* "**Pedestrian attribute recognition based on attribute correlation**." Zhao, Ruijie, et al.  Multimedia Systems 28.3 (2022): 1069-1081. 
[[Paper](https://link.springer.com/article/10.1007/s00530-022-00893-y)]

* "**Overview of Deep Learning Based Pedestrian Attribute Recognition and Reidentification**." Wu, Duidi, et al.  Available at SSRN 4082891 (2022). 
[[Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4082891)]

* "**Pedestrian Attribute Recognition with Feature Combination in Transformer with Attention Model**." Tang, Xikai, Zhikun Lin, and Yiran Wang.  International Conference on Computing, Control and Industrial Engineering. Springer, Singapore, 2022.
[[Paper](https://link.springer.com/chapter/10.1007/978-981-19-3927-3_49)]

* **Visual Attention Consistency for Human Attribute Recognition**. Guo, H., Fan, X., & Wang, S. (2022).  International Journal of Computer Vision, 130(4), 1088-1106. https://doi.org/10.1007/s11263-022-01591-y [[Paper](https://link.springer.com/article/10.1007/s11263-022-01591-y#citeas)]

* "**DRFormer: Learning dual relations using Transformer for pedestrian attribute recognition**." Tang, Zengming, and Jun Huang.  Neurocomputing 497 (2022): 159-169. 
[[Paper](https://www.sciencedirect.com/science/article/pii/S0925231222005598)]

* **Inter-Attribute Awareness for Pedestrian Attribute Recognition**. Wu, J., Huang, Y., Gao, Z., Hong, Y., Zhao, J., & Du, X. (2022).  Pattern Recognition, 108865. [[Paper](https://www.sciencedirect.com/science/article/pii/S0031320322003466)]

* "**Pedestrian attribute recognition in video surveillance scenarios based on view-attribute attention localization**." Chen, Wei-Chen, Xin-Yi Yu, and Lin-Lin Ou.  Machine Intelligence Research 19.2 (2022): 153-168. [[Paper](https://link.springer.com/content/pdf/10.1007/s11633-022-1321-8.pdf)]

* **A Framework for Pedestrian Attribute Recognition Using Deep Learning**. Sakib, S.; Deb, K.; Dhar, P.K.; Kwon, O.-J.  Appl. Sci. 2022, 12, 622. https://doi.org/10.3390/app12020622 [[Paper](https://www.mdpi.com/2076-3417/12/2/622/htm)] 

* Zhao, Yazhi, et al. "**FLSRNet: pedestrian attribute recognition using focal label smoothing regularization.**" Signal, Image and Video Processing (2022): 1-8. [[Paper](https://link.springer.com/content/pdf/10.1007/s11760-021-02099-7.pdf)]


* Weissenfeld, Axel, and Bernhard Strobl. "**Pedestrian Attribute Recognition (PAR).**" [[Paper](https://www.ait.ac.at/fileadmin/mc/digital_safety_security/downloads/PedestrianAttributeRecognition.pdf)]

* Zhao, Ruijie, et al. "**Pedestrian attribute recognition based on attribute correlation.**" Multimedia Systems 28.3 (2022): 1069-1081. [[Paper](https://link.springer.com/content/pdf/10.1007/s00530-022-00893-y.pdf)] 

* Chen, L., Song, J., Zhang, X. et al. **MCFL: multi-label contrastive focal loss for deep imbalanced pedestrian attribute recognition.** Neural Comput & Applic (2022). [[Paper](https://link.springer.com/article/10.1007/s00521-022-07300-7)] 

* Yan, Yan, et al. "**Drop Loss for Person Attribute Recognition With Imbalanced Noisy-Labeled Samples**." IEEE Transactions on Cybernetics (2022). [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9780248)]

* **Reinforced Pedestrian Attribute Recognition with Group Optimization Reward**, Zhong Ji, Zhenfei Hu, Yaodong Wang, Shengjia Li, arxiv-preprint 2205.14042
[[Paper](https://arxiv.org/abs/2205.14042)]

* **A Simple Visual-Textual Baseline for Pedestrian Attribute Recognition**, Xinhua Cheng;Mengxi Jia;Qian Wang;Jian Zhang, IEEE TCSVT-2022
[[Paper](https://ieeexplore.ieee.org/document/9782406)] [[Code](https://github.com/cxh0519/VTB)]

* **Fair Contrastive Learning for Facial Attribute Classification**, Sungho Park, Jewook Lee, Pilhyeon Lee, Sunhee Hwang, Dohyung Kim, Hyeran Byun
[[Paper](https://arxiv.org/pdf/2203.16209.pdf)]
[[Code](https://github.com/sungho-CoolG/FSCL)]

* **Learning Disentangled Attribute Representations for Robust Pedestrian Attribute Recognition**, Jian Jia, Naiyu Gao, Fei He, Xiaotang Chen, Kaiqi Huang, AAAI-2022 [[Paper](https://www.aaai.org/AAAI22Papers/AAAI-2142.JianJ.pdf)]



### Year-2021 

* X. Shan, P. Peng, Y. Zhai, C. Zhang, T. Huang and Y. Tian, "**Generate And Adjust: A Novel Framework For Semi-Supervised Pedestrian Attribute Recognition**," 2021 IEEE International Conference on Multimedia & Expo Workshops (ICMEW), 2021, pp. 1-6, doi: 10.1109/ICMEW53276.2021.9455965. [[Paper](https://ieeexplore.ieee.org/abstract/document/9455965)]

* Yang, Y., Tan, Z., Tiwari, P. et al. **Cascaded Split-and-Aggregate Learning with Feature Recombination for Pedestrian Attribute Recognition**. Int J Comput Vis 129, 2731–2744 (2021). https://doi.org/10.1007/s11263-021-01499-z
[[Paper](https://link.springer.com/article/10.1007/s11263-021-01499-z#citeas)]


* Lee, Geonu, Kimin Yun, and Jungchan Cho. "Robust Pedestrian Attribute Recognition Using Group Sparsity for Occlusion Videos." arXiv preprint arXiv:2110.08708 (2021). 
[[Paper](https://arxiv.org/pdf/2110.08708.pdf)]

* Z. Chen, S. Gu, F. Zhu, J. Xu and R. Zhao, "**Improving Facial Attribute Recognition by Group and Graph Learning**," 2021 IEEE International Conference on Multimedia and Expo (ICME), 2021, pp. 1-6, doi: 10.1109/ICME51207.2021.9428078. [[Paper](https://ieeexplore.ieee.org/abstract/document/9428078)]

* J. Zhong, H. Qiao, L. Chen, M. Shang and Q. Liu, "**Improving Pedestrian Attribute Recognition with Multi-Scale Spatial Calibration,**" 2021 International Joint Conference on Neural Networks (IJCNN), 2021, pp. 1-8, doi: 10.1109/IJCNN52387.2021.9533647. [[Paper](https://ieeexplore.ieee.org/abstract/document/9533647)]

* X. Zheng, Z. Yu, L. Chen, F. Zhu and S. Wang, "**Multi-label Contrastive Focal Loss for Pedestrian Attribute Recognition**," 2020 25th International Conference on Pattern Recognition (ICPR), 2021, pp. 7349-7356, doi: 10.1109/ICPR48806.2021.9411959. [[Paper](https://ieeexplore.ieee.org/abstract/document/9411959)]

* **Robust Pedestrian Attribute Recognition Using Group Sparsity for Occlusion Videos**, Geonu Lee, Kimin Yun, Jungchan Cho, arxiv 2021 [[Paper](https://arxiv.org/pdf/2110.08708.pdf)]

* **Spatial and Semantic Consistency Regularizations for Pedestrian Attribute Recognition**， Jian Jia, Xiaotang Chen, Kaiqi Huang, ICCV-2021. [[Paper](https://arxiv.org/pdf/2109.05686.pdf)]

* **UAV-Human: A Large Benchmark for Human Behavior Understanding with Unmanned Aerial Vehicles**, CVPR 2021, Tianjiao Li, Jun Liu1 Wei Zhang Yun Ni Wenqian Wang Zhiheng Li [[Paper](https://arxiv.org/pdf/2104.00946.pdf)] [[Github](https://github.com/SUTDCV/UAV-Human)] 

* **"Rethinking of Pedestrian Attribute Recognition: A Reliable Evaluation under Zero-Shot Pedestrian Identity Setting"**, Jian Jia, Houjing Huang, Xiaotang Chen, Kaiqi Huang [[arxiv](https://arxiv.org/pdf/2107.03576.pdf)] [[Code](https://github.com/valencebond/Rethinking_of_PAR)]

* **"Learning To Predict Visual Attributes in the Wild**", Khoi Pham, Kushal Kafle, Zhe Lin, Zhihong Ding, Scott Cohen, Quan Tran, Abhinav Shrivastava, [[CVPR2021](https://openaccess.thecvf.com/content/CVPR2021/papers/Pham_Learning_To_Predict_Visual_Attributes_in_the_Wild_CVPR_2021_paper.pdf)]

* **"Multi-Branch Gabor Wavelet Layers for Pedestrian Attribute Recognition."** Junejo, Imran N. IEEE Access 9 (2021): 40019-40026. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9360746)] 

* **"Depthwise Separable Convolutional Neural Networks for Pedestrian Attribute Recognition."** Junejo, Imran N., and Naveed Ahmed. SN Computer Science 2.2 (2021): 1-11. [[Paper](https://link.springer.com/content/pdf/10.1007/s42979-021-00493-z.pdf)] 

* **"Jointly human semantic parsing and attribute recognition with feature pyramid structure in EfficientNets."** Moghaddam, Mahnaz, Mostafa Charmi, and Hossein Hassanpoor. IET Image Processing (2021). [[Paper](https://ietresearch.onlinelibrary.wiley.com/doi/pdfdirect/10.1049/ipr2.12195)] 


### Year-2020 

* **"An evaluation of design choices for pedestrian attribute recognition in video."** Specker, Andreas, Arne Schumann, and Jürgen Beyerer.  In 2020 IEEE International Conference on Image Processing (ICIP), pp. 2331-2335. IEEE, 2020. 
[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9191264)]

* "**Attribute-aware pedestrian detection in a crowd.**" Zhang, Jialiang, Lixiang Lin, Jianke Zhu, Yang Li, Yun-chen Chen, Yao Hu, and Steven CH Hoi.  IEEE Transactions on Multimedia 23 (2020): 3085-3097. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9184102)]

* Wu, Jingjing, Hao Liu, Jianguo Jiang, Meibin Qi, Bo Ren, Xiaohong Li, and Yashen Wang. "**Person attribute recognition by sequence contextual relation learning.**" IEEE Transactions on Circuits and Systems for Video Technology 30, no. 10 (2020): 3398-3412. 
[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9045945)]

* H. An, H. -M. Hu, Y. Guo, Q. Zhou and B. Li, "**Hierarchical Reasoning Network for Pedestrian Attribute Recognition**," in IEEE Transactions on Multimedia, vol. 23, pp. 268-280, 2021, doi: 10.1109/TMM.2020.2975417. [[Paper](https://ieeexplore.ieee.org/abstract/document/9005186)]

* Deep Template Matching for Pedestrian Attribute Recognition with the Auxiliary Supervision of Attribute-wise Keypoints, Jiajun Zhang, Pengyuan Ren, Jianmin Li, [[arXiv](https://arxiv.org/pdf/2011.06798.pdf)]

* Gu, Z., Zhang, J., Pan, Z., Zhao, H., & Zhang, L. (2019, July). Clothes keypoints localization and attribute recognition via prior knowledge. In 2019 IEEE International Conference on Multimedia and Expo (ICME) (pp. 550-555). IEEE.[[Paper](https://sci-hub.st/https://ieeexplore.ieee.org/abstract/document/8785043/)]

* Ji, Z., Hu, Z., He, E., Han, J., & Pang, Y. (2020). Pedestrian Attribute Recognition Based on Multiple Time Steps Attention. Pattern Recognition Letters. [[PRL](https://sci-hub.st/https://www.sciencedirect.com/science/article/pii/S0167865520302646)]

* Texture and Shape Biased Two-Stream Networks for Clothing Classification and Attribute Recognition, Yuwei Zhang, Peng Zhang, Chun Yuan, Zhi Wang [[CVPR2020](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Texture_and_Shape_Biased_Two-Stream_Networks_for_Clothing_Classification_and_CVPR_2020_paper.html)]

* Hierarchical Feature Embedding for Attribute Recognition, Jie Yang, Jiarou Fan, Yiru Wang, Yige Wang, Weihao Gan, Lin Liu, Wei Wu [[CVPR2020](https://arxiv.org/pdf/2005.11576.pdf)] 

* Rethinking of Pedestrian Attribute Recognition: Realistic Datasets and A Strong Baseline, Jian Jia, Houjing Huang, Wenjie Yang, Xiaotang Chen, and Kaiqi Huang [[arXiv](https://arxiv.org/pdf/2005.11909.pdf)] [[Code](https://github.com/valencebond/Strong_Baseline_of_Pedestrian_Attribute_Recognition)] 

* Multi-Task Learning via Co-Attentive Sharing for Pedestrian Attribute Recognition, Haitian Zeng, Haizhou Ai, Zijie Zhuang, Long Chen, [[ICME 2020](https://arxiv.org/pdf/2004.03164.pdf)]

* Distraction-Aware Feature Learning for Human Attribute Recognition via Coarse-to-Fine Attention Mechanism, Mingda Wu (Beihang University)*; Di Huang (Beihang University, China); Yuanfang Guo (Beihang University); Yunhong Wang (State Key Laboratory of Virtual Reality Technology and System, Beihang University, Beijing 100191, China), AAAI-2020 [[Paper](https://arxiv.org/pdf/1911.11351)]

* Relation-Aware Pedestrian Attribute Recognition with Graph Convolutional Networks, Zichang Tan (NLPR); Yang Yang (Institute of Automation, Chinese Academy of Sciences); Jun Wan (NLPR, CASIA)*; Guodong Guo (West Virginia University); Stan Li (National Lab. of Pattern Recognition, China), AAAI-2020, [[Paper](https://sci-hub.tw/https://aaai.org/ojs/index.php/AAAI/article/view/6883)]

* An Attention-Based Deep Learning Model for Multiple Pedestrian Attributes Recognition, Ehsan Yaghoubi, Diana Borza, Jo˜ao Neves, Aruna Kumar, Hugo Proen¸ca, [[arXiv-Paper](https://arxiv.org/pdf/2004.01110.pdf)] [[Code](https://github.com/Ehsan-Yaghoubi/MAN-PAR-)]



### Year-2019

Zhang, S., Song, Z., Cao, X., Zhang, H., & Zhou, J. (2019). Task-aware attention model for clothing attribute prediction. IEEE Transactions on Circuits and Systems for Video Technology (T-CSVT), 30(4), 1051-1064. [[Paper](https://sci-hub.st/https://ieeexplore.ieee.org/abstract/document/8654674/)]

GSR-MAR: Global Super-Resolution for Person Multi-Attribute Recognition. Siadari, Thomhert Suprapto, Mikyong Han, and Hyunjin Yoon. 2019 IEEE/CVF International Conference on Computer Vision Workshop (ICCVW). IEEE, 2019.[[Paper](https://openaccess.thecvf.com/content_ICCVW_2019/papers/RLQ/Siadari_GSR-MAR_Global_Super-Resolution_for_Person_Multi-Attribute_Recognition_ICCVW_2019_paper.pdf)]

Distraction-Aware Feature Learning for Human Attribute Recognition via Coarse-to-Fine Attention Mechanism, Mingda Wu, Di Huang, Yuanfang Guo Yunhong Wang [[Paper]](https://arxiv.org/pdf/1911.11351.pdf) , AAAI-2020 oral presentation. 


Improving Pedestrian Attribute Recognition With Weakly-Supervised Multi-Scale Attribute-Specific Localization	Chufeng Tang, Lu Sheng, Zhaoxiang Zhang, Xiaolin Hu, ICCV-2019, [[Paper]](https://arxiv.org/pdf/1910.04562.pdf) [[Code](https://github.com/chufengt/iccv19_attribute)]

Ji, Zhong, Erlu He, Haoran Wang, and Aiping Yang. "[Image-attribute reciprocally guided attention network for pedestrian attribute recognition](https://www.sciencedirect.com/science/article/pii/S016786551830727X)" Pattern Recognition Letters 120 (2019): 89-95.

Zichang Tan, Yang Yang, Jun Wan, Yingyi Chen, Guodong Guo, Stan Z. Li. [Attention based Pedestrian Attribute Analysis](https://ieeexplore.ieee.org/document/8755326). IEEE TIP, 2019.

Qiaozhe Li, Xin Zhao, Ran He, Kaiqi Huang, [Pedestrian Attribute Recognition by Joint Visual-semantic Reasoning and Knowledge Distillation](https://www.ijcai.org/proceedings/2019/0117.pdf), IJCAI-2019. 

Kai Han, Yunhe Wang, Han Shu, Chuanjian Liu, Chunjing Xu, Chang Xu, [Attribute Aware Pooling for Pedestrian Attribute Recognition](https://drive.google.com/open?id=1qon05hq165YLy2TWr445nKt9qezrMEBa), IJCAI-2019 

Liuyu Xiang, Xiaoming Jin, Guiguang Ding, Jungong Han, Leida Li [Incremental Few-Shot Learning for Pedestrian Attribute Recognition](https://arxiv.org/pdf/1906.00330.pdf), IJCAI-2019. 

Esube Bekele and Wallace Lawson [The Deeper, the Better: Analysis of Person Attributes Recognition](https://arxiv.org/pdf/1901.03756), submitted to FG2019

Zhiyuan Chen, Annan Li, and Yunhong Wang, Video-Based Pedestrian Attribute Recognition, arXiv paper, 2019 [[Paper](https://arxiv.org/pdf/1901.05742.pdf)]

Wang, Yiru, Weihao Gan, Wei Wu, and Junjie Yan. [Dynamic Curriculum Learning for Imbalanced Data Classification](https://arxiv.org/pdf/1901.06783.pdf), ICCV 2019. 

Xin Zhao; Liufang Sang; guiguang ding; Jungong Han; Na Di; Chenggang Yan, [Recurrent Attention Model for Pedestrian Attribute Recognition](https://drive.google.com/open?id=18R4rCmJ4vTK6JQEKtPF4wTNrbuqQWTsT), AAAI-2019

Qiaozhe Li*; Xin Zhao; Ran He; KAIQI HUANG, [Visual-semantic Graph Reasoning for Pedestrian Attribute Recognition](https://drive.google.com/open?id=1acQHYIDxyN8bp1hFljccZrAJr355Gb0_), AAAI-2019 

Li, Dangwei, Zhang Zhang, Xiaotang Chen, and Kaiqi Huang. "[A richly annotated pedestrian dataset for person retrieval in real surveillance scenarios](https://ieeexplore.ieee.org/abstract/document/8510891)." IEEE transactions on image processing 28, no. 4 (2019): 1575-1590. 





### Year-2018 
Wang, Wenguan, et al. "Attentive fashion grammar network for fashion landmark detection and clothing category classification." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2018. [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Attentive_Fashion_Grammar_CVPR_2018_paper.pdf)

Li, Dangwei, Xiaotang Chen, Zhang Zhang, and Kaiqi Huang. "Pose Guided Deep Model for Pedestrian Attribute Recognition in Surveillance Scenarios." In 2018 IEEE International Conference on Multimedia and Expo (ICME), pp. 1-6. IEEE, 2018. Paper: http://dangweili.github.io/misc/pdfs/icme18.pdf

Chen, Tianshui, Zhouxia Wang, Guanbin Li, and Liang Lin. "Recurrent Attentional Reinforcement Learning for Multi-label Image Recognition." AAAI2018 Paper: http://www.linliang.net/wp-content/uploads/2018/01/AAAI2018_AttentionRL.pdf

Park, Seyoung, Bruce Xiaohan Nie, and Song-Chun Zhu. "Attribute and-or grammar for joint parsing of human pose, parts and attributes." IEEE transactions on pattern analysis and machine intelligence 40, no. 7 (2018): 1555-1569. 

Zhao, Xin, Liufang Sang, Guiguang Ding, Yuchen Guo, and Xiaoming Jin. "Grouping Attribute Recognition for Pedestrian with Joint Recurrent Learning." In IJCAI, pp. 3177-3183. 2018. Paper：https://www.ijcai.org/proceedings/2018/0441.pdf Code:https://github.com/slf12/GRLModel  

Sarafianos, Nikolaos, Theodoros Giannakopoulos, Christophoros Nikou, and Ioannis A. Kakadiaris. "Curriculum learning of visual attribute clusters for multi-task classification." Pattern Recognition 80 (2018): 94-108. 

Sarafianos, Nikolaos, Xiang Xu, and Ioannis A. Kakadiaris. "Deep Imbalanced Attribute Classification using Visual Attention Aggregation." In Proceedings of the European Conference on Computer Vision (ECCV), pp. 680-697. 2018. Paper: http://openaccess.thecvf.com/content_ECCV_2018/papers/Nikolaos_Sarafianos_Deep_Imbalanced_Attribute_ECCV_2018_paper.pdf Code: https://github.com/cvcode18/imbalanced_learning

Liu, Hao, Jingjing Wu, Jianguo Jiang, Meibin Qi, and Ren Bo. "Sequence-based Person Attribute Recognition with Joint CTC-Attention Model." arXiv preprint arXiv:1811.08115 (2018). 

Liu, P., Liu, X., Yan, J., & Shao, J. (2018). Localization guided learning for pedestrian attribute recognition. arXiv preprint arXiv:1808.09102. BMVC-paper




### Year-2017 
Fabbri, Matteo, Simone Calderara, and Rita Cucchiara. "Generative adversarial models for people attribute recognition in surveillance." In Advanced Video and Signal Based Surveillance (AVSS), 2017 14th IEEE International Conference on, pp. 1-6. IEEE, 2017. 

Guo, Qi, Ce Zhu, Zhiqiang Xia, Zhengtao Wang, and Yipeng Liu. "Attribute-controlled face photo synthesis from simple line drawing." In Image Processing (ICIP), 2017 IEEE International Conference on, pp. 2946-2950. IEEE, 2017. Paper

Hand, Emily M., and Rama Chellappa. "Attributes for Improved Attributes: A Multi-Task Network Utilizing Implicit and Explicit Relationships for Facial Attribute Classification." In AAAI, pp. 4068-4074. 2017.

Wang, Jingya, Xiatian Zhu, Shaogang Gong, and Wei Li. "Attribute Recognition by Joint Recurrent Learning of Context and Correlation." In Computer Vision (ICCV), 2017 IEEE International Conference on, pp. 531-540. IEEE, 2017.

Wang, Z., Chen, T., Li, G., Xu, R., & Lin, L. (2017, October). Multi-label Image Recognition by Recurrently Discovering Attentional Regions. In Computer Vision (ICCV), 2017 IEEE International Conference on (pp. 464-472). IEEE. Paper: http://openaccess.thecvf.com/content_ICCV_2017/papers/Wang_Multi-Label_Image_Recognition_ICCV_2017_paper.pdf Code: https://github.com/James-Yip/AttentionImageClass

Trigeorgis, George, Konstantinos Bousmalis, Stefanos Zafeiriou, and Björn W. Schuller. "A deep matrix factorization method for learning attribute representations." IEEE transactions on pattern analysis and machine intelligence 39, no. 3 (2017): 417-429.

Lin, Yutian, Liang Zheng, Zhedong Zheng, Yu Wu, and Yi Yang. "Improving person re-identification by attribute and identity learning." arXiv preprint arXiv:1703.07220 (2017).

Liu, Xihui, Haiyu Zhao, Maoqing Tian, Lu Sheng, Jing Shao, Shuai Yi, Junjie Yan, and Xiaogang Wang. "Hydraplus-net: Attentive deep features for pedestrian analysis." arXiv preprint arXiv:1709.09930 (2017). Code: https://github.com/xh-liu/HydraPlus-Net

Fouhey, David F., Abhinav Gupta, and Andrew Zisserman. "Understanding higher-order shape via 3D shape attributes." IEEE TPAMI (2017).

Zhou, Yang, Kai Yu, Biao Leng, Zhang Zhang, Dangwei Li, Kaiqi Huang, Bailan Feng, and Chunfeng Yao. "Weakly-supervised learning of mid-level features for pedestrian attribute recognition and localization." In BMVC. 2017. Paper: Code: https://github.com/YangZhou1994/WPAL-network

Su, Jong-Chyi, Chenyun Wu, Huaizu Jiang, and Subhransu Maji. "Reasoning about fine-grained attribute phrases using reference games." arXiv preprint arXiv:1708.08874 (2017).

Dong, Qi, Shaogang Gong, and Xiatian Zhu. "Multi-task curriculum transfer deep learning of clothing attributes." In Applications of Computer Vision (WACV), 2017 IEEE Winter Conference on, pp. 520-529. IEEE, 2017.

Kalayeh, Mahdi M., Boqing Gong, and Mubarak Shah. "Improving facial attribute prediction using semantic segmentation." In Computer Vision and Pattern Recognition (CVPR), 2017 IEEE Conference on, pp. 4227-4235. IEEE, 2017.

Lu, Yongxi, Abhishek Kumar, Shuangfei Zhai, Yu Cheng, Tara Javidi, and Rogério Schmidt Feris. "Fully-adaptive Feature Sharing in Multi-Task Networks with Applications in Person Attribute Classification." In CVPR, vol. 1, no. 2, p. 6. 2017. 

Guo, Hao, Xiaochuan Fan, and Song Wang. "Human attribute recognition by refining attention heat map." Pattern Recognition Letters 94 (2017): 38-45. 

Zhu, Jianqing, et al. "Multi-label convolutional neural network based pedestrian attribute classification." Image and Vision Computing 58 (2017): 224-229. 

Sarafianos, Nikolaos, Theodore Giannakopoulos, Christophoros Nikou, and Ioannis A. Kakadiaris. "Curriculum Learning for Multi-Task Classification of Visual Attributes." In Proceedings of the IEEE International Conference on Computer Vision, pp. 2608-2615. 2017. 

He, Keke, Zhanxiong Wang, Yanwei Fu, Rui Feng, Yu-Gang Jiang, and Xiangyang Xue. "Adaptively Weighted Multi-task Deep Network for Person Attribute Classification." In Proceedings of the 2017 ACM on Multimedia Conference, pp. 1636-1644. ACM, 2017. https://dl.acm.org/citation.cfm?id=3123424

Sarfraz, M. Saquib, Arne Schumann, Yan Wang, and Rainer Stiefelhagen. "Deep View-Sensitive Pedestrian Attribute Inference in an end-to-end Model." arXiv preprint arXiv:1707.06089 (2017). [[Paper]](https://arxiv.org/pdf/1707.06089.pdf), [[Code]](https://github.com/asc-kit/vespa)

Liu, Xihui, Haiyu Zhao, Maoqing Tian, Lu Sheng, Jing Shao, Shuai Yi, Junjie Yan, and Xiaogang Wang. "HydraPlus-Net: Attentive Deep Features for Pedestrian Analysis." In Proceedings of the IEEE International Conference on Computer Vision, pp. 350-359. 2017. Paper: http://openaccess.thecvf.com/content_ICCV_2017/papers/Liu_HydraPlus-Net_Attentive_Deep_ICCV_2017_paper.pdf Code: https://github.com/xh-liu/HydraPlus-Net






### Year-2016 
Li, Dangwei, Zhang Zhang, Xiaotang Chen, Haibin Ling, and Kaiqi Huang. "A richly annotated dataset for pedestrian attribute recognition." arXiv preprint arXiv:1603.07054 (2016). 

Yan, Xinchen, Jimei Yang, Kihyuk Sohn, and Honglak Lee. "Attribute2image: Conditional image generation from visual attributes." In European Conference on Computer Vision, pp. 776-791. Springer, Cham, 2016.

Li, Yining, Chen Huang, Chen Change Loy, and Xiaoou Tang. "Human attribute recognition by deep hierarchical contexts." In European Conference on Computer Vision, pp. 684-700. Springer, Cham, 2016.

Yang, L. , Zhu, L. , Wei, Y. , Liang, S. , & Tan, P. . (2016). Attribute recognition from adaptive parts.

Wang, Jiang, Yi Yang, Junhua Mao, Zhiheng Huang, Chang Huang, and Wei Xu. "Cnn-rnn: A unified framework for multi-label image classification." In Proceedings of the IEEE conference on computer vision and pattern recognition, pp. 2285-2294. 2016.

Fouhey, David F., Abhinav Gupta, and Andrew Zisserman. "3D shape attributes." In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pp. 1516-1524. 2016.

Wang, Jing, Yu Cheng, and Rogerio Schmidt Feris. "Walk and learn: Facial attribute representation learning from egocentric video and contextual data." In Proceedings of the IEEE conference on computer vision and pattern recognition, pp. 2295-2304. 2016.

Pedestrian Attribute Detection using CNN, Standford University, CS231n, 2016, Agrim Gupta and Jayanth Ramesh, Paper: http://cs231n.stanford.edu/reports/2016/pdfs/255_Report.pdf

Sudowe, Patrick, and Bastian Leibe. "PatchIt: Self-Supervised Network Weight Initialization for Fine-grained Recognition" In BMVC. 2016. 

Liu, Ziwei, Ping Luo, Shi Qiu, Xiaogang Wang, and Xiaoou Tang. "Deepfashion: Powering robust clothes recognition and retrieval with rich annotations." In Proceedings of the IEEE conference on computer vision and pattern recognition, pp. 1096-1104. 2016. 

Li, Mu, Wangmeng Zuo, and David Zhang. "Deep identity-aware transfer of facial attributes." arXiv preprint arXiv:1610.05586 (2016).

Diba, Ali, Ali Mohammad Pazandeh, Hamed Pirsiavash, and Luc Van Gool. "Deepcamp: Deep convolutional action & attribute mid-level patterns." In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pp. 3557-3565. 2016. 








### Year-2015 
Sudowe, Patrick, Hannah Spitzer, and Bastian Leibe. "Person attribute recognition with a jointly-trained holistic cnn model." In Proceedings of the IEEE International Conference on Computer Vision Workshops, pp. 87-95. 2015.

Park, Seyoung, and Song-Chun Zhu. "Attributed grammars for joint estimation of human attributes, part and pose." In Proceedings of the IEEE International Conference on Computer Vision, pp. 2372-2380. 2015.

Gkioxari, Georgia, Ross Girshick, and Jitendra Malik. "Actions and attributes from wholes and parts." In Proceedings of the IEEE International Conference on Computer Vision, pp. 2470-2478. 2015.

Deng, Y., Luo, P., Loy, C. C., & Tang, X. (2015). Learning to recognize pedestrian attribute. arXiv preprint arXiv:1501.00901.Paper

Zhu, Jianqing, Shengcai Liao, Dong Yi, Zhen Lei, and Stan Z. Li. "Multi-label cnn based pedestrian attribute learning for soft biometrics." In Biometrics (ICB), 2015 International Conference on, pp. 535-540. IEEE, 2015.

Yamaguchi, Kota, Takayuki Okatani, Kyoko Sudo, Kazuhiko Murasaki, and Yukinobu Taniguchi. "Mix and Match: Joint Model for Clothing and Attribute Recognition." In BMVC, vol. 1, no. 2, p. 4. 2015.

Li, Dangwei, Xiaotang Chen, and Kaiqi Huang. "Multi-attribute learning for pedestrian attribute recognition in surveillance scenarios." In Pattern Recognition (ACPR), 2015 3rd IAPR Asian Conference on, pp. 111-115. IEEE, 2015.

Hall, David, and Pietro Perona. "Fine-grained classification of pedestrians in video: Benchmark and state of the art." In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pp. 5482-5491. 2015.

Abdulnabi, Abrar H., Gang Wang, Jiwen Lu, and Kui Jia. "Multi-task CNN model for attribute prediction." IEEE Transactions on Multimedia 17, no. 11 (2015): 1949-1959.





### Before Year-2015  
Deng, Yubin, Ping Luo, Chen Change Loy, and Xiaoou Tang. "Pedestrian attribute recognition at far distance." In Proceedings of the 22nd ACM international conference on Multimedia, pp. 789-792. ACM, 2014. 

Zhang, Ning, Manohar Paluri, Marc'Aurelio Ranzato, Trevor Darrell, and Lubomir Bourdev. "Panda: Pose aligned networks for deep attribute modeling." In Proceedings of the IEEE conference on computer vision and pattern recognition, pp. 1637-1644. 2014. 

Lampert, Christoph H., Hannes Nickisch, and Stefan Harmeling. "Attribute-based classification for zero-shot visual object categorization." IEEE Transactions on Pattern Analysis and Machine Intelligence 36, no. 3 (2014): 453-465.

Zhu, Jianqing, Shengcai Liao, Zhen Lei, Dong Yi, and Stan Li. "Pedestrian attribute classification in surveillance: Database and evaluation." In Proceedings of the IEEE International Conference on Computer Vision Workshops, pp. 331-338. 2013. 

Joo, Jungseock, Shuo Wang, and Song-Chun Zhu. "Human attribute recognition by rich appearance dictionary." In Proceedings of the IEEE International Conference on Computer Vision, pp. 721-728. 2013. Paper

Chen, Huizhong, Andrew Gallagher, and Bernd Girod. "Describing clothing by semantic attributes." European conference on computer vision. Springer, Berlin, Heidelberg, 2012.

Sharma, G. and Jurie, F., 2011, August. Learning discriminative spatial representation for image classification. In BMVC 2011-British Machine Vision Conference (pp. 1-11). BMVA Press. 

Bourdev, Lubomir, Subhransu Maji, and Jitendra Malik. "Describing people: A poselet-based approach to attribute classification." In Computer Vision (ICCV), 2011 IEEE International Conference on, pp. 1543-1550. IEEE, 2011.

 





















## Applications (Person Attribute based Tasks)
## Person Re-ID based on Attributes 

* Specker, Andreas, and Jürgen Beyerer. "**Balanced pedestrian attribute recognition for improved attribute-based person retrieval.**"
  2023 IEEE 13th International Conference on Pattern Recognition Systems (ICPRS). IEEE, 2023.
  [[Paper](https://ieeexplore.ieee.org/abstract/document/10178990)] 

* **Instruct-ReID: A Multi-purpose Person Re-identification Task with Instructions**, Weizhen He, Yiheng Deng, Shixiang Tang, Qihao Chen, Qingsong Xie, Yizhou Wang, Lei Bai, Feng Zhu, Rui Zhao, Wanli Ouyang, Donglian Qi, Yunfeng Yan
  [[Paper](https://arxiv.org/abs/2306.07520)]
  [[Code](https://github.com/hwz-zju/Instruct-ReID)] 

* T. Chai, Z. Chen, A. Li, J. Chen, X. Mei and Y. Wang, "**Video Person Re-identification Using Attribute-enhanced Features**," in IEEE Transactions on Circuits and Systems for Video Technology, 2022, doi: 10.1109/TCSVT.2022.3189027. [[Paper](https://ieeexplore.ieee.org/abstract/document/9817378)]

Attribute Guided Sparse Tensor-Based Model for Person Re-Identification, Fariborz Taherkhani, Ali Dabouei, Sobhan Soleymani, Jeremy Dawson, Nasser M. Nasrabadi, [[Paper](https://arxiv.org/abs/2108.04352)]

ASMR: Learning Attribute-Based Person Search with Adaptive Semantic Margin Regularizer, Boseung Jeong, Jicheol Park, Suha Kwak, ICCV-2021 [[Paper](https://arxiv.org/abs/2108.04533)]

Han, Kai, Jianyuan Guo, Chao Zhang, and Mingjian Zhu. "[Attribute-aware attention model for fine-grained representation learning](https://dl.acm.org/citation.cfm?id=3240550)" In 2018 ACM Multimedia Conference on Multimedia Conference, pp. 2040-2048. ACM, 2018. 

Su, Chi, Shiliang Zhang, Junliang Xing, Wen Gao, and Qi Tian. "[Deep attributes driven multi-camera person re-identification](https://arxiv.org/pdf/1605.03259)." In European conference on computer vision, pp. 475-491. Springer, Cham, 2016.

Layne, Ryan, Timothy M. Hospedales, and Shaogang Gong. "[Towards person identification and re-identification with attributes](https://www.researchgate.net/profile/Timothy_Hospedales/publication/262167008_Towards_Person_Identification_and_Re-identification_with_Attributes/links/55c1df5708aeb5e0c58415e6.pdf)." In European Conference on Computer Vision, pp. 402-412. Springer, Berlin, Heidelberg, 2012.

Layne, Ryan, Timothy M. Hospedales, Shaogang Gong, and Q. Mary. "[Person re-identification by attributes](https://www.researchgate.net/profile/Timothy_Hospedales/publication/235624133_Person_Re-identification_by_Attributes/links/02bfe511f930e214d6000000/Person-Re-identification-by-Attributes.pdf)." In Bmvc, vol. 2, no. 3, p. 8. 2012.

Lin, Yutian, Liang Zheng, Zhedong Zheng, Yu Wu, Zhilan Hu, Chenggang Yan, and Yi Yang. "[Improving person re-identification by attribute and identity learning](https://www.sciencedirect.com/science/article/pii/S0031320319302377)." Pattern Recognition (2019).

Khamis, Sameh, Cheng-Hao Kuo, Vivek K. Singh, Vinay D. Shet, and Larry S. Davis. "[Joint learning for attribute-consistent person re-identification](http://www.samehkhamis.com/khamis-eccvw2014.pdf)." In European Conference on Computer Vision, pp. 134-146. Springer, Cham, 2014.

Layne, Ryan, Timothy M. Hospedales, and Shaogang Gong. "[Attributes-based re-identification](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.638.3544&rep=rep1&type=pdf)." In Person Re-Identification, pp. 93-117. Springer, London, 2014.

Li, Annan, Luoqi Liu, Kang Wang, Si Liu, and Shuicheng Yan. "[Clothing attributes assisted person reidentification](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6887366)." IEEE Transactions on Circuits and Systems for Video Technology 25, no. 5 (2015): 869-878.

Schumann, Arne, and Rainer Stiefelhagen. "[Person re-identification by deep learning attribute-complementary information](http://openaccess.thecvf.com/content_cvpr_2017_workshops/w17/papers/Schumann_Person_Re-Identification_by_CVPR_2017_paper.pdf)." In Computer Vision and Pattern Recognition Workshops (CVPRW), 2017 IEEE Conference on, pp. 1435-1443. IEEE, 2017. 

Shuzhao Li, Huimin Yu, Wei Huang, Jing Zhang, [Attributes-aided Part Detection and Refinement for Person Re-identification](https://arxiv.org/pdf/1902.10528.pdf), Zhejiang University, arXiv paper-2019 

Ling, Hefei, Ziyang Wang, Ping Li, Yuxuan Shi, Jiazhong Chen, and Fuhao Zou. "[Improving person re-identification by multi-task learning](https://reader.elsevier.com/reader/sd/pii/S0925231219300396?token=AA140DBCBF5089012B0D0E5A6366D024B996E47F657914AD7D1A93DF3DCFD2C270872BBB2D534FEEC39AF612CE47FC0C)." Neurocomputing 347 (2019): 109-118. 

Su, Chi, Shiliang Zhang, Fan Yang, Guangxiao Zhang, Qi Tian, Wen Gao, and Larry S. Davis. "[Attributes driven tracklet-to-tracklet person re-identification using latent prototypes space mapping](https://www.sciencedirect.com/science/article/pii/S0031320317300067)." Pattern Recognition 66 (2017): 4-15.



## Pedestrian Detection based on Attributes
Tian, Yonglong, Ping Luo, Xiaogang Wang, and Xiaoou Tang. "[Pedestrian detection aided by deep learning semantic tasks](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Tian_Pedestrian_Detection_Aided_2015_CVPR_paper.pdf)." In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pp. 5079-5087. 2015.

## Person Retrieval based on Attributes
Wang, Xianwang, Tong Zhang, Daniel R. Tretter, and Qian Lin. "[Personal clothing retrieval on photo collections by color and attributes](https://ieeexplore.ieee.org/abstract/document/6585791)." IEEE Transactions on Multimedia 15, no. 8 (2013): 2035-2045.

Feris, Rogerio, Russel Bobbitt, Lisa Brown, and Sharath Pankanti. "[Attribute-based people search: Lessons learnt from a practical surveillance system](https://dl.acm.org/citation.cfm?id=2578732)." In Proceedings of International Conference on Multimedia Retrieval, p. 153. ACM, 2014.

## Action Recognition and Scene Understanding
Liu, Jingen, Benjamin Kuipers, and Silvio Savarese. "Recognizing human actions by attributes." In Computer Vision and Pattern Recognition (CVPR), 2011 IEEE Conference on, pp. 3337-3344. IEEE, 2011.

Shao, Jing, Kai Kang, Chen Change Loy, and Xiaogang Wang. "Deeply learned attributes for crowded scene understanding." In Proceedings of the IEEE conference on computer vision and pattern recognition, pp. 4657-4666. 2015.





## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=wangxiao5791509/Pedestrian-Attribute-Recognition-Paper-List&type=Date)](https://star-history.com/#wangxiao5791509/Pedestrian-Attribute-Recognition-Paper-List&Date)


