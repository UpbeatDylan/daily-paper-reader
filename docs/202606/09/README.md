# 日报 · 2026-06-09

- 生成时间：2026-06-09 21:54:46 UTC
- 当次推荐总数：10
- 精读区：5
- 速读区：5

## 今日简报（AI）
今日聚焦稀疏注意力与KV缓存共享，两篇9分论文提出高效长上下文服务新思路。  
SparseX针对交错式LLM服务实现段级缓存复用，FlashMemory-DeepSeek-V4用前瞻稀疏注意力加速超长上下文索引。  
后续可关注混合模型中稀疏预填与KV缓存在单次前向传递中的压缩方法（如Still），以及VLA统一推理运行时（vla.cpp）。

## 精读区
1. [SparseX: Efficient Segment-Level KV Cache Sharing for Interleaved LLM Serving](/202606/09/2606.01751v2-sparsex-efficient-segment-level-kv-cache-sharing-for-interleaved-llm-serving) （9.0/10）
2. [FlashMemory-DeepSeek-V4: Lightning Index Ultra-Long Context via Lookahead Sparse Attention](/202606/09/2606.09079v1-flashmemory-deepseek-v4-lightning-index-ultra-long-context-via-lookahead-sparse-attention) （9.0/10）
3. [From Rigid to Dynamic: Entropy-Guided Adaptive Inference for Long-Context LLMs](/202606/09/2606.09508v1-from-rigid-to-dynamic-entropy-guided-adaptive-inference-for-long-context-llms) （9.0/10）
4. [Semantic Cache Distillation: Efficient State Transfer via Reuse and Selective Patching](/202606/09/2606.07684v1-semantic-cache-distillation-efficient-state-transfer-via-reuse-and-selective-patching) （8.0/10）
5. [End-to-End Context Compression at Scale](/202606/09/2606.09659v1-end-to-end-context-compression-at-scale) （8.0/10）

## 速读区
1. [How Much Dense Attention is Necessary? Oracle-Guided Sparse Prefill for Full/GQA Layers in Hybrid Long-Context Models](/202606/09/2606.07703v1-how-much-dense-attention-is-necessary-oracle-guided-sparse-prefill-for-fullgqa-layers-in-hybrid-long-context-models) （7.0/10）
2. [Still: Amortized KV Cache Compaction in a Single Forward Pass](/202606/09/2606.07878v1-still-amortized-kv-cache-compaction-in-a-single-forward-pass) （7.0/10）
3. [vla.cpp: A Unified Inference Runtime for Vision-Language-Action Models](/202606/09/2606.08094v1-vlacpp-a-unified-inference-runtime-for-vision-language-action-models) （7.0/10）
4. [SpectrumKV: Per-Token Mixed-Precision KV Cache Transfer for Prefill-Decode Disaggregated LLM Serving](/202606/09/2606.08635v1-spectrumkv-per-token-mixed-precision-kv-cache-transfer-for-prefill-decode-disaggregated-llm-serving) （7.0/10）
5. [BUDDY: BUdget-Driven DYnamic Depth Routing for Adaptive Large Language Model Inference](/202606/09/2606.09514v1-buddy-budget-driven-dynamic-depth-routing-for-adaptive-large-language-model-inference) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
