<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-14
- 运行时间：2026-07-14 21:41:32 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：2
- 速读区：5

### 今日简报（AI）
今日重点关注多智能体工作流KV缓存优化与LLM推理加速，精读两篇高分论文。最值得看的是AAFLOW+的无拷贝分布式KV缓存编排与MemDecay的区域感知缓存淘汰策略。建议优先精读这两篇，深入理解零拷贝通信和缓存管理对提升推理效率的实际价值。
- 详情：[/202607/14/README](/202607/14/README)

### 精读区论文标签
1. [[AAFLOW+] Stateful Operator Abstraction with Zero-Copy Distributed KV Cache Orchestration for Multi-Agent Workflows](/202607/14/2607.10987v1-aaflow-stateful-operator-abstraction-with-zero-copy-distributed-kv-cache-orchestration-for-multi-agent-workflows)  
   标签：评分：9.0/10、query:pic
   evidence：在分布式系统中将KV缓存作为一等公民并提供零拷贝编排
2. [MemDecay: Region-Aware KV Cache Eviction for Efficient LLM Agent Inference](/202607/14/2607.10582v1-memdecay-region-aware-kv-cache-eviction-for-efficient-llm-agent-inference)  
   标签：评分：8.0/10、query:pic
   evidence：区域感知的KV缓存逐出，提升LLM Agent推理效率

### 速读区论文标签
1. [BlockServe: Block-Grained Continuous Batching for High-Throughput Diffusion LLM Serving](/202607/14/2607.08930v1-blockserve-block-grained-continuous-batching-for-high-throughput-diffusion-llm-serving)  
   标签：评分：7.0/10、query:pic
   evidence：块粒度连续批处理框架，集成双缓存和并行解码
2. [Remembering Distinct Items, Not Tokens: A Learnable Dirichlet-Process Cache Between State-Space Models and Attention](/202607/14/2607.09889v1-remembering-distinct-items-not-tokens-a-learnable-dirichlet-process-cache-between-state-space-models-and-attention)  
   标签：评分：7.0/10、query:pic
   evidence：稀疏缓存追踪不同项目用于上下文缓存
3. [FlashAccel: Leveraging High-Bandwidth Flash for High-Throughput LLM Inference](/202607/14/2607.10186v1-flashaccel-leveraging-high-bandwidth-flash-for-high-throughput-llm-inference)  
   标签：评分：7.0/10、query:pic
   evidence：利用高带宽闪存扩展KV缓存容量，支持长上下文推理
4. [Context by Distinct Information: An Auditable Dirichlet-Process Working Memory for Long, Redundant Context Streams](/202607/14/2607.10441v1-context-by-distinct-information-an-auditable-dirichlet-process-working-memory-for-long-redundant-context-streams)  
   标签：评分：7.0/10、query:pic
   evidence：基于新颖性分配的缓存用于长上下文流
5. [Sparse Delta Memory: Scaling the State of Linear RNNs through Sparsity](/202607/14/2607.07386v1-sparse-delta-memory-scaling-the-state-of-linear-rnns-through-sparsity)  
   标签：评分：6.0/10、query:pic
   evidence：通过稀疏记忆扩展线性RNN状态，改善长上下文召回，类似于KV缓存扩展


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
