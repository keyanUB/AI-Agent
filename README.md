# AI-Agent Security


## Whitepaper

- Google: Agents. [paper](./resources/Newwhitepaper_Agents2.pdf)

## Survey

- AI Agents Under Threat: A Survey of Key Security Challenges and Future Pathways. [paper](https://arxiv.org/pdf/2406.02630)

- Security of AI Agents. [paper](https://arxiv.org/pdf/2406.08689)

- Navigating the Risks: A Survey of Security, Privacy, and Ethics Threats in LLM-Based Agents. [paper](https://arxiv.org/pdf/2411.09523)

- Personal LLM Agents: Insights and Survey about the Capability, Efficiency and Security. [paper](https://arxiv.org/abs/2401.05459)

- The Rise and Potential of Large Language Model Based Agents: A Survey. [paper](https://arxiv.org/pdf/2309.07864)

- The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies. [paper](https://arxiv.org/pdf/2407.19354)

## Paper

### Attack
- Towards Action Hijacking of Large Language Model-based Agent. [paper](https://arxiv.org/pdf/2412.10807)


### Defense
- Defining and Detecting the Defects of the Large Language Model-based Autonomous Agent. [paper](https://arxiv.org/pdf/2412.18371)


### Related Papers
- SecCodePLT: A Unified Platform for Evaluating the Security of Code GenAI. [github](https://seccodeplt.github.io) [dataset](https://huggingface.co/datasets/Virtue-AI-HUB/SecCodePLT) [paper](https://arxiv.org/pdf/2410.11096)


### Article / Resource

- LLM-enabled agent systems safety and security. [link](https://henrygwb.github.io/posts/agent_security.htm)



### Addtional knowledge

- **Key Differences Between Pre-Training, Post-Training, and Fine-Tuning**

| **Aspect**          | **Pre-Training**                        | **Post-Training**                        | **Fine-Tuning**                          |
|----------------------|------------------------------------------|------------------------------------------|------------------------------------------|
| **Definition**       | Initial training of a model on a large, general dataset to learn foundational knowledge. | Additional training to refine the model's behavior or outputs after pre-training. | Further training on a task-specific dataset to adapt the model to a specific task or domain. |
| **Purpose**          | Learn general-purpose representations (e.g., language understanding, image features). | Improve general behavior, alignment, or safety (e.g., reducing biases, improving coherence). | Specialize the model for a specific task or domain (e.g., sentiment analysis, medical text classification). |
| **Process**          | Train from scratch or continue training on a massive dataset (e.g., text corpora, image datasets). | Use techniques like reinforcement learning from human feedback (RLHF), adversarial training, or unsupervised learning. | Update the model's weights on a smaller, task-specific dataset, often with a lower learning rate. |
| **Data Requirements**| Large, diverse, and often unlabeled datasets (e.g., Common Crawl, ImageNet). | May use unlabeled data, human feedback, or other forms of supervision. | Requires labeled data specific to the task or domain. |
| **Training Scope**   | General-purpose learning (e.g., language modeling, image recognition). | General or behavioral refinement (e.g., alignment with human preferences). | Task-specific adaptation (e.g., classifying emails as spam or not spam). |
| **Model Changes**    | Initializes or updates the model's weights with general knowledge. | Refines the model's behavior without necessarily specializing it for a task. | Updates the model's weights to specialize it for a specific task or domain. |
| **Use Cases**        | Foundation for transfer learning (e.g., GPT, BERT, ResNet). | Aligning LLMs with human values, reducing harmful outputs, or improving robustness. | Adapting pre-trained models to specific tasks like sentiment analysis, object detection, or medical diagnosis. |
| **Example**          | Training GPT on a large text corpus to learn language patterns. | Using RLHF to make ChatGPT more aligned with user intentions. | Fine-tuning BERT on a dataset of customer reviews for sentiment analysis. |
