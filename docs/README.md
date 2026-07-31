<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-31
- 运行时间：2026-07-31 21:41:44 UTC
- 运行状态：成功
- 本次总论文数：8
- 精读区：6
- 速读区：2

### 今日简报（AI）
今日精读6篇、速读2篇，核心聚焦KV缓存优化与投机解码加速。
最值得关注的是《SemPIC》满分10分，提出语义位置无关缓存；《Back from the Future》8分，用反因果意外度管理缓存。
若想快速上手，优先看KV缓存压缩与固定前缀精度控制两篇即可。
- 详情：[/202607/31/README](/202607/31/README)

### 精读区论文标签
1. [SemPIC: Learning Semantic Position-Independent KV Caches](/202607/31/2607.28069v1-sempic-learning-semantic-position-independent-kv-caches)  
   标签：评分：10.0/10、query:pic
   evidence：直接提出SemPIC学习语义位置无关KV缓存
2. [Back from the Future: Key-Value Cache Management by Counter-Causal Surprise](/202607/31/2607.27600v1-back-from-the-future-key-value-cache-management-by-counter-causal-surprise)  
   标签：评分：8.0/10、query:pic
   evidence：提出KV缓存剪枝与逐出方法，降低内存占用同时保持长上下文推理精度
3. [Recall Before You Rank: Similarity-Guided Top-$K$ Reuse for Efficient Long-Context Attention](/202607/31/2607.27692v1-recall-before-you-rank-similarity-guided-top-k-reuse-for-efficient-long-context-attention)  
   标签：评分：8.0/10、query:pic
   evidence：复用历史检索决策避免全量KV缓存打分，加速长上下文动态Top-K注意力
4. [A Sparse Glimpse of the Whole: Train-Free Self-Speculative Decoding](/202607/31/2607.27735v1-a-sparse-glimpse-of-the-whole-train-free-self-speculative-decoding)  
   标签：评分：8.0/10、query:pic
   evidence：利用稀疏可召回KV缓存的免训练自推测解码
5. [SmartGen: Seamless Disaggregated LLM Inference with Selective KV Cache Transfer](/202607/31/2607.28150v1-smartgen-seamless-disaggregated-llm-inference-with-selective-kv-cache-transfer)  
   标签：评分：8.0/10、query:pic
   evidence：面向分离式推理的选择性KV缓存传输
6. [Understanding Is Done Early: A Depth Division of Labor in Large Language Models and Its Use for Unbounded-Context Memory](/202607/31/2607.28263v1-understanding-is-done-early-a-depth-division-of-labor-in-large-language-models-and-its-use-for-unbounded-context-memory)  
   标签：评分：8.0/10、query:pic
   evidence：缓存每个上下文块的残差状态并仅重算上层，使读取成本与存储长度无关

### 速读区论文标签
1. [Stage-Replay Divergence Follows the KV Cache: Fixed-Prefix Precision Controls and Bidirectional Cache Transplantation](/202607/31/2607.28495v1-stage-replay-divergence-follows-the-kv-cache-fixed-prefix-precision-controls-and-bidirectional-cache-transplantation)  
   标签：评分：8.0/10、query:pic
   evidence：研究固定前缀缓存一致性及双向缓存移植，关系前缀缓存与KV缓存重用
2. [Beyond KV Reconstruction: Functional Reconstruction for MLA Draft Models in Speculative Decoding](/202607/31/2607.27269v1-beyond-kv-reconstruction-functional-reconstruction-for-mla-draft-models-in-speculative-decoding)  
   标签：评分：7.0/10、query:pic
   evidence：将MHA/GQA转换为MLA以获得KV缓存效率并加速长上下文推理


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
