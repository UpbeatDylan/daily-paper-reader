<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-15
- 运行时间：2026-09-15 22:40:58 UTC
- 运行状态：成功
- 本次总论文数：11
- 精读区：4
- 速读区：7

### 今日简报（AI）
今日精读4篇、速读7篇，重点聚焦大模型推理中的KV缓存与显存优化。最值得看的是《Prefix Sharing Is a Sorting Problem》（9.0/10）提出的前缀共享排序思路，以及《Grouped Value Attention》（8.0/10）用按需重建键值来省缓存。普通读者可先读这两篇精读，再按兴趣扫速读中的AgentKV与MoE负载均衡方向。
- 详情：[/202609/15/README](/202609/15/README)

### 精读区论文标签
1. [Prefix Sharing Is a Sorting Problem](/202609/15/2609.13692v1-prefix-sharing-is-a-sorting-problem)  
   标签：评分：9.0/10、query:pic
   evidence：通过选择分块顺序最大化LLM服务中的KV缓存前缀共享
2. [Grouped Value Attention: Efficient KV Caching via On-Demand Key Reconstruction](/202609/15/2609.13285v1-grouped-value-attention-efficient-kv-caching-via-on-demand-key-reconstruction)  
   标签：评分：8.0/10、query:pic
   evidence：按需重建内容键并单独缓存位置键，减少持久缓存标量
3. [Dynamic HBM Repartitioning for Multi-Turn MoE Serving](/202609/15/2609.13537v1-dynamic-hbm-repartitioning-for-multi-turn-moe-serving)  
   标签：评分：8.0/10、query:pic
   evidence：可复用KV前缀被驱逐，动态HBM再划分
4. [Shared KV Caching for Replicated 27B Inference: Correctness Failures and Performance Boundaries](/202609/15/2609.15021v1-shared-kv-caching-for-replicated-27b-inference-correctness-failures-and-performance-boundaries)  
   标签：评分：8.0/10、query:pic
   evidence：共享主机内存缓存避免重复预填充并涉及前缀局部性

### 速读区论文标签
1. [A Voice-Interactive Multi-Agent System for Smart Operating Rooms: Architecture Design and Key Technologies](/202609/15/2609.11231v2-a-voice-interactive-multi-agent-system-for-smart-operating-rooms-architecture-design-and-key-technologies)  
   标签：评分：7.0/10、query:pic
   evidence：KV缓存前缀预热与字节级最长公共前缀复用降低延迟
2. [Physically Partitioned KVCache Format for CPU--GPU Load Balancing in MoE Inference](/202609/15/2609.14507v1-physically-partitioned-kvcache-format-for-cpu--gpu-load-balancing-in-moe-inference)  
   标签：评分：7.0/10、query:pic
   evidence：面向长上下文MoE推理的物理驻留KVCache抽象
3. [AgentKV: Phase-Aware KV Eviction for Agentic LLMs](/202609/15/2609.14872v1-agentkv-phase-aware-kv-eviction-for-agentic-llms)  
   标签：评分：7.0/10、query:pic
   evidence：面向智能体LLM的阶段感知KV缓存驱逐，按各阶段查询缓冲打分
4. [Validating Hybrid-State Cache Recovery for GLM-5.3-Flash with vLLM and LMCache](/202609/15/2609.15030v1-validating-hybrid-state-cache-recovery-for-glm-53-flash-with-vllm-and-lmcache)  
   标签：评分：7.0/10、query:pic
   evidence：用vLLM与LMCache验证混合模型外部KV缓存严格前缀恢复的一致性
5. [Fixed State, Long Reach: What a Constant-Size Cache Buys Block Diffusion at Scale](/202609/15/2609.11998v1-fixed-state-long-reach-what-a-constant-size-cache-buys-block-diffusion-at-scale)  
   标签：评分：6.0/10、query:pic
   evidence：面向扩散语言模型的定长可复用状态块KV缓存
6. [Towards Evolving Context Parameterization for Large Language Models](/202609/15/2609.14168v1-towards-evolving-context-parameterization-for-large-language-models)  
   标签：评分：6.0/10、query:pic
   evidence：上下文参数化将上下文内化为可复用参数，避免重复处理
7. [Pull: Lazy Materialization of Working Memory for Stateful LLM Conversations](/202609/15/2609.14773v1-pull-lazy-materialization-of-working-memory-for-stateful-llm-conversations)  
   标签：评分：6.0/10、query:pic
   evidence：惰性物化减少长对话每次查询的上下文词元


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
