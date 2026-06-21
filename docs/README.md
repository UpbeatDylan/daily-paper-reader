<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-21
- 运行时间：2026-06-21 21:08:13 UTC
- 运行状态：成功
- 本次总论文数：4
- 精读区：1
- 速读区：3

### 今日简报（AI）
今日日报重点推荐一篇关于MLA中QK归一化且无需完整键缓存的论文，同时关注MoE推理预取、尾部感知调度和模型并行重配置三项技术。  
高分精读论文提出QK归一化无需全键缓存，在推理效率上值得关注；三篇速读论文分别从预取、调度和重配置角度优化LLM推理。  
建议优先精读《QK-Normed MLA》以理解其核心创新，其余三篇可作为扩展了解当前LLM推理优化方向。
- 详情：[/202606/21/README](/202606/21/README)

### 精读区论文标签
1. [QK-Normed MLA: QK normalization without full key caching](/202606/21/2606.16310v1-qk-normed-mla-qk-normalization-without-full-key-caching)  
   标签：评分：9.0/10、query:pic
   evidence：MLA的KV缓存优化

### 速读区论文标签
1. [A Spatio-Temporal Expert Prefetching Framework for Efficient MoE-based LLM Inference](/202606/21/2606.15453v1-a-spatio-temporal-expert-prefetching-framework-for-efficient-moe-based-llm-inference)  
   标签：评分：6.0/10、query:pic
   evidence：MoE专家预取，减少专家加载开销
2. [Beyond Prediction: Tail-Aware Scheduling for LLM Inference](/202606/21/2606.18431v1-beyond-prediction-tail-aware-scheduling-for-llm-inference)  
   标签：评分：6.0/10、query:pic
   evidence：面向LLM推理的尾部感知调度，结合缓存感知的抢占，与长上下文推理加速相关
3. [ReMP: Low-Downtime Runtime Model-Parallelism Reconfiguration for LLM Serving](/202606/21/2606.18741v1-remp-low-downtime-runtime-model-parallelism-reconfiguration-for-llm-serving)  
   标签：评分：6.0/10、query:pic
   evidence：解决运行时重配置中的KV缓存丢失问题


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
