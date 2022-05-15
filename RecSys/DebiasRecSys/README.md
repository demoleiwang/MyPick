
### Casual Perspective
* A Model-Agnostic Causal Learning Framework for Recommendation using Search Data, in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/10.1145/3485447.3511951). [\[code\]](https://github.com/Ethan00Si/Instrumental-variables-for-recommendation)
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>. Existing RSs mostly ignored the striking differences between the causal parts and non-causal parts when using these embedding vectors.  <strong>Solution</strong>. They propose a model-agnostic framework named IV4Rec that can effectively **decompose** the embedding vectors into these two parts, hence enhancing recommendation results. Specifically, we **jointly** **consider** users’ behaviors in **search** scenarios and **recommendation** scenarios. <strong>Datasets</strong>. Kuaishou and MIND. <strong>Baselines</strong>. NRHUB and DIN. <strong>Future</strong> N.A <strong>Inspiration</strong> N.A.
    </details>


### Explicit Modeling
* Learning Explicit User Interest **Boundary** for Recommendation, in *WWW* 2022. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3485447.3511971). [\[code\]](https://github.com/JianhuanZhuo/Code-for-UIB-WWW2022) :thumbsup: 
    <details>
    <summary>Summary</summary>
    <strong>Motivation</strong>. Point-wise and pair-wise approaches are hard to explicitly provide a personalized decision boundary to determine if users are interested in items unseen. <strong>Solution</strong>. They propose a boundary to combine point-wise an pair-wise losses. <strong>Datasets</strong>. Amazon Instant Video (AIV), LastFM, Movielens-1M (ML1M) and Movielens-10M (ML10M). <strong>Baselines</strong>. BPR, SML and LightGCN. <strong>Future</strong>?? <strong>Inspiration</strong> Balanced Space?
    </details>
