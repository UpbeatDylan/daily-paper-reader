<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-29
- 运行时间：2026-09-29 23:38:32 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
- 今日共生成 17 篇推荐（精读 6 篇，速读 11 篇）
- 精读：《RelaxKV: Recomputation Guided by the Query with Sparse Context Attention for Efficient KV Cache Reuse》（10.0/10）, 《Memory as a cache: Exact context reuse and deletion by construction》（9.0/10）
- 速读：《Prefill-Free Cross-Family KV Cache Transfer for Heterogeneous Multi-Agent LLMs》（8.0/10）, 《RR-Evict: Fine-Grained Prefix Cache Eviction beyond LRU for Agentic LLM Serving》（8.0/10）, 《Distance-KV: Exploiting Relative Distance for Efficient Long-Context Inference》（8.0/10）
- 这些结果覆盖了当下较热的方向，建议先看精读区论文的关键问题与方法。
- 详情：[/202609/29/README](/202609/29/README)

### 精读区论文标签
1. [RelaxKV: Recomputation Guided by the Query with Sparse Context Attention for Efficient KV Cache Reuse](/202609/29/2609.33503v1-relaxkv-recomputation-guided-by-the-query-with-sparse-context-attention-for-efficient-kv-cache-reuse)  
   标签：评分：10.0/10、query:pic
   evidence：位置无关缓存与选择性重计算实现高效KV缓存复用
2. [Memory as a cache: Exact context reuse and deletion by construction](/202609/29/2609.32395v1-memory-as-a-cache-exact-context-reuse-and-deletion-by-construction)  
   标签：评分：9.0/10、query:pic
   evidence：块局部编码器使上下文缓存独立于前缀位置
3. [Tessera: Demand-Driven KV Cache Management for Retrieval-Augmented LLM Serving](/202609/29/2609.32999v1-tessera-demand-driven-kv-cache-management-for-retrieval-augmented-llm-serving)  
   标签：评分：9.0/10、query:pic
   evidence：跨不同提示位置的可组合KV复用
4. [Just Let Linear States Forget the Distant Past: Prefix Caching via Suffix Replay for Hybrid LLMs](/202609/29/2609.33477v1-just-let-linear-states-forget-the-distant-past-prefix-caching-via-suffix-replay-for-hybrid-llms)  
   标签：评分：9.0/10、query:pic
   evidence：通过后缀重放实现混合LLM的前缀缓存系统
5. [Dynamic Flow, Static Graph: KV Cache Reuse for Efficient LLM Serving on Mobile NPUs](/202609/29/2609.34727v1-dynamic-flow-static-graph-kv-cache-reuse-for-efficient-llm-serving-on-mobile-npus)  
   标签：评分：9.0/10、query:pic
   evidence：面向前缀与非前缀KV复用的计算存储协同设计
6. [CacheRepair: Learning to Repair Cross-Chunk Context in RAG for KV Cache Fusion](/202609/29/2609.35139v1-cacherepair-learning-to-repair-cross-chunk-context-in-rag-for-kv-cache-fusion)  
   标签：评分：9.0/10、query:pic
   evidence：独立预计算各块KV缓存并拼接

### 速读区论文标签
1. [Prefill-Free Cross-Family KV Cache Transfer for Heterogeneous Multi-Agent LLMs](/202609/29/2609.32259v1-prefill-free-cross-family-kv-cache-transfer-for-heterogeneous-multi-agent-llms)  
   标签：评分：8.0/10、query:pic
   evidence：跨模型家族复用发送方KV缓存，免预填充迁移
2. [RR-Evict: Fine-Grained Prefix Cache Eviction beyond LRU for Agentic LLM Serving](/202609/29/2609.32278v1-rr-evict-fine-grained-prefix-cache-eviction-beyond-lru-for-agentic-llm-serving)  
   标签：评分：8.0/10、query:pic
   evidence：前缀缓存避免重复预填充，超越LRU的细粒度前缀缓存淘汰
3. [Distance-KV: Exploiting Relative Distance for Efficient Long-Context Inference](/202609/29/2609.32663v1-distance-kv-exploiting-relative-distance-for-efficient-long-context-inference)  
   标签：评分：8.0/10、query:pic
   evidence：按相对距离学习KV保留模式以加速长上下文推理
4. [EfficientAgent: What Makes KV Cache Offloading Work for Concurrent Agents?](/202609/29/2609.33762v1-efficientagent-what-makes-kv-cache-offloading-work-for-concurrent-agents)  
   标签：评分：8.0/10、query:pic
   evidence：面向并发LLM智能体的KV缓存卸载与前缀复用
5. [FlashLoop: Fast and Memory-Efficient Looped Transformers via Lazy Updates](/202609/29/2609.29812v2-flashloop-fast-and-memory-efficient-looped-transformers-via-lazy-updates)  
   标签：评分：7.0/10、query:pic
   evidence：惰性更新减少循环深度与长上下文带来的KV缓存增长
6. [KV-Lingo: Learning KV-Cache Translators with Distillation](/202609/29/2609.32610v1-kv-lingo-learning-kv-cache-translators-with-distillation)  
   标签：评分：7.0/10、query:pic
   evidence：跨模型翻译KV缓存以复用已处理上下文
7. [UniCache: Task- and Type-Aware KV Cache Compression for Unified Multimodal Models](/202609/29/2609.32831v1-unicache-task--and-type-aware-kv-cache-compression-for-unified-multimodal-models)  
   标签：评分：7.0/10、query:pic
   evidence：面向多模态长上下文的任务与类型感知KV缓存压缩
8. [Resource-Efficient Speculative Decoding for Long-Context LLM Serving](/202609/29/2609.33184v1-resource-efficient-speculative-decoding-for-long-context-llm-serving)  
   标签：评分：7.0/10、query:pic
   evidence：面向长上下文服务的高效KV卸载与共享
9. [LAM: Efficient Lossy Agent Memory Framework With A Retrieval-Score Error Bound](/202609/29/2609.32256v1-lam-efficient-lossy-agent-memory-framework-with-a-retrieval-score-error-bound)  
   标签：评分：6.0/10、query:pic
   evidence：保留缓存前缀并将压缩与推理重叠
10. [Splitting Prompt Prefill from Response Replay for Context-Parallel Long-Context LLM Post-Training](/202609/29/2609.33133v1-splitting-prompt-prefill-from-response-replay-for-context-parallel-long-context-llm-post-training)  
   标签：评分：6.0/10、query:pic
   evidence：共享提示KV状态只计算一次，避免每个响应分支重复计算
11. [Thinking Outside the Box: Retention and Transmission of Information in Sliding-Window KV Inference](/202609/29/2609.34049v1-thinking-outside-the-box-retention-and-transmission-of-information-in-sliding-window-kv-inference)  
   标签：评分：6.0/10、query:pic
   evidence：研究固定大小滚动KV缓存中的信息保留


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
