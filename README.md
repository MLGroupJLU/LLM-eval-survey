<div align="center">
  <img src="imgs/logo-llmeval.png" alt="LLM evaluation" width="500"><br>
  A collection of papers and resources related to evaluations on large language models.
</div>
<br>
 
<p align="center">
  Yupeng Chang<sup>*1</sup>&nbsp&nbsp
  Xu Wang<sup>*1</sup>&nbsp&nbsp
  Jindong Wang<sup>#2</sup>&nbsp&nbsp
  Yuan Wu<sup>#1</sup>&nbsp&nbsp
  Kaijie Zhu<sup>3</sup>&nbsp&nbsp 
  Hao Chen<sup>4</sup>&nbsp&nbsp 
  Linyi Yang<sup>5</sup>&nbsp&nbsp 
  Xiaoyuan Yi<sup>2</sup>&nbsp&nbsp 
  Cunxiang Wang<sup>5</sup>&nbsp&nbsp
  Yidong Wang<sup>6</sup>&nbsp&nbsp
  Wei Ye<sup>6</sup>&nbsp&nbsp
  Yue Zhang<sup>5</sup>&nbsp&nbsp 
  Yi Chang<sup>1</sup>&nbsp&nbsp
  Philip S. Yu<sup>7</sup>&nbsp&nbsp
  Qiang Yang<sup>8</sup>&nbsp&nbsp 
  Xing Xie<sup>2</sup>
</p>  

<p align="center">
<sup>1</sup> Jilin University,
<sup>2</sup> Microsoft Research,
<sup>3</sup> Institute of Automation, CAS
<sup>4</sup> Carnegie Mellon University,
<sup>5</sup> Westlake University,
<sup>6</sup> Peking University,
<sup>7</sup> University of Illinois,
<sup>8</sup> Hong Kong University of Science and Technology<br>
(*: Co-first authors, #: Co-corresponding authors)
</p>


# Papers and resources for LLMs evaluation

The papers are organized according to our survey: [A Survey on Evaluation of Large Language Models](https://arxiv.org/abs/2307.03109). 

**NOTE:** As we cannot update the arXiv paper in real time, please refer to this repo for the latest updates and the paper may be updated later. We also welcome any pull request or issues to help us make this survey perfect. Your contributions will be acknowledged in <a href="#acknowledgements">acknowledgements</a>.

Related projects:
- Prompt benchmark for large language models: [[PromptBench: robustness evaluation of LLMs](https://github.com/microsoft/promptbench)]
- Evlauation of large language models: [[LLM-eval](https://llm-eval.github.io/)]

![](imgs/framework_new.png)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#news-and-updates">News and Updates</a></li>
    <li>
      <a href="#what-to-evaluate">What to evaluate</a>
      <ul>
        <li><a href="#natural-language-processing">Natural language processing</a></li>
        <li><a href="#robustness-ethics-biases-and-trustworthiness">Robustness, ethics, biases, and trustworthiness</a></li>
        <li><a href="#social-science">Social science</a></li>
        <li><a href="#natural-science-and-engineering">Natural science and engineering</a></li>
        <li><a href="#medical-applications">Medical applications</a></li>
        <li><a href="#agent-applications">Agent applications</a></li>
        <li><a href="#other-applications">Other applications</a></li>
      </ul>
    </li>
    <li><a href="where-to-evaluate">Where to evaluate</a></li>
    <li><a href="#Contributing">Contributing</a></li>
    <li><a href="#citation">Citation</a></li>
    <li><a href="#acknowledgements">Acknowledgments</a></li>
  </ol>
</details>

## News and updates

- [12/07/2023] The second version of the paper is released on arXiv, along with [Chinese blog](https://zhuanlan.zhihu.com/p/642689101).
- [07/07/2023] The first version of the paper is released on arXiv: [A Survey on Evaluation of Large Language Models](https://arxiv.org/abs/2307.03109).

## What to evaluate

### Natural language processing

#### Natural language understanding

##### Sentiment analysis
1. A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity. _Yejin Bang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.04023)]
2. A Systematic Study and Comprehensive Evaluation of ChatGPT on Benchmark Datasets, _Laskar et al._ ACL 2023 (Findings). [[paper](https://arxiv.org/abs/2305.18486)]
3. Holistic Evaluation of Language Models. _Percy Liang et al._ arXiv 2022. [[paper](https://arxiv.org/abs/2211.09110)]
4. Can ChatGPT forecast stock price movements? return predictability and large language models. _Alejandro Lopez-Lira et al._ SSRN 2023. [[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4412788)]
5. Is ChatGPT a general-purpose natural language processing task solver? _Chengwei Qin et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.06476)]
6. Is ChatGPT a Good Sentiment Analyzer? A Preliminary Study. _Zengzhi Wang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2304.04339)]
7. Sentiment analysis in the era of large language models: A reality check. _Wenxuan Zhang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.15005)]
   
##### Text classification
1. Holistic evaluation of language models. _Percy Liang et al._ arXiv 2022. [[paper](https://arxiv.org/abs/2211.09110)]
2. Leveraging large language models for topic classification in the domain of public affairs. _Alejandro Peña et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.02864)]
3. Large language models can rate news outlet credibility. _Kai-Cheng Yang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2304.00228)]
   
##### Natural language inference
1. A Systematic Study and Comprehensive Evaluation of ChatGPT on Benchmark Datasets, _Laskar et al._ ACL 2023 (Findings). [[paper](https://arxiv.org/abs/2305.18486)]
2. Can Large Language Models Infer and Disagree like Humans? _Noah Lee et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.13788)]
3. Is ChatGPT a general-purpose natural language processing task solver? _Chengwei Qin et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.06476)]
    
##### Others
1. Do LLMs Understand Social Knowledge? Evaluating the Sociability of Large Language Models with SocKET Benchmark. _Minje Choi et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.14938)]
2. The two word test: A semantic benchmark for large language models. _Nicholas Riccardi et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.04610)]
3. EvEval: A Comprehensive Evaluation of Event Semantics for Large Language Models. _Zhengwei Tao et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.15268)]
   
#### Reasoning
1. A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity. _Yejin Bang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.04023)]
2. ChatGPT is a knowledgeable but inexperienced solver: An investigation of commonsense problem in large language models. _Ning Bian et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2303.16421)]
3. Chain-of-Thought Hub: A continuous effort to measure large language models' reasoning performance. _Yao Fu et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.17306)]
4. A Systematic Study and Comprehensive Evaluation of ChatGPT on Benchmark Datasets, _Laskar et al._ ACL 2023 (Findings). [[paper](https://arxiv.org/abs/2305.18486)]
5. Can large language models reason about medical questions? _Valentin Liévin et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2207.08143)]
6. Evaluating the Logical Reasoning Ability of ChatGPT and GPT-4. _Hanmeng Liu et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2304.03439)]
7. Mathematical Capabilities of ChatGPT. _Simon Frieder et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2301.13867)]
8. Human-like problem-solving abilities in large language models using ChatGPT. _Graziella Orrù et al._ Front. Artif. Intell. 2023 [[paper](https://www.frontiersin.org/articles/10.3389/frai.2023.1199350/full)]
9. Is ChatGPT a general-purpose natural language processing task solver? _Chengwei Qin et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.06476)]
10. Testing the general deductive reasoning capacity of large language models using OOD examples. _Abulhair Saparov et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.15269)]
11. MindGames: Targeting Theory of Mind in Large Language Models with Dynamic Epistemic Modal Logic. _Damien Sileo et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.03353)]
12. Reasoning or Reciting? Exploring the Capabilities and Limitations of Language Models Through Counterfactual Tasks. _Zhaofeng Wu_ arXiv 2023. [[paper](https://arxiv.org/abs/2307.02477?utm_source=tldrai)]
13. Are large language models really good logical reasoners? a comprehensive evaluation from deductive, inductive and abductive views. _Fangzhi Xu et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.09841)]
14. Efficiently Measuring the Cognitive Ability of LLMs: An Adaptive Testing Perspective. _Yan Zhuang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.10512)]
   
#### Natural language generation

##### Summarization  
1. A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity. _Yejin Bang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.04023)]
2. A Systematic Study and Comprehensive Evaluation of ChatGPT on Benchmark Datasets, _Laskar et al._ ACL 2023 (Findings). [[paper](https://arxiv.org/abs/2305.18486)]
3. Holistic Evaluation of Language Models. _Percy Liang et al._ arXiv 2022. [[paper](https://arxiv.org/abs/2211.09110)]
4. ChatGPT vs Human-authored text: Insights into controllable text summarization and sentence style transfer. _Dongqi Pu et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.07799)]
5. Is ChatGPT a general-purpose natural language processing task solver? _Chengwei Qin et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.06476)]
   
##### Dialogue
1. A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity. _Yejin Bang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.04023)]
2. LLM-Eval: Unified Multi-Dimensional Automatic Evaluation for Open-Domain Conversations with Large Language Models. _Yen-Ting Lin et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.13711)]
3. Is ChatGPT a general-purpose natural language processing task solver? _Chengwei Qin et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.06476)]
   
##### Translation
1. A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity. _Yejin Bang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.04023)]
2. A Systematic Study and Comprehensive Evaluation of ChatGPT on Benchmark Datasets, _Laskar et al._ ACL 2023 (Findings). [[paper](https://arxiv.org/abs/2305.18486)]
3. Translating Radiology Reports into Plain Language using ChatGPT and GPT-4 with Prompt Learning: Promising Results, Limitations, and Potential. _Qing Lyu et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2303.09038)]
4. Document-Level Machine Translation with Large Language Models. _Longyue Wang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2304.02210)]
5.  Case Study of Improving English-Arabic Translation Using the Transformer Model. _Donia Gamal et al._ ijicis 2023. [[paper](https://ijicis.journals.ekb.eg/article_305271.html)]
6. Taqyim: Evaluating Arabic NLP Tasks Using ChatGPT Models. _Zaid Alyafeai et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.16322)]
   
##### Question answering
1. Benchmarking Foundation Models with Language-Model-as-an-Examiner. _Yushi Bai et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.04181)]
2. A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity. _Yejin Bang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.04023)]
3. ChatGPT is a knowledgeable but inexperienced solver: An investigation of commonsense problem in large language models. _Ning Bian et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2303.16421)]
4. A Systematic Study and Comprehensive Evaluation of ChatGPT on Benchmark Datasets, _Laskar et al._ ACL 2023 (Findings). [[paper](https://arxiv.org/abs/2305.18486)]
5. Holistic Evaluation of Language Models. _Percy Liang et al._ arXiv 2022. [[paper](https://arxiv.org/abs/2211.09110)]
6. Is ChatGPT a general-purpose natural language processing task solver? _Chengwei Qin et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.06476)]
   
##### Others
1. Exploring the use of large language models for reference-free text quality evaluation: A preliminary empirical study. _Yi Chen et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2304.00723)]
2. INSTRUCTEVAL: Towards Holistic Evaluation of Instruction-Tuned Large Language Models. _Yew Ken Chia et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.04757)]
3. ChatGPT vs Human-authored Text: Insights into Controllable Text Summarization and Sentence Style Transfer. _Dongqi Pu et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.07799)]
   
#### Multilingual tasks
1. Benchmarking Arabic AI with large language models. _Ahmed Abdelali et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.14982)]
2. MEGA: Multilingual Evaluation of Generative AI. _Kabir Ahuja et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2303.12528)]
3. A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity. _Yejin Bang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.04023)]
4. ChatGPT beyond English: Towards a comprehensive evaluation of large language models in multilingual learning. _Viet Dac Lai et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2304.05613)]
5. A Systematic Study and Comprehensive Evaluation of ChatGPT on Benchmark Datasets, _Laskar et al._ ACL 2023 (Findings). [[paper](https://arxiv.org/abs/2305.18486)]
6. M3Exam: A Multilingual, Multimodal, Multilevel Benchmark for Examining Large Language Models. _Wenxuan Zhang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.05179)]
  
#### Factuality
1. TrueTeacher: Learning Factual Consistency Evaluation with Large Language Models. _Zorik Gekhman et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.11171)]
2. TRUE: Re-evaluating Factual Consistency Evaluation. _Or Honovich et al._ arXiv 2022. [[paper](https://arxiv.org/abs/2204.04991)]
3. SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models. _Potsawee Manakul et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2303.08896)]
4. FActScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation. _Sewon Min et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.14251)]
5. Measuring and Modifying Factual Knowledge in Large Language Models. _Pouya Pezeshkpour_ arXiv 2023. [[paper](https://arxiv.org/abs/2306.06264)]
6. Evaluating Open Question Answering Evaluation. _Cunxiang Wang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.12421)]
   
### Robustness, ethics, biases, and trustworthiness

#### Robustness
1. A Survey on Out-of-Distribution Evaluation of Neural NLP Models. _Xinzhe Li et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.15261)]
2. Generalizing to Unseen Domains: A Survey on Domain Generalization. _Jindong Wang et al._ TKDE 2022. [[paper](https://arxiv.org/abs/2103.03097)]
3. On the Robustness of ChatGPT: An Adversarial and Out-of-distribution Perspective. _Jindong Wang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.12095)]
4. GLUE-X: Evaluating Natural Language Understanding Models from an Out-of-Distribution Generalization Perspective. _Linyi Yang et al._ arXiv 2022. [[paper](https://arxiv.org/abs/2211.08073)]
5. On Evaluating Adversarial Robustness of Large Vision-Language Models. _Yunqing Zhao et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.16934)]
6. PromptBench: Towards Evaluating the Robustness of Large Language Models on Adversarial Prompts. _Kaijie Zhu et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.04528)]
7. On Robustness of Prompt-based Semantic Parsing with Large Pre-trained Language Model: An Empirical Study on Codex. _Terry Yue Zhuo et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2301.12868)]
  
#### Ethics and bias
1. Assessing Cross-Cultural Alignment between ChatGPT and Human Societies: An Empirical Study. _Yong Cao et al._ C3NLP@EACL 2023. [[paper](https://arxiv.org/abs/2303.17466)]
2. Toxicity in ChatGPT: Analyzing persona-assigned language models. _Ameet Deshpande et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2304.05335)]
3. BOLD: Dataset and Metrics for Measuring Biases in Open-Ended Language Generation. _Jwala Dhamala et al._ FAccT 2021 [[paper](https://dl.acm.org/doi/10.1145/3442188.3445924)]
4. Should ChatGPT be Biased? Challenges and Risks of Bias in Large Language Models. _Emilio Ferrara_ arXiv 2023. [[paper](https://arxiv.org/abs/2304.03738)]
5. RealToxicityPrompts: Evaluating Neural Toxic Degeneration in Language Models. _Samuel Gehman et al._ EMNLP 2020. [[paper](https://aclanthology.org/2020.findings-emnlp.301/)]
6. The political ideology of conversational AI: Converging evidence on ChatGPT's pro-environmental, left-libertarian orientation. _Jochen Hartmann et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2301.01768)]
7. A Systematic Study and Comprehensive Evaluation of ChatGPT on Benchmark Datasets, _Laskar et al._ ACL 2023 (Findings). [[paper](https://arxiv.org/abs/2305.18486)]
8. BBQ: A hand-built bias benchmark for question answering. _Alicia Parrish et al._ ACL 2022. [[paper](https://aclanthology.org/2022.findings-acl.165/)]
9. The Self-Perception and Political Biases of ChatGPT. _Jérôme Rutinowski et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2304.07333)]
10. Societal Biases in Language Generation: Progress and Challenges. _Emily Sheng et al._ ACL-IJCNLP 2021. [[paper](https://aclanthology.org/2021.acl-long.330/)]
11. Moral Mimicry: Large Language Models Produce Moral Rationalizations Tailored to Political Identity. _Gabriel Simmons et al._ arXiv 2022. [[paper](https://arxiv.org/abs/2209.12106)]
12. Large Language Models are not Fair Evaluators. _Peiyi Wang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.17926)]
13. Exploring AI Ethics of ChatGPT: A Diagnostic Analysis. _Terry Yue Zhuo et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2301.12867)]

#### Trustworthiness
1. Human-Like Intuitive Behavior and Reasoning Biases Emerged in Language Models -- and Disappeared in GPT-4. _Thilo Hagendorff et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.07622)]
2. DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models. _Boxin Wang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.11698)]
   
### Social science
1. How ready are pre-trained abstractive models and LLMs for legal case judgement summarization. _Aniket Deroy et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.01248)]
2. Baby steps in evaluating the capacities of large language models. _Michael C. Frank_ Nature Reviews Psychology 2023. [[paper](https://www.nature.com/articles/s44159-023-00211-x)]
3. Large Language Models as Tax Attorneys: A Case Study in Legal Capabilities Emergence. _John J. Nay et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.07075)]
4. Large language models can be used to estimate the ideologies of politicians in a zero-shot learning setting. _Patrick Y. Wu et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2303.12057)]
5. Can large language models transform computational social science? _Caleb Ziems et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.03514)]
 
### Natural science and engineering

#### Mathematics
1. Have LLMs Advanced Enough? A Challenging Problem Solving Benchmark for Large Language Models. _Daman Arora et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.15074)]
2. Sparks of Artificial General Intelligence: Early experiments with GPT-4. _Sébastien Bubeck et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2303.12712)]
3. Evaluating Language Models for Mathematics through Interactions. _Katherine M. Collins et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.01694)]
4. Investigating the effectiveness of ChatGPT in mathematical reasoning and problem solving: Evidence from the Vietnamese national high school graduation examination. _Xuan-Quy Dao et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.06331)]
5. A Systematic Study and Comprehensive Evaluation of ChatGPT on Benchmark Datasets, _Laskar et al._ ACL 2023 (Findings). [[paper](https://arxiv.org/abs/2305.18486)]
6. CMATH: Can Your Language Model Pass Chinese Elementary School Math Test? _Tianwen Wei et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.16636)]
7. An empirical study on challenging math problem solving with GPT-4. _Yiran Wu et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.01337)]
8. How well do Large Language Models perform in Arithmetic Tasks? _Zheng Yuan et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2304.02015)]
   
#### General science
1. Have LLMs Advanced Enough? A Challenging Problem Solving Benchmark for Large Language Models. _Daman Arora et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.15074)]
2. Do Large Language Models Understand Chemistry? A Conversation with ChatGPT. _Castro Nascimento CM et al._ JCIM 2023. [[paper](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00285)]
3. What indeed can GPT models do in chemistry? A comprehensive benchmark on eight tasks. _Taicheng Guo et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.18365)][[GitHub](https://github.com/ChemFoundationModels/ChemLLMBench)]
   
#### Engineering
1. Sparks of Artificial General Intelligence: Early Experiments with GPT-4. _Sébastien Bubeck et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2303.12712)]
2. Is your code generated by ChatGPT really correct? Rigorous evaluation of large language models for code generation. _Jiawei Liu et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.01210)]
3. Understanding the Capabilities of Large Language Models for Automated Planning. _Vishal Pallagani et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.16151)]
4. ChatGPT: A study on its utility for ubiquitous software engineering tasks. _Giriprasad Sridhara et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.16837)]
5. Large language models still can't plan (A benchmark for LLMs on planning and reasoning about change). _Karthik Valmeekam et al._ arXiv 2022. [[paper](https://arxiv.org/abs/2206.10498)]
6. On the Planning Abilities of Large Language Models – A Critical Investigation. _Karthik Valmeekam et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.06706)]
7. Efficiently Measuring the Cognitive Ability of LLMs: An Adaptive Testing Perspective. _Yan Zhuang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.10512)]

### Medical applications

#### Medical Queries
1. The promise and peril of using a large language model to obtain clinical information: ChatGPT performs strongly as a fertility counseling tool with limitation. _Joseph Chervenak M.D. et al._ Fertility and Sterility 2023. [[paper](https://www.sciencedirect.com/science/article/pii/S0015028223005228)]
2. Analysis of large-language model versus human performance for genetics questions. _Dat Duong et al._ European Journal of Human Genetics 2023. [[paper](https://www.nature.com/articles/s41431-023-01396-8)]
3. Evaluation of AI Chatbots for Patient-Specific EHR Questions. _Alaleh Hamidi et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.02549)]
4. Evaluating Large Language Models on a Highly-specialized Topic, Radiation Oncology Physics. _Jason Holmes et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2304.01938)]
5. Evaluation of ChatGPT on Biomedical Tasks: A Zero-Shot Comparison with Fine-Tuned Generative Transformers. _Israt Jahan et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.04504)]
6. Assessing the Accuracy and Reliability of AI-Generated Medical Responses: An Evaluation of the Chat-GPT Model. _Douglas Johnson et al._ Residential Square 2023. [[paper](https://pubmed.ncbi.nlm.nih.gov/36909565/)]
7. Assessing the Accuracy of Responses by the Language Model ChatGPT to Questions Regarding Bariatric Surgery. _Jamil S. Samaan et al._ Obesity Surgery 2023. [[paper](https://link.springer.com/article/10.1007/s11695-023-06603-5)]
8. Trialling a Large Language Model (ChatGPT) in General Practice With the Applied Knowledge Test: Observational Study Demonstrating Opportunities and Limitations in Primary Care. _Arun James Thirunavukarasu et al._ JMIR Med Educ. 2023. [[paper](https://pubmed.ncbi.nlm.nih.gov/37083633/)]
9. CARE-MI: Chinese Benchmark for Misinformation Evaluation in Maternity and Infant Care. _Tong Xiang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2307.01458)]

#### Medical examination
1. How Does ChatGPT Perform on the United States Medical Licensing Examination? The Implications of Large Language Models for Medical Education and Knowledge Assessment. _Aidan Gilson et al._ JMIR Med Educ. 2023. [[paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9947764/)]
2. Performance of ChatGPT on USMLE: Potential for AI-assisted medical education using large language models. _Tiffany H. Kung et al._ PLOS Digit Health. 2023. [[paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9931230/)]
   
#### Medical assistants
1. Evaluating the feasibility of ChatGPT in healthcare: an analysis of multiple clinical and research scenarios. _Marco Cascella et al._ Journal of Medical Systems 2023. [[paper](https://link.springer.com/article/10.1007/s10916-023-01925-4)]
2. covLLM: Large Language Models for COVID-19 Biomedical Literature. _Yousuf A. Khan et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.04926)]
3. Evaluating the use of large language model in identifying top research questions in gastroenterology. _Adi Lahat et al._ Scientific reports 2023. [[paper](https://www.nature.com/articles/s41598-023-31412-2)]
4. Translating Radiology Reports into Plain Language using ChatGPT and GPT-4 with Prompt Learning: Promising Results, Limitations, and Potential. _Qing Lyu et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2303.09038)]
5. ChatGPT goes to the operating room: Evaluating GPT-4 performance and its potential in surgical education and training in the era of large language models. _Namkee Oh et al._ Ann Surg Treat Res. 2023. [[paper](https://pubmed.ncbi.nlm.nih.gov/37179699/)]
6. Can LLMs like GPT-4 outperform traditional AI tools in dementia diagnosis? Maybe, but not today. _Zhuo Wang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.01499)]

### Agent applications
1. Language Is Not All You Need: Aligning Perception with Language Models. _Shaohan Huang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.14045)]
2. MRKL Systems: A modular, neuro-symbolic architecture that combines large language models, external knowledge sources and discrete reasoning. _Ehud Karpas et al._ [[paper](https://arxiv.org/abs/2205.00445)]
3. The Unsurprising Effectiveness of Pre-Trained Vision Models for Control. _Simone Parisi et al._ ICMl 2022. [[paper](https://arxiv.org/abs/2203.03580)]
4. Toolformer: Language Models Can Teach Themselves to Use Tools. _Timo Schick et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2302.04761)]
5. HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face. _Yongliang Shen et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2303.17580)]

### Other applications

#### Education
1. Can Large Language Models Provide Feedback to Students? A Case Study on ChatGPT. _Wei Dai et al._ ICALT 2023. [[paper](https://edarxiv.org/hcgzj/)]
2. Can ChatGPT pass high school exams on English Language Comprehension? _Joost de Winter_ Researchgate. [[paper](https://www.researchgate.net/publication/366659237_Can_ChatGPT_pass_high_school_exams_on_English_Language_Comprehension)]
3. Exploring the Responses of Large Language Models to Beginner Programmers' Help Requests. _Arto Hellas et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.05715)]
4. Is ChatGPT a Good Teacher Coach? Measuring Zero-Shot Performance For Scoring and Providing Actionable Insights on Classroom Instruction. _Rose E. Wang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.03090)]
5. CMATH: Can Your Language Model Pass Chinese Elementary School Math Test? _Tianwen Wei et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.16636)]

#### Search and recommendation
1. Uncovering ChatGPT's Capabilities in Recommender Systems. _Sunhao Dai et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.02182)]
2. Recommender Systems in the Era of Large Language Models (LLMs). _Wenqi Fan et al._ Researchgate. [[paper](https://www.researchgate.net/publication/372137006_Recommender_Systems_in_the_Era_of_Large_Language_Models_LLMs)]
3. Exploring the Upper Limits of Text-Based Collaborative Filtering Using Large Language Models: Discoveries and Insights. _Ruyu Li et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.11700)]
4. Is ChatGPT Good at Search? Investigating Large Language Models as Re-Ranking Agent. _Weiwei Sun et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2304.09542)]
5. ChatGPT vs. Google: A Comparative Study of Search Performance and User Experience. _Ruiyun Xu et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2307.01135)]
6. Where to Go Next for Recommender Systems? ID- vs. Modality-based Recommender Models Revisited. _Zheng Yuan et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2303.13835)]
7. Is ChatGPT Fair for Recommendation? Evaluating Fairness in Large Language Model Recommendation. _Jizhi Zhang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.07609)]

#### Personality testing
1. ChatGPT is fun, but it is not funny! Humor is still challenging Large Language Models. _Sophie Jentzsch et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.04563)]
2. Personality Traits in Large Language Models. _Mustafa Safdari et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2307.00184)]
3. Have Large Language Models Developed a Personality?: Applicability of Self-Assessment Tests in Measuring Personality in LLMs. _Xiaoyang Song et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2305.14693)]
4. Emotional Intelligence of Large Language Models. _Xuena Wang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2307.09042)]

#### Specific tasks
1. ChatGPT and Other Large Language Models as Evolutionary Engines for Online Interactive Collaborative Game Design. _Pier Luca Lanzi et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2303.02155)]
2. An Evaluation of Log Parsing with ChatGPT. _Van-Hoang Le et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.01590)]
3. PandaLM: An Automatic Evaluation Benchmark for LLM Instruction Tuning Optimization. _Yidong Wang et al._ arXiv 2023. [[paper](https://arxiv.org/abs/2306.05087)]

## Where to evaluate

The paper lists several popular benchmarks. For better summarization, these benchmarks are divided into two categories: general language task benchmarks and specific downstream task benchmarks.

**NOTE:** We may miss some benchmarks. Your suggestions are highly welcomed!


| Benchmark   | Focus                              | Domain                   | Evaluation Criteria                           |
|-------------|------------------------------------|--------------------------|-----------------------------------------------|
| MMBench [[paper](https://arxiv.org/abs/2307.06281)]     | Multimodal LLMs  | General language task | Fine-grained abilities of perception and reasoning       |
| SOCKET [[paper](https://arxiv.org/abs/2305.14938)]      | Social knowledge                        | Specific downstream task | Social language understanding           |
| MME [[paper](https://arxiv.org/abs/2306.13394)]      | Multimodal LLMs                        | General language task | Ability of perception and cognition           |
| Xiezhi [[paper](https://arxiv.org/abs/2306.05783)][[GitHub](https://github.com/MikeGu721/XiezhiBenchmark)]      | Comprehensive domain knowledge   | General language task | Overall performance across multiple benchmarks   |
| CUAD [[paper](https://arxiv.org/abs/2103.06268)] | Legal contract review | Specific downstream task | Legal contract understanding |
| TRUSTGPT [[paper](https://arxiv.org/abs/2306.11507)] | Ethic | Specific downstream task | Toxicity, bias, and value-alignment |
| MMLU [[paper](https://arxiv.org/abs/2009.03300)]      | Text models                        | General language task | Multitask accuracy           |
| MATH [[paper](https://arxiv.org/abs/2103.03874)] | Mathematical problem  | Specific downstream task | Mathematical ability |
| APPS [[paper](https://arxiv.org/abs/2105.09938)]|Coding challenge competence | Specific downstream task | Code generation ability|
| C-Eval [[paper](https://arxiv.org/abs/2305.08322)][[GitHub](https://github.com/SJTU-LIT/ceval)]      | Chinese evaluation                 | General language task | 52 Exams in a Chinese context   |
| OpenLLM [[Link](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)] | Chatbots          | General language task | Leaderboard rankings   |
| DynaBench [[paper](https://arxiv.org/abs/2104.14337)]   | Dynamic evaluation                 | General language task    | NLI, QA, sentiment, and hate speech               |
| Chatbot Arena [[Link](https://lmsys.org/blog/2023-05-03-arena/)]  | Chat assistants      | General language task    | Crowdsourcing and Elo rating system              |
| AlpacaEval [[GitHub](https://github.com/tatsu-lab/alpaca_eval)]  | Automated evaluation               | General language task    | Metrics, robustness, and diversity       |
| HELM [[paper](https://arxiv.org/abs/2211.09110)][[Link](https://crfm.stanford.edu/helm/latest/)]        | Holistic evaluation           | General language task    | Multi-metric                         |
| API-Bank [[paper](https://arxiv.org/abs/2304.08244)]    | Tool-augmented                     | Specific downstream task | API call, response, and planning                                       |
| M3KE [[paper](https://arxiv.org/abs/2305.10263)]    | Multi-task  | General language task | Multi-task accuracy                                       |
| ARB [[paper](https://arxiv.org/abs/2307.13692)]  | Advanced reasoning ability       | Specific downstream task | Multidomain advanced reasoning ability|
| BIG-bench [[paper](https://arxiv.org/abs/2206.04615)][[GitHub](https://github.com/google/BIG-bench)]    | Capabilities and limitations of LMs | General language task | Model performance and calibration         |
| MultiMedQA [[paper](https://arxiv.org/abs/2212.13138)]  | Medical QA       | Specific downstream task | Model performance, medical knowledge, and reasoning ability|
| CVALUES [[paper](https://arxiv.org/abs/2307.09705)] [[GitHub](https://github.com/X-PLUG/CValues)]     | Safety and responsibility | Specific downstream task | Alignment ability of LLMs                         |
| ToolBench [[GitHub](https://github.com/sambanova/toolbench)]  | Software tools               | Specific downstream task | Execution success rate                  |
| PandaLM [[paper](https://arxiv.org/abs/2306.05087)] [[GitHub](https://github.com/WeOpenML/PandaLM)]     | Instruction tuning               | General language task    | Winrate judged by PandaLM             |
| GLUE-X [[paper](https://arxiv.org/abs/2211.08073)] [[GitHub](https://github.com/YangLinyi/GLUE-X)]     | OOD robustness for NLU tasks     | General language task    | OOD robustness                       |
| KoLA [[paper](https://arxiv.org/abs/2306.09296)]       | Knowledge-oriented evaluation      | General language task    | Self-contrast metrics |
| AGIEval [[paper](https://arxiv.org/abs/2304.06364)]     | Human-centered foundational models | General language task    | General                            |
| PromptBench [[paper](https://arxiv.org/abs/2306.04528)] [[GitHub](https://github.com/microsoft/promptbench)] | Adversarial prompt resilience      | General language task    | Adversarial robustness           |
| MT-Bench [[paper](https://arxiv.org/abs/2306.05685)]  | Multi-turn conversation      | General language task    | Winrate judged by GPT-4                |
| M3Exam [[paper](https://arxiv.org/abs/2306.05179)] [[GitHub](https://github.com/DAMO-NLP-SG/M3Exam)]     | Human exams | Specific downstream task | Task-specific metrics                         |
| GAOKAO-Bench [[paper](https://arxiv.org/abs/2305.12474)]     | Chinese Gaokao examination | Specific downstream task | Accuracy and scoring rate                         |

## Contributing

We welcome contributions to LLM-eval-survey! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch with your changes.
3. Submit a pull request with a clear description of your changes.

You can also open an issue if you have anything to add or comment.


## Citation

If you find this project useful in your research or work, please consider citing it:

```
@article{chang2023survey,
      title={A Survey on Evaluation of Large Language Models}, 
      author={Chang, Yupeng and Wang, Xu and Wang, Jindong and Wu, Yuan and Zhu, Kaijie and Chen, Hao and Yang, Linyi and Yi, Xiaoyuan and Wang, Cunxiang and Wang, Yidong and Ye, Wei and Zhang, Yue and Chang, Yi and Yu, Philip S. and Yang, Qiang and Xie, Xing},
      journal={arXiv preprint arXiv:2307.03109},
      year={2023}
}
```

## Acknowledgements

1. Tahmid Rahman ([@tahmedge](https://github.com/tahmedge)) for [PR#1](https://github.com/MLGroupJLU/LLM-eval-survey/pull/1).
2. Hao Zhao for suggestions on new benchmarks.
3. Chenhui Zhang for suggestions on robustness, ethics, and trustworthiness.
4. Damien Sileo ([@sileod](https://github.com/sileod)) for [PR#2](https://github.com/MLGroupJLU/LLM-eval-survey/pull/2).
5. Peiyi Wang ([@Wangpeiyi9979](https://github.com/Wangpeiyi9979)) for [issue#3](https://github.com/MLGroupJLU/LLM-eval-survey/issues/3).
6. Zengzhi Wang for sentiment analysis.
7. Kenneth Leung ([@kennethleungty](https://github.com/kennethleungty)) for [PR#4](https://github.com/MLGroupJLU/LLM-eval-survey/pull/4) to [PR#6](https://github.com/MLGroupJLU/LLM-eval-survey/pull/6).
8. [@Aml-Hassan-Abd-El-hamid](https://github.com/Aml-Hassan-Abd-El-hamid) for [PR#7](https://github.com/MLGroupJLU/LLM-eval-survey/pull/7).
9. [@taichengguo](https://github.com/taichengguo) for [issue#9](https://github.com/MLGroupJLU/LLM-eval-survey/issues/9)
