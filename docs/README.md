<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-09
- 运行时间：2026-06-09 21:54:46 UTC
- 运行状态：成功
- 本次总论文数：10
- 精读区：5
- 速读区：5

### 今日简报（AI）
今日重点报道LLM推理优化中稀疏注意力与KV缓存技术突破，以及多模态推理框架新进展。精读推荐《SparseX》的交错服务段级缓存共享和《FlashMemory-DeepSeek-V4》的闪电索引超长上下文稀疏注意力，均获9.0高分。建议关注稀疏预填充在混合长上下文模型中的进一步探索，如《How Much Dense Attention is Necessary?》提出的Oracle引导方法。
- 详情：[/202606/09/README](/202606/09/README)

### 精读区论文标签
1. [SparseX: Efficient Segment-Level KV Cache Sharing for Interleaved LLM Serving](/202606/09/2606.01751v2-sparsex-efficient-segment-level-kv-cache-sharing-for-interleaved-llm-serving)  
   标签：评分：9.0/10、query:pic
   evidence：段级KV缓存共享处理交错服务中的非前缀重复内容
2. [FlashMemory-DeepSeek-V4: Lightning Index Ultra-Long Context via Lookahead Sparse Attention](/202606/09/2606.09079v1-flashmemory-deepseek-v4-lightning-index-ultra-long-context-via-lookahead-sparse-attention)  
   标签：评分：9.0/10、query:pic
   evidence：前瞻稀疏注意力通过选择性KV缓存实现超长上下文
3. [From Rigid to Dynamic: Entropy-Guided Adaptive Inference for Long-Context LLMs](/202606/09/2606.09508v1-from-rigid-to-dynamic-entropy-guided-adaptive-inference-for-long-context-llms)  
   标签：评分：9.0/10、query:pic
   evidence：熵引导自适应稀疏注意力和KV缓存压缩用于长上下文LLM
4. [Semantic Cache Distillation: Efficient State Transfer via Reuse and Selective Patching](/202606/09/2606.07684v1-semantic-cache-distillation-efficient-state-transfer-via-reuse-and-selective-patching)  
   标签：评分：8.0/10、query:pic
   evidence：通过重用和选择性补丁实现KV缓存蒸馏以高效传输状态
5. [End-to-End Context Compression at Scale](/202606/09/2606.09659v1-end-to-end-context-compression-at-scale)  
   标签：评分：8.0/10、query:pic
   evidence：针对长上下文推理的上下文压缩

### 速读区论文标签
1. [How Much Dense Attention is Necessary? Oracle-Guided Sparse Prefill for Full/GQA Layers in Hybrid Long-Context Models](/202606/09/2606.07703v1-how-much-dense-attention-is-necessary-oracle-guided-sparse-prefill-for-fullgqa-layers-in-hybrid-long-context-models)  
   标签：评分：7.0/10、query:pic
   evidence：基于oracle的稀疏预填充，降低长上下文预填充开销
2. [Still: Amortized KV Cache Compaction in a Single Forward Pass](/202606/09/2606.07878v1-still-amortized-kv-cache-compaction-in-a-single-forward-pass)  
   标签：评分：7.0/10、query:pic
   evidence：单次前向的KV缓存压缩用于长上下文部署
3. [vla.cpp: A Unified Inference Runtime for Vision-Language-Action Models](/202606/09/2606.08094v1-vlacpp-a-unified-inference-runtime-for-vision-language-action-models)  
   标签：评分：7.0/10、query:pic
   evidence：缓存视觉-语言前缀用于VLA推理，类似前缀缓存
4. [SpectrumKV: Per-Token Mixed-Precision KV Cache Transfer for Prefill-Decode Disaggregated LLM Serving](/202606/09/2606.08635v1-spectrumkv-per-token-mixed-precision-kv-cache-transfer-for-prefill-decode-disaggregated-llm-serving)  
   标签：评分：7.0/10、query:pic
   evidence：面向分离式服务的混合精度KV缓存传输
5. [BUDDY: BUdget-Driven DYnamic Depth Routing for Adaptive Large Language Model Inference](/202606/09/2606.09514v1-buddy-budget-driven-dynamic-depth-routing-for-adaptive-large-language-model-inference)  
   标签：评分：6.0/10、query:pic
   evidence：动态深度路由中重用第一层KV缓存作为全局上下文


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
