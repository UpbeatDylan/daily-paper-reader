<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-04
- 运行时间：2026-08-04 21:34:44 UTC
- 运行状态：成功
- 本次总论文数：6
- 精读区：2
- 速读区：4

### 今日简报（AI）
今日共读6篇论文，精读2篇、速读4篇，覆盖光器件、长时LLM推理、稀疏注意力与缓存优化。  
最值得精读的是《Opt.Gear Technical Report》与《LiveMem》，分数均为8.0/10，前者聚焦光器件技术，后者解决长运行LLM的内存状态连续性。  
若想跟进效率方向，可速读《LongCat Sparse Attention》与《Messages, Not Tokens》，分别涉及跨层稀疏索引和VLM压缩。
- 详情：[/202608/04/README](/202608/04/README)

### 精读区论文标签
1. [Opt.Gear Technical Report](/202608/04/2608.01034v1-optgear-technical-report)  
   标签：评分：8.0/10、query:pic
   evidence：提出结合卷积KV门控混合器与局部-全局注意力的混合架构，减少长上下文KV缓存内存并加速推理
2. [LiveMem: Maintaining Memory State Continuity in Long-Running LLM Inference](/202608/04/2608.02515v1-livemem-maintaining-memory-state-continuity-in-long-running-llm-inference)  
   标签：评分：8.0/10、query:pic
   evidence：有界KV窗口下的持久记忆状态，支撑长期推理

### 速读区论文标签
1. [LongCat Sparse Attention: Taming the Lightning via Streaming-aware Hierarchical Cross-Layer Indexing](/202608/04/2608.01662v1-longcat-sparse-attention-taming-the-lightning-via-streaming-aware-hierarchical-cross-layer-indexing)  
   标签：评分：7.0/10、query:pic
   evidence：硬件对齐索引优化 KV 访存模式，降低稀疏注意力开销
2. [Messages, Not Tokens: Grounded Coresets for Faithful VLM Compression](/202608/04/2608.02134v1-messages-not-tokens-grounded-coresets-for-faithful-vlm-compression)  
   标签：评分：7.0/10、query:pic
   evidence：基于核集的VLM提示KV缓存压缩，利用集体注意力消息
3. [LaCache: Robust Semantic Caching for LLM Serving](/202608/04/2608.01718v1-lacache-robust-semantic-caching-for-llm-serving)  
   标签：评分：6.0/10、query:pic
   evidence：面向 LLM 服务延迟降低的鲁棒语义缓存方案
4. [DART: Decoded Attention over Recurrent States for Efficient Long-Context Sequence Modeling](/202608/04/2608.02032v1-dart-decoded-attention-over-recurrent-states-for-efficient-long-context-sequence-modeling)  
   标签：评分：6.0/10、query:pic
   evidence：提出利用循环状态作为压缩KV缓存的高效长上下文建模架构，与加速方法相关。


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
