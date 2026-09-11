<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-11
- 运行时间：2026-09-11 21:44:05 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：2
- 速读区：5

### 今日简报（AI）
今日日报精读2篇、速读5篇，重点追踪LLM推理中的KV缓存外部化与内存共享。最值得看的是9.0分的《Building py-kvcache》用NVMe SSD为vLLM做外部KV缓存，以及8.0分的《Composable CXL Memory》把CXL内存做成Kubernetes原生共享内存。普通读者可优先从这两篇切入，理解“KV缓存/内存解耦”如何降低长上下文LLM服务成本，再按兴趣看KV淘汰、智能手术室多智能体和预填充分块等速读。
- 详情：[/202609/11/README](/202609/11/README)

### 精读区论文标签
1. [Building py-kvcache: A Performance Characterization of External KV Caching for vLLM with NVMe SSDs](/202609/11/2609.11744v1-building-py-kvcache-a-performance-characterization-of-external-kv-caching-for-vllm-with-nvme-ssds)  
   标签：评分：9.0/10、query:pic
   evidence：面向vLLM的外部前缀KV缓存以降低首token时延
2. [Composable CXL Memory as a Kubernetes-Native Shared Memory for LLM Serving](/202609/11/2609.10790v1-composable-cxl-memory-as-a-kubernetes-native-shared-memory-for-llm-serving)  
   标签：评分：8.0/10、query:pic
   evidence：通过共享CXL内存实现跨节点KV缓存复用与前缀缓存

### 速读区论文标签
1. [ECOKV: Geometry-Aware KV Cache Eviction via Complementary Diversity Metrics](/202609/11/2609.06663v1-ecokv-geometry-aware-kv-cache-eviction-via-complementary-diversity-metrics)  
   标签：评分：7.0/10、query:pic
   evidence：通过KV缓存驱逐降低长上下文推理的内存与计算开销
2. [A Voice-Interactive Multi-Agent System for Smart Operating Rooms: Architecture Design and Key Technologies](/202609/11/2609.11231v1-a-voice-interactive-multi-agent-system-for-smart-operating-rooms-architecture-design-and-key-technologies)  
   标签：评分：7.0/10、query:pic
   evidence：KV缓存前缀预热与字节级最长公共前缀复用降低重计算延迟
3. [Deadline-Aware Adaptive Prefill Chunking for Efficient Large Language Model Serving](/202609/11/2609.07883v1-deadline-aware-adaptive-prefill-chunking-for-efficient-large-language-model-serving)  
   标签：评分：6.0/10、query:pic
   evidence：自适应预填充分块以保障LLM服务逐词延迟
4. [REVA: Reusable Evidence View Aggregation for Context-Efficient RAG Serving](/202609/11/2609.11209v1-reva-reusable-evidence-view-aggregation-for-context-efficient-rag-serving)  
   标签：评分：6.0/10、query:pic
   evidence：可复用证据视图以实现上下文高效RAG服务
5. [PATTON: Enabling Commodity PIM for Production LLM Serving](/202609/11/2609.11392v1-patton-enabling-commodity-pim-for-production-llm-serving)  
   标签：评分：6.0/10、query:pic
   evidence：生产LLM服务中的KV缓存块分配、共享与缓存


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
