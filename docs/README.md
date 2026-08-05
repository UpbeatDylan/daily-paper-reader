<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-05
- 运行时间：2026-08-05 20:35:29 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：3
- 速读区：4

### 今日简报（AI）
今日7篇论文聚焦KV Cache压缩与高效推理，精读2篇高分工作。重点看《AnchorKV》与《TaskPress》的压缩方案，分别从锚点残差和任务引导剪枝提升效率。可优先跟进KV量化与稀疏注意力方向，适合关注LLM推理优化者。
- 详情：[/202608/05/README](/202608/05/README)

### 精读区论文标签
1. [AnchorKV: Anchor-Residual KV Cache Compression](/202608/05/2608.02901v1-anchorkv-anchor-residual-kv-cache-compression)  
   标签：评分：8.0/10、query:pic
   evidence：基于锚点和残差的KV缓存压缩，不丢弃任何token，直接提升长上下文推理效率
2. [TaskPress: Query-Agnostic KV Cache Compression via Task-Guided Pruning](/202608/05/2608.03276v1-taskpress-query-agnostic-kv-cache-compression-via-task-guided-pruning)  
   标签：评分：8.0/10、query:pic
   evidence：通过任务引导构建可复用的KV缓存表示，面向不可见查询实现缓存复用
3. [Heterogeneous LLM Serving with General-Purpose Processing-Near-Memory for Retrieval-Based Sparse Attention](/202608/05/2608.03555v1-heterogeneous-llm-serving-with-general-purpose-processing-near-memory-for-retrieval-based-sparse-attention)  
   标签：评分：8.0/10、query:pic
   evidence：异构服务系统将KV缓存移入近内存处理单元，支持百万token上下文的检索式稀疏注意力

### 速读区论文标签
1. [LongCat Sparse Attention: Taming the Lightning via Streaming-aware Hierarchical Cross-Layer Indexing](/202608/05/2608.01662v2-longcat-sparse-attention-taming-the-lightning-via-streaming-aware-hierarchical-cross-layer-indexing)  
   标签：评分：7.0/10、query:pic
   evidence：面向长上下文稀疏注意力的软硬件协同设计，通过流感知和跨层索引降低KV索引开销
2. [Output-Aware Rotation for INT2 KV-Cache Quantization](/202608/05/2608.02691v1-output-aware-rotation-for-int2-kv-cache-quantization)  
   标签：评分：7.0/10、query:pic
   evidence：输出感知旋转的INT2 KV缓存量化，降低长上下文推理的内存与带宽瓶颈
3. [ATFlash: Per-RoPE-Wavelength Attention Windows for Compute/Memory-Efficient LLM Inference](/202608/05/2608.02947v1-atflash-per-rope-wavelength-attention-windows-for-computememory-efficient-llm-inference)  
   标签：评分：6.0/10、query:pic
   evidence：RoPE波长注意力窗口降低长序列推理的计算和内存开销
4. [PI-Mem: Pushing Long-Context Reasoning to 3.6M Tokens with Parallel-Iterative Memory](/202608/05/2608.03048v1-pi-mem-pushing-long-context-reasoning-to-36m-tokens-with-parallel-iterative-memory)  
   标签：评分：6.0/10、query:pic
   evidence：并行-迭代记忆降低超长上下文推理延迟


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
