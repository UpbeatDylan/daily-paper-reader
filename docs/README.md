<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-31
- 运行时间：2026-08-31 23:22:57 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：2
- 速读区：5

### 今日简报（AI）
今日7篇论文聚焦KV缓存优化，含2篇精读与5篇速读，覆盖淘汰、压缩及量化方向。  
最值得看《Trust the Mass》与《Parser States Already Know》（均8分），分别用强制权重淘汰和结构条件持久化提升缓存效率。  
建议从精读两篇入手，再速读《DAMP》与《DensityKV》，理解量化与视频生成场景的缓存压缩取舍。
- 详情：[/202608/31/README](/202608/31/README)

### 精读区论文标签
1. [Trust the Mass: Forced Weights in KV-Cache Eviction](/202608/31/2608.25230v2-trust-the-mass-forced-weights-in-kv-cache-eviction)  
   标签：评分：8.0/10、query:pic
   evidence：分析KV缓存驱逐规则，指出保留最大注意力权重接近最优，并揭示掩码存储的内存影响，对缓存重用有指导意义
2. [Parser States Already Know: Structure-Conditioned KV Persistence for Structured Generation](/202608/31/2608.28276v1-parser-states-already-know-structure-conditioned-kv-persistence-for-structured-generation)  
   标签：评分：8.0/10、query:pic
   evidence：利用解析器状态指导KV持久化，直接解决结构化生成中的KV缓存复用。

### 速读区论文标签
1. [DAMP: Decay-Aware Mixed-Precision Recurrent-State Quantization](/202608/31/2608.27513v1-damp-decay-aware-mixed-precision-recurrent-state-quantization)  
   标签：评分：7.0/10、query:pic
   evidence：对GDN/KDA模型中的循环状态进行量化，替代KV缓存以减少内存带宽和解码延迟，属于KV缓存优化的最新方法。
2. [DensityKV: Density-Guided KV Cache Compression for Long Video Generation](/202608/31/2608.27922v1-densitykv-density-guided-kv-cache-compression-for-long-video-generation)  
   标签：评分：7.0/10、query:pic
   evidence：提出密度引导的历史KV存储库管理，减少冗余KV覆盖并支持长时一致性
3. [A Probabilistic Interpretation of KV Cache Eviction](/202608/31/2608.28293v1-a-probabilistic-interpretation-of-kv-cache-eviction)  
   标签：评分：7.0/10、query:pic
   evidence：通过概率推理形式化KV缓存驱逐问题，将驱逐归结为期望估计，与KV缓存重用相关。
4. [Learning-Augmented Heuristics: Simple, yet Smart, Robust and Interpretable Cache Eviction](/202608/31/2608.27975v1-learning-augmented-heuristics-simple-yet-smart-robust-and-interpretable-cache-eviction)  
   标签：评分：6.0/10、query:pic
   evidence：提出学习增强的缓存逐出框架，可应用于LLM KV缓存管理
5. [Sliding-window beats linear attention](/202608/31/2608.28444v1-sliding-window-beats-linear-attention)  
   标签：评分：6.0/10、query:pic
   evidence：滑动窗口注意力可减少KV缓存内存并加速长上下文推理


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
