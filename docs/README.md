<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-30
- 运行时间：2026-09-30 23:18:06 UTC
- 运行状态：成功
- 本次总论文数：8
- 精读区：5
- 速读区：3

### 今日简报（AI）
今日筛选 8 篇 LLM 推理优化论文，精读 5 篇、速读 3 篇，主线集中在 KV Cache 的共享、压缩与纠错。

最值得看的是两篇 8.0 分精读：《PReCache》用低秩预计算与中性重构实现多 LoRA Agent 的 KV Cache 共享，《KVCMAS》则为多智能体共享上下文做 KV Cache 纠错，都指向"多 Agent 场景下缓存复用"这一痛点。

普通读者可先读这两篇精读建立整体框架，再扫《When to Evict, Not What to Keep》了解免训练压缩思路，其余速读按需查阅即可。
- 详情：[/202609/30/README](/202609/30/README)

### 精读区论文标签
1. [PReCache: Efficient KV Cache Sharing for Multi-LoRA Agents via Low-Rank Precomputation and Neutral Reconstruction](/202609/30/2609.34054v1-precache-efficient-kv-cache-sharing-for-multi-lora-agents-via-low-rank-precomputation-and-neutral-reconstruction)  
   标签：评分：8.0/10、query:pic
   evidence：面向多LoRA智能体的免训练KV缓存共享与复用
2. [KVCMAS: Efficient KV cache Correction for Shared Context in Multi-Agent Systems](/202609/30/2609.34060v1-kvcmas-efficient-kv-cache-correction-for-shared-context-in-multi-agent-systems)  
   标签：评分：8.0/10、query:pic
   evidence：校正共享上下文KV缓存以避免重复预填充
3. [PulseInfer: I/O-Centric Sparse KV Cache Offloading for Efficient Long-Context LLM Decoding](/202609/30/2609.34555v1-pulseinfer-io-centric-sparse-kv-cache-offloading-for-efficient-long-context-llm-decoding)  
   标签：评分：8.0/10、query:pic
   evidence：面向长上下文解码的I/O中心稀疏KV缓存卸载
4. [TempoKV: Timely Staging of LLM KV Caches for Memory-Semantic Flash](/202609/30/2609.35065v1-tempokv-timely-staging-of-llm-kv-caches-for-memory-semantic-flash)  
   标签：评分：8.0/10、query:pic
   evidence：可复用前缀KV缓存面向内存语义闪存的适时暂存
5. [Cartridges++: KV Cache Compression without Off-Context Derailment](/202609/30/2609.35621v1-cartridges-kv-cache-compression-without-off-context-derailment)  
   标签：评分：8.0/10、query:pic
   evidence：面向长文档重复服务的压缩KV复用

### 速读区论文标签
1. [When to Evict, Not What to Keep: Draft-Guided Eviction for Training-Free KV-Cache Compression](/202609/30/2609.33334v1-when-to-evict-not-what-to-keep-draft-guided-eviction-for-training-free-kv-cache-compression)  
   标签：评分：7.0/10、query:pic
   evidence：免训练KV缓存压缩中由草稿引导的驱逐时机优化
2. [Where Activation Sparsity and KV-Cache Sparsity Cross in LLM Decoding](/202609/30/2609.33889v1-where-activation-sparsity-and-kv-cache-sparsity-cross-in-llm-decoding)  
   标签：评分：6.0/10、query:pic
   evidence：比较激活稀疏与KV缓存稀疏以加速长上下文解码
3. [SlimWise: Decoupling Expert Pruning Across Prefill and Decode for Efficient MoE Serving](/202609/30/2609.34117v1-slimwise-decoupling-expert-pruning-across-prefill-and-decode-for-efficient-moe-serving)  
   标签：评分：6.0/10、query:pic
   evidence：解码阶段复用预填充生成KV缓存的免训练缓存交接


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
