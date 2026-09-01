<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-01
- 运行时间：2026-09-01 22:59:30 UTC
- 运行状态：成功
- 本次总论文数：12
- 精读区：7
- 速读区：5

### 今日简报（AI）
今日聚焦KV Cache优化，精读7篇、速读5篇，共12篇长上下文推理相关论文。最值得关注WnW与TwinKV，前者提出增减式KV管理，后者用成对冗余提升驱逐效率；速读中SemKV与RouteSparse也值得参考。建议读者优先精读WnW，并留意混合精度量化与输入条件路由的后续应用。
- 详情：[/202609/01/README](/202609/01/README)

### 精读区论文标签
1. [WnW: Waxing-and-Waning KV Cache for Long-Form Speech LLMs](/202609/01/2608.22704v2-wnw-waxing-and-waning-kv-cache-for-long-form-speech-llms)  
   标签：评分：9.0/10、query:pic
   evidence：面向长语音大语言模型解码的增消式KV缓存策略
2. [TwinKV: A Composable Repair Pass for KV Cache Eviction via Pairwise Key Redundancy](/202609/01/2608.27128v2-twinkv-a-composable-repair-pass-for-kv-cache-eviction-via-pairwise-key-redundancy)  
   标签：评分：9.0/10、query:pic
   evidence：针对长上下文推理内存瓶颈的KV缓存驱逐方法
3. [Strong Drafts Need Compact Memories: Long-Context Speculative Decoding with Compressed KV Cache](/202609/01/2608.30252v1-strong-drafts-need-compact-memories-long-context-speculative-decoding-with-compressed-kv-cache)  
   标签：评分：9.0/10、query:pic
   evidence：长上下文推测解码结合压缩KV缓存
4. [CateKV: On Sequential Consistency for Long-Context LLM Inference Acceleration](/202609/01/2608.30295v1-catekv-on-sequential-consistency-for-long-context-llm-inference-acceleration)  
   标签：评分：9.0/10、query:pic
   evidence：面向长上下文推理的混合KV缓存精简，直接针对长上下文缓存加速
5. [Tail-Replay: Escaping the Curse of Linear Attention in Prefix Caching for Hybrid LLMs](/202609/01/2608.30310v1-tail-replay-escaping-the-curse-of-linear-attention-in-prefix-caching-for-hybrid-llms)  
   标签：评分：9.0/10、query:pic
   evidence：支持混合大语言模型无约束token级前缀复用的一种前缀缓存机制
6. [DASC: Decay-Aware State Compression for Hybrid Linear-Attention Serving](/202609/01/2608.30386v1-dasc-decay-aware-state-compression-for-hybrid-linear-attention-serving)  
   标签：评分：9.0/10、query:pic
   evidence：DASC针对混合线性注意力服务中的持久状态进行压缩，解决前缀复用与缓存驱逐问题
7. [A Universal Context-Reuse Layer for Cross-Model KV Sharing](/202609/01/2608.30963v1-a-universal-context-reuse-layer-for-cross-model-kv-sharing)  
   标签：评分：9.0/10、query:pic
   evidence：跨模型KV共享，直接面向LLM推理中的KV缓存复用

### 速读区论文标签
1. [SemKV: Semantic Mixed-Precision KV Cache Quantization Guided by the Quality Cliff for Long-Context LLM Inference](/202609/01/2608.28911v1-semkv-semantic-mixed-precision-kv-cache-quantization-guided-by-the-quality-cliff-for-long-context-llm-inference)  
   标签：评分：8.0/10、query:pic
   evidence：面向长上下文LLM推理的KV缓存量化
2. [RouteSparse: Input-Conditional Pattern Routing for Budgeted Long-Context Prefilling](/202609/01/2608.29058v1-routesparse-input-conditional-pattern-routing-for-budgeted-long-context-prefilling)  
   标签：评分：8.0/10、query:pic
   evidence：通过输入条件稀疏模式路由加速长上下文预填充
3. [What It Costs to Compose, Rebuild, and Correct Precomputed Memory](/202609/01/2608.30647v1-what-it-costs-to-compose-rebuild-and-correct-precomputed-memory)  
   标签：评分：8.0/10、query:pic
   evidence：研究跨请求复用预计算记忆/KV缓存的正确性与代价
4. [Faithfulness Is Not Free: Auditing Offline KV-Cache Quantization in Retrieval-Augmented Generation](/202609/01/2608.30996v1-faithfulness-is-not-free-auditing-offline-kv-cache-quantization-in-retrieval-augmented-generation)  
   标签：评分：8.0/10、query:pic
   evidence：审计RAG中离线KV缓存量化
5. [Learning-Augmented Heuristics: Simple, yet Smart, Robust and Interpretable Cache Eviction](/202609/01/2608.27975v1-learning-augmented-heuristics-simple-yet-smart-robust-and-interpretable-cache-eviction)  
   标签：评分：6.0/10、query:pic
   evidence：LAH通过学习增强的启发式方法学习缓存驱逐参数，可迁移至包含KV缓存管理在内的一般缓存场景


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
