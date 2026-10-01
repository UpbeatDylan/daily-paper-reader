<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-10-01
- 运行时间：2026-10-01 23:00:36 UTC
- 运行状态：成功
- 本次总论文数：4
- 精读区：0
- 速读区：4

### 今日简报（AI）
2026-10-01 日报速读4篇，0精读，聚焦LLM效率优化。最值得关注GSM（7.0分）用共享全局状态提升语言建模效率，以及CascadeEP和FoldAttention针对MoE推理与注意力解码的加速方案。普通读者可优先从GSM入手，理解"共享状态"如何在不牺牲效果的前提下降低计算开销。
- 详情：[/202610/01/README](/202610/01/README)

### 精读区论文标签
- 本次无精读推荐。

### 速读区论文标签
1. [GSM: Efficient Language Modeling with Shared Global State](/202610/01/2609.33465v1-gsm-efficient-language-modeling-with-shared-global-state)  
   标签：评分：7.0/10、query:pic
   evidence：避免重复构建历史键值表示
2. [CascadeEP: Asynchronous Expert Execution for MoE Prefill under Attention Imbalance](/202610/01/2609.33252v1-cascadeep-asynchronous-expert-execution-for-moe-prefill-under-attention-imbalance)  
   标签：评分：6.0/10、query:pic
   evidence：MoE预填充中共享提示前缀的KV缓存复用
3. [FoldAttention: Declared-Reference Softmax for Fast Decode and Deterministic Backward](/202610/01/2609.33410v1-foldattention-declared-reference-softmax-for-fast-decode-and-deterministic-backward)  
   标签：评分：6.0/10、query:pic
   evidence：固定参考值的加性softmax，扫描KV缓存前即可确定归一化
4. [SPIMOE: Exploiting Hybrid Sparsity for Reasoning MoE Inference on Heterogeneous PIM Architectures](/202610/01/2609.34612v1-spimoe-exploiting-hybrid-sparsity-for-reasoning-moe-inference-on-heterogeneous-pim-architectures)  
   标签：评分：6.0/10、query:pic
   evidence：面向长推理MoE的物理KV缓存淘汰与稀疏注意力加速


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
