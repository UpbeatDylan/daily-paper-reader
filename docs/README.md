<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-10-02
- 运行时间：2026-10-02 22:42:53 UTC
- 运行状态：成功
- 本次总论文数：16
- 精读区：6
- 速读区：10

### 今日简报（AI）
2026-10-02 共筛出 16 篇 LLM 推理优化论文，精读 6 篇、速读 10 篇，主题几乎全部围绕 KV Cache 复用、压缩与调度。

最值得看的是精读满分的《ATTUNER：通过 Query 侧适配实现免重算的 KV Cache 复用》，以及 9 分的《ARC-KV：为重建式 KV Cache 压缩分摊锚点搜索》，速读中《Preserving Provenance in Shared KV Caches》与《PatchKV：KV Cache 的权重空间补偿》也值得跟进。

普通读者可先读 ATTUNER 了解"不重算也能复用缓存"的思路，再顺着 PatchKV、SparseEngine 看工程侧如何落地。
- 详情：[/202610/02/README](/202610/02/README)

### 精读区论文标签
1. [ATTUNER: Recomputation-Free KV Cache Reuse via Query-Side Adaptation](/202610/02/2609.36722v1-attuner-recomputation-free-kv-cache-reuse-via-query-side-adaptation)  
   标签：评分：10.0/10、query:pic
   evidence：位置无关缓存PIC在任意位置复用KV状态且免重算
2. [ARC-KV: Amortizing Anchor Search for Reconstruction-Based KV Cache Compaction](/202610/02/2609.36835v1-arc-kv-amortizing-anchor-search-for-reconstruction-based-kv-cache-compaction)  
   标签：评分：9.0/10、query:pic
   evidence：面向长可复用前缀的基于重构的KV缓存压缩
3. [Capture the lifecycle: KV Cache management in ReAct Agents with KVTether](/202610/02/2609.39819v1-capture-the-lifecycle-kv-cache-management-in-react-agents-with-kvtether)  
   标签：评分：9.0/10、query:pic
   evidence：ReAct智能体中的生命周期感知KV缓存复用
4. [When Fancy Eviction Fails: Rethinking Cache Replacement For LLM Prefix Reuse](/202610/02/2609.28870v2-when-fancy-eviction-fails-rethinking-cache-replacement-for-llm-prefix-reuse)  
   标签：评分：8.0/10、query:pic
   evidence：面向大模型前缀复用的前缀缓存与替换
5. [Prefill-Free Cross-Family KV Cache Transfer for Heterogeneous Multi-Agent LLMs](/202610/02/2609.32259v2-prefill-free-cross-family-kv-cache-transfer-for-heterogeneous-multi-agent-llms)  
   标签：评分：8.0/10、query:pic
   evidence：复用发送方KV缓存避免跨模型重复预填充
6. [AVSG: Accelerated Vectorized Sparse Gather for Efficient KV Cache Offload in Sparse-Attention LLM Serving](/202610/02/2609.37538v1-avsg-accelerated-vectorized-sparse-gather-for-efficient-kv-cache-offload-in-sparse-attention-llm-serving)  
   标签：评分：8.0/10、query:pic
   evidence：稀疏注意力服务中跨解码步复用选中的KV条目

### 速读区论文标签
1. [Preserving Provenance in Shared KV Caches for LLM Serving](/202610/02/2609.38706v1-preserving-provenance-in-shared-kv-caches-for-llm-serving)  
   标签：评分：8.0/10、query:pic
   evidence：共享KV缓存层复用与前缀缓存来源问题
2. [SparseEngine: Sparse-First Inference Engine](/202610/02/2609.39068v1-sparseengine-sparse-first-inference-engine)  
   标签：评分：8.0/10、query:pic
   evidence：推理引擎中的前缀缓存与KV缓存状态管理
3. [PatchKV: Weight-Space Compensation of KV Cache](/202610/02/2609.39329v1-patchkv-weight-space-compensation-of-kv-cache)  
   标签：评分：8.0/10、query:pic
   evidence：补偿KV缓存压缩以支持长上下文推理
4. [EchoPress: Query-Agnostic KV Cache Pruning via Virtual Context Reconstruction](/202610/02/2610.00412v1-echopress-query-agnostic-kv-cache-pruning-via-virtual-context-reconstruction)  
   标签：评分：8.0/10、query:pic
   evidence：面向长上下文推理的无训练KV缓存剪枝
5. [Periodic Weak Spots: Phase Sensitivity from Chunked KV-Cache Compression](/202610/02/2609.36322v1-periodic-weak-spots-phase-sensitivity-from-chunked-kv-cache-compression)  
   标签：评分：7.0/10、query:pic
   evidence：面向长上下文推理的分块KV缓存压缩
6. [Efficient Agentic LLM Serving over SSD-based Sparse KV Storage](/202610/02/2609.36938v1-efficient-agentic-llm-serving-over-ssd-based-sparse-kv-storage)  
   标签：评分：7.0/10、query:pic
   evidence：长会话中保留历史KV缓存以避免重算
7. [CADOC: Cache-Aware Dynamic Object Context for Long-Horizon Agents](/202610/02/2609.37012v1-cadoc-cache-aware-dynamic-object-context-for-long-horizon-agents)  
   标签：评分：7.0/10、query:pic
   evidence：保持前缀缓存复用的缓存感知上下文编辑
8. [KV-Kaizen: Learning Context-Adaptive Cache Compression Choices](/202610/02/2609.37988v2-kv-kaizen-learning-context-adaptive-cache-compression-choices)  
   标签：评分：7.0/10、query:pic
   evidence：面向长上下文LLM推理的上下文自适应KV缓存压缩
9. [Can Computation from Earlier Problems Help LLMs Solve New Ones?](/202610/02/2609.39394v1-can-computation-from-earlier-problems-help-llms-solve-new-ones)  
   标签：评分：6.0/10、query:pic
   evidence：STAIR通过固定缓存库复用先前查询的键值
10. [Persistent Context Graphs for Efficient Memory Compaction in LLM Agents](/202610/02/2609.40118v1-persistent-context-graphs-for-efficient-memory-compaction-in-llm-agents)  
   标签：评分：6.0/10、query:pic
   evidence：面向长智能体上下文的内存压缩与KV缓存复用


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
