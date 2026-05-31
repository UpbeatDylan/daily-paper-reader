<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-31
- 运行时间：2026-05-31 20:04:07 UTC
- 运行状态：成功
- 本次总论文数：20
- 精读区：9
- 速读区：11

### 今日简报（AI）
今日核心聚焦KV缓存管理优化，精读9篇涵盖两篇9分论文，分别提出预留KV声明机制与混合精度置信度感知淘汰策略。  
值得关注的方向：KV缓存压缩与多模态智能体技能蒸馏，CONF-KV与PANDO分别代表两项前沿探索。  
建议重点关注KV缓存调优技术（如混合精度、离线回放）对长上下文推理性能的直接影响。
- 详情：[/202605/31/README](/202605/31/README)

### 精读区论文标签
1. [Resident KV Claims: A Conformance Contract for Future Reuse under Active KV Pressure](/202605/31/2605.24259v1-resident-kv-claims-a-conformance-contract-for-future-reuse-under-active-kv-pressure)  
   标签：评分：9.0/10、query:pic
   evidence：定义内存压力下的未来KV缓存复用契约
2. [CONF-KV: Confidence-Aware KV Cache Eviction with Mixed-Precision Storage for Long-Horizon LLM](/202605/31/2605.24786v1-conf-kv-confidence-aware-kv-cache-eviction-with-mixed-precision-storage-for-long-horizon-llm)  
   标签：评分：9.0/10、query:pic
   evidence：面向长视野LLM的置信度感知KV缓存驱逐
3. [MVR-cache: Optimizing Semantic Caching via Multi-Vector Retrieval and Learned Prompt Segmentation](/202605/31/2605.24914v1-mvr-cache-optimizing-semantic-caching-via-multi-vector-retrieval-and-learned-prompt-segmentation)  
   标签：评分：9.0/10、query:pic
   evidence：使用多向量检索和提示分割优化语义缓存以降低LLM延迟
4. [IndexMem: Learned KV-Cache Eviction with Latent Memory for Long-Context LLM Inference](/202605/31/2605.25475v1-indexmem-learned-kv-cache-eviction-with-latent-memory-for-long-context-llm-inference)  
   标签：评分：9.0/10、query:pic
   evidence：学习型KV缓存驱逐与潜在记忆用于长上下文LLM推理
5. [Stateful Inference for Low-Latency Multi-Agent Tool Calling](/202605/31/2605.26289v1-stateful-inference-for-low-latency-multi-agent-tool-calling)  
   标签：评分：9.0/10、query:pic
   evidence：有状态推理架构通过持久化KV缓存和基数前缀缓存实现跨轮KV缓存复用
6. [NestedKV: Nested Memory Routing for Long-Context KV Cache Compression](/202605/31/2605.26678v1-nestedkv-nested-memory-routing-for-long-context-kv-cache-compression)  
   标签：评分：9.0/10、query:pic
   evidence：长上下文KV缓存压缩的嵌套评分方法
7. [UNIQUE: Universal Top-k Sparse Attention for Training-free Inference and Sparsity-aware Training](/202605/31/2605.27740v1-unique-universal-top-k-sparse-attention-for-training-free-inference-and-sparsity-aware-training)  
   标签：评分：9.0/10、query:pic
   evidence：通用top-k稀疏注意力用于KV缓存缩减
8. [RTP-LLM: High-Performance Alibaba LLM Inference Engine](/202605/31/2605.29639v1-rtp-llm-high-performance-alibaba-llm-inference-engine)  
   标签：评分：9.0/10、query:pic
   evidence：分层多级KV缓存管理实现高效缓存复用
9. [Moment-KV: Momentum-Based Decode-Time KV Cache Compression for Long Generation](/202605/31/2605.29873v1-moment-kv-momentum-based-decode-time-kv-cache-compression-for-long-generation)  
   标签：评分：9.0/10、query:pic
   evidence：基于动量的解码时KV缓存压缩用于长生成任务

### 速读区论文标签
1. [Interdomain Attention: Beyond Token-Level Key-Value Memory](/202605/31/2605.24330v1-interdomain-attention-beyond-token-level-key-value-memory)  
   标签：评分：8.0/10、query:pic
   evidence：提出跨域注意力，将SSM集成到注意力中，实现固定大小状态上的查询条件注意力，直接涉及KV缓存复用与效率
2. [PANDO: Efficient Multimodal AI Agents via Online Skill Distillation](/202605/31/2605.24785v2-pando-efficient-multimodal-ai-agents-via-online-skill-distillation)  
   标签：评分：8.0/10、query:pic
   evidence：识别出提示缓存利用率低的问题，并提出缓存感知提示
3. [Do Language Models Need Sleep? Offline Recurrence for Improved Online Inference](/202605/31/2605.26099v2-do-language-models-need-sleep-offline-recurrence-for-improved-online-inference)  
   标签：评分：8.0/10、query:pic
   evidence：离线递归合并上下文并清空KV缓存
4. [Augmenting Attention with Exponentially Decaying Memory Improves Query-Aware KV Sparsity](/202605/31/2605.28640v1-augmenting-attention-with-exponentially-decaying-memory-improves-query-aware-kv-sparsity)  
   标签：评分：8.0/10、query:pic
   evidence：研究指数衰减记忆（RAT+）改善查询感知KV稀疏性，直接推进长上下文LLM的KV缓存复用
5. [WhenLoss: Diagnosing Write and Retrieval Bottlenecks in Long-Context Memory Systems](/202605/31/2605.24579v1-whenloss-diagnosing-write-and-retrieval-bottlenecks-in-long-context-memory-systems)  
   标签：评分：7.0/10、query:pic
   evidence：诊断长上下文记忆系统中的写入与检索瓶颈，提出写时压缩的EPC方法，与上下文缓存相关
6. [Polynomial Context-Truncation Sensitivity in Autoregressive Language Models: Sequential Wyner-Ziv Bounds for KV Cache Compression](/202605/31/2605.25085v1-polynomial-context-truncation-sensitivity-in-autoregressive-language-models-sequential-wyner-ziv-bounds-for-kv-cache-compression)  
   标签：评分：7.0/10、query:pic
   evidence：研究在线KV缓存压缩的率失真极限
7. [Latent Recurrent Transformer: Architecture Exploration, Training Strategies, and Scaling Behavior](/202605/31/2605.26797v1-latent-recurrent-transformer-architecture-exploration-training-strategies-and-scaling-behavior)  
   标签：评分：7.0/10、query:pic
   evidence：重用前一个token的隐藏状态作为循环记忆，保留KV缓存接口
8. [Hurwitz Quaternion Multiplicative Quantization for KV Cache Compression](/202605/31/2605.27646v1-hurwitz-quaternion-multiplicative-quantization-for-kv-cache-compression)  
   标签：评分：7.0/10、query:pic
   evidence：KV缓存压缩以实现更高效的复用
9. [ReMoE: Boosting Expert Reuse through Router Fine-Tuning in Memory-Constrained MoE LLM Inference](/202605/31/2605.27081v1-remoe-boosting-expert-reuse-through-router-fine-tuning-in-memory-constrained-moe-llm-inference)  
   标签：评分：6.0/10、query:pic
   evidence：通过路由微调提高MoE中的专家复用，减少从外部存储加载，类似KV缓存复用策略
10. [Context Distillation as Latent Memory Management](/202605/31/2605.28889v1-context-distillation-as-latent-memory-management)  
   标签：评分：6.0/10、query:pic
   evidence：引入缓存共享减少推理开销
11. [Knowledge Offloading: Decomposing LLMs into Sparse Backbones and Memory Modules](/202605/31/2605.29075v1-knowledge-offloading-decomposing-llms-into-sparse-backbones-and-memory-modules)  
   标签：评分：6.0/10、query:pic
   evidence：将LLM分解为共享骨干和包含学习型KV缓存的外部记忆


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
