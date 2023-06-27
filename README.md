<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>

# Paper List


## Papers 📰


### Large Language Models (LLMs) 🛰

[[link](./llm-note.md)]

+ **A Survey on In-context Learning.**

    *Qingxiu Dong, Lei Li, Damai Dai, Ce Zheng, Zhiyong Wu, Baobao Chang, Xu Sun, Jingjing Xu, Lei Li, Zhifang Sui.* **arxiv, 2023.** [[pdf](./documents/2023.A%20Survey%20on%20In-context%20Learning.pdf)] [[arxiv](https://arxiv.org/abs/2301.00234)] [[project](https://github.com/dqxiu/ICL_PaperList)]

+ **Finetuned Language Models Are Zero-Shot Learners.**

    *Jason Wei, Maarten Bosma, Vincent Y. Zhao, Kelvin Guu, Adams Wei Yu, Brian Lester, Nan Du, Andrew M. Dai, Quoc V. Le.* **ICLR, 2022.** [[pdf](./documents/2022.Finetuned%20Language%20Models%20Are%20Zero-Shot%20Learners.pdf)] [[arxiv](https://arxiv.org/abs/2109.01652)]

    Proposed instruction tuning and conducted experiments on many tasks.

+ **Learning to summarize from human feedback.**

    *Nisan Stiennon, Long Ouyang, Jeff Wu, Daniel M. Ziegler, Ryan Lowe, Chelsea Voss, Alec Radford, Dario Amodei, Paul Christiano.* **NeurIPS, 2020.** [[pdf](./documents/2020.Learning%20to%20summarize%20from%20human%20feedback.pdf)] [[arxiv](https://arxiv.org/abs/2009.01325)] [[project](https://github.com/openai/summarize-from-feedback)] [[samples](https://openaipublic.blob.core.windows.net/summarize-from-feedback/website/index.html#/)]

    Summarize with RLHF.

+ **Training language models to follow instructions with human feedback.**

    *Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Chong Zhang, Sandhini Agarwal, Katarina Slama, Alex Ray, John Schulman, Jacob Hilton, Fraser Kelton, Luke Miller, Maddie Simens, Amanda Askell, Peter Welinder, Paul Christiano, Jan Leike, Ryan Lowe.* **NeurIPS, 2022.** [[pdf](./documents/2022.InstructGPT.pdf)] [[arxiv](https://arxiv.org/abs/2203.02155)] [[blog](https://openai.com/research/instruction-following)]

+ **Scaling Laws for Reward Model Overoptimization.**

    *Leo Gao, John Schulman, Jacob Hilton.* **arxiv, 2022.** [[pdf](./documents/2022.Scaling%20Laws%20for%20Reward%20Model%20Overoptimization.pdf)] [[arxiv](https://arxiv.org/abs/2210.107605)]

    About over-optimization in RLHF.

+ **From Zero to Hero: Examining the Power of Symbolic Tasks in Instruction Tuning.**

    *Qian Liu, Fan Zhou, Zhengbao Jiang, Longxu Dou, Min Lin.* **arxiv, 2023.** [[pdf](./documents/2023.From%20Zero%20to%20Hero-Examining%20the%20Power%20of%20Symbolic%20Tasks%20in%20Instruction%20Tuning.pdf)] [[arxiv](https://arxiv.org/abs/2304.07995)] [[project](https://github.com/sail-sg/symbolic-instruction-tuning)]

    This paper introduces a straightforward yet effective method for enhancing instruction tuning by employing symbolic tasks.

+ **Chain-of-Thought Prompting Elicits Reasoning in Large Language Models.**

    *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou.* **NeurIPS, 2022.** [[pdf](./documents/2022.Chain-of-Thought%20Prompting%20Elicits%20Reasoning%20in%20Large%20Language%20Models.pdf)] [[arxiv](https://arxiv.org/abs/2201.11903)]

+ **Emergent Abilities of Large Language Models.**

    *Jason Wei, Yi Tay, Rishi Bommasani, Colin Raffel, Barret Zoph, Sebastian Borgeaud, Dani Yogatama, Maarten Bosma, Denny Zhou, Donald Metzler, Ed H. Chi, Tatsunori Hashimoto, Oriol Vinyals, Percy Liang, Jeff Dean, William Fedus.* **Transactions on Machine Learning Research (TMLR), 2022.** [[pdf](./documents/2022.Emergent%20Abilities%20of%20Large%20Language%20Models.pdf)] [[arxiv](https://arxiv.org/abs/2206.07682)]

    + definition of emergent abilities of LLMs: *An ability is emergent if it is not present in smaller models but is present in larger models.*

    + few-shot prompting (in-context learning ability)

    + augmented prompting strategies (CoT prompting, instruction following without exemplars/demonstrations and so on)

+ **Toolformer: Language Models Can Teach Themselves to Use Tools.**

    *Timo Schick, Jane Dwivedi-Yu, Roberto Dessì, Roberta Raileanu, Maria Lomeli, Luke Zettlemoyer, Nicola Cancedda, Thomas Scialom.* **arxiv, 2023.** [[pdf](./documents/2023.Toolformer.pdf)] [[arxiv](https://arxiv.org/abs/2302.04761)]

+ **Tool Learning with Foundation Models.**

    *Yujia Qin, Shengding Hu, Yankai Lin, Weize Chen, Ning Ding, Ganqu Cui, Zheni Zeng, Yufei Huang, Chaojun Xiao, Chi Han, Yi Ren Fung, Yusheng Su, Huadong Wang, Cheng Qian, Runchu Tian, Kunlun Zhu, Shihao Liang, Xingyu Shen, Bokai Xu, Zhen Zhang, Yining Ye, Bowen Li, Ziwei Tang, Jing Yi, Yuzhang Zhu, Zhenning Dai, Lan Yan, Xin Cong, Yaxi Lu, Weilin Zhao, Yuxiang Huang, Junxi Yan, Xu Han, Xian Sun, Dahai Li, Jason Phang, Cheng Yang, Tongshuang Wu, Heng Ji, Zhiyuan Liu, Maosong Sun.* **arxiv, 2023.** [[pdf](./documents/2023.Tool%20Learning%20with%20Foundation%20Models.pdf)] [[arxiv](https://arxiv.org/abs/2304.08354)] [[project](https://github.com/OpenBMB/BMTools)]

+ **GLM: General Language Model Pretraining with Autoregressive Blank Infilling.**

    *Zhengxiao Du, Yujie Qian, Xiao Liu, Ming Ding, Jiezhong Qiu, Zhilin Yang, Jie Tang.* **ACL, 2022.** [[pdf](./documents/2022.GLM.pdf)] [[acl](https://aclanthology.org/2022.acl-long.26/)] [[arxiv](https://arxiv.org/abs/2103.10360)] [[project](https://github.com/THUDM/GLM)]

    GLM is a General Language Model pretrained with an autoregressive blank-filling objective and can be finetuned on various natural language understanding and generation tasks. 

    Seems like the perturbation language modeling in XLNet. (*Zhilin Yang* is the co-first author of XLNet.)

+ **GLM-130B: An Open Bilingual Pre-trained Model.**

    *Aohan Zeng, Xiao Liu, Zhengxiao Du, Zihan Wang, Hanyu Lai, Ming Ding, Zhuoyi Yang, Yifan Xu, Wendi Zheng, Xiao Xia, Weng Lam Tam, Zixuan Ma, Yufei Xue, Jidong Zhai, Wenguang Chen, Peng Zhang, Yuxiao Dong, Jie Tang.* **ICLR, 2023.** [[pdf](./documents/2022.GLM-130B.pdf)] [[arxiv](https://arxiv.org/abs/2210.02414)] [[project](https://github.com/THUDM/GLM-130B)]

    GLM as backbone. A bilingual (English and Chinese) pre-trained language model with 130 billion parameters from Tsinghua and Zhipu. They released ChatGLM-6B in March 2023. ChatGLM-6B is an open bilingual language model based on General Language Model (GLM) framework, with 6.2 billion parameters. Related information about ChatGLM: [[blog](https://chatglm.cn/blog)] [[project](https://github.com/THUDM/ChatGLM-6B)]

+ **LLaMA: Open and Efficient Foundation Language Models.**

    *Hugo Touvron, Thibaut Lavril, Gautier Izacard, Xavier Martinet, Marie-Anne Lachaux, Timothée Lacroix, Baptiste Rozière, Naman Goyal, Eric Hambro, Faisal Azhar, Aurelien Rodriguez, Armand Joulin, Edouard Grave, Guillaume Lample.* **arxiv, 2023.** [[pdf](./documents/2023.LLaMA.pdf)] [[arxiv](https://arxiv.org/abs/2302.13971)] [[project](https://github.com/facebookresearch/llama)]

    A series of LLMs (7B, 13B, 33B, 65B) from Meta AI.

+ **PaLM 2 Technical Report.**

    *Rohan Anil, Andrew M. Dai, Orhan Firat, Melvin Johnson and many authors.* **arxiv, 2023.** [[pdf](./documents/2023.PaLM%202%20Technical%20Report.pdf)] [[arxiv](https://arxiv.org/abs/2305.10403)]

+ **Harnessing the Power of LLMs in Practice: A Survey on ChatGPT and Beyond.**

    *Jingfeng Yang, Hongye Jin, Ruixiang Tang, Xiaotian Han, Qizhang Feng, Haoming Jiang, Bing Yin, Xia Hu.* **arxiv, 2023.** [[pdf](./documents/2023.Harnessing%20the%20Power%20of%20LLMs%20in%20Practice-A%20Survey%20on%20ChatGPT%20and%20Beyond.pdf)] [[arxiv](https://arxiv.org/abs/2210.02414)] [[project](https://github.com/Mooler0410/LLMsPracticalGuide)]

    Authors also provide a curated list of practical guide resources for LLMs. 
    
    ~~It's an evolutionary tree of modern LLMs.~~ (The taxonomy and nomenclature may be confusing sometimes, so I do not refer to the tree diagram here.)

    Moreover, they build a decision flow for choosing LLMs or fine-tuned models for user's NLP applications. The decision flow helps users assess whether their downstream NLP applications at hand meet specific conditions and, based on that evaluation, determine whether LLMs or fine-tuned models are the most suitable choice for their applications.
    <img src="./notes/pics/llm-decision-flow.png" alt="alt text" title="Optional title" width="90%" />


### Parameter-Efficient Fine-Tuning 🛩

+ **LoRA: Low-Rank Adaptation of Large Language Models.**

    *Edward J. Hu, Yelong Shen, Phillip Wallis, Zeyuan Allen-Zhu, Yuanzhi Li, Shean Wang, Lu Wang, Weizhu Chen.* **arxiv, 2021.** [[pdf](./documents/2021.LoRA-low-rank-adaptation.pdf)] [[arxiv](https://arxiv.org/abs/2106.09685)]

    A low-rank approximation method for parameter-efficient fine-tuning.

    $$
        W = W + \Delta W, W \in \mathbb{R}^{d \times d} \notag \\
        \Delta W = A B, A \in \mathbb{R}^{d \times r}, B \in \mathbb{R}^{r \times d} \notag \\
    $$

+ **Towards a Unified View of Parameter-Efficient Transfer Learning.**

    *Junxian He, Chunting Zhou, Xuezhe Ma, Taylor Berg-Kirkpatrick, Graham Neubig.* **ICLR, 2022.** [[pdf](./documents/2021.Towards%20a%20Unified%20View%20of%20Parameter-Efficient%20Transfer%20Learning.pdf)] [[arxiv](https://arxiv.org/abs/2110.04366)] [[project](https://github.com/jxhe/unify-parameter-efficient-tuning)]

    It provides a unified view of three representative PEFT methods (adapter, prefix tuning and LoRA). Authors also proposed three variants: Parallel Adapter, Multi-head Parallel Adapter and Scaled Parallel Adapter and conducted further experiments and discussions. Insightful.


### Model Architecture / Training and Tuning / Decoding 🚋

+ **Attention is All You Need.**

    *Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, Illia Polosukhin.* **NIPS, 2017.** [[pdf](./documents/2017.Attention%20Is%20All%20You%20Need.pdf)] [[arxiv](https://arxiv.org/abs/1706.03762)]

    Transformer, a model architecture.

+ **Modeling Relational Data with Graph Convolutional Networks.**

    *Michael Schlichtkrull, Thomas N. Kipf, Peter Bloem, Rianne van den Berg, Ivan Titov, Max Welling.* **European Semantic Web Conference (ESWC), 2018.** [[pdf](./documents/2017.Modeling%20Relational%20Data%20with%20Graph%20Convolutional%20Networks.pdf)] [[arxiv](https://arxiv.org/abs/1703.06103)]

    Relational GCN.

+ **NeuroLogic Decoding: (Un)supervised Neural Text Generation with Predicate Logic Constraints.**

    *Ximing Lu, Peter West, Rowan Zellers, Ronan Le Bras, Chandra Bhagavatula, Yejin Choi.* **NAACL, 2021.** [[pdf](./documents/2021.NeuroLogic%20Decoding.pdf)] [[acl](https://aclanthology.org/2021.naacl-main.339/)] [[arxiv](https://arxiv.org/abs/2010.12884)]

+ **NeuroLogic A\*esque Decoding: Constrained Text Generation with Lookahead Heuristics.**

    *Ximing Lu, Sean Welleck, Peter West, Liwei Jiang, Jungo Kasai, Daniel Khashabi, Ronan Le Bras, Lianhui Qin, Youngjae Yu, Rowan Zellers, Noah A. Smith, Yejin Choi.* **NAACL, 2022.** [[pdf](./documents/2022.NeuroLogic%20Aesque%20Decoding.pdf)] [[acl](https://aclanthology.org/2022.naacl-main.57/)] [[arxiv](https://arxiv.org/abs/2112.08726)]


### Information Extraction / Script Learning 🛴

+ **A survey of script learning.**

    *Yi Han, Linbo Qiao, Jianming Zheng, Hefeng Wu, Dongsheng Li, Xiangke Liao.* **Frontiers of Information Technology & Electronic Engineering, 2021.** [[pdf](./documents/2021.A%20survey%20of%20script%20learning.pdf)] [[journal website](https://journal.hep.com.cn/ckcest/fitee/EN/10.1631/FITEE.2000347)]

+ **What Happens Next? Event Prediction Using a Compositional Neural Network Model.**

    *Mark Granroth-Wilding, Stephen Clark.* **AAAI, 2016.** [[pdf](./documents/2016.What%20Happens%20Next%20Event%20Prediction%20Using%20a%20Compositional%20Neural%20Network%20Model.pdf)] [[aaai](https://ojs.aaai.org/index.php/AAAI/article/view/10344)] 

+ **Multi-Relational Script Learning for Discourse Relations.**

    *I-Ta Lee, Dan Goldwasser.* **ACL, 2019.** [[pdf](./documents/2019.Multi-Relational%20Script%20Learning%20for%20Discourse%20Relations.pdf)] [[acl](https://aclanthology.org/P19-1413/)] [[project](https://github.com/doug919/multi_relational_script_learning)]

+ **Weakly-Supervised Modeling of Contextualized Event Embedding for Discourse Relations.**

    *I-Ta Lee, Maria Leonor Pacheco, Dan Goldwasser.* **Findings of EMNLP, 2020.** [[pdf](./documents/2020.Weakly-Supervised%20Modeling%20of%20Contextualized%20Event%20Embedding.pdf)] [[acl](https://aclanthology.org/2020.findings-emnlp.446/)] [[project](https://github.com/doug919/narrative_graph_emnlp2020)]

+ **Modeling Human Mental States with an Entity-based Narrative Graph.**

    *I-Ta Lee, Maria Leonor Pacheco, Dan Goldwasser.* **NAACL, 2021.** [[pdf](./documents/2021.Modeling%20Human%20Mental%20States%20with%20an%20Entity-based%20Narrative%20Graph.pdf)] [[acl](https://aclanthology.org/2021.naacl-main.391/)] [[arxiv](https://arxiv.org/abs/2104.07079)] [[project](https://github.com/doug919/entity_based_narrative_graph)]

+ **A Survey on Deep Learning Event Extraction: Approaches and Applications.**

    *Qian Li, Jianxin Li, Jiawei Sheng, Shiyao Cui, Jia Wu, Yiming Hei, Hao Peng, Shu Guo, Lihong Wang, Amin Beheshti, Philip S. Yu.* **IEEE TNNLS, 2021.** [[pdf-v6-2022.11](./documents/2022.A%20Survey%20on%20Deep%20Learning%20Event%20Extraction-Approaches%20and%20Applications.pdf)] [[pdf-v1-2021.07](./documents/2021.A%20Compact%20Survey%20on%20Event%20Extraction%20Approaches%20and%20Applications.pdf)] [[arxiv](https://arxiv.org/abs/2107.02126)]

+ **Open Domain Event Extraction Using Neural Latent Variable Models.**

    *Xiao Liu, Heyan Huang, Yue Zhang.* **ACL, 2019.** [[pdf](./documents/2019.Open%20Domain%20Event%20Extraction%20Using%20Neural%20Latent%20Variable%20Models.pdf)] [[acl](https://aclanthology.org/P19-1276/)] [[arxiv](https://arxiv.org/abs/1906.06947)] [[project](https://github.com/lx865712528/ACL2019-ODEE)]

+ **Entity, Relation, and Event Extraction with Contextualized Span Representations.**

    *David Wadden, Ulme Wennberg, Yi Luan, Hannaneh Hajishirzi.* **EMNLP-IJCNLP, 2019.** [[pdf](./documents/2019.DyGIE%2B%2B.pdf)] [[acl](https://aclanthology.org/D19-1585/)] [[project](https://github.com/dwadden/dygiepp)]

    DyGIE++.

+ **Event Extraction as Machine Reading Comprehension.**

    *Jian Liu, Yubo Chen, Kang Liu, Wei Bi, Xiaojiang Liu.* **EMNLP, 2020.** [[pdf](./documents/2020.Event%20Extraction%20as%20Machine%20Reading%20Comprehension.pdf)] [[acl](https://aclanthology.org/2020.emnlp-main.128/)] [[project](https://github.com/jianliu-ml/EEasMRC)]

+ **A Joint Neural Model for Information Extraction with Global Features.**

    *Ying Lin, Heng Ji, Fei Huang, Lingfei Wu.* **ACL, 2020.** [[pdf](./documents/2020.oneie.pdf)] [[acl](https://aclanthology.org/2020.acl-main.713/)] [[official website](http://blender.cs.illinois.edu/software/oneie/)]

    OneIE.

+ **Text2Event: Controllable Sequence-to-Structure Generation for End-to-end Event Extraction.**

    *Yaojie Lu, Hongyu Lin, Jin Xu, Xianpei Han, Jialong Tang, Annan Li, Le Sun, Meng Liao, Shaoyi Chen.* **ACL-IJCNLP, 2021.** [[pdf](./documents/2021.Text2Event.pdf)] [[acl](https://aclanthology.org/2021.acl-long.217/)] [[arxiv](https://arxiv.org/abs/2106.09232)] [[project](https://github.com/luyaojie/Text2Event)]

    Formulate event extraction as a sequence-to-structure generation task.

+ **Unified Structure Generation for Universal Information Extraction.**

    *Yaojie Lu, Qing Liu, Dai Dai, Xinyan Xiao, Hongyu Lin, Xianpei Han, Le Sun, Hua Wu.* **ACL, 2022.** [[pdf](./documents/2022.Unified%20Structure%20Generation%20for%20Universal%20Information%20Extraction.pdf)] [[acl](https://aclanthology.org/2022.acl-long.395/)] [[arxiv](https://arxiv.org/abs/2203.12277)] [[project](https://github.com/universal-ie/UIE)]

    Namely UIE. Phrase four infomation extraction tasks (RE, NER, EE, and IE) as a unified structure generation task. In PaddleNLP from Baidu Inc., UIE is implemented in two ways:

    + extraction (prompt + MRC): An ERNIE model with two linear layers on top of the hidden states output to compute `start_prob` and `end_prob`. [[implementation](https://github.com/PaddlePaddle/PaddleNLP/blob/413fd2fd5f8a8e43ba6dad7d20b54f37f0af619c/paddlenlp/transformers/ernie/modeling.py#L1219)]

    + sequence-to-structure: The way in original paper. [[implementation](https://github.com/PaddlePaddle/PaddleNLP/tree/develop/examples/information_extraction/DuUIE)]

+ **Zero-Shot Information Extraction via Chatting with ChatGPT.**

    *Xiang Wei, Xingyu Cui, Ning Cheng, Xiaobin Wang, Xin Zhang, Shen Huang, Pengjun Xie, Jinan Xu, Yufeng Chen, Meishan Zhang, Yong Jiang, Wenjuan Han.* **arxiv, 2023.** [[pdf](./documents/2023.Zero-Shot%20Information%20Extraction%20via%20Chatting%20with%20ChatGPT.pdf)] [[arxiv](https://arxiv.org/abs/2302.10205)]

    This paper transforms the zero-shot IE task into a multi-turn QA problem with a two-stage framework named ChatIE (based-on ChatGPT). Experiments are conducted on RE, NER and EE tasks across two languages (English and Chinese).

+ **InstructUIE: Multi-task Instruction Tuning for Unified Information Extraction.**

    *Xiao Wang, Weikang Zhou, Can Zu, Han Xia, Tianze Chen, Yuansen Zhang, Rui Zheng, Junjie Ye, Qi Zhang, Tao Gui, Jihua Kang, Jingsheng Yang, Siyuan Li, Chunsai Du.* **arxiv, 2023.** [[pdf](./documents/2023.InstructUIE.pdf)] [[arxiv](https://arxiv.org/abs/2304.08085)] [[project](https://github.com/BeyonderXX/InstructUIE)]

    Flan-T5 (11B) as backbone.


### Event Relation Identification (Extraction/Classification) 🌱

+ **Modeling Document-level Causal Structures for Event Causal Relation Identification.**

    *Lei Gao, Prafulla Kumar Choubey, Ruihong Huang.* **NAACL, 2019.** [[pdf](./documents/2019.Modeling%20Document-level%20Causal%20Structures%20for%20Event%20Causal%20Relation%20Identification.pdf)] [[acl](https://aclanthology.org/N19-1179/)]

+ **Graph Convolutional Networks for Event Causality Identification with Rich Document-level Structures.**

    *Minh Tran Phu, Thien Huu Nguyen.* **NAACL, 2021.** [[pdf](./documents/2021.Graph%20Convolutional%20Networks%20for%20Event%20Causality%20Identification%20with%20Rich%20Document-level%20Structures.pdf)] [[acl](https://aclanthology.org/2021.naacl-main.273/)]


### Event Type Induction / Event Schema Induction 🚲

+ **The Future is not One-dimensional: Complex Event Schema Induction by Graph Modeling for Event Prediction.**

    *Manling Li, Sha Li, Zhenhailong Wang, Lifu Huang, Kyunghyun Cho, Heng Ji, Jiawei Han, Clare Voss.* **EMNLP, 2021.** [[pdf](./documents/2021.Complex%20Event%20Schema%20Induction%20by%20Graph%20Modeling%20for%20Event%20Prediction.pdf)] [[acl](https://aclanthology.org/2021.emnlp-main.422/)] [[arxiv](https://arxiv.org/abs/2104.06344)] [[project](https://github.com/limanling/temporal-graph-schema)] [[note](./notes/2021.The%20Future%20is%20not%20One-dimensional-Complex%20Event%20Schema%20Induction%20by%20Graph%20Modeling%20for%20Event%20Prediction.md)]

    (no codes, only data)

+ **Corpus-based Open-Domain Event Type Induction.**

    *Jiaming Shen, Yunyi Zhang, Heng Ji, Jiawei Han.* **EMNLP, 2021.** [[pdf](./documents/2021.Corpus-based%20Open-Domain%20Event%20Type%20Induction.pdf)] [[acl](https://aclanthology.org/2021.emnlp-main.441/)] [[arxiv](https://arxiv.org/abs/2109.03322)] [[project](https://github.com/mickeysjm/ETypeClus)]

+ **Harvesting Event Schemas from Large Language Models.**

    *Jialong Tang, Hongyu Lin, Zhuoqun Li, Yaojie Lu, Xianpei Han, Le Sun.* **arxiv, 2023.** [[pdf](./documents/2023.Harvesting%20Event%20Schemas%20from%20Large%20Language%20Models.pdf)] [[arxiv](https://arxiv.org/abs/2305.07280)] [[project](https://github.com/TangJiaLong/Event-Schema-Harvester)] [[note](./notes/2023.Harvesting%20Event%20Schemas%20from%20Large%20Language%20Models.md)]


### Language Aquisition 📚

+ **Word Acquisition in Neural Language Models.**

    *Tyler A. Chang, Benjamin K. Bergen.* **TACL, 2022.** [[pdf](./documents/2021.Word%20Acquisition%20in%20Neural%20Language%20Models.pdf)] [[acl](https://aclanthology.org/2022.tacl-1.1/)] [[arxiv](https://arxiv.org/abs/2110.02406)] [[project](https://github.com/tylerachang/word-acquisition-language-models)]

+ **TinyStories: How Small Can Language Models Be and Still Speak Coherent English?**

    *Ronen Eldan, Yuanzhi Li.* **arxiv, 2023.** [[pdf](./documents/2023.TinyStories.pdf)] [[arxiv](https://arxiv.org/abs/2305.07759)]

### Graph Learning 🗺

+ **GraphRNN: Generating Realistic Graphs with Deep Auto-regressive Models.**

    *Jiaxuan You, Rex Ying, Xiang Ren, William Hamilton, Jure Leskovec.* **ICML, 2018.** [[pdf](./documents/2018.GraphRNN.pdf)] [[icml](https://proceedings.mlr.press/v80/you18a.html)] [[arxiv](https://arxiv.org/abs/1802.08773)] [[project](https://github.com/snap-stanford/GraphRNN)]


### Causal Inference 👌🏻

+ **Causal Inference in Natural Language Processing: Estimation, Prediction, Interpretation and Beyond.**

    *Amir Feder, Katherine A. Keith, Emaad Manzoor, Reid Pryzant, Dhanya Sridhar, Zach Wood-Doughty, Jacob Eisenstein, Justin Grimmer, Roi Reichart, Margaret E. Roberts, Brandon M. Stewart, Victor Veitch, Diyi Yang.* **TACL, 2022.** [[pdf](./documents/2021.Casusal%20Inference%20in%20NLP.pdf)] [[acl](https://aclanthology.org/2022.tacl-1.66/)] [[arxiv](https://arxiv.org/abs/2109.00725)] [[mit archive](https://direct.mit.edu/tacl/article-pdf/doi/10.1162/tacl_a_00511/2054690/tacl_a_00511.pdf)] 

+ **Learning Causal Effects on Hypergraphs.**

    *Jing Ma, Mengting Wan, Longqi Yang, Jundong Li, Brent Hecht, Jaime Teevan.* **KDD, 2022.** [[pdf](./documents/2022.Learning%20Causal%20Effects%20on%20Hypergraphs.pdf)] [[arxiv](https://arxiv.org/abs/2207.04049)]


### Video / Audio / Multimodal 🎞

+ **Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models.**

    *Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan.* **arxiv, 2023** [[pdf](./documents/2023.Visual%20ChatGPT.pdf)] [[arxiv](https://arxiv.org/abs/2303.04671)] [[project](https://github.com/microsoft/TaskMatrix)]


### Linguistics 📜

+ **Causal relatedness and importance of story events.**

    *Tom Trabasso, Linda L. Sperry.* **Journal of memory and language. 1985.** [[pdf](./documents/1985.Causal%20relatedness%20and%20importance%20of%20story%20events.pdf)] 

+ **Narrative ablities of Mandarin-speaking children with and without specific langauge impairment: macrostructure and microstructure.**

    *Pao-Chuan Torng, Wen-Hui Sah.* **Clinical Linguistics & Phonetics. 2019.** [[pdf](./documents/2019.Narrative%20abilities%20of%20Mandarin-speaking%20children.pdf)] 

+ **The development of coherence in narratives: causal relations.**

    *Wen-Hui Sah.* **Pacific Asia Conference on Language, Information and Computaion (PACLIC). 2013.** [[pdf](./documents/2013.The%20Development%20of%20Coherence%20in%20Narratives-Causal%20Relations.pdf)] [[acl](https://aclanthology.org/Y13-1015/)]


## Courses and Tutorials / Tools 🍔

+ **Introduction to Large Language Models.**

    *Qi Zhang, Tao Gui, Rui Zheng, Xuanjing Huang.* **online resource, 2023.** [[official website](https://intro-llm.github.io/)] [[github](https://github.com/intro-llm/intro-llm.github.io)]

+ **Introduction to Natural Language Processing.**

    *Qi Zhang, Tao Gui, Xuanjing Huang.* **online resource, 2023.** [[pdf](./documents/Introduction_To_NLP.pdf)] [[official website](https://intro-nlp.github.io/)] [[github](https://github.com/intro-nlp/intro-nlp.github.io)] 

+ **Natural Language Processing with Transformers.**

    *Lewis Tunstall, Leandro von Werra, Thomas Wolf.* **Published by O'Reilly, 2022.**  [[pdf](./documents/HuggingFace-Transformers-Book.pdf)] [[project](https://github.com/nlp-with-transformers/notebooks)]

+ **CS 224N (23') Lecture 10.Natural Language Generation.**

    *Xiang Lisa Li.* **2023.** [[slides](./documents/cs224n-2023-lecture10-nlg.pdf)] [[slides on-line](https://web.stanford.edu/class/cs224n/slides/cs224n-2023-lecture10-nlg.pdf)]

+ **CS 224N (23') Lecture 11.Prompting, Reinforcement Learning from Human Feedback.**

    *Jesse Mu.* **2023.** [[slides](./documents/cs224n-2023-lecture11-prompting-rlhf.pdf)] [[slides on-line](https://web.stanford.edu/class/cs224n/slides/cs224n-2023-lecture11-prompting-rlhf.pdf)] [[note](./notes/cs224n-2023-lecture11-prompting-rlhf.md)]

    + zero-shot and few-shot prompting (in-context learning)

    + instruction fine-tuning

    + reinforcement learning from human feedback (RLHF)

+ **Lecture: Graph Convolutional Neural Networks.**

    *Huawei Shen (ICT, CAS).* **2021.** [[slides](./documents/Huawei-Shen-Graph-convolutional-neura-networks.pdf)] [[video](https://www.bilibili.com/video/BV1dT4y1o7VF/)]

+ **YEDDA: A Lightweight Collaborative Text Span Annotation Tool.**

    *Jie Yang, Yue Zhang, Linwei Li, Xingxuan Li.* **ACL 2018, System Demonstrations.** [[pdf](./documents/2018.YEDDA.pdf)] [[acl](https://aclanthology.org/P18-4006/)] [[arxiv](https://arxiv.org/abs/1711.03759)] [[project](https://github.com/jiesutd/YEDDA)]

    YEDDA (SUTDAnnotator) is developed for annotating chunk/entity/event on text. It supports shortcut annoatation. The tool is developed based on tkinter package in Python.