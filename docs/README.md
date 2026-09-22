<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-22
- 运行时间：2026-09-22 22:35:46 UTC
- 运行状态：成功
- 本次总论文数：8
- 精读区：0
- 速读区：8

### 今日简报（AI）
今天筛出8篇LLM推理加速论文，全部速读，无精读。

最值得看的是KV缓存淘汰与稀疏注意力两线：《ValueDiff》用值几何做KV淘汰，《SPLASH》把稀疏注意力与高带宽闪存协同设计。

普通读者可先读这两篇的摘要与方法图，理解“省显存”与“省算力”两条路线即可。
- 详情：[/202609/22/README](/202609/22/README)

### 精读区论文标签
- 本次无精读推荐。

### 速读区论文标签
1. [ValueDiff: Value-Geometric KV Cache Eviction for Sink-Suppressed LLMs](/202609/22/2609.23314v1-valuediff-value-geometric-kv-cache-eviction-for-sink-suppressed-llms)  
   标签：评分：7.0/10、query:pic
   evidence：固定缓存预算下的值几何KV缓存淘汰
2. [SPLASH: Co-Designing Sparse Attention with High-Bandwidth Flash for Efficient Long-Context Inference](/202609/22/2609.23816v1-splash-co-designing-sparse-attention-with-high-bandwidth-flash-for-efficient-long-context-inference)  
   标签：评分：7.0/10、query:pic
   evidence：面向长上下文推理的KV缓存分层与稀疏注意力
3. [H-Spec: Parallel Speculative Decoding Without a Drafter-Side KV Cache](/202609/22/2609.24197v1-h-spec-parallel-speculative-decoding-without-a-drafter-side-kv-cache)  
   标签：评分：7.0/10、query:pic
   evidence：原地复用目标KV而非草稿端KV缓存
4. [ARM: Attention with Routed-Memory for Learnable Sparse Control](/202609/22/2609.24417v1-arm-attention-with-routed-memory-for-learnable-sparse-control)  
   标签：评分：7.0/10、query:pic
   evidence：面向长上下文推理的可微固定大小KV记忆结构
5. [Zarya: A Hybrid Autoregressive--Masked Diffusion Language Model with Flexible Training and Dual-Mode Inference](/202609/22/2609.19868v1-zarya-a-hybrid-autoregressive--masked-diffusion-language-model-with-flexible-training-and-dual-mode-inference)  
   标签：评分：6.0/10、query:pic
   evidence：针对扩散解码无法复用KV缓存问题的混合模型
6. [Block-Sparse Attention with Semantic-Geometric Decoupled Routing](/202609/22/2609.22884v1-block-sparse-attention-with-semantic-geometric-decoupled-routing)  
   标签：评分：6.0/10、query:pic
   evidence：面向长上下文推理的免训练块稀疏注意力路由
7. [From Inference Engine to Inference Control Plane: Connecting vLLM, llm-d, and the Evolution of Efficient Distributed LLM Serving](/202609/22/2609.23130v1-from-inference-engine-to-inference-control-plane-connecting-vllm-llm-d-and-the-evolution-of-efficient-distributed-llm-serving)  
   标签：评分：6.0/10、query:pic
   evidence：分布式LLM服务中的可复用状态与PagedAttention
8. [KV-COBRA: KV Cache Compression via Co-Optimized Bit-Rank Allocation](/202609/22/2609.24298v1-kv-cobra-kv-cache-compression-via-co-optimized-bit-rank-allocation)  
   标签：评分：6.0/10、query:pic
   evidence：通过逐头协同优化秩与位宽分配实现KV缓存压缩


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
