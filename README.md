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



### Additional knowledge

 - **Key Differences Between Pre-Training, Post-Training, Fine-Tuning, and In-Context Learning**

| **Aspect**          | **Pre-Training**                        | **Post-Training**                        | **Fine-Tuning**                          | **In-Context Learning**                  |
|----------------------|------------------------------------------|------------------------------------------|------------------------------------------|------------------------------------------|
| **Definition**       | Initial training of a model on a large, general dataset to learn foundational knowledge. | Additional training to refine the model's behavior or outputs after pre-training. | Further training on a task-specific dataset to adapt the model to a specific task or domain. | Using the model (Lauguange model) directly, with task-specific examples provided in the input prompt, to perform a task without updating its weights. |
| **Purpose**          | Learn general-purpose representations (e.g., language understanding, image features). | Improve general behavior, alignment, or safety (e.g., reducing biases, improving coherence). | Specialize the model for a specific task or domain (e.g., sentiment analysis, medical text classification). | Perform a task dynamically by leveraging the model's pre-trained knowledge and providing examples in the input. |
| **Process**          | Train from scratch or continue training on a massive dataset (e.g., text corpora, image datasets). | Use techniques like reinforcement learning from human feedback (RLHF), adversarial training, or unsupervised learning. | Update the model's weights on a smaller, task-specific dataset, often with a lower learning rate. | Provide task-specific examples or instructions in the input prompt, and the model generates the desired output without weight updates. |
| **Data Requirements**| Large, diverse, and often unlabeled datasets (e.g., Common Crawl, ImageNet). | May use unlabeled data, human feedback, or other forms of supervision. | Requires labeled data specific to the task or domain. | Requires only a few examples or instructions in the input prompt (no additional training data). |
| **Training Scope**   | General-purpose learning (e.g., language modeling, image recognition). | General or behavioral refinement (e.g., alignment with human preferences). | Task-specific adaptation (e.g., classifying emails as spam or not spam). | No training; the model uses its pre-trained knowledge and attention mechanisms to adapt its behavior dynamically based on the examples or instructions provided in the input prompt. |
| **Model Changes**    | Initializes or updates the model's weights with general knowledge. | Refines the model's behavior without necessarily specializing it for a task. | Updates the model's weights to specialize it for a specific task or domain. | No changes to the model's weights; it relies on the input prompt for task-specific guidance. |
| **Use Cases**        | Foundation for transfer learning (e.g., GPT, BERT, ResNet). | Aligning LLMs with human values, reducing harmful outputs, or improving robustness. | Adapting pre-trained models to specific tasks like sentiment analysis, object detection, or medical diagnosis. | Performing tasks like translation, summarization, or question-answering without additional training. |
| **Example**          | Training GPT on a large text corpus to learn language patterns. | Using RLHF to make ChatGPT more aligned with user intentions. | Fine-tuning BERT on a dataset of customer reviews for sentiment analysis. | Provide a few examples of English-to-French translations in the input prompt and ask the model to translate a new sentence. |


### Reasoning
- SAFECHAIN: Safety of Language Models with Long Chain-of-Thought Reasoning Capabilities https://arxiv.org/pdf/2502.12025
- Are Smarter LLMs Safer? Exploring Safety-Reasoning Trade-offs in Prompting and Fine-Tuning https://arxiv.org/pdf/2502.09673
- Challenges in Ensuring AI Safety in DeepSeek-R1 Models: The Shortcomings of Reinforcement Learning Strategies https://arxiv.org/pdf/2501.17030v1
- A Mousetrap: Fooling Large Reasoning Models for Jailbreak with Chain of Iterative Chaos https://arxiv.org/pdf/2502.15806
- Enhancing Model Defense Against Jailbreaks with Proactive Safety Reasoning https://arxiv.org/pdf/2501.19180
- Safety at Scale: A Comprehensive Survey of Large Model Safety https://arxiv.org/pdf/2502.05206
- Rethinking Bottlenecks in Safety Fine-Tuning of Vision Language Models https://arxiv.org/pdf/2501.18533
- OVERTHINK: Slowdown Attacks on Reasoning LLMs https://arxiv.org/pdf/2502.02542
- Demystifying Long Chain-of-Thought Reasoning in LLMs https://arxiv.org/abs/2502.03373