<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-02 ~ 2026-05-31
- 运行时间：2026-05-31 08:28:30 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日推荐17篇论文，聚焦LLM缓存与推理加速，精读与速读均有高分成果。

最值得关注两个方向：Irminsul提出MLA原生位置无关缓存优化Agent推理，RcLLM利用超越前缀的KV缓存加速生成式推荐。

建议普通读者优先精读这两篇高分论文，并速读分层KV可见性与预测式缓存管理方法，把握LLM服务效率提升的核心路径。
- 详情：[/20260502-20260531/README](/20260502-20260531/README)

### 精读区论文标签
1. [Irminsul: MLA-Native Position-Independent Caching for Agentic LLM Serving](/20260502-20260531/2605.05696v1-irminsul-mla-native-position-independent-caching-for-agentic-llm-serving)  
   标签：评分：10.0/10、query:pic
   evidence：面向LLM推理加速的位置无关缓存
2. [RcLLM: Accelerating Generative Recommendation via Beyond-Prefix KV Caching](/20260502-20260531/2605.07443v1-rcllm-accelerating-generative-recommendation-via-beyond-prefix-kv-caching)  
   标签：评分：9.0/10、query:pic
   evidence：超越前缀的KV缓存用于生成式推荐
3. [Adaptive KV Cache Reuse for Fast Long-Context LLM Serving](/20260502-20260531/2605.24022v1-adaptive-kv-cache-reuse-for-fast-long-context-llm-serving)  
   标签：评分：9.0/10、query:pic
   evidence：自适应KV缓存重用直接针对非前缀（位置无关）KV重用
4. [Tutti: Making SSD-Backed KV Cache Practical for Long-Context LLM Serving](/20260502-20260531/2605.03375v1-tutti-making-ssd-backed-kv-cache-practical-for-long-context-llm-serving)  
   标签：评分：8.0/10、query:pic
   evidence：基于SSD的KV缓存实现长上下文LLM服务中的前缀缓存
5. [AdapShot: Adaptive Many-Shot In-Context Learning with Semantic-Aware KV Cache Reuse](/20260502-20260531/2605.03644v1-adapshot-adaptive-many-shot-in-context-learning-with-semantic-aware-kv-cache-reuse)  
   标签：评分：8.0/10、query:pic
   evidence：语义感知的KV缓存重用用于多示例上下文学习
6. [Training Transformers for KV Cache Compressibility](/20260502-20260531/2605.05971v2-training-transformers-for-kv-cache-compressibility)  
   标签：评分：8.0/10、query:pic
   evidence：训练KV可压缩性以减少缓存大小

### 速读区论文标签
1. [Shallow Prefill, Deep Decoding: Efficient Long-Context Inference via Layer-Asymmetric KV Visibility](/20260502-20260531/2605.06105v1-shallow-prefill-deep-decoding-efficient-long-context-inference-via-layer-asymmetric-kv-visibility)  
   标签：评分：8.0/10、query:pic
   evidence：SPEED通过层非对称KV可见性降低长上下文成本
2. [Efficient Serving for Dynamic Agent Workflows with Prediction-based KV-Cache Management](/20260502-20260531/2605.06472v1-efficient-serving-for-dynamic-agent-workflows-with-prediction-based-kv-cache-management)  
   标签：评分：8.0/10、query:pic
   evidence：基于预测的KV缓存管理用于动态智能体工作流
3. [Reformulating KV Cache Eviction Problem for Long-Context LLM Inference](/20260502-20260531/2605.07234v1-reformulating-kv-cache-eviction-problem-for-long-context-llm-inference)  
   标签：评分：8.0/10、query:pic
   evidence：输出感知的KV缓存淘汰重表述
4. [RDKV: Rate-Distortion Bit Allocation for Joint Eviction and Quantization of the KV Cache](/20260502-20260531/2605.08317v1-rdkv-rate-distortion-bit-allocation-for-joint-eviction-and-quantization-of-the-kv-cache)  
   标签：评分：8.0/10、query:pic
   evidence：RDKV联合优化驱逐与量化以压缩KV缓存
5. [Training Transformers for KV Cache Compressibility](/20260502-20260531/2605.05971v1-training-transformers-for-kv-cache-compressibility)  
   标签：评分：7.0/10、query:pic
   evidence：通过训练提升KV缓存可压缩性以减少内存和解码成本
6. [Requests of a Feather Must Flock Together: Batch Size vs. Prefix Homogeneity in LLM Inference](/20260502-20260531/2605.06046v1-requests-of-a-feather-must-flock-together-batch-size-vs-prefix-homogeneity-in-llm-inference)  
   标签：评分：7.0/10、query:pic
   evidence：批处理中的前缀同质性改善KV缓存局部性
7. [Sparse Attention as a Range Searching Problem: Towards an Inference-Efficient Index for KV Cache](/20260502-20260531/2605.06763v1-sparse-attention-as-a-range-searching-problem-towards-an-inference-efficient-index-for-kv-cache)  
   标签：评分：7.0/10、query:pic
   evidence：稀疏注意力索引减少长上下文推理中的KV缓存开销
8. [Sparse Attention as a Range Searching Problem: Towards an Inference-Efficient Index for KV Cache](/20260502-20260531/2605.06763v2-sparse-attention-as-a-range-searching-problem-towards-an-inference-efficient-index-for-kv-cache)  
   标签：评分：7.0/10、query:pic
   evidence：基于范围搜索的KV缓存稀疏注意力索引
9. [Training-Inference Consistent Segmented Execution for Long-Context LLMs](/20260502-20260531/2605.11744v1-training-inference-consistent-segmented-execution-for-long-context-llms)  
   标签：评分：6.0/10、query:pic
   evidence：训练推理一致的逐段执行用于长上下文LLM
10. [H$^{2}$MT: Semantic Hierarchy-Aware Hierarchical Memory Transformer](/20260502-20260531/2605.24930v1-h2mt-semantic-hierarchy-aware-hierarchical-memory-transformer)  
   标签：评分：6.0/10、query:pic
   evidence：用于长上下文推理加速的语义层次记忆
11. [Grounded Cache Routing for Retrieval-Augmented Generation: When Is It Safe to Reuse an Answer?](/20260502-20260531/2605.27494v1-grounded-cache-routing-for-retrieval-augmented-generation-when-is-it-safe-to-reuse-an-answer)  
   标签：评分：6.0/10、query:pic
   evidence：讨论了RAG中的位置无关KV缓存重用，并提出安全的答案重用


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
