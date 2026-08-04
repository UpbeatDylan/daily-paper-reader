<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-06 ~ 2026-08-04
- 运行时间：2026-08-04 10:53:53 UTC
- 运行状态：成功
- 本次总论文数：11
- 精读区：6
- 速读区：5

### 今日简报（AI）
今日精读聚焦LLM前缀缓存优化，结合速读覆盖KV压缩与多租户管理，共11篇论文。  
最值得关注两篇满分精读：无线边缘的前缀缓存建模，以及异构成本下前缀KV放置的优化方案。  
建议普通读者优先了解前缀缓存如何降低推理延迟与成本，再跟进KV压缩实践。
- 详情：[/20260706-20260804/README](/20260706-20260804/README)

### 精读区论文标签
1. [Spatial Prefix Caching for Wireless Edge LLM Inference: A Stochastic-Geometry and Queueing Framework](/20260706-20260804/2608.01126v1-spatial-prefix-caching-for-wireless-edge-llm-inference-a-stochastic-geometry-and-queueing-framework)  
   标签：评分：9.0/10、query:pic
   evidence：直接研究LLM推理中的前缀缓存，通过复用共享提示前缀的KV状态降低首次响应时间
2. [PrefixPlace: Provable Prefix Key-Value Placement for Large Language Model Serving under Heterogeneous Compute and Transfer Costs](/20260706-20260804/2608.01655v1-prefixplace-provable-prefix-key-value-placement-for-large-language-model-serving-under-heterogeneous-compute-and-transfer-costs)  
   标签：评分：9.0/10、query:pic
   evidence：面向异构计算与传输成本的前缀KV可证明放置，优化复用
3. [HyMCache: A KV Cache Framework for Multi-Turn LLM Serving with CXL-Hybrid Memory](/20260706-20260804/2607.18141v2-hymcache-a-kv-cache-framework-for-multi-turn-llm-serving-with-cxl-hybrid-memory)  
   标签：评分：8.0/10、query:pic
   evidence：利用CXL混合内存支持多轮上下文KV缓存复用的框架
4. [S$^4$R: Selective Sampling, Subspaces, and Sparse Reconstruction for Compressed Long-Context KV Caching](/20260706-20260804/2608.00528v1-s4r-selective-sampling-subspaces-and-sparse-reconstruction-for-compressed-long-context-kv-caching)  
   标签：评分：8.0/10、query:pic
   evidence：利用低秩子空间与稀疏重建进行长上下文KV缓存压缩
5. [RestoreKV: Recovering Full-Cache Behavior Under Aggressive Query-Agnostic KV Cache Eviction](/20260706-20260804/2608.01247v1-restorekv-recovering-full-cache-behavior-under-aggressive-query-agnostic-kv-cache-eviction)  
   标签：评分：8.0/10、query:pic
   evidence：跨任意查询复用查询无关KV缓存并学习恢复信息
6. [An Internet for the KV Cache: Rethinking Classical Infrastructure Boundaries in the LLM Inference Age](/20260706-20260804/2608.01526v1-an-internet-for-the-kv-cache-rethinking-classical-infrastructure-boundaries-in-the-llm-inference-age)  
   标签：评分：8.0/10、query:pic
   evidence：主张跨基础设施存储和复用KV缓存，直接契合LLM推理中的KV缓存复用

### 速读区论文标签
1. [Bole: Efficient Tree Speculation for Hybrid-Attention Language Models](/20260706-20260804/2608.01651v1-bole-efficient-tree-speculation-for-hybrid-attention-language-models)  
   标签：评分：8.0/10、query:pic
   evidence：面向混合注意力大模型的树推测解码，加速长上下文推理
2. [Preserving Admission Responsibility in Multi-Tenant Large Language Model Prefix Caches](/20260706-20260804/2608.01657v1-preserving-admission-responsibility-in-multi-tenant-large-language-model-prefix-caches)  
   标签：评分：8.0/10、query:pic
   evidence：多租户LLM服务中的前缀缓存准入控制与KV块复用
3. [Practical Online KV Cache Compaction for LLM Agents: An Empirical Study](/20260706-20260804/2608.00902v1-practical-online-kv-cache-compaction-for-llm-agents-an-empirical-study)  
   标签：评分：7.0/10、query:pic
   evidence：通过在线KV缓存压缩降低长轨迹LLM代理推理开销，属于长上下文推理加速方法
4. [SeDeM: Selective Decompression of Hidden-State Memories for Long-Context Question Answering](/20260706-20260804/2608.00311v1-sedem-selective-decompression-of-hidden-state-memories-for-long-context-question-answering)  
   标签：评分：6.0/10、query:pic
   evidence：选择性解压隐藏状态记忆以降低长上下文推理成本
5. [Structured Memory for Edge Language Models: Persistent Context and Corpus Retrieval via O(1) SSM State Injection](/20260706-20260804/2608.02560v1-structured-memory-for-edge-language-models-persistent-context-and-corpus-retrieval-via-o1-ssm-state-injection)  
   标签：评分：6.0/10、query:pic
   evidence：利用与位置无关的SSM状态注入实现恒定时间上下文复用，类似面向长上下文的位置无关缓存


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
