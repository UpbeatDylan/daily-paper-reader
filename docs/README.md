<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-03
- 运行时间：2026-08-03 20:20:15 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：3
- 速读区：4

### 今日简报（AI）
今日精读聚焦KV缓存跨模型翻译与压缩，速读覆盖视觉检索与量化风险，共7篇论文。  
最值得关注：《Mixture-of-Translators》实现异质LLM间KV缓存迁移，《ResKV》以固定预算重建注意力贡献，二者均获9.0高分。  
建议优先精读上述两篇高分歧作，速读《ReToken》与《WitCert》以拓宽视觉检索和量化安全视角。
- 详情：[/202608/03/README](/202608/03/README)

### 精读区论文标签
1. [Mixture-of-Translators: Translating KV Caches Across Heterogeneous Large Language Models](/202608/03/2607.28979v1-mixture-of-translators-translating-kv-caches-across-heterogeneous-large-language-models)  
   标签：评分：9.0/10、query:pic
   evidence：跨异构LLM复用KV缓存
2. [ResKV: Reconstructing Omitted Attention Contributions for Fixed-Budget KV Cache Compression](/202608/03/2607.29591v1-reskv-reconstructing-omitted-attention-contributions-for-fixed-budget-kv-cache-compression)  
   标签：评分：9.0/10、query:pic
   evidence：面向长上下文高效推理的KV缓存压缩方法，用残差缓存重建被丢弃token的注意力贡献
3. [TokTier: Exact Stateful Tokenization for Agentic LLM Serving](/202608/03/2607.29678v1-toktier-exact-stateful-tokenization-for-agentic-llm-serving)  
   标签：评分：9.0/10、query:pic
   evidence：通过保证令牌ID精确一致来维持KV缓存复用，减少智能体服务中的缓存失效

### 速读区论文标签
1. [ReToken: One Token to Improve Vision-Language Models for Visual Retrieval](/202608/03/2607.28627v1-retoken-one-token-to-improve-vision-language-models-for-visual-retrieval)  
   标签：评分：7.0/10、query:pic
   evidence：利用预填充的视觉KV缓存选择稀疏查询相关标记，加速长视觉上下文推理
2. [WitCert: Sound Runtime Risk Observability and Gating for KV-Cache Quantization](/202608/03/2607.28699v1-witcert-sound-runtime-risk-observability-and-gating-for-kv-cache-quantization)  
   标签：评分：7.0/10、query:pic
   evidence：面向长上下文推理加速的KV缓存量化运行时可观测性
3. [TransMem: Transforming Hidden States into Memory for Large Language Models](/202608/03/2607.29032v1-transmem-transforming-hidden-states-into-memory-for-large-language-models)  
   标签：评分：7.0/10、query:pic
   evidence：提出将历史隐藏状态转化为可复用记忆的推理期模块，避免长历史重复编码
4. [Selective KV Cache Protection for Noise-Resilient LLM Inference on Analog Compute-In-Memory Systems](/202608/03/2607.29076v1-selective-kv-cache-protection-for-noise-resilient-llm-inference-on-analog-compute-in-memory-systems)  
   标签：评分：7.0/10、query:pic
   evidence：模拟CIM上KV缓存噪声保护，支持长上下文推理加速与可靠性


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
