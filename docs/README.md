<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-03
- 运行时间：2026-06-03 22:24:47 UTC
- 运行状态：成功
- 本次总论文数：5
- 精读区：4
- 速读区：1

### 今日简报（AI）
今日精读4篇、速读1篇，其中两篇以9.0高分聚焦LLM训练与推理中的共享机制优化。

最值得关注的方向：调度级共享前缀重用（提升RL训练效率）与分段级KV缓存共享（优化交错服务场景内存开销）。

建议优先精读这两篇高分论文，理解其核心方法后，可对比现有缓存策略，尝试在轻量实验中验证性能提升。
- 详情：[/202606/03/README](/202606/03/README)

### 精读区论文标签
1. [Schedule-Level Shared-Prefix Reuse for LLM RL Training](/202606/03/2606.01143v1-schedule-level-shared-prefix-reuse-for-llm-rl-training)  
   标签：评分：9.0/10、query:pic
   evidence：LLM强化学习训练中的共享前缀复用，类似于前缀缓存
2. [SparseX: Efficient Segment-Level KV Cache Sharing for Interleaved LLM Serving](/202606/03/2606.01751v1-sparsex-efficient-segment-level-kv-cache-sharing-for-interleaved-llm-serving)  
   标签：评分：9.0/10、query:pic
   evidence：段级KV缓存共享，处理非前缀重复内容，提升LLM推理复用
3. [NetKV: Network-Aware Decode Instance Selection for Disaggregated LLM Inference](/202606/03/2606.03910v1-netkv-network-aware-decode-instance-selection-for-disaggregated-llm-inference)  
   标签：评分：8.0/10、query:pic
   evidence：解耦推理中网络感知的KV缓存路由
4. [Value-Aware Stochastic KV Cache Eviction for Reasoning Models](/202606/03/2606.03928v1-value-aware-stochastic-kv-cache-eviction-for-reasoning-models)  
   标签：评分：8.0/10、query:pic
   evidence：值感知随机驱逐策略优化推理模型的KV缓存

### 速读区论文标签
1. [Don't Read Everything: A Curvature-Conditioned Query for Linear Attention](/202606/03/2606.01294v1-dont-read-everything-a-curvature-conditioned-query-for-linear-attention)  
   标签：评分：6.0/10、query:pic
   evidence：曲率条件化查询提升线性注意力长上下文检索


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
