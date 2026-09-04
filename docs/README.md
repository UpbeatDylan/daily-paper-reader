<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-04
- 运行时间：2026-09-04 22:00:15 UTC
- 运行状态：成功
- 本次总论文数：5
- 精读区：2
- 速读区：3

### 今日简报（AI）
今日5篇论文聚焦LLM推理效率，核心方向为KV缓存压缩与复用。最值得精读《DoPR》的文档前缀重用重排序与《Random Attention》的随机淘汰机制。建议优先阅读这两篇高分论文，再按需扫读速读列表中硬件加速与缓存管理方案。
- 详情：[/202609/04/README](/202609/04/README)

### 精读区论文标签
1. [DoPR: Reusable Compressed Document Prefixes for Efficient LLM Reranking](/202609/04/2609.03311v1-dopr-reusable-compressed-document-prefixes-for-efficient-llm-reranking)  
   标签：评分：9.0/10、query:pic
   evidence：将文档离线预计算成压缩前缀并在查询间复用，减少LLM重排冗余计算，属前缀缓存技术。
2. [Random Attention: Rethinking KV Cache Eviction for Efficient Reasoning](/202609/04/2609.03430v1-random-attention-rethinking-kv-cache-eviction-for-efficient-reasoning)  
   标签：评分：8.0/10、query:pic
   evidence：用随机KV驱逐加速长思维链推理并提供更高吞吐

### 速读区论文标签
1. [Hardware Acceleration of Block-Diffusion LLM for Edge Devices](/202609/04/2609.01084v1-hardware-acceleration-of-block-diffusion-llm-for-edge-devices)  
   标签：评分：7.0/10、query:pic
   evidence：LLM推理中前缀KV与块级缓存重用
2. [GrowPage: On-Demand KV Budgeting for Efficient LLM Reasoning Serving](/202609/04/2609.03494v1-growpage-on-demand-kv-budgeting-for-efficient-llm-reasoning-serving)  
   标签：评分：7.0/10、query:pic
   evidence：在长输出推理中将KV容量作为运行时资源按需分配
3. [SGD-KV: Summarization Guided KV Cache Compression](/202609/04/2609.03235v1-sgd-kv-summarization-guided-kv-cache-compression)  
   标签：评分：6.0/10、query:pic
   evidence：通过总结诊断划分注意力头功能并进行KV缓存压缩，缓解长上下文推理内存瓶颈


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
