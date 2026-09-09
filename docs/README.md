<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-09
- 运行时间：2026-09-09 21:43:15 UTC
- 运行状态：成功
- 本次总论文数：13
- 精读区：6
- 速读区：7

### 今日简报（AI）
今日筛选13篇论文，精读6篇、速读7篇，聚焦大模型注意力控制与KV缓存优化。  
最值得关注的两大方向：语言模型可主动控制自身注意力，以及面向长上下文解码的KV缓存量化/压缩技术（如接口感知量化、自适应压缩）。  
建议普通读者优先关注KV缓存优化类工作，能显著提升长文本推理效率，降低显存成本。
- 详情：[/202609/09/README](/202609/09/README)

### 精读区论文标签
1. [Language Models Can Control Their Own Attention](/202609/09/2609.02737v1-language-models-can-control-their-own-attention)  
   标签：评分：8.0/10、query:pic
   evidence：提出声明式注意力协议，令模型在思维链中声明需关注的上下文位置，避免超长对话逐token读取整个KV缓存
2. [Interface-Aware KV Cache Quantization for Dense On-Chip NVM in Long-Context LLM Decoding](/202609/09/2609.05764v1-interface-aware-kv-cache-quantization-for-dense-on-chip-nvm-in-long-context-llm-decoding)  
   标签：评分：8.0/10、query:pic
   evidence：长上下文解码中面向片上NVM的接口感知KV缓存量化
3. [CONDUIT: A Unified Residual-Stream Restoration Framework for KV Cache Reuse in Vision-Language Models](/202609/09/2609.05821v1-conduit-a-unified-residual-stream-restoration-framework-for-kv-cache-reuse-in-vision-language-models)  
   标签：评分：8.0/10、query:pic
   evidence：在前缀变化时复用视觉前缀KV缓存，用残差流恢复策略刷新陈旧token
4. [Unified AI Gateway: A Framework for Joint Model Routing and KV Cache Management](/202609/09/2609.06940v1-unified-ai-gateway-a-framework-for-joint-model-routing-and-kv-cache-management)  
   标签：评分：8.0/10、query:pic
   evidence：联合模型路由与KV缓存动作选择，在多个大模型间复用或重建缓存
5. [Enabling High-Bandwidth Flash for Generative Recommendation Serving with Write-Aware KV Cache Policy](/202609/09/2609.07175v1-enabling-high-bandwidth-flash-for-generative-recommendation-serving-with-write-aware-kv-cache-policy)  
   标签：评分：8.0/10、query:pic
   evidence：针对生成式推荐中的用户级KV缓存复用，提出写感知的缓存准入淘汰策略以优化推理服务吞吐
6. [CEDAR: Error-Bounded Residual Routing for Efficient Long-Context Attention](/202609/09/2609.07237v1-cedar-error-bounded-residual-routing-for-efficient-long-context-attention)  
   标签：评分：8.0/10、query:pic
   evidence：面向快速长上下文注意力的误差有界残差路由

### 速读区论文标签
1. [MetaKV: Adaptive KV Cache Compression for Constrained LLM Inference](/202609/09/2609.07966v1-metakv-adaptive-kv-cache-compression-for-constrained-llm-inference)  
   标签：评分：8.0/10、query:pic
   evidence：面向长上下文在延迟和内存预算下逐提示词自适应选择KV压缩配置
2. [Jacap: Robust KV Cache Eviction via Jacobian-Based Nonlinear Information Capacity Preservation](/202609/09/2609.08131v1-jacap-robust-kv-cache-eviction-via-jacobian-based-nonlinear-information-capacity-preservation)  
   标签：评分：8.0/10、query:pic
   evidence：用雅可比信息容量目标指导KV缓存驱逐，直接服务长上下文LLM推理中的KV缓存优化
3. [BIO-MEMART: Biometric-Aware KV Cache Memory for Multi-User LLM Agents](/202609/09/2609.08566v1-bio-memart-biometric-aware-kv-cache-memory-for-multi-user-llm-agents)  
   标签：评分：8.0/10、query:pic
   evidence：为可复用KV块附加生物特征模板，在多用户智能体授权范围内执行KV缓存复用
4. [Intra-Prompt Parallel Decoding for Common-Context Question Answering](/202609/09/2609.05707v1-intra-prompt-parallel-decoding-for-common-context-question-answering)  
   标签：评分：7.0/10、query:pic
   evidence：把共享上下文问题合并到单条提示中并行解码，减少公共上下文重复计算与缓存压力
5. [DFlow: Enabling Verifier Information Flow in Block Diffusion Speculative Decoding](/202609/09/2609.06498v1-dflow-enabling-verifier-information-flow-in-block-diffusion-speculative-decoding)  
   标签：评分：7.0/10、query:pic
   evidence：在块扩散投机解码中将被拒绝位置的验证器表示跨轮重用以避免重复计算，体现KV信息复用思想
6. [ECOKV: Geometry-Aware KV Cache Eviction via Complementary Diversity Metrics](/202609/09/2609.06663v1-ecokv-geometry-aware-kv-cache-eviction-via-complementary-diversity-metrics)  
   标签：评分：7.0/10、query:pic
   evidence：提出几何感知复合多样性度量改进多模态大模型的KV缓存驱逐，属于KV缓存优化主题但未涉及位置无关复用
7. [PARSER: Read in Parallel, Reason in Depth for Long-Context LLM Agents](/202609/09/2609.06702v1-parser-read-in-parallel-reason-in-depth-for-long-context-llm-agents)  
   标签：评分：7.0/10、query:pic
   evidence：通过并行分块读取与散射-聚合迭代推理，解耦顺序读取和推理深度，降低长上下文LLM智能体的时延


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
