<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-02
- 运行时间：2026-07-02 21:38:43 UTC
- 运行状态：成功
- 本次总论文数：4
- 精读区：3
- 速读区：1

### 今日简报（AI）
今天重点关注长上下文LLM服务中的KV缓存优化，精读两篇高分方案并速读一篇经典缓存失效分析。  
最值得关注MosaicKV的动态双层KV缓存压缩（9.0分）和PersistentKV的页面感知解码调度（8.0分），两者分别从压缩与调度角度破解长序列显存瓶颈。  
建议优先精读这两篇，理解其设计差异后，可在实际部署中尝试组合优化，并留意语义缓存替换策略的启发。
- 详情：[/202607/02/README](/202607/02/README)

### 精读区论文标签
1. [MosaicKV: Serving Long-Context LLM with Dynamic Two-D KV Cache Compression](/202607/02/2607.00760v1-mosaickv-serving-long-context-llm-with-dynamic-two-d-kv-cache-compression)  
   标签：评分：9.0/10、query:pic
   evidence：面向长上下文LLM服务的动态二维KV缓存压缩
2. [PersistentKV: Page-Aware Decode Scheduling for Long-Context LLM Serving on Commodity GPUs](/202607/02/2606.26666v2-persistentkv-page-aware-decode-scheduling-for-long-context-llm-serving-on-commodity-gpus)  
   标签：评分：8.0/10、query:pic
   evidence：长上下文服务中的KV缓存移动优化
3. [GSRQ: Gain-Shape Residual Quantization for Sub-1-bit KV Cache](/202607/02/2607.01065v1-gsrq-gain-shape-residual-quantization-for-sub-1-bit-kv-cache)  
   标签：评分：8.0/10、query:pic
   evidence：使用增益形状残差量化实现亚1比特KV缓存压缩，用于长上下文LLM推理

### 速读区论文标签
1. [When Classic Cache Policies Fail: Learning-Augmented Replacement for Semantic Retrieval Buffers](/202607/02/2607.00394v1-when-classic-cache-policies-fail-learning-augmented-replacement-for-semantic-retrieval-buffers)  
   标签：评分：7.0/10、query:pic
   evidence：LLM智能体的语义缓存替换策略


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
