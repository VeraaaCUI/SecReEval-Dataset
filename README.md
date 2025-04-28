# SecEval: A Scenario-Based Security Evaluation Dataset for Large Language Models

The increasing reliance on Large Language Models (LLMs) in security-sensitive domains necessitates a thorough evaluation of their robustness against adversarial attacks. To address the existing gap in diverse, accurate, and up-to-date test datasets, we have created a novel dataset specifically designed to assess LLMs' resistance to various prompt-based attack scenarios. 

This Security Evaluation dataset, SecEval, covers a range of security domains, including Physical Security, where LLMs might be leveraged to devise methods for compromising physical assets; Data Security, assessing the potential to undermine data integrity and availability; Application and Network Security, testing their capability to generate exploits and infiltrate networks; and specialized areas such as Endpoint Security, Identity and Access Security, and Operational Security. 

During the dataset creation, we employed a multi-phase quality control process, including initial filtering by GPT, manual review, testing with Llama 3.1, and iterative human refinement to ensure relevance and accuracy. We then conducted a detailed evaluation of state-of-the-art LLMs: Llama 3.1, Gemma 2, Mirstral v3.0 and DeepSeek-R1 focusing on their vulnerability to these attack types and their response efficiency. Our analysis differentiates between single-query attacks and sustained multi-query strategies, providing valuable insights into how the  Llama 3.1, Gemma 2, Mirstral v3.0 and DeepSeek-R1 models adapt and maintains their security posture under continuous threats.
## Introduction

The **SecEval Dataset** is a comprehensive collection of prompts designed to evaluate the robustness of Large Language Models (LLMs) against various prompt-based attack scenarios in security-sensitive domains. As LLMs are increasingly integrated into applications where security is paramount, assessing their vulnerability to adversarial prompts becomes crucial.

## Dataset Overview

- **Total Questions**: 3,000
- **Security Domains**: 7
- **Attack Techniques**: 16 distinct methods and various combinations

### Security Domains Covered

1. **Physical Security**
2. **Data Security**
3. **Application Security**
4. **Network Security**
5. **Endpoint Security**
6. **Identity and Access Security**
7. **Operational Security**

### Attack Techniques Employed

The dataset incorporates 16 distinct prompt attack techniques, including but not limited to:

- Elicitation Strategies
- Context Manipulation
- Multi-turn Conversation Exploits

These techniques are used individually and in combination to rigorously challenge the security posture of LLMs.

## Dataset Creation Process

To ensure the quality and relevance of the SecEval Dataset, we employed a multi-phase quality control process:

1. **Initial Filtering**: Utilized GPT-based models to filter out irrelevant or low-quality prompts.
2. **Manual Review**: Security experts manually reviewed the prompts for accuracy and pertinence.
3. **Testing with Llama 3.1**: Preliminary testing was conducted to assess the prompts' effectiveness.
4. **Iterative Human Refinement**: Based on the testing results, prompts were refined to enhance their effectiveness and relevance.


## Accessing the Dataset

The SecEval Dataset is publicly available for the research community. You can access it through this repository.

- **Dataset Link**: [SecEval-Dataset](https://github.com/VeraaaCUI/SecEval-Dataset)

## Citation

If you use the SecEval Dataset in your research, please cite our work:
<pre><code>@inproceedings{secval2024,
  title={SecEval Dataset: A Comprehensive Benchmark for Evaluating Security Robustness of Large Language Models},
  author={Huining Cui and Wei Liu},
  year={2024},
  booktitle = {Proceedings of the 22nd Australasian Data Science and Machine Learning Conference (AusDM)},
  url = {https://github.com/VeraaaCUI/SecEval-Dataset}
}
</code></pre>
