# 日报 · 2026-09-17

- 生成时间：2026-09-17 21:54:59 UTC
- 当次推荐总数：7
- 精读区：2
- 速读区：5

## 今日简报（AI）
今天筛完7篇KV缓存相关论文，精读2篇、速读5篇，主线是复用、修复与推理加速。  
最值得看：LoRA适配器共享前缀KV复用的质量与服务权衡，以及文档编辑后按“连续性”而非“重要性”预算修复陈旧KV缓存。  
普通读者可优先读这两篇精读，先建立“缓存复用要算质量账、修复要看结构连续性”的判断。

## 精读区
1. [Shared-Prefix KV Reuse Across Standard LoRA Adapters: Quality and Serving Tradeoffs](/202609/17/2609.17109v1-shared-prefix-kv-reuse-across-standard-lora-adapters-quality-and-serving-tradeoffs) （9.0/10）
2. [Contiguity, Not Importance: Budgeted Repair of Stale KV Caches After Document Edits](/202609/17/2609.17983v1-contiguity-not-importance-budgeted-repair-of-stale-kv-caches-after-document-edits) （8.0/10）

## 速读区
1. [Where Should the KV Cache Live? Placement Policies Across GPU, CPU, and SSD for Long-Lived Sessions](/202609/17/2609.16215v1-where-should-the-kv-cache-live-placement-policies-across-gpu-cpu-and-ssd-for-long-lived-sessions) （7.0/10）
2. [Fathom: Per-Query Read Depth for Sparse Decoding over Offloaded KV Caches](/202609/17/2609.17652v1-fathom-per-query-read-depth-for-sparse-decoding-over-offloaded-kv-caches) （7.0/10）
3. [ASPIRE: Asynchronous Batched Self-Speculative Decoding for Long-Context LLM Inference](/202609/17/2609.17943v1-aspire-asynchronous-batched-self-speculative-decoding-for-long-context-llm-inference) （7.0/10）
4. [Where Should a Document Live: Context, Representations, or Parameters?](/202609/17/2609.17346v1-where-should-a-document-live-context-representations-or-parameters) （6.0/10）
5. [The Inference Engineering Pareto Atlas: Which Optimizations Dominate the Cost, Quality, and Latency Frontier?](/202609/17/2609.17863v1-the-inference-engineering-pareto-atlas-which-optimizations-dominate-the-cost-quality-and-latency-frontier) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
