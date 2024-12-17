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
| <span style='display: inline-block; width: 42px;'>arXiv2205.12615</span> | **Autoformalization with Large Language Models**<br><sub>机构: Google Research<br>这篇论文的主要内容是探讨了如何使用大型语言模型（LLMs）来实现自动形式化（Autoformalization），即将自然语言数学问题自动翻译成形式规范和证明。研究者们发现大型语言模型在将数学竞赛问题完美翻译成Isabelle/HOL形式规范方面表现出了惊人的能力，并且通过在这些自动形式化定理上训练神经定理证明器，提高了证明率，从而在MiniF2F定理证明基准测试中取得了新的最佳结果。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2205.12615)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.19672.md)  |


---

### 软件工程（顶会）

| &nbsp;Conference/Year&nbsp;&nbsp; | Paper | Links & Summary |
| --- | --- | --- |
| <span style='display: inline-block; width: 42px;'>06-30</span> | **Step-Controlled DPO: Leveraging Stepwise Error for Enhanced Mathematical Reasoning**<br><sub>机构: Multimedia Laboratory (MMLab), The Chinese University of Hong Kong<br>本论文提出了一种新的数学推理优化方法——SCDPO，通过在特定步骤监督错误的方式，自动化地生成训练样本，显著提升了LLMs在数学问题求解方面的性能，证明了该方法的潜力。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.00782v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-06/2407.00782.md)  |
| <span style='display: inline-block; width: 42px;'>06-29</span> | **LiteSearch: Efficacious Tree Search for LLM**<br><sub>机构: Xiamen University, Tencent AI Lab<br>该论文通过提出一种效率更高的树搜索算法来降低在辅助大型语言模型解决复杂数学推理任务时的资源消耗，同时确保保持高性能水平。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.00320v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-06/2407.0032.md)  |
| <span style='display: inline-block; width: 42px;'>FSE2024</span> | **Can Large Language Models Transform Natural Language Intent into Formal Method Postconditions?**<br><sub>机构: University of Michigan, USA<br>本论文探索了利用 LLMs 作为非正式自然语言和方法后置条件之间的桥梁（我们称这种方法为 nl2postcond）的可行性。方法后置条件是断言，它将方法输入和输出状态相关联，并在任何成功执行方法后成立。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://dl.acm.org/doi/pdf/10.1145/3660791)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-12/2412.09161.md)  |
| <span style='display: inline-block; width: 42px;'>FSE2024</span> | **CoqPyt: Proof Navigation in Python in the Era of LLMs**<br><sub>机构: Imperial College London, UK<br>本论文介绍了 CoqPyt，这是一个使用 Coq LSP 作为后端在 Python 中与 Coq 交互的工具。可以促进基于 LLM 的 Coq 证明合成和修复研究。它通过提供丰富的上下文数据和灵活的修改功能，为开发神经网络定理证明器提供了便利。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://dl.acm.org/doi/pdf/10.1145/3663529.3663814)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-12/2412.09162.md)  |
| <span style='display: inline-block; width: 42px;'>FSE2024</span> | **Neuro-Symbolic Approach to Certiﬁed Scientiﬁc Software Synthesis**<br><sub>机构: University of Nebraska-Lincoln, NE, USA<br>本论文提出了一种创新的“神经符号方法”，用于认证科学软件的自动合成。该框架将大型语言模型（LLMs）与形式化方法相结合，实现了复杂科学软件的自动化合成，同时确保了可验证性和正确性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://www.researchgate.net/profile/Mohamad-Fazelnia-2/publication/382156788_Neuro-Symbolic_Approach_to_Certified_Scientific_Software_Synthesis/links/66b9cb9951aa0775f27a994f/Neuro-Symbolic-Approach-to-Certified-Scientific-Software-Synthesis.pdf)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-12/2412.09163.md)  |
| <span style='display: inline-block; width: 42px;'>FSE2023</span> | **Baldur: Whole-Proof Generation and Repair with Large Language Models**<br><sub>机构: University of Massachusetts Amherst, MA, USA<br>本文提出了 Baldur，一种使用大型语言模型（LLMs）生成整个形式化证明的方法，无需使用锤子或昂贵的搜索。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/pdf/2303.04910)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-12/2412.09164.md)  |
| <span style='display: inline-block; width: 42px;'>FSE2024</span> | **Testing Learning-Enabled Cyber-Physical Systems with Large-Language Models: A Formal Approach**<br><sub>机构: Macquarie University<br>本文探讨了学习型 CPS （网络物理系统）验证和确认的实用测试策略。使用大型语言模型 (LLM) 从现有的规则和法规中提取人类知识，并分析学习型 CPS 生成或捕获的大量数据，包括传感器数据和日志。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://dl.acm.org/doi/pdf/10.1145/3663529.3663779)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-12/2412.09165.md)  |
| <span style='display: inline-block; width: 42px;'>FSE2023</span> | **The FormAI Dataset: Generative AI in Software Security through the Lens of Formal Verification**<br><sub>机构: Technology Innovation Institute<br>本文介绍了 FormAI 数据集，这是一个包含 112,000 个由 AI 生成并可编译的独立 C 程序的大型数据集，并对程序中的漏洞进行了分类。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://dl.acm.org/doi/pdf/10.1145/3617555.3617874)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-12/2412.09166.md)  |
| <span style='display: inline-block; width: 42px;'>FSE2023</span> | **Towards AI-Assisted Synthesis of Verified Dafny Methods**<br><sub>机构: The University of Manchester<br>本文演示了如何提高两个预训练模型在 Dafny 验证感知语言中的熟练程度。我们使用 MBPP 数据集中的 178 个问题，提示两个当代模型（GPT-4 和 PaLM-2）生成 Dafny 方法。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://dl.acm.org/doi/pdf/10.1145/3691620.3695512)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-12/2412.09167.md)  |
| <span style='display: inline-block; width: 42px;'>ASE2024</span> | **LLM-Generated Invariants for Bounded Model Checking Without Loop Unrolling**<br><sub>机构: University of California Irvine<br>本文研究了一种经典有界模型检验（BMC）过程的修改，它不是通过循环展开来处理循环，而是通过修改控制流图（CFG）。将表示循环的 CFG 的一部分替换为一个节点，该节点断言循环的不变量。我们使用大型语言模型（LLMs）生成这些不变量，并使用一阶定理证明器来确保生成语句的正确性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://dl.acm.org/doi/pdf/10.1145/3643763)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-12/2412.09191.md)  |
| <span style='display: inline-block; width: 42px;'>ASE2024</span> | **Proof Automation with Large Language Models**<br><sub>机构: Purdue University<br>本文提出了 PALM，这是一种新颖的“生成然后修复”方法，它首先提示 LLM 生成一个初始证明，然后利用针对单个证明步骤的低级别问题的有针对性的符号方法进行迭代修复。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://dl.acm.org/doi/pdf/10.1145/3691620.3695521)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-12/2412.09192.md)  |
| <span style='display: inline-block; width: 42px;'>MODELS-C</span> | **Towards an Extensible Architecture and Tool Support for Model-Based Verification**<br><sub>机构: Universidad de Málaga<br>提出了一种基于 Web 的架构，旨在支持域模型的定义，并提供对不同验证形式的转换能力。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://ieeexplore.ieee.org/document/10350808/authors#authors)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.19672.md)  |
| <span style='display: inline-block; width: 42px;'>CSECS2024</span> | **Enhancing Translation Validation of Compiler Transformations with Large Language Models**<br><sub>机构: Department of Computer Science Portland State University<br>这篇论文的主要内容是介绍了一个集成了大型语言模型（LLMs）的框架，用于增强编译器转换的翻译验证，特别是在LLVM编译器转换中，传统的正式验证工具难以处理的地方。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2401.16797)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.19672.md)  |

---

### 形式化，编程语言，系统，安全（顶刊）

| &nbsp;Journal/Year&nbsp;&nbsp; | Paper | Links & Summary |
| --- | --- | --- |
| <span style='display: inline-block; width: 42px;'>05-31</span> | **Preemptive Answer "Attacks" on Chain-of-Thought Reasoning**<br><sub>机构: Tsinghua University<br>论文研究了预先答案对LLMs推理能力的负面影响，并提出了减轻其影响的策略。实验结果表明，这些策略不能完全抵消预先答案的影响，提示需要进一步增强CoT的鲁棒性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2405.20902v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-05/2405.20902.md)  |
| <span style='display: inline-block; width: 42px;'>05-31</span> | **Preemptive Answer "Attacks" on Chain-of-Thought Reasoning**<br><sub>机构: Tsinghua University<br>论文研究了预先答案对LLMs推理能力的负面影响，并提出了减轻其影响的策略。实验结果表明，这些策略不能完全抵消预先答案的影响，提示需要进一步增强CoT的鲁棒性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2405.20902v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-05/2405.20902.md)  |
| <span style='display: inline-block; width: 42px;'>05-31</span> | **Transformers are SSMs: Generalized Models and Efficient Algorithms Through Structured State Space Duality**<br><sub>机构: Princeton University, Carnegie Mellon University<br>本论文展示了一个全新的状态空间对偶性（SSD）框架，连接了结构化的状态空间模型（SSMs）和注意力机制变体。论文的主要贡献包括将原本针对Transformers的算法和系统优化应用到SSMs上，以及开发了一种新的SSD算法，有效提高了模型训练和推理的效率。Mamba-2架构作为最终产品，实现了理想的性能表现，为未来的深度学习模型设计和优化提供了新的方向。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2405.21060v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-05/2405.2106.md)  |
| <span style='display: inline-block; width: 42px;'>TDSC2024</span> | **Formal-LLM: Integrating Formal Language and Natural Language for Controllable LLM-based Agents**<br><sub>机构: Department of Computer Science, Rutgers University, New Brunswick<br>这篇论文的主要内容是提出了一个名为“Formal-LLM”的框架，旨在将形式语言的精确性与自然语言的表现力结合起来，以提高基于大型语言模型（LLM）的智能代理的计划生成的可控性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2402.00798)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-05/2405.2106.md)  |
| <span style='display: inline-block; width: 42px;'>TOCS2024</span> | **The FormAI Dataset: Generative AI in Software Security Through the Lens of Formal Verification**<br><sub>机构: Technology Innovation Institute Abu Dhabi UAE<br>这篇论文的主要内容是介绍了FormAI数据集，这是一个包含112,000个AI生成的可编译独立C程序的大型数据集，旨在通过形式验证来分析软件安全性。FormAI数据集为研究AI生成代码的安全性提供了重要的资源。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2307.02192)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-05/2405.2106.md)  |

---

### 软件工程（顶刊）

| &nbsp;Journal/Year&nbsp;&nbsp; | Paper | Links & Summary |
| --- | --- | --- |
| <span style='display: inline-block; width: 42px;'>TOSEM2024</span> | **Smart Contract Code Repair Recommendation based on Reinforcement Learning and Multi-metric Optimization**<br><sub>机构: Georgia Institute of Technology<br>本文提出了一种基于强化学习的智能合约漏洞修复方法RLRep，能够在缺乏监督数据的情况下为开发者提供漏洞修复建议。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/pdf/2409.06213?logo=arxiv)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19737.md)  |
| <span style='display: inline-block; width: 42px;'>TOSEM2024</span> | **On the Reliability and Explainability of Language Models for Program Generation**<br><sub>机构: Monash University<br>本文通过实证研究揭示了当前主流预训练语言模型在自动程序生成任务中的局限性，指出数据重复导致的过于乐观的性能评估问题，并通过可解释性分析表明这些模型在代码语法和结构识别方面有一定能力，但对输入变化的鲁棒性较差，呼吁更严格的评估方法和基准测试以提升模型的可靠性和可解释性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/pdf/2409.06213?logo=arxiv)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19737.md)  |
| <span style='display: inline-block; width: 42px;'>TOSEM2024</span> | **Beyond Fidelity: Explaining Vulnerability Localization of Learning-Based Detectors**<br><sub>机构: Peking University<br>本文评估了10种解释方法在深度学习漏洞检测器中的表现，发现现有方法在关键漏洞相关代码行的精确性方面表现较差，这主要归因于解释器选择重要特征的效率低下以及检测器学习到的无关信息，研究结果强调了单纯依赖忠实度指标的局限性，并提出需要改进解释方法以提高准确性和实用性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/pdf/2409.06213?logo=arxiv)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19737.md)  |
| <span style='display: inline-block; width: 42px;'>TOSEM2024</span> | **Automated Mapping of Vulnerability Advisories onto their Fix Commits in Open Source Repositories**<br><sub>机构: SAP Security Research <br>本文提出了一种结合经验启发和自然语言处理的机器学习方法，用于匹配漏洞公告与修复提交，通过FixFinder原型验证，在前10结果中成功定位修复提交的比例达84.03%，显著减少了查找漏洞修复提交的工作量。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/pdf/2409.06213?logo=arxiv)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19737.md)  |
| <span style='display: inline-block; width: 42px;'>TSE2022</span> | **Automated Generation of Acceptance Test Cases From Use Case Specifications: An NLP-Based Approach**<br><sub>机构: null<br>本文提出了UMTG方法，通过自然语言处理技术从需求规格中自动生成验收测试用例，减少人工工作量并覆盖需求，在两项工业案例中正确转换95%的用例步骤，并发现了专家未考虑的关键测试场景。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/pdf/2409.06213?logo=arxiv)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19737.md)  |
| <span style='display: inline-block; width: 42px;'>TSE2023</span> | **Specification-Based Autonomous Driving System Testing**<br><sub>机构: Nanyang Technological University<br>本文提出AVUnit框架，通过自定义规范系统化测试自动驾驶系统，支持动态场景属性和精细断言，结合模糊测试发现Apollo在复杂路口和变道场景下存在19种问题，表明其性能不足。</sub>|<div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/pdf/2409.06213?logo=arxiv)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19737.md)  |
| <span style='display: inline-block; width: 42px;'>TSE2024</span> | **No Need to Lift a Finger Anymore? Assessing the Quality of Code Generation by ChatGPT**<br><sub>机构: hanghaiTech University<br>本文对ChatGPT在代码生成任务中的表现进行了系统评估，涵盖正确性、复杂性和安全性三方面，通过728道算法题和多轮修复能力测试揭示其潜在问题，为改进基于大语言模型的代码生成技术提供了重要参考。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/pdf/2409.06213?logo=arxiv)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-04/2404.19737.md)  |

---

### AI方向会议期刊

| &nbsp;Conference/Year&nbsp;&nbsp; | Paper | Links & Summary |
| --- | --- | --- |
| <span style='display: inline-block; width: 42px;'>NeurIPS2022</span> | **Autoformalization with large language modelss**<br><sub>机构: Google Research<br>用LLM从自然语言自动生成形式化规约</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.19672v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.19672.md)  |
| <span style='display: inline-block; width: 42px;'>ICLR2022</span> | **PACT：Proof Artifact Co-training for Theorem Proving with Language Models**<br><sub>机构: OpenAI<br>用自监督学习PACT利用起来了LEAN的已有定理库，解决数据稀少的问题。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>neurIPS2022</span> | **HTPS：HyperTree Proof Search for Neural Theorem Proving**<br><sub>机构: Meta AI<br>用基于hyperTree搜索的算法寻找形式化证明步骤，并且借助online training训练模型。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>neurIPS2022</span> | **Thor: Wielding Hammers to Integrate Language Models and Automated Theorem Provers**<br><sub>机构: Cambridge University<br>第一个把LLM和Isabelle中的sledgehammer结合，去寻找要证明的定理的相关引理，大模型只负责判断何时调用hammer。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>neurIPS2022</span> | **NATURALPROVER: Grounded Mathematical Proof Generation with Language Models**<br><sub>机构: University of Washington<br>生成了用于数学证明的自然语言数据集，并且第一个训练模型生成自然语言证明。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>ICLR2023</span> | **Draft, Sketch, and Prove: Guiding Formal Theorem Provers with Informal Proofs**<br><sub>机构: Cambridge University<br>利用Isabelle的sledgehammer解决形式化证明生成的问题，从非形式化的数学描述开始，生成形式化的完整证明。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>neurIPS2023</span> | **LeanDojo: Theorem Proving with Retrieval-Augmented Language Models**<br><sub>机构: Caltech<br>在LEAN中做证明生成的鼻祖，并且有对应的工具Copilot。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>TOPLAS2024</span> | **Passport: Improving Automated Formal Verification Using Identifiers**<br><sub>机构: UIUC<br>在coq中做引理查找。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>ICLR2024</span> | **Magnushammer: A Transformer-based Approach to Premise Selection**<br><sub>机构: Google Research<br>在Isabelle中的改进的引理查找。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>ICLR2024</span> | **LEGO-Prover: Neural Theorem Proving with Growing Libraries**<br><sub>机构: Huawei<br>用prompt engineering做证明生成，重点在构建了一个持续增长的定理库。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>NeurIPS2024</span> | **FVEL: Interactive Formal Verification Environment with Large Language Models via Theorem Proving**<br><sub>机构: Huawei<br>类似于LEGO。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>暂时没中</span> | **Decomposing the Enigma: Subgoal-based Demonstration Learning for Formal Theorem Proving**<br><sub>机构: HongKong<br>把完整的证明拆分成subgoal去做，思路简单。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>TMLR2024</span> | **Lyra: Orchestrating Dual Correction in Automated Theorem Proving**<br><sub>机构: Huawei<br>类似LEGO。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>ICML2024</span> | **Graph2Tac: Online Representation Learning of Formal Math Concepts**<br><sub>机构: Institut des Hautes Etudes Scientifiques<br>Graph2Tac 和在线 k-NN 求解器通过利用在线信息，显著提高了 Coq 证明辅助工具的性能，并优于现有的通用证明器。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>ICML2024</span> | **Autoformalizing Euclidean Geometry**<br><sub>机构: University of Toronto<br>介绍了一种用于自动形式化欧几里得几何的神经符号框架，该框架结合了领域知识、SMT求解器和大型语言模型（LLM）。使用定理证明器自动填补这些图表信息，从而使LLM只需要自动形式化显式的文本步骤，从而使模型更容易理解。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>ICML2024</span> | **Subgoal-based Demonstration Learning for Formal Theorem Proving**<br><sub>机构: The University of Hong Kong<br>提出了一种基于子目标的演示学习框架，基于子目标的演示学习框架，旨在提升大型语言模型（LLM）在形式定理证明方面的效率。该框架显著提高了 LLM 在形式定理证明领域的性能，为 LLM 在该领域的应用开辟了新的途径。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>ICLR2024</span> | **Don't Trust: Verify -- Grounding LLM Quantitative Reasoning with Autoformalization**<br><sub>机构: Cornell University<br>该论文探讨了大型语言模型（LLM）在解决数学定量推理问题时，如何通过自动形式化（autoformalization）将非正式数学陈述转换为形式化的Isabelle代码，以验证其内部一致性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2403.18120)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>ICLR2023</span> | **Lemur: Integrating Large Language Models in Automated Program Verification**<br><sub>机构: Department of Computer Science Stanford University<br>这篇论文的主要内容是提出了一个名为LEMUR的框架，该框架整合了大型语言模型（LLMs）和自动化推理器，用于自动化程序验证。在两组基准测试上对LEMUR进行了实验评估，展示了其效率与现有的AI驱动和传统验证工具相比的优势。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2310.04870)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>ICLR2023</span> | **A New Era in Software Security: Towards Self-Healing Software via Large Language Models and Formal Verification**<br><sub>机构: Technology Innovation Institute (TII), UAE<br>这篇论文的主要内容是介绍了一个名为ESBMC-AI的框架，该框架结合了大型语言模型（LLMs）和形式验证策略，用于自动软件漏洞修复。使用有界模型检测（BMC）来识别漏洞并提取反例，然后将这些反例与原始源代码一起输入到LLM中，LLM被指导尝试修复代码。修复后的代码再次使用BMC进行验证，确保修复成功。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2305.14752)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>ICLR2023</span> | **Baldur: Whole-Proof Generation and Repair with Large Language Models**<br><sub>机构: University of Massachusetts Amherst, MA, USA<br>这篇论文的主要内容是介绍了一个名为Baldur的系统，该系统利用大型语言模型（LLMs）进行完整的证明生成和修复，以自动化形式验证软件属性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2303.04910)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |

---------------------------


### 开源大模型

| &nbsp;Conference/Year&nbsp;&nbsp; | Paper | Links & Summary |
| --- | --- | --- |
| <span style='display: inline-block; width: 42px;'>07-29</span> | **SeaLLMs 3: Open Foundation and Chat Multilingual Large Language Models for Southeast Asian Languages**<br><sub>机构: DAMO Academy, Alibaba Group<br>SeaLLMs 3是专为东南亚多语言环境设计的大型语言模型，重点在于克服现有模型的局限性，通过高效的语言增强技术和安全可靠的机制，使之能够提供文化适宜的回应，同时减少幻觉现象。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.19672v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.19672.md)  |
| <span style='display: inline-block; width: 42px;'>07-29</span> | **QAEA-DR: A Unified Text Augmentation Framework for Dense Retrieval**<br><sub>机构: Tsinghua University<br>QAEA-DR框架提出了一个针对密集检索的创新文本增强技术，通过集成事件提取和问题答案生成来提高文本生成的质量和健壮性，同时还可以与多种嵌入模型兼容，证明了其在实验中的有效性。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2407.20207v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2024-07/2407.20207.md)  |
| <span style='display: inline-block; width: 42px;'>arXiv:2408.08152 (2024).</span> | **DeepSeek-Prover-V1.5-Harnessing Proof Assistant Feedback**<br><sub>机构: DeepSeek-AI <br>DeepSeek-Prover-V1.5旨在 Lean 4 中进行定理证明，该模型在 DeepSeekMath-Base 上进行了预训练，专注于形式数学语言，并使用从 DeepSeek-Prover-V1 派生的增强形式定理证明数据集进行了监督微调。通过从证明助手反馈中进行强化学习（RLPAF），进一步实现了精细化，在高中水平的 miniF2F 基准测试集上取得了新的最先进结果（63.5%），以及在ProofNet 基准测试上达到了 25.3%。。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/pdf/2408.08152?)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)]()  |
| <span style='display: inline-block; width: 42px;'>ICLR2024</span> | **LLEMMA: AN OPEN LANGUAGE MODEL FOR MATHEMATICS**<br><sub>机构: Princeton University <br>LLEMMA，一个用于数学的大型语言模型。模型在Proof-Pile-2上对Code Llama进行预训练，Proof-Pile-2是一个包含科学论文、含有数学的网络数据和数学代码的混合数据集，从而生成了LLEMMA。在MATH基准测试中，LLEMMA超越了所有已知的开放基础模型，以及未发布的Minerva模型套件，且在参数相等的基础上表现优异。此外，LLEMMA能够使用工具并进行形式化定理证明，而无需进一步的微调。（复现后在minif2f上的正确率为20.29%(128 times)）</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/pdf/2408.08152?)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)]()  |
| <span style='display: inline-block; width: 42px;'>arXiv:2407.03203, 2024.</span> | **Theoremllama: Transforming general-purpose llms into lean4 experts**<br><sub>机构: Hong Kong University of Science and Technology <br>本文提出了TheoremLlama，一个端到端框架，旨在训练一个通用的LLM成为Lean4专家。TheoremLlama包括NL-FL数据集生成和引导方法，使用课程学习和块训练技术来训练模型，以及迭代证明写作方法，以协同编写有效的Lean4证明。TheoremLlama框架在MiniF2F-Valid和Test数据集上分别达到了36.48%和33.61%的累积准确率，超过了GPT-4基线的22.95%和25.41%。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/pdf/2408.08152?)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)]()  |
| <span style='display: inline-block; width: 42px;'>arXiv:2302.13971, 2023.</span> | **LLaMA: Open and Efficient Foundation Language Models**<br><sub>机构: Meta <br>这篇论文介绍了 LLaMA，这是一系列由 Meta AI 开发的基础语言模型，参数规模从7B（70亿参数）到65B（650亿参数）不等。这些模型在数万亿个token上进行训练，展示了仅使用公开可用的数据集就能训练出达到最先进水平的模型，而不需要依赖私有且难以获取的数据集。</sub>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](https://arxiv.org/abs/2302.13971)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)]()  |



---

