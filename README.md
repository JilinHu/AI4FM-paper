<h2 align='center'>AI4FM-paper 论文列表</h2>
<div align='center'>

[![Status](https://img.shields.io/badge/status-Update_12.06_12:00-success.svg)]() [![简体中文 badge](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-Simplified%20Chinese-blue)](./README.md) [![English badge](https://img.shields.io/badge/%E8%8B%B1%E6%96%87-English-blue)](./README_en.md) 

</div>

欢迎来到 **AI4FM-paper**! 本列表收集形式化方向、编程语言方向、软工方向、系统方向、安全方向的顶会顶刊中关于AI for FM的论文。



## 最新论文
### 形式化，编程语言，系统，安全（顶会）

| &nbsp;Conference/Year&nbsp;&nbsp; | Paper | Links & Summary |
| --- | --- | --- |
| <span style='display: inline-block; width: 42px;'>POPL2025</span> | **Automated Program Refinement: Guide and Verify Code Large Language Model with Refinement Calculus**<br><sub>机构: National University of Singapore<br>设计了一个framework用来辅助LLM生成可信的代码，能自动生成需要证明的规约，以保证生成代码的正确性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.19672v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.19672.md)  |
| <span style='display: inline-block; width: 42px;'>NDSS2025</span> | **PropertyGPT: LLM-driven Formal Verification of Smart Contracts through Retrieval-Augmented Property Generation**<br><sub>机构: Nanyang Technological University<br>用LLM和已有属性数据库给智能合约生成优质的安全属性，利用了iterative feedback, similarity ranking等技巧。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.19672v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.19672.md)  |
| <span style='display: inline-block; width: 42px;'>OOPSLA2024</span> | **Enhancing Static Analysis for Practical Bug Detection: An LLM-Integrated Approach**<br><sub>机构: University of California,<br>LLift结合了LLM和静态分析，用来检测linux kernel中存在的UBI bugs，还用post-constraint guidance增强path analysis。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>OSDI2024</span> | **IronSpec: Increasing the Reliability of Formal Specifications**<br><sub>机构: University of Michigan<br>IronSpec能够检测形式化规约本身的正确性，用了automated sanity checking, a methodology for writing SpecTesting Proofs (STPs), and automated spec mutation testing。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>CAV2024</span> | **Enchanting Program Specification Synthesis by Large Language Models using Static Analysis and Program Verification**<br><sub>机构: Fermat Labs, Huawei<br>AutoSpec能自动给C代码生成对应的前后置条件，通过大模型和frama-C的不断交互，最终证明C代码的正确性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>CCS2024</span> | **PromSec: Prompt Optimization for Secure Generation of Functional Source Code with Large Language Models**<br><sub>机构: New Jersey Institute of Technology<br>该算法用于优化prompt，从而生成既安全又功能完备的代码。PromSec通过结合生成对抗图神经网络（gGAN）进行代码漏洞修复，与LLM形成交互式循环优化安全性，同时保留代码功能。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>CAV2023</span> | **nl2spec: Interactively Translating Unstructured Natural Language to Temporal Logics with Large Language Models**<br><sub>机构: Stanford University<br>利用LLM从自然语言描述以时序逻辑的格式自动生成形式化规约。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>CAV2020</span> | **Code2Inv: A Deep Learning Framework for Program Verification**<br><sub>机构:  University of Pennsylvani<br>用deep learning给程序生成不变式规约，例如循环不变式。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>OOPSLA2020</span> | **TacTok: Semantics-Aware Proof Synthesis**<br><sub>机构: University of Massachusetts Amherst<br>用来生成形式化证明，通过已有的部分证明代码和当前证明状态的语义，比Coqhammer等的证明效果要好。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.19672v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.19672.md)  |


---

### 软件工程（顶会）

| &nbsp;Conference/Year&nbsp;&nbsp; | Paper | Links & Summary |
| --- | --- | --- |
| <span style='display: inline-block; width: 42px;'>06-30</span> | **Step-Controlled DPO: Leveraging Stepwise Error for Enhanced Mathematical Reasoning**<br><sub>机构: Multimedia Laboratory (MMLab), The Chinese University of Hong Kong<br>本论文提出了一种新的数学推理优化方法——SCDPO，通过在特定步骤监督错误的方式，自动化地生成训练样本，显著提升了LLMs在数学问题求解方面的性能，证明了该方法的潜力。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.00782v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-06/2407.00782.md)  |
| <span style='display: inline-block; width: 42px;'>06-29</span> | **LiteSearch: Efficacious Tree Search for LLM**<br><sub>机构: Xiamen University, Tencent AI Lab<br>该论文通过提出一种效率更高的树搜索算法来降低在辅助大型语言模型解决复杂数学推理任务时的资源消耗，同时确保保持高性能水平。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.00320v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-06/2407.0032.md)  |

---

### 形式化，编程语言，系统，安全（顶刊）

| &nbsp;Journal/Year&nbsp;&nbsp; | Paper | Links & Summary |
| --- | --- | --- |
| <span style='display: inline-block; width: 42px;'>05-31</span> | **Preemptive Answer "Attacks" on Chain-of-Thought Reasoning**<br><sub>机构: Tsinghua University<br>论文研究了预先答案对LLMs推理能力的负面影响，并提出了减轻其影响的策略。实验结果表明，这些策略不能完全抵消预先答案的影响，提示需要进一步增强CoT的鲁棒性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2405.20902v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-05/2405.20902.md)  |
| <span style='display: inline-block; width: 42px;'>05-31</span> | **Transformers are SSMs: Generalized Models and Efficient Algorithms Through Structured State Space Duality**<br><sub>机构: Princeton University, Carnegie Mellon University<br>本论文展示了一个全新的状态空间对偶性（SSD）框架，连接了结构化的状态空间模型（SSMs）和注意力机制变体。论文的主要贡献包括将原本针对Transformers的算法和系统优化应用到SSMs上，以及开发了一种新的SSD算法，有效提高了模型训练和推理的效率。Mamba-2架构作为最终产品，实现了理想的性能表现，为未来的深度学习模型设计和优化提供了新的方向。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2405.21060v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-05/2405.2106.md)  |

---

### 软件工程（顶刊）

| &nbsp;Journal/Year&nbsp;&nbsp; | Paper | Links & Summary |
| --- | --- | --- |
| <span style='display: inline-block; width: 42px;'>TOSEM2024</span> | **Smart Contract Code Repair Recommendation based on Reinforcement Learning and Multi-metric Optimization**<br><sub>机构: Georgia Institute of Technology<br>本文提出了一种基于强化学习的智能合约漏洞修复方法RLRep，能够在缺乏监督数据的情况下为开发者提供漏洞修复建议。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/pdf/2409.06213?logo=arxiv)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19737.md)  |

| <span style='display: inline-block; width: 42px;'>TOSEM2024</span> | **On the Reliability and Explainability of Language Models for Program Generation**<br><sub>机构: Monash University<br>本文通过实证研究揭示了当前主流预训练语言模型在自动程序生成任务中的局限性，指出数据重复导致的过于乐观的性能评估问题，并通过可解释性分析表明这些模型在代码语法和结构识别方面有一定能力，但对输入变化的鲁棒性较差，呼吁更严格的评估方法和基准测试以提升模型的可靠性和可解释性。</sub>| <div style='min-width:85px;'>[![arXiv](https://arxiv.org/pdf/2302.09587?logo=arxiv)](http://arxiv.org/pdf/2404.19234v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19234.md)  |


| <span style='display: inline-block; width: 42px;'>TOSEM2024</span> | **Beyond Fidelity: Explaining Vulnerability Localization of Learning-Based Detectors**<br><sub>机构: Peking University<br>本文评估了10种解释方法在深度学习漏洞检测器中的表现，发现现有方法在关键漏洞相关代码行的精确性方面表现较差，这主要归因于解释器选择重要特征的效率低下以及检测器学习到的无关信息，研究结果强调了单纯依赖忠实度指标的局限性，并提出需要改进解释方法以提高准确性和实用性。</sub>| <div style='min-width:85px;'>[![arXiv](https://arxiv.org/abs/2401.02686?logo=arxiv)](http://arxiv.org/pdf/2404.19234v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19234.md)  |
| <span style='display: inline-block; width: 42px;'>TOSEM2024</span> | **Automated Mapping of Vulnerability Advisories onto their Fix Commits in Open Source Repositories**<br><sub>机构: SAP Security Research <br>本文提出了一种结合经验启发和自然语言处理的机器学习方法，用于匹配漏洞公告与修复提交，通过FixFinder原型验证，在前10结果中成功定位修复提交的比例达84.03%，显著减少了查找漏洞修复提交的工作量。</sub>| <div style='min-width:85px;'>[![arXiv](https://arxiv.org/abs/2103.13375?logo=arxiv)](http://arxiv.org/pdf/2404.19234v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19234.md)  |
| <span style='display: inline-block; width: 42px;'>TSE2022</span> | **Automated Generation of Acceptance Test Cases From Use Case Specifications: An NLP-Based Approach**<br><sub>机构: null<br>本文提出了UMTG方法，通过自然语言处理技术从需求规格中自动生成验收测试用例，减少人工工作量并覆盖需求，在两项工业案例中正确转换95%的用例步骤，并发现了专家未考虑的关键测试场景。</sub>| <div style='min-width:85px;'>[![arXiv](https://arxiv.org/abs/1907.08490?logo=arxiv)](http://arxiv.org/pdf/2404.19234v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19234.md)  |
| <span style='display: inline-block; width: 42px;'>TSE2023</span> | **Specification-Based Autonomous Driving System Testing**<br><sub>机构: Nanyang Technological University<br>本文提出AVUnit框架，通过自定义规范系统化测试自动驾驶系统，支持动态场景属性和精细断言，结合模糊测试发现Apollo在复杂路口和变道场景下存在19种问题，表明其性能不足。</sub>| <div style='min-width:85px;'>[![arXiv](https://cposkitt.github.io/files/publications/avunit_tse23.pdf)](http://arxiv.org/pdf/2404.19234v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19234.md)  |
| <span style='display: inline-block; width: 42px;'>TSE2024</span> | **No Need to Lift a Finger Anymore? Assessing the Quality of Code Generation by ChatGPT**<br><sub>机构: hanghaiTech University<br>本文对ChatGPT在代码生成任务中的表现进行了系统评估，涵盖正确性、复杂性和安全性三方面，通过728道算法题和多轮修复能力测试揭示其潜在问题，为改进基于大语言模型的代码生成技术提供了重要参考。</sub>| <div style='min-width:85px;'>[![arXiv](https://arxiv.org/pdf/2308.04838?logo=arxiv)](http://arxiv.org/pdf/2404.19234v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19234.md)  |









---------------------------

### AI方向会议期刊

| &nbsp;Conference/Year&nbsp;&nbsp; | Paper | Links & Summary |
| --- | --- | --- |
| <span style='display: inline-block; width: 42px;'>07-29</span> | **SeaLLMs 3: Open Foundation and Chat Multilingual Large Language Models for Southeast Asian Languages**<br><sub>机构: DAMO Academy, Alibaba Group<br>SeaLLMs 3是专为东南亚多语言环境设计的大型语言模型，重点在于克服现有模型的局限性，通过高效的语言增强技术和安全可靠的机制，使之能够提供文化适宜的回应，同时减少幻觉现象。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.19672v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.19672.md)  |
| <span style='display: inline-block; width: 42px;'>07-29</span> | **QAEA-DR: A Unified Text Augmentation Framework for Dense Retrieval**<br><sub>机构: Tsinghua University<br>QAEA-DR框架提出了一个针对密集检索的创新文本增强技术，通过集成事件提取和问题答案生成来提高文本生成的质量和健壮性，同时还可以与多种嵌入模型兼容，证明了其在实验中的有效性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |

---------------------------


### 开源大模型

| &nbsp;Conference/Year&nbsp;&nbsp; | Paper | Links & Summary |
| --- | --- | --- |
| <span style='display: inline-block; width: 42px;'>07-29</span> | **SeaLLMs 3: Open Foundation and Chat Multilingual Large Language Models for Southeast Asian Languages**<br><sub>机构: DAMO Academy, Alibaba Group<br>SeaLLMs 3是专为东南亚多语言环境设计的大型语言模型，重点在于克服现有模型的局限性，通过高效的语言增强技术和安全可靠的机制，使之能够提供文化适宜的回应，同时减少幻觉现象。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.19672v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.19672.md)  |
| <span style='display: inline-block; width: 42px;'>07-29</span> | **QAEA-DR: A Unified Text Augmentation Framework for Dense Retrieval**<br><sub>机构: Tsinghua University<br>QAEA-DR框架提出了一个针对密集检索的创新文本增强技术，通过集成事件提取和问题答案生成来提高文本生成的质量和健壮性，同时还可以与多种嵌入模型兼容，证明了其在实验中的有效性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |

---

