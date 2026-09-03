<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-03
- 运行时间：2026-09-03 23:08:48 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：3
- 速读区：4

### 今日简报（AI）
今日7篇论文聚焦LLM推理效率，精读2篇高分解码与预填充优化，速读3篇覆盖压缩与缓存策略。最值得关注的是利用注意力稀疏性实现“比Flash更快”的长上下文解码，及输入自适应稀疏预填充CRISP。建议普通读者优先关注这两项技术如何降低单GPU长文本推理成本。
- 详情：[/202609/03/README](/202609/03/README)

### 精读区论文标签
1. [Faster Than Flash: Exploiting Attention Sparsity for Efficient Long-Context Decoding](/202609/03/2609.00097v1-faster-than-flash-exploiting-attention-sparsity-for-efficient-long-context-decoding)  
   标签：评分：8.0/10、query:pic
   evidence：融合内核利用注意力稀疏性加速长上下文解码
2. [CRISP: Cliff-awaRe Input-adaptive Sparse Prefilling with Structural-Mass-Motivated Routing](/202609/03/2609.01925v1-crisp-cliff-aware-input-adaptive-sparse-prefilling-with-structural-mass-motivated-routing)  
   标签：评分：8.0/10、query:pic
   evidence：面向长上下文LLM二次复杂度预填充阶段的输入自适应稀疏注意力方法
3. [HeadWiseKV: Budgeted Per-Head Cache Residency for Hybrid Long-Context Language Models](/202609/03/2609.02029v1-headwisekv-budgeted-per-head-cache-residency-for-hybrid-long-context-language-models)  
   标签：评分：8.0/10、query:pic
   evidence：面向混合长上下文LLM的按头KV缓存驻留预算分配与内存压缩

### 速读区论文标签
1. [Budget-Aware Compression Pipeline for Single-GPU LLM Inference: Methods, Trade-offs, and Coupling Effects](/202609/03/2608.30076v1-budget-aware-compression-pipeline-for-single-gpu-llm-inference-methods-trade-offs-and-coupling-effects)  
   标签：评分：7.0/10、query:pic
   evidence：针对长上下文吞吐与KV缓存压缩的推理优化
2. [Multi-Turn LLM Conversations under the Least-Recently-Used Policy: Mean-Field Asymptotics and Hit Ratio Approximation](/202609/03/2609.02027v1-multi-turn-llm-conversations-under-the-least-recently-used-policy-mean-field-asymptotics-and-hit-ratio-approximation)  
   标签：评分：7.0/10、query:pic
   evidence：面向多轮LLM服务的LRU缓存淘汰命中率分析
3. [mzCache: On-Device LLM Memory Management under Multitasking](/202609/03/2609.01338v1-mzcache-on-device-llm-memory-management-under-multitasking)  
   标签：评分：6.0/10、query:pic
   evidence：移动端多任务内存压力下KV缓存被驱逐后的弹性恢复，避免重新计算KV缓存
4. [Architecting Conversational Data Systems for Stateless LLM APIs: The Hydration Proxy Pattern](/202609/03/2609.01834v1-architecting-conversational-data-systems-for-stateless-llm-apis-the-hydration-proxy-pattern)  
   标签：评分：6.0/10、query:pic
   evidence：通过Hydration代理模式稳定会话语境以改善无状态LLM API的KV缓存利用


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
