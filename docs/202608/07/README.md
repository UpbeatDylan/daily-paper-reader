# 日报 · 2026-08-07

- 生成时间：2026-08-07 20:54:50 UTC
- 当次推荐总数：7
- 精读区：1
- 速读区：6

## 今日简报（AI）
今日聚焦KV缓存压缩：7篇推荐中，1篇精读（8.0分）聚焦向量量化与注意力保持变换，3篇速读覆盖INT2旋转量化、无训练哈希注意力等方向。  
最值得关注的是“按查询重要性分配量化位”的注意力保持方案，以及输出感知旋转在极低比特量化中的潜力。  
若想快速上手，可从INT2量化与熵驱动淘汰技术入手，平衡长上下文解码中的精度与效率。

## 精读区
1. [Spend Bits Where Queries Look: KV Cache Vector Quantization with Attention-Preserving Transforms](/202608/07/2608.04074v1-spend-bits-where-queries-look-kv-cache-vector-quantization-with-attention-preserving-transforms) （8.0/10）

## 速读区
1. [Output-Aware Rotation for INT2 KV-Cache Quantization](/202608/07/2608.02691v2-output-aware-rotation-for-int2-kv-cache-quantization) （7.0/10）
2. [Training-Free Hashing-Based Attention via Binary Principal Components](/202608/07/2608.04405v1-training-free-hashing-based-attention-via-binary-principal-components) （7.0/10）
3. [QEvict: Recoverable Quantized KV Eviction for Attention-Drift-Robust Long-Context Decoding](/202608/07/2608.05326v1-qevict-recoverable-quantized-kv-eviction-for-attention-drift-robust-long-context-decoding) （7.0/10）
4. [Unified Lookup-Table Inference with Signed-Digit K/V Caches for Ternary LLMs](/202608/07/2608.03229v1-unified-lookup-table-inference-with-signed-digit-kv-caches-for-ternary-llms) （6.0/10）
5. [Fewer Tokens, Smaller Cache: Reward-Coordinated Efficient Reasoning](/202608/07/2608.04771v1-fewer-tokens-smaller-cache-reward-coordinated-efficient-reasoning) （6.0/10）
6. [RAC: Reference-Aware Activation Compression for Communication-Efficient Split LLM Inference](/202608/07/2608.04991v1-rac-reference-aware-activation-compression-for-communication-efficient-split-llm-inference) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
