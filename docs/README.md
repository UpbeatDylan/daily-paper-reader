<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-07
- 运行时间：2026-09-07 23:05:59 UTC
- 运行状态：成功
- 本次总论文数：3
- 精读区：1
- 速读区：2

### 今日简报（AI）
今日精读提出BeaconKV，以Beacon查询引导键值缓存压缩，显著提升大模型推理效率；速读则揭示量化会放大缓存导致的输出分歧，并给出低秩注意力恢复方案。最值得关注BeaconKV的查询感知压缩思路，以及量化缓存质量与一致性间的矛盾。普通读者可优先了解KV缓存压缩对推理速度的影响，再看量化如何改变模型回答的稳定性。
- 详情：[/202609/07/README](/202609/07/README)

### 精读区论文标签
1. [BeaconKV: Key-Value Cache Compression Guided by Beacon Queries for Efficient Large Reasoning Model Inference](/202609/07/2609.04971v1-beaconkv-key-value-cache-compression-guided-by-beacon-queries-for-efficient-large-reasoning-model-inference)  
   标签：评分：9.0/10、query:pic
   evidence：面向大型推理模型长思维链的KV缓存压缩方法

### 速读区论文标签
1. [Same Request, Different Answer: Quantization Amplifies Cache-Induced Divergence in LLM Serving](/202609/07/2609.04748v1-same-request-different-answer-quantization-amplifies-cache-induced-divergence-in-llm-serving)  
   标签：评分：7.0/10、query:pic
   evidence：实证研究默认前缀缓存在权重量化下引起的输出分歧，与缓存服务的稳定性高度相关
2. [Quality Recovery for Quantized KV Caches via Low-Rank Attention Adaptation](/202609/07/2609.04263v1-quality-recovery-for-quantized-kv-caches-via-low-rank-attention-adaptation)  
   标签：评分：6.0/10、query:pic
   evidence：面向内存高效长上下文推理的KV缓存量化与低秩适配


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
