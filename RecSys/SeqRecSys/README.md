
### Main
* Sequential Recommendation via Stochastic Self-Attention, in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512077). [\[code\]](https://github.com/zfan20/STOSA) :thumbsup: 
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>.  users’ real-world sequential behaviors are uncertain rather than deterministic, posing a significant challenge to present techniques. We further suggest that dot-product-based approaches cannot fully capture collaborative transitivity, which can be derived in **item-item transitions** inside sequences and is beneficial for cold start items. We further argue that BPR loss has no constraint on positive and sampled negative items, which misleads the optimization.
    <strong>Solution</strong>. It embeds each item as a stochastic Gaussian distribution, the covariance of which encodes the uncertainty.
    <strong>Datasets</strong>.  
    <strong>Baselines</strong>. 
    <strong>Future</strong>. 
    <strong>Ins</strong>.
    </details>
 
* Generative Session-based Recommendation, in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512095).
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>. Data sparsity.
    <strong>Solution</strong>. The first adversarial module aims to make the generated samples conform to the underlying patterns of the real user sequential preference (rationality requirement). The second adversarial module is targeted at widening the model experiences by generating samples which can induce larger model losses (informativeness requirement).
    <strong>Datasets</strong>.  
    <strong>Baselines</strong>. 
    <strong>Future</strong>. 
    <strong>Ins</strong>.
    </details>

* Sequential Recommendation with Decomposed Item Feature Routing, in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512101). 
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>. Data Augmentation  
    <strong>Solution</strong>. 
    <strong>Datasets</strong>.  
    <strong>Baselines</strong>. 
    <strong>Future</strong>. 
    <strong>Ins</strong>.
    </details>
    
* Filter-enhanced MLP is All You Need for Sequential Recommendation, in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512111). [\[code\]](https://github.com/RUCAIBox/FMLP-Rec) :thumbsup: 
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>.  
    <strong>Solution</strong>. 
    <strong>Datasets</strong>.  
    <strong>Baselines</strong>. 
    <strong>Future</strong>. 
    <strong>Ins</strong>.
    </details>
    
* Learn over Past, Evolve for Future: Search-based Time-aware Recommendation with Sequential Behavior Data in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512117). [\[code\]](https://github.com/RUCAIBox/FMLP-Rec) :thumbsup: 
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>.  
    <strong>Solution</strong>. 
    <strong>Datasets</strong>.  
    <strong>Baselines</strong>. 
    <strong>Future</strong>. 
    <strong>Ins</strong>.
    </details>    

### Contrastive Learning
* Intent Contrastive Learning for Sequential Recommendation, in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512090).[\[code\]](https://github.com/salesforce/ICLRec) :thumbsup: 
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>.  
    <strong>Solution</strong>. 
    <strong>Datasets</strong>.  
    <strong>Baselines</strong>. 
    <strong>Future</strong>. 
    <strong>Ins</strong>.
    </details>
    
* Disentangling Long and Short-Term Interests for Recommendation, in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512098). [\[code\]](https://github.com/tsinghua-fib-lab/CLSR) :thumbsup: 
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>.  
    <strong>Solution</strong>. 
    <strong>Datasets</strong>.  
    <strong>Baselines</strong>. 
    <strong>Future</strong>. 
    <strong>Ins</strong>.
    </details>
    
### Debias
* Unbiased Sequential Recommendation with Latent Confounders, in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512090). 
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>. the observational data may have been contaminated by the exposure or selection biases, which renders the learned sequential models unreliable. 
    <strong>Solution</strong>. 
    <strong>Datasets</strong>.  
    <strong>Baselines</strong>. 
    <strong>Future</strong>. 
    <strong>Ins</strong>.
    </details>

### Sets2sets
* Element-guided Temporal Graph Representation Learning for Temporal Sets Prediction, in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512064). [\[code\]](https://github.com/yule-BUAA/ETGNN) :thumbsup: 
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>. Recent studies on temporal sets prediction follow the same pipeline that only learns from each user’s own sequence, which fails to discover the collaborative signals among the sequences of **different users**. <strong>Solution</strong>. Element-guided larger graph. <strong>Datasets</strong>. DC, TaoBao, JD, and TMS.   <strong>Baselines</strong>. DNNTSP.
    <strong>Future</strong>. (1) Example-based interpretability? (2) Disentangling. (3) How to revise BasketTR based on this method. (4) DuoRec?
    <strong>Ins</strong>. Their model.
    </details>
    
### Graph
* GSL4Rec: Session-based Recommendations with Collective Graph Structure Learning and Next Interaction Prediction, in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512085).
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>.  
    <strong>Solution</strong>. 
    <strong>Datasets</strong>.  
    <strong>Baselines</strong>. 
    <strong>Future</strong>. 
    <strong>Ins</strong>.
    </details>

### Side Info
* Decoupled Side Information Fusion for Sequential Recommendation, in *SIGIR* 2022. [\[paper\]](https://arxiv.org/abs/2204.11046).
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>.  
    <strong>Solution</strong>. 
    <strong>Datasets</strong>.  
    <strong>Baselines</strong>. 
    <strong>Future</strong>. 
    <strong>Ins</strong>.
    </details>

### NAS
* Towards Automatic Discovering of Deep Hybrid Network Architecture for Sequential Recommendation, in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512066)
