<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-25
- 运行时间：2026-08-25 20:48:23 UTC
- 运行状态：成功
- 本次总论文数：6
- 精读区：2
- 速读区：4

### 今日简报（AI）
今日聚焦长上下文LLM的KV缓存淘汰与高效推理，精读两篇高相关论文，速读覆盖策略评估、长序列生成及记忆增强推理。最值得关注的是《WnW》提出的动态缓存修剪（9.0分）和《Sigmoid Attention》用注意力替代Softmax提升淘汰鲁棒性（8.0分）。建议从KV缓存策略入手，结合系统对比研究，体验不同工作负载下的实际收益。
- 详情：[/202608/25/README](/202608/25/README)

### 精读区论文标签
1. [WnW: Waxing-and-Waning KV Cache for Long-Form Speech LLMs](/202608/25/2608.22704v1-wnw-waxing-and-waning-kv-cache-for-long-form-speech-llms)  
   标签：评分：9.0/10、query:pic
   evidence：面向长语音LLM的KV缓存头分类与CPU驻留召回，直接涉及KV缓存复用和长上下文效率
2. [Sigmoid Attention as a Better Substrate for Learned KV Cache Eviction](/202608/25/2608.23296v1-sigmoid-attention-as-a-better-substrate-for-learned-kv-cache-eviction)  
   标签：评分：8.0/10、query:pic
   evidence：针对KV缓存淘汰的学习方法，是KV缓存管理的核心优化

### 速读区论文标签
1. [Which Eviction Policy Should an LLM Cache Use? A Systematic Study Across Workloads, Capacities, and Encoders](/202608/25/2608.20280v2-which-eviction-policy-should-an-llm-cache-use-a-systematic-study-across-workloads-capacities-and-encoders)  
   标签：评分：7.0/10、query:pic
   evidence：系统评估LLM语义缓存的淘汰策略，与提示/响应缓存直接相关
2. [ProxyFormer: A Dual-Stream Proxy Architecture for Ultra-Long Context and High-Resolution Generation](/202608/25/2608.23463v1-proxyformer-a-dual-stream-proxy-architecture-for-ultra-long-context-and-high-resolution-generation)  
   标签：评分：7.0/10、query:pic
   evidence：通过代理令牌压缩全局交互，降低超长上下文的KV缓存和注意力开销
3. [Memory Augmentation Unlocks Efficient Chain-of-Thought Reasoning](/202608/25/2608.21265v1-memory-augmentation-unlocks-efficient-chain-of-thought-reasoning)  
   标签：评分：6.0/10、query:pic
   evidence：在预填充阶段检索可复用推理记忆，减少解码生成，降低推理延迟
4. [Benchmarking Composable Compression Techniques in Mixture-of-Experts LLMs](/202608/25/2608.21693v1-benchmarking-composable-compression-techniques-in-mixture-of-experts-llms)  
   标签：评分：6.0/10、query:pic
   evidence：针对MoE LLM长上下文KV缓存压缩等可组合压缩技术进行基准评测，与KV缓存优化相关


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
