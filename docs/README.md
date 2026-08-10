<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-10
- 运行时间：2026-08-10 20:41:01 UTC
- 运行状态：成功
- 本次总论文数：5
- 精读区：3
- 速读区：2

### 今日简报（AI）
今日聚焦5篇长上下文效率研究，精读3篇、速读2篇，核心围绕KV Cache复用与压缩。最值得关注CoinRAG的上下文信息块复用（9.0分）及“每项缓存皆有其位”的全局分配压缩（8.0分），两者直击长文本推理成本痛点。建议普通读者优先了解KV Cache压缩的收益边界，再跟进参考感知激活压缩的通信优化方向。
- 详情：[/202608/10/README](/202608/10/README)

### 精读区论文标签
1. [CoinRAG: Contextualized Information Nugget KV Cache Reuse for Long-Context RAG](/202608/10/2608.07458v1-coinrag-contextualized-information-nugget-kv-cache-reuse-for-long-context-rag)  
   标签：评分：9.0/10、query:pic
   evidence：细粒度KV缓存复用用于长上下文RAG，降低prefill延迟并提升精度
2. [Every Cache Entry Earns Its Place: Global Allocation of Resolution and Coverage for KV Cache Compression](/202608/10/2608.07001v1-every-cache-entry-earns-its-place-global-allocation-of-resolution-and-coverage-for-kv-cache-compression)  
   标签：评分：8.0/10、query:pic
   evidence：面向长上下文推理的KV缓存压缩，通过全局资源分配降低显存瓶颈
3. [HiSparse: Scaling Sparse-Attention Decoding with Hierarchical KV Cache Management](/202608/10/2608.07009v1-hisparse-scaling-sparse-attention-decoding-with-hierarchical-kv-cache-management)  
   标签：评分：8.0/10、query:pic
   evidence：分层KV缓存管理将完整KV历史放在主机内存，并限制GPU缓存占用以支持稀疏注意力解码

### 速读区论文标签
1. [RAC: Reference-Aware Activation Compression for Communication-Efficient Split LLM Inference](/202608/10/2608.04991v1-rac-reference-aware-activation-compression-for-communication-efficient-split-llm-inference)  
   标签：评分：7.0/10、query:pic
   evidence：复用精确token历史片段用于预填充上行，并重建状态以降低拆分推理时延，类似提示缓存
2. [Autonomy-of-Heads: Data-Free Sparse Attention from Frozen Query-Key Geometry](/202608/10/2608.06849v1-autonomy-of-heads-data-free-sparse-attention-from-frozen-query-key-geometry)  
   标签：评分：7.0/10、query:pic
   evidence：无数据头剪枝，降低长上下文注意力与KV缓存开销


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
