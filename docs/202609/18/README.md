# 日报 · 2026-09-18

- 生成时间：2026-09-18 22:12:08 UTC
- 当次推荐总数：5
- 精读区：1
- 速读区：4

## 今日简报（AI）
今天精读 1 篇、速读 4 篇，主线集中在 H100 上的 LLM 服务效率与 KV 缓存优化。
最值得看的是《PrefixBench-H100》（9.0/10）对前缀复用与首字延迟（TTFT）的实测刻画，其次是《DeepSeek-V4.1-Flash》（7.0/10）在 KV 缓存压缩上的推进。
普通读者可先看 H100 前缀复用的结论，再顺着 Fathom、On-Demand Attention 等速读理解缓存压缩与按需召回如何影响长上下文推理的显存与速度。

## 精读区
1. [PrefixBench-H100: Characterizing Prefix Reuse and Time-to-First-Token in H100 LLM Serving](/202609/18/2609.19657v1-prefixbench-h100-characterizing-prefix-reuse-and-time-to-first-token-in-h100-llm-serving) （9.0/10）

## 速读区
1. [Fathom: Per-Query Read Depth for Sparse Decoding over Offloaded KV Caches](/202609/18/2609.17652v2-fathom-per-query-read-depth-for-sparse-decoding-over-offloaded-kv-caches) （7.0/10）
2. [DeepSeek-V4.1-Flash: Pushing the Limits of KV Cache Compression](/202609/18/2609.19969v1-deepseek-v41-flash-pushing-the-limits-of-kv-cache-compression) （7.0/10）
3. [On-Demand Attention: Language Models Know When to Recall](/202609/18/2609.20734v1-on-demand-attention-language-models-know-when-to-recall) （7.0/10）
4. [D-Quant: Driftable Entropy Coding for KV Cache Quantization](/202609/18/2609.19880v1-d-quant-driftable-entropy-coding-for-kv-cache-quantization) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
