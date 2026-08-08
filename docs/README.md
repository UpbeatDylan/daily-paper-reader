<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-08
- 运行时间：2026-08-08 20:29:46 UTC
- 运行状态：成功
- 本次总论文数：6
- 精读区：2
- 速读区：4

### 今日简报（AI）
今日聚焦KV缓存优化，精读跨模型映射与低秩索引两篇高分论文；最值得关注的是LLM家族间KV缓存迁移的闭式映射方法，以及长上下文检索的SAKI索引；建议普通读者留意KV缓存压缩对推理忠实度的潜在影响。
- 详情：[/202608/08/README](/202608/08/README)

### 精读区论文标签
1. [Cross-Model KV Cache Transfer in LLM Families: A Closed-Form Linear Mapping for Prefill Reuse](/202608/08/2608.03893v1-cross-model-kv-cache-transfer-in-llm-families-a-closed-form-linear-mapping-for-prefill-reuse)  
   标签：评分：9.0/10、query:pic
   evidence：直接提出跨模型KV缓存复用以跳过预填充，与KV缓存复用加速推理需求匹配。
2. [SAKI: Score-Aware Low-Rank Key Indexing for Long-Context KV Retrieval](/202608/08/2608.03228v1-saki-score-aware-low-rank-key-indexing-for-long-context-kv-retrieval)  
   标签：评分：8.0/10、query:pic
   evidence：面向长上下文KV检索的得分感知低秩键索引，直接保留注意力得分

### 速读区论文标签
1. [Relevant but Incomplete: Referential Dangling as a Paradigm-Level Failure Mode in Hard Prompt Compression](/202608/08/2608.04569v1-relevant-but-incomplete-referential-dangling-as-a-paradigm-level-failure-mode-in-hard-prompt-compression)  
   标签：评分：7.0/10、query:pic
   evidence：硬提示压缩在长上下文推理成本中的失效模式
2. [Opt.Gear Technical Report](/202608/08/2608.01034v2-optgear-technical-report)  
   标签：评分：6.0/10、query:pic
   evidence：混合架构结合卷积键值门控混合器与局部-全局注意力以降低KV缓存内存
3. [Does Accuracy Equal Evidence? Reasoning Faithfulness under KV Cache Compression](/202608/08/2608.01631v1-does-accuracy-equal-evidence-reasoning-faithfulness-under-kv-cache-compression)  
   标签：评分：6.0/10、query:pic
   evidence：使用固定轨迹重放协议评估KV缓存压缩方法对推理忠实度的影响
4. [Enhancing Tabular Learners with Context-Aware Semantic Embeddings](/202608/08/2608.03565v1-enhancing-tabular-learners-with-context-aware-semantic-embeddings)  
   标签：评分：6.0/10、query:pic
   evidence：通过预填充和复用Gemma表格语言模型的KV缓存来生成上下文感知的行嵌入


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
