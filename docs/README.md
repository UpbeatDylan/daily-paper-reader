<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-07
- 运行时间：2026-08-07 20:54:50 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：1
- 速读区：6

### 今日简报（AI）
今日精读1篇、速读6篇，聚焦KV Cache量化与注意力加速优化。最值得关注的是《Spend Bits Where Queries Look》提出的注意力保持变换量化方法（8.0分），以及三篇7.0分工作分别从旋转、哈希、驱逐角度降低长上下文解码开销。建议优先阅读精读文章，再按需选读速读中的INT2量化或免训练哈希方案。
- 详情：[/202608/07/README](/202608/07/README)

### 精读区论文标签
1. [Spend Bits Where Queries Look: KV Cache Vector Quantization with Attention-Preserving Transforms](/202608/07/2608.04074v1-spend-bits-where-queries-look-kv-cache-vector-quantization-with-attention-preserving-transforms)  
   标签：评分：8.0/10、query:pic
   evidence：KV缓存向量量化压缩缓存体积，缓解带宽瓶颈，加速长上下文LLM解码

### 速读区论文标签
1. [Output-Aware Rotation for INT2 KV-Cache Quantization](/202608/07/2608.02691v2-output-aware-rotation-for-int2-kv-cache-quantization)  
   标签：评分：7.0/10、query:pic
   evidence：INT2 KV缓存量化降低长上下文推理的内存与带宽，属于长上下文推理加速
2. [Training-Free Hashing-Based Attention via Binary Principal Components](/202608/07/2608.04405v1-training-free-hashing-based-attention-via-binary-principal-components)  
   标签：评分：7.0/10、query:pic
   evidence：基于哈希的稀疏注意力降低长上下文LLM的KV处理开销，免训练
3. [QEvict: Recoverable Quantized KV Eviction for Attention-Drift-Robust Long-Context Decoding](/202608/07/2608.05326v1-qevict-recoverable-quantized-kv-eviction-for-attention-drift-robust-long-context-decoding)  
   标签：评分：7.0/10、query:pic
   evidence：可恢复量化KV驱逐，针对长上下文解码中的注意力漂移更鲁棒
4. [Unified Lookup-Table Inference with Signed-Digit K/V Caches for Ternary LLMs](/202608/07/2608.03229v1-unified-lookup-table-inference-with-signed-digit-kv-caches-for-ternary-llms)  
   标签：评分：6.0/10、query:pic
   evidence：三元LLM中面向统一查找表推理的有符号数字K/V缓存表示
5. [Fewer Tokens, Smaller Cache: Reward-Coordinated Efficient Reasoning](/202608/07/2608.04771v1-fewer-tokens-smaller-cache-reward-coordinated-efficient-reasoning)  
   标签：评分：6.0/10、query:pic
   evidence：用奖励协调KV缓存压缩，降低推理模型长思维链推理成本
6. [RAC: Reference-Aware Activation Compression for Communication-Efficient Split LLM Inference](/202608/07/2608.04991v1-rac-reference-aware-activation-compression-for-communication-efficient-split-llm-inference)  
   标签：评分：6.0/10、query:pic
   evidence：参考感知编码器在拆分LLM推理中复用精确词元历史片段，降低通信开销，与KV/上下文复用及推理加速相关


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
