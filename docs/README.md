<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-11
- 运行时间：2026-08-11 21:30:04 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：5
- 速读区：2

### 今日简报（AI）
今日共读7篇论文，精读5篇、速读2篇，核心聚焦KV Cache压缩与推理优化。

最值得精读的是《SPECTRA》（9.0分）通过谱变换编码突破2-bit压缩极限，以及《OasisKV》（9.0分）用前瞻稀疏预取将解码KV Cache扩展到HBM之外。

建议优先关注这两篇的联合思路：压缩极限与访问带宽解耦，或将成为长上下文推理的关键突破口。
- 详情：[/202608/11/README](/202608/11/README)

### 精读区论文标签
1. [SPECTRA: Pushing the KV Cache Beyond the 2-Bit Cliff via Spectral Transform Coding](/202608/11/2608.07915v1-spectra-pushing-the-kv-cache-beyond-the-2-bit-cliff-via-spectral-transform-coding)  
   标签：评分：9.0/10、query:pic
   evidence：利用谱变换编码压缩KV缓存以加速长上下文LLM推理
2. [OasisKV: Scaling In-Decode KV Cache Beyond HBM with Lookahead Sparse Prefetching](/202608/11/2608.08097v1-oasiskv-scaling-in-decode-kv-cache-beyond-hbm-with-lookahead-sparse-prefetching)  
   标签：评分：9.0/10、query:pic
   evidence：通过稀疏预取将KV缓存扩展到HBM之外以支持长上下文LLM解码
3. [RippleKV: Cross-Layer KV Cache Allocation via Perturbation Propagation](/202608/11/2608.08684v1-ripplekv-cross-layer-kv-cache-allocation-via-perturbation-propagation)  
   标签：评分：9.0/10、query:pic
   evidence：通过扰动传播进行跨层KV缓存分配
4. [DistillCache: KL-Guided Adaptive KV-Cache Eviction for Memory-Efficient LLM Inference](/202608/11/2608.08878v1-distillcache-kl-guided-adaptive-kv-cache-eviction-for-memory-efficient-llm-inference)  
   标签：评分：9.0/10、query:pic
   evidence：基于强化学习的自适应KV缓存驱逐以保留预测影响力
5. [LiveMem: Maintaining Memory State Continuity in Long-Running LLM Inference](/202608/11/2608.02515v2-livemem-maintaining-memory-state-continuity-in-long-running-llm-inference)  
   标签：评分：8.0/10、query:pic
   evidence：提出生命周期独立于活动上下文的固定容量记忆状态，在有限KV窗口下保持长程状态连续性，与位置无关持久化思想一致

### 速读区论文标签
1. [CommitKV: Lifecycle-Aware KV Cache Compression via Commit Transitions for Multi-Turn Agents](/202608/11/2608.07855v1-commitkv-lifecycle-aware-kv-cache-compression-via-commit-transitions-for-multi-turn-agents)  
   标签：评分：7.0/10、query:pic
   evidence：面向多轮Agent的KV缓存压缩，通过提交转变识别生命周期，减少长轨迹推理开销
2. [VoxZip: Semantic-Anchored Temporal KV Cache Compression for Long-Context Audio Inference](/202608/11/2608.08569v1-voxzip-semantic-anchored-temporal-kv-cache-compression-for-long-context-audio-inference)  
   标签：评分：6.0/10、query:pic
   evidence：针对长上下文音频推理的KV缓存压缩，以降低缓存内存开销


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
