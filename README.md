# Llama3-8B-from-scratch

这是一个关于 **Llama 3 架构** 的“白盒”级重构与解析项目。本项目旨在脱离高层框架抽象，从底层张量运算开始，逐步实现 Llama 3 的核心组件，并加载官方权重进行推理验证。

##  介绍
- **从零实现 (From Scratch)**：不依赖于现成的 Transformer 库，手动构建模型架构。
- **底层算子理解**：深入 Rotary Positional Embeddings (RoPE)、Grouped Query Attention (GQA) 和 KV Cache 的代码级实现。
- **白盒解析**：对 Llama 3 的 8B 参数模型进行权重映射与手动加载。
