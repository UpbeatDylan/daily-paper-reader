<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-10-09
- 运行时间：2026-10-09 00:17:30 UTC
- 运行状态：成功
- 本次总论文数：8
- 精读区：0
- 速读区：8

### 今日简报（AI）
2026-10-09 日报速读 8 篇，重点集中在长上下文与 KV-Cache 优化。最值得看的是《CommunityKV》用图分区加速长上下文解码，以及《A Self-Pruning Transformer》实现极端 KV-Cache 压缩。普通读者可优先了解 KV-Cache 压缩与动态计算这两条省显存、提速度的实用路线。
- 详情：[/202610/09/README](/202610/09/README)

### 精读区论文标签
- 本次无精读推荐。

### 速读区论文标签
1. [CommunityKV: Efficient Long-Context Decoding via Graph Partitioning](/202610/09/2610.00418v1-communitykv-efficient-long-context-decoding-via-graph-partitioning)  
   标签：评分：7.0/10、query:pic
   evidence：通过降低KV缓存传输实现高效长上下文解码
2. [Enabling Dynamic Computation in Looped LMs](/202610/09/2610.09013v1-enabling-dynamic-computation-in-looped-lms)  
   标签：评分：7.0/10、query:pic
   evidence：最优可用KV缓存策略减少FLOPs与KV显存
3. [A Self-Pruning Transformer: Extreme KV-Cache Compression with Universal Attention](/202610/09/2610.09051v1-a-self-pruning-transformer-extreme-kv-cache-compression-with-universal-attention)  
   标签：评分：7.0/10、query:pic
   evidence：基于衰减的位置机制实现KV缓存剪枝
4. [Scaling Parameter and Context in Attention: Native Sparse Attention from Mixture-of-Head](/202610/09/2609.38832v1-scaling-parameter-and-context-in-attention-native-sparse-attention-from-mixture-of-head)  
   标签：评分：6.0/10、query:pic
   evidence：面向长上下文高效扩展的架构原生稀疏注意力机制
5. [The Evolution of Attention in Large Language Models: Mechanisms, Trade-offs, and Emerging Trends](/202610/09/2609.39661v1-the-evolution-of-attention-in-large-language-models-mechanisms-trade-offs-and-emerging-trends)  
   标签：评分：6.0/10、query:pic
   evidence：综述注意力机制，涵盖KV缓存增长与长上下文内存压缩
6. [Persistent Memory in Multi-Agent LLM Inference: What It Costs, What It Buys, and When You Can Tell](/202610/09/2610.07782v1-persistent-memory-in-multi-agent-llm-inference-what-it-costs-what-it-buys-and-when-you-can-tell)  
   标签：评分：6.0/10、query:pic
   evidence：分解式长上下文推理中的KV缓存工作集
7. [Lachesis: Lifetime-Aware KV Cache Placement for Agent Serving across HBM and High-Bandwidth Flash](/202610/09/2610.08378v1-lachesis-lifetime-aware-kv-cache-placement-for-agent-serving-across-hbm-and-high-bandwidth-flash)  
   标签：评分：6.0/10、query:pic
   evidence：面向智能体服务的KV缓存生命周期感知放置与复用
8. [Cache the Encoder Within:Compact, Reusable Memory across LLM Queries](/202610/09/2610.10058v1-cache-the-encoder-withincompact-reusable-memory-across-llm-queries)  
   标签：评分：6.0/10、query:pic
   evidence：跨重复LLM查询缓存可复用紧凑记忆


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
