<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-23
- 运行时间：2026-06-23 22:04:33 UTC
- 运行状态：成功
- 本次总论文数：8
- 精读区：5
- 速读区：3

### 今日简报（AI）
今日精读5篇、速读3篇，聚焦KV缓存优化与LLM推理效率两大核心议题。最值得关注的两项高分研究：《Recency/Frequency Adaptive KV Caching》提出自适应缓存策略，《Keyless Attention》通过值空间路由实现无键注意力变革。建议后续关注缓存校准安全（如RAG侧信道攻击）与在线调度几何优化。
- 详情：[/202606/23/README](/202606/23/README)

### 精读区论文标签
1. [Recency/Frequency Adaptive KV Caching for Large Language Model Serving](/202606/23/2606.21238v1-recencyfrequency-adaptive-kv-caching-for-large-language-model-serving)  
   标签：评分：9.0/10、query:pic
   evidence：自适应KV缓存用于LLM服务，提升命中率和首Token延迟
2. [Keyless Attention: Value-Space Routing and Value-Only Caching for Efficient Transformers](/202606/23/2606.21848v1-keyless-attention-value-space-routing-and-value-only-caching-for-efficient-transformers)  
   标签：评分：9.0/10、query:pic
   evidence：仅值缓存将KV缓存内存减少50%
3. [SpotAttention: Plug-In Block-Sparse Routing for Pretrained Long-Context Transformers](/202606/23/2606.22874v1-spotattention-plug-in-block-sparse-routing-for-pretrained-long-context-transformers)  
   标签：评分：9.0/10、query:pic
   evidence：用于长上下文加速的稀疏注意力
4. [HERALD: High-Throughput Block Diffusion LLM Serving via CPU-GPU Cooperative KV Cache Retrieval](/202606/23/2606.21633v1-herald-high-throughput-block-diffusion-llm-serving-via-cpu-gpu-cooperative-kv-cache-retrieval)  
   标签：评分：8.0/10、query:pic
   evidence：块扩散LLM中的KV缓存卸载与稀疏检索复用
5. [WiSP: A Working-Set View of Mixture-of-Experts Serving on Extremely Low-Resource Hardware](/202606/23/2606.21868v1-wisp-a-working-set-view-of-mixture-of-experts-serving-on-extremely-low-resource-hardware)  
   标签：评分：8.0/10、query:pic
   evidence：KV缓存与专家权重竞争内存

### 速读区论文标签
1. [Closing the Calibration Gap in Semantic Caching](/202606/23/2606.19719v2-closing-the-calibration-gap-in-semantic-caching)  
   标签：评分：7.0/10、query:pic
   evidence：语义缓存校准用于降低LLM推理成本
2. [Geometry-Aware Online Scheduling for LLM Serving: From Theoretical Bound to System Practice](/202606/23/2606.22327v1-geometry-aware-online-scheduling-for-llm-serving-from-theoretical-bound-to-system-practice)  
   标签：评分：7.0/10、query:pic
   evidence：KV缓存动态内存管理与推理调度
3. [Agent-Assisted Side-Channel Attacks on Non-Prefix KV Cache in RAG](/202606/23/2606.21842v1-agent-assisted-side-channel-attacks-on-non-prefix-kv-cache-in-rag)  
   标签：评分：6.0/10、query:pic
   evidence：KV缓存侧信道攻击揭示了非前缀KV缓存的结构


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
