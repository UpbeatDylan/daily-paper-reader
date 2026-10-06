<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-10-06
- 运行时间：2026-10-06 00:42:11 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：2
- 速读区：5

### 今日简报（AI）
今天汇总7篇LLM推理优化工作，精读2篇、速读5篇，主线集中在KV缓存复用、修复与压缩。

最值得看的是9.0分的《Budgeted Cache Repair for Cross-Context KV-Cache Reuse》和8.0分的《KV$^2$: A Self-Refining KV Cache》，分别指向跨上下文复用修复与自精炼缓存。

普通读者可优先关注KV缓存复用/压缩在长上下文和多轮推理中的落地效果与成本收益。
- 详情：[/202610/06/README](/202610/06/README)

### 精读区论文标签
1. [Budgeted Cache Repair for Cross-Context KV-Cache Reuse](/202610/06/2610.02233v1-budgeted-cache-repair-for-cross-context-kv-cache-reuse)  
   标签：评分：9.0/10、query:pic
   evidence：跨上下文KV缓存复用与选择性重算
2. [KV$^2$: A Self-Refining KV Cache](/202610/06/2610.03198v1-kv2-a-self-refining-kv-cache)  
   标签：评分：8.0/10、query:pic
   evidence：可复用预填充场景的查询无关KV压缩

### 速读区论文标签
1. [iS-KV: Online Low-Rank KV Cache Compression via Block-Incremental SVD](/202610/06/2610.02815v1-is-kv-online-low-rank-kv-cache-compression-via-block-incremental-svd)  
   标签：评分：7.0/10、query:pic
   evidence：面向长解码的在线低秩KV缓存压缩
2. [Vosti: Specifying, Implementing, and Verifying Deterministic LLM Inference](/202610/06/2609.38981v1-vosti-specifying-implementing-and-verifying-deterministic-llm-inference)  
   标签：评分：6.0/10、query:pic
   evidence：面向含KV缓存复用、驱逐与重计算的确定性LLM推理规约
3. [SlimKV: Joint Token-Feature KV Cache Compression with Reconstruction-Free Beacon Attention](/202610/06/2610.02953v1-slimkv-joint-token-feature-kv-cache-compression-with-reconstruction-free-beacon-attention)  
   标签：评分：6.0/10、query:pic
   evidence：面向长上下文服务的令牌-特征联合KV缓存压缩
4. [Tailoring the Quantization Space for 1-Bit KV Cache Compression](/202610/06/2610.03027v1-tailoring-the-quantization-space-for-1-bit-kv-cache-compression)  
   标签：评分：6.0/10、query:pic
   evidence：缓解长上下文推理内存瓶颈的1比特KV缓存压缩
5. [Page-EntroKV: Hardware-Aligned, Entropy-Weighted KV-Cache Eviction under Grouped-Query Attention](/202610/06/2610.03135v1-page-entrokv-hardware-aligned-entropy-weighted-kv-cache-eviction-under-grouped-query-attention)  
   标签：评分：6.0/10、query:pic
   evidence：面向长上下文自回归服务的KV缓存驱逐框架


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
