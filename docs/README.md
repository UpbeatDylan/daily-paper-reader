<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-18
- 运行时间：2026-08-18 20:59:08 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：3
- 速读区：4

### 今日简报（AI）
1) 今日7篇论文聚焦KV-Cache优化，精读3篇、速读4篇，核心围绕多智能体长共享前缀与推理模型缓存管理。
2) 最值得关注《GraniKV》以非对称粒度分页解决多智能体长前缀缓存瓶颈，以及《KV-Rescue》通过逐步交错挽救推理模型KV逐出损失，均获高分。
3) 建议普通读者优先精读上述两篇，速读可关注《Aborted but Not Forgotten》以理解KV缓存保留引发的回滚一致性问题。
- 详情：[/202608/18/README](/202608/18/README)

### 精读区论文标签
1. [GraniKV: Asymmetric Granularity KV-Cache Paging for Multi-Agent Systems with Long Shared Prefix](/202608/18/2608.15584v1-granikv-asymmetric-granularity-kv-cache-paging-for-multi-agent-systems-with-long-shared-prefix)  
   标签：评分：9.0/10、query:pic
   evidence：提出了面向长共享前缀的非对称粒度KV缓存分页层，直接提升前缀缓存效率。
2. [KV-Rescue: Recovering Reasoning Language Model KV Eviction Loss via Stepwise Interleaving](/202608/18/2608.15797v1-kv-rescue-recovering-reasoning-language-model-kv-eviction-loss-via-stepwise-interleaving)  
   标签：评分：8.0/10、query:pic
   evidence：通过小模型逐步交错来恢复KV缓存逐出丢失的信息
3. [KV-Pipe: On the Relation Between KV Sharing and Pipeline Parallel Efficiency in LLMs](/202608/18/2608.15943v1-kv-pipe-on-the-relation-between-kv-sharing-and-pipeline-parallel-efficiency-in-llms)  
   标签：评分：8.0/10、query:pic
   evidence：跨层KV共享与KV重用于大模型推理

### 速读区论文标签
1. [Aborted but Not Forgotten: KV-Cache Retention Breaks Rollback Consistency in Language Agents](/202608/18/2608.15939v1-aborted-but-not-forgotten-kv-cache-retention-breaks-rollback-consistency-in-language-agents)  
   标签：评分：7.0/10、query:pic
   evidence：KV缓存保留与回滚一致性问题，与KV缓存复用直接相关
2. [BAG: Budget-Aware Gating for Diffusion Caching](/202608/18/2608.09231v1-bag-budget-aware-gating-for-diffusion-caching)  
   标签：评分：6.0/10、query:pic
   evidence：预算感知门控的缓存策略可迁移至KV缓存复用
3. [SEER: Long-Context Reasoning via Selective Visual-Text Compression](/202608/18/2608.15962v1-seer-long-context-reasoning-via-selective-visual-text-compression)  
   标签：评分：6.0/10、query:pic
   evidence：通过选择性视觉-文本压缩加速长上下文推理
4. [Proteus: Incremental Memory Activation for Long-Context Sequence Modeling](/202608/18/2608.16844v1-proteus-incremental-memory-activation-for-long-context-sequence-modeling)  
   标签：评分：6.0/10、query:pic
   evidence：增量记忆激活以降低长上下文注意力成本


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
