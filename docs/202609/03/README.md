# 日报 · 2026-09-03

- 生成时间：2026-09-03 23:08:48 UTC
- 当次推荐总数：7
- 精读区：3
- 速读区：4

## 今日简报（AI）
今日精读聚焦长上下文解码与预填充两大稀疏化方向，速读覆盖压缩管线、缓存策略与端侧内存管理。  
最值得关注的是“Faster Than Flash”利用注意力稀疏性加速解码，以及CRISP依输入结构做自适应稀疏预填充，双双获8分高分。  
建议重点理解稀疏注意力在长文本推理中的实际收益，并留意压缩与缓存策略对单卡部署的耦合影响。

## 精读区
1. [Faster Than Flash: Exploiting Attention Sparsity for Efficient Long-Context Decoding](/202609/03/2609.00097v1-faster-than-flash-exploiting-attention-sparsity-for-efficient-long-context-decoding) （8.0/10）
2. [CRISP: Cliff-awaRe Input-adaptive Sparse Prefilling with Structural-Mass-Motivated Routing](/202609/03/2609.01925v1-crisp-cliff-aware-input-adaptive-sparse-prefilling-with-structural-mass-motivated-routing) （8.0/10）
3. [HeadWiseKV: Budgeted Per-Head Cache Residency for Hybrid Long-Context Language Models](/202609/03/2609.02029v1-headwisekv-budgeted-per-head-cache-residency-for-hybrid-long-context-language-models) （8.0/10）

## 速读区
1. [Budget-Aware Compression Pipeline for Single-GPU LLM Inference: Methods, Trade-offs, and Coupling Effects](/202609/03/2608.30076v1-budget-aware-compression-pipeline-for-single-gpu-llm-inference-methods-trade-offs-and-coupling-effects) （7.0/10）
2. [Multi-Turn LLM Conversations under the Least-Recently-Used Policy: Mean-Field Asymptotics and Hit Ratio Approximation](/202609/03/2609.02027v1-multi-turn-llm-conversations-under-the-least-recently-used-policy-mean-field-asymptotics-and-hit-ratio-approximation) （7.0/10）
3. [mzCache: On-Device LLM Memory Management under Multitasking](/202609/03/2609.01338v1-mzcache-on-device-llm-memory-management-under-multitasking) （6.0/10）
4. [Architecting Conversational Data Systems for Stateless LLM APIs: The Hydration Proxy Pattern](/202609/03/2609.01834v1-architecting-conversational-data-systems-for-stateless-llm-apis-the-hydration-proxy-pattern) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
