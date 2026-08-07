<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-07
- 运行时间：2026-08-07 02:14:48 UTC
- 运行状态：成功
- 本次总论文数：5
- 精读区：1
- 速读区：4

### 今日简报（AI）
今日精读1篇、速读4篇，共5篇论文，聚焦KV缓存量化、哈希注意力与高效推理。

最值得关注的是精读论文《Spend Bits Where Queries Look》提出的注意力保持变换下的KV缓存向量量化（8.0分），以及训练无关的哈希注意力方法。

建议普通读者优先从这篇KV缓存量化论文入手，可快速理解如何在不损失注意力质量的前提下压缩缓存。
- 详情：[/202608/07/README](/202608/07/README)

### 精读区论文标签
1. [Spend Bits Where Queries Look: KV Cache Vector Quantization with Attention-Preserving Transforms](/202608/07/2608.04074v1-spend-bits-where-queries-look-kv-cache-vector-quantization-with-attention-preserving-transforms)  
   标签：评分：8.0/10、query:pic
   evidence：通过注意力保持变换进行KV缓存向量量化，减小缓存大小并提高解码速度

### 速读区论文标签
1. [Training-Free Hashing-Based Attention via Binary Principal Components](/202608/07/2608.04405v1-training-free-hashing-based-attention-via-binary-principal-components)  
   标签：评分：7.0/10、query:pic
   evidence：面向长上下文LLM推理加速的无训练哈希稀疏注意力
2. [Fewer Tokens, Smaller Cache: Reward-Coordinated Efficient Reasoning](/202608/07/2608.04771v1-fewer-tokens-smaller-cache-reward-coordinated-efficient-reasoning)  
   标签：评分：7.0/10、query:pic
   evidence：利用过程奖励沿推理轨迹协调KV缓存压缩，降低显存与生成开销
3. [RAC: Reference-Aware Activation Compression for Communication-Efficient Split LLM Inference](/202608/07/2608.04991v1-rac-reference-aware-activation-compression-for-communication-efficient-split-llm-inference)  
   标签：评分：7.0/10、query:pic
   evidence：在拆分式LLM推理中复用历史激活跨度作为上下文缓存，以减少通信并加速长上下文处理
4. [Does Accuracy Equal Evidence? Reasoning Faithfulness under KV Cache Compression](/202608/07/2608.01631v1-does-accuracy-equal-evidence-reasoning-faithfulness-under-kv-cache-compression)  
   标签：评分：6.0/10、query:pic
   evidence：评估KV缓存压缩方法下的推理忠实度，揭示准确率与证据保留之间的差距


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
