<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-19
- 运行时间：2026-06-19 21:32:04 UTC
- 运行状态：成功
- 本次总论文数：6
- 精读区：3
- 速读区：3

### 今日简报（AI）
今日日报聚焦KV缓存优化与LLM系统效率，共6篇论文。  
最值得看的两篇精读分别提出基于CXL互连的稀疏注意力KV缓存分离系统（SAC）和面向上下文密集型代理的4-bit KV缓存量化（UltraQuant），均获9/10高分。  
建议普通读者优先关注KV缓存压缩与硬件协同设计方向，这对降低LLM推理成本有直接帮助。
- 详情：[/202606/19/README](/202606/19/README)

### 精读区论文标签
1. [SAC: Disaggregated KV Cache System for Sparse Attention LLMs with CXL](/202606/19/2606.19746v1-sac-disaggregated-kv-cache-system-for-sparse-attention-llms-with-cxl)  
   标签：评分：9.0/10、query:pic
   evidence：面向稀疏注意力LLM的KV缓存系统
2. [UltraQuant: 4-bit KV Caching for Context-Heavy Agents](/202606/19/2606.20474v1-ultraquant-4-bit-kv-caching-for-context-heavy-agents)  
   标签：评分：9.0/10、query:pic
   evidence：面向重上下文智能体的4位KV缓存，直接解决KV缓存复用
3. [CacheWeaver: Cache-Aware Evidence Ordering for Efficient Grounded RAG Inference](/202606/19/2606.19667v1-cacheweaver-cache-aware-evidence-ordering-for-efficient-grounded-rag-inference)  
   标签：评分：8.0/10、query:pic
   evidence：缓存感知的证据排序以提高RAG中前缀缓存重用

### 速读区论文标签
1. [ReMP: Low-Downtime Runtime Model-Parallelism Reconfiguration for LLM Serving](/202606/19/2606.18741v1-remp-low-downtime-runtime-model-parallelism-reconfiguration-for-llm-serving)  
   标签：评分：6.0/10、query:pic
   evidence：处理并行重配置中的KV缓存丢失
2. [PACMS: Submodular Context Selection as a Pluggable Engine for LLM Agents](/202606/19/2606.20047v1-pacms-submodular-context-selection-as-a-pluggable-engine-for-llm-agents)  
   标签：评分：6.0/10、query:pic
   evidence：面向LLM智能体的子模上下文选择，与上下文缓存相关
3. [Execution-State Capsules: Graph-Bound Execution-State Checkpoint and Restore for Low-Latency, Small-Batch, On-Device Physical-AI Serving](/202606/19/2606.20537v1-execution-state-capsules-graph-bound-execution-state-checkpoint-and-restore-for-low-latency-small-batch-on-device-physical-ai-serving)  
   标签：评分：6.0/10、query:pic
   evidence：讨论KV缓存前缀重用的局限性，提出执行状态胶囊作为完整状态检查点


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
