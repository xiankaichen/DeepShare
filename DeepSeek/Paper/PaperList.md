# DeepSeek相关论文
以下是 DeepSeek 系列模型的主要版本及其相关论文列表。

## DeepSeek LLM
**论文标题**：DeepSeek LLM: Scaling Open-Source Language Models with Longtermism
**发布时间**：2024 年 1 月 5 日
**主要内容**：基于Transformer 架构，采用分组查询注意力（GQA）优化推理成本。支持多步学习率调度器，提升训练效率。在预训练和对齐（监督微调与 DPO）方面进行了创新。
**论文地址**：https://arxiv.org/abs/2401.0295420

## DeepSeekMoE
**论文标题**：DeepSeekMoE: Towards Ultimate Expert Specialization in Mixture-of-Experts Language Models
**发布时间**：2024 年 1 月 11 日
**主要内容**：提出细粒度专家分割（Fine-Grained Expert Segmentation）和共享专家隔离（Shared Expert Isolation）策略。通过更灵活的专家组合提升模型性能，同时保持计算成本不变。
**论文地址**：https://arxiv.org/abs/2401.060662

## DeepSeek-V2
**论文标题**：DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model
**发布时间**：2024 年 5 月
**主要内容**：引入多头潜在注意力（Multi-head Latent Attention, MLA）和 DeepSeekMoE 架构。在推理效率和训练成本上进行了优化，为后续版本奠定了基础。
**论文地址**：https://arxiv.org/abs/2405.044343

## DeepSeek-V3 强化学习模型
**论文标题**：DeepSeek-V3 Technical Report
**发布时间**：2024 年 12 月 27 日
**主要内容**：总参数量为 671B，每个 token 激活 37B 参数。采用无辅助损失的负载均衡策略和多令牌预测（Multi-Token Prediction, MTP）训练目标。支持 FP8 混合精度训练，显著降低训练成本。
**论文地址**：https://arxiv.org/abs/2412.1943714

## DeepSeek-R1 推理模型
**论文标题**：DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning
**发布时间**：2025 年 1 月
**主要内容**：基于 DeepSeek-V3-Base，通过强化学习（RL）提升推理能力。引入冷启动数据和多阶段训练流程，优化模型的可读性和性能。
**论文地址**：https://arxiv.org/abs/2501.129481

## DeepSeek-R1 蒸馏模型
**论文标题**：Distilling Reasoning Capabilities from DeepSeek-R1 to Smaller Models
**发布时间**：2025 年 1 月
**主要内容**：将 DeepSeek-R1 的推理能力蒸馏到更小的模型（如 Qwen 和 Llama 系列）。蒸馏后的模型在多个基准测试中表现优异，显著超越同类开源模型。
**论文地址**：https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf5

## Janus-Pro 多模态模型
**论文标题**：Janus-Pro: Unified Multimodal Understanding and Generation with Data and Model Scaling
**发布时间**：2025 年 1 月
**主要内容**：Janus-Pro 是先前作品 Janus 的升级版。具体来说，Janus-Pro 引入了以下改进：(1) 优化的训练策略，(2) 扩展的训练数据，以及 (3) 更大规模的模型。通过这些改进，Janus-Pro 在多模态理解和文本到图像的指令跟随能力上取得了显著进步，同时增强了文本到图像生成的稳定性。
**论文地址**：https://arxiv.org/pdf/2501.17811