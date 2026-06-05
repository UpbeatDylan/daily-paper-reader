<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-05
- 运行时间：2026-06-05 20:39:18 UTC
- 运行状态：成功
- 本次总论文数：8
- 精读区：4
- 速读区：4

### 今日简报（AI）
今日精读缓存隔离审计与RAG查询感知融合，速读稀疏KV投机解码、LoRA内存优化及长时记忆管理。最值得看的方向：CacheProbe审计缓存隔离安全性，QCFuse通过压缩视图提升RAG服务效率。建议优先精读这两篇，分别对应安全和效率优化场景。
- 详情：[/202606/05/README](/202606/05/README)

### 精读区论文标签
1. [CacheProbe: Auditing Prompt Cache Isolation in Gateway APIs](/202606/05/2605.30613v1-cacheprobe-auditing-prompt-cache-isolation-in-gateway-apis)  
   标签：评分：9.0/10、query:pic
   evidence：审计网关API中的提示缓存隔离，直接与提示缓存相关
2. [QCFuse: Query-Aware Cache Fusion via Compressed View for Efficient RAG Serving](/202606/05/2606.05875v1-qcfuse-query-aware-cache-fusion-via-compressed-view-for-efficient-rag-serving)  
   标签：评分：9.0/10、query:pic
   evidence：查询感知缓存融合重用预计算KV缓存
3. [RedKnot: Efficient Long-Context LLM Serving with Head-Aware KV Reuse and SegPagedAttention](/202606/05/2606.06256v1-redknot-efficient-long-context-llm-serving-with-head-aware-kv-reuse-and-segpagedattention)  
   标签：评分：9.0/10、query:pic
   evidence：解决位置无关KV缓存、头感知重用和SegPagedAttention以实现高效长上下文服务
4. [You Only Index Once: Cross-Layer Sparse Attention with Shared Routing](/202606/05/2606.06467v1-you-only-index-once-cross-layer-sparse-attention-with-shared-routing)  
   标签：评分：8.0/10、query:pic
   evidence：跨层稀疏注意力与共享KV缓存路由用于高效长上下文推理

### 速读区论文标签
1. [BudgetDraft: Acceptance-Aware Multi-View Training for Sparse-KV Speculative Decoding](/202606/05/2606.00144v1-budgetdraft-acceptance-aware-multi-view-training-for-sparse-kv-speculative-decoding)  
   标签：评分：7.0/10、query:pic
   evidence：稀疏KV推测解码加速中长上下文推理
2. [Rethinking LoRA Memory Through the Lens of KV Cache Compression](/202606/05/2606.05698v1-rethinking-lora-memory-through-the-lens-of-kv-cache-compression)  
   标签：评分：7.0/10、query:pic
   evidence：研究KV缓存压缩与LoRA的交互
3. [EMBER: Efficient Memory via Budgeted Evidence Retention for Long-Horizon Agents](/202606/05/2606.05894v1-ember-efficient-memory-via-budgeted-evidence-retention-for-long-horizon-agents)  
   标签：评分：7.0/10、query:pic
   evidence：针对长上下文智能体的预算化证据保留，类似于提示缓存
4. [Depth-Attention: Cross-Layer Value Mixing for Language Models](/202606/05/2606.05014v1-depth-attention-cross-layer-value-mixing-for-language-models)  
   标签：评分：6.0/10、query:pic
   evidence：在KV缓存约束内进行跨层注意力


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
