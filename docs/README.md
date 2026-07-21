<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-21
- 运行时间：2026-07-21 21:13:34 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：5
- 速读区：2

### 今日简报（AI）
今日日报精读两篇高分论文，聚焦KV缓存管理与压缩复用，速读两篇扩散语言模型相关研究。
推荐关注《Robust KV Cache Management》与《C$^2$KV: Compressed and Composable KV Cache Reuse》，均获9.0高分，分别解决输出长度不确定性下的缓存管理和高效缓存复用。
下一步可深入研读这两篇精读论文，并留意扩散语言模型的精确缓存与自校正解码方向。
- 详情：[/202607/21/README](/202607/21/README)

### 精读区论文标签
1. [Robust KV Cache Management for LLM Serving under Output Token Length Uncertainty](/202607/21/2607.16892v1-robust-kv-cache-management-for-llm-serving-under-output-token-length-uncertainty)  
   标签：评分：9.0/10、query:pic
   evidence：鲁棒KV缓存管理，在输出长度不确定下联合优化预留和前缀缓存
2. [C$^2$KV: Compressed and Composable KV Cache Reuse for Efficient LLM Inference](/202607/21/2607.17715v1-c2kv-compressed-and-composable-kv-cache-reuse-for-efficient-llm-inference)  
   标签：评分：9.0/10、query:pic
   evidence：提出C2KV框架实现非前缀KV缓存重用与压缩
3. [HyMCache: A KV Cache Framework for Multi-Turn LLM Serving with CXL-Hybrid Memory](/202607/21/2607.18141v1-hymcache-a-kv-cache-framework-for-multi-turn-llm-serving-with-cxl-hybrid-memory)  
   标签：评分：9.0/10、query:pic
   evidence：面向多轮LLM服务的KV缓存框架，采用CXL混合内存
4. [Regularize or Localize: When Training-Time KV-Cache Geometry Pays Under Quantization](/202607/21/2607.17019v1-regularize-or-localize-when-training-time-kv-cache-geometry-pays-under-quantization)  
   标签：评分：8.0/10、query:pic
   evidence：通过正则化改变KV缓存几何结构以利于量化
5. [SALT: Salience-Aware Lexical Trie for Long-Context Compression](/202607/21/2607.17486v1-salt-salience-aware-lexical-trie-for-long-context-compression)  
   标签：评分：8.0/10、query:pic
   evidence：通过显著感知词汇树实现长上下文压缩

### 速读区论文标签
1. [LaCache: Exact Caching and Precision-Adaptive Inference for Diffusion Large Language Models](/202607/21/2607.16339v1-lacache-exact-caching-and-precision-adaptive-inference-for-diffusion-large-language-models)  
   标签：评分：6.0/10、query:pic
   evidence：缓存中间状态避免重计算
2. [FlowBlock: Wavefront-Parallel Decoding for Self-Correcting Diffusion Language Models](/202607/21/2607.17652v1-flowblock-wavefront-parallel-decoding-for-self-correcting-diffusion-language-models)  
   标签：评分：6.0/10、query:pic
   evidence：在扩散LLM中跨块重用KV缓存


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
