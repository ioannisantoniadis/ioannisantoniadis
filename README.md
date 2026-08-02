# About me

I'm **trying to optimize** a notoriously **complex loss function**, navigating a **high-dimensional, non-convex** landscape—**one small step at a time**. Probably, so are you!

**My learnings from this winding journey:**

- **Choose your objective with caution**—you drift toward whatever you optimize.
- **Curate what you train on**—you learn from what you keep feeding yourself.
- **Set the pace**—bold enough to move, small enough not to overshoot.
- **Favour signal over noise**—small, informative steps beat thrashing.
- **Rein in the extremes**—when gradients explode, nobody benefits.
- **Beware tunnel vision** (overfitting)—a little **regularization** keeps you adaptable.
- **Use momentum**—keep going; let earlier progress carry you through flat stretches.

## Education

I hold an **MEng in Electrical and Computer Engineering** (2015, top 3% of my class) from **Aristotle University of Thessaloniki**, Greece, and an **MSc in Artificial Intelligence** (2022, *magna cum laude*) from **KU Leuven**, Belgium. I was fortunate to learn from outstanding professors and mentors in **mathematics**, **physics**, **engineering**, and **computer science**.

I have authored two papers:

- [Antoniadis, I., Vercruyssen, V. and Davis, J. (2022). Systematic Evaluation of CASH Search Strategies for Unsupervised Anomaly Detection. Proceedings of the Fourth International Workshop on Learning with Imbalanced Domains: Theory and Applications, in Proceedings of Machine Learning Research 183:8–22.](https://proceedings.mlr.press/v183/antoniadis22a)
- [I. I. Antoniadis, K. C. Chatzidimitriou and A. L. Symeonidis, "Security and Privacy for Smart Meters: A Data-Driven Mapping Study," 2019 IEEE PES Innovative Smart Grid Technologies Europe (ISGT-Europe), Bucharest, Romania, 2019, pp. 1–5, doi: 10.1109/ISGTEurope.2019.8905611.](https://ieeexplore.ieee.org/document/8905611)

## Experience

My professional career started in **2015**, when I joined the [Centre for Research and Technology Hellas (CERTH)](https://www.iti.gr/iti/en/home/) as a **research associate** (Nov 2015–Jul 2016). There, I contributed to an EU-funded H2020 project on cloud computing—when the field was still in its early stages—and worked with a large consortium of European institutions.

I continued as a **software engineer** at [Veltio](https://veltio.com/) (Dec 2016–Jul 2018), an Oracle partner offering supply-chain automation solutions. I worked on real-world, large-scale problems alongside an exceptional team and led the development of data pipelines and systems used by major international retailers, including Sainsbury's in the UK.

I then joined the [Intelligent Systems and Software Engineering Lab (ISSEL)](https://issel.ee.auth.gr/en/13-2/) at the Department of Electrical and Computer Engineering, AUTH, as an **ML research engineer** (Oct 2018–Sep 2021). I was the technical lead on an EU-funded project on energy monitoring and load disaggregation: applied ML research, NLP pipelines (e.g. BERT, topic models), and a high-throughput event streaming engine for real-time smart-meter analytics.

In **September 2022** I joined [Expedia Group](https://www.expediagroup.com/home/default.aspx) in London as a **machine learning scientist**. On the Content & Relevance team I work on large-scale ranking and retrieval—reviews, amenities, and property understanding—using **deep learning**, LLMs, and **multimodal** methods. My recent work has included cross-brand review ranking, semantic relevance and distillation for low-latency embeddings, LLM-as-judge labelling, internal TensorFlow ranking frameworks shared across teams, distributed evaluation tooling, and research on bias, calibration, and data pruning.

<sub>*My first job was in 2011, during my second year at AUTH, as a part-time support representative at OTE, the largest telecommunications company in Greece.</sub>

## What motivates me

I find it exciting to push human boundaries with technology, and I believe we have a responsibility to leave the world better for future generations.

*All it takes is one small step at a time!*

## Selected GitHub repositories

Past **side projects**, **coursework**, and **research code** live in separate repositories. Most of the older ones are **archived** on GitHub (read-only snapshots; not actively maintained) — the algorithm-visualiser portfolio below is the exception: it's active and still growing.

**Algorithm visualisers** (self-directed; from-scratch NumPy implementations, each with an interactive step-by-step Streamlit + Plotly walkthrough — no scikit-learn/PyTorch in the core algorithm)

*Clustering*

- [kmeans-viz](https://github.com/johnantonn/kmeans-viz) — k-means, manual centroid placement  
- [dbscan-viz](https://github.com/johnantonn/dbscan-viz) — DBSCAN density clustering, core/border/noise points  
- [gmm-viz](https://github.com/johnantonn/gmm-viz) — Gaussian mixture models, EM algorithm  

*Dimensionality reduction*

- [pca-viz](https://github.com/johnantonn/pca-viz) — PCA: covariance, eigenvectors, rank-*k* reconstruction  
- [umap-viz](https://github.com/johnantonn/umap-viz) — UMAP: fuzzy simplicial graph + embedding SGD  
- [tsne-viz](https://github.com/johnantonn/tsne-viz) — t-SNE: KL-divergence descent on affinities  

*Classification & ensembles*

- [perceptron-viz](https://github.com/johnantonn/perceptron-viz) — perceptron + SGD/momentum/Adam gradient descent  
- [svm-viz](https://github.com/johnantonn/svm-viz) — soft-margin kernel SVM via SMO  
- [random-forest-viz](https://github.com/johnantonn/random-forest-viz) — bagging, feature subsampling, OOB error  

*Deep learning building blocks*

- [backprop-viz](https://github.com/johnantonn/backprop-viz) — MLP backpropagation, gradient flow  
- [transformer-attention-viz](https://github.com/johnantonn/transformer-attention-viz) — scaled dot-product self-attention, multi-head  

*Generative & self-supervised models*

- [vae-viz](https://github.com/johnantonn/vae-viz) — variational autoencoder, reparameterisation trick  
- [diffusion-viz](https://github.com/johnantonn/diffusion-viz) — DDPM forward/reverse diffusion process  
- [contrastive-learning-viz](https://github.com/johnantonn/contrastive-learning-viz) — SimCLR-style contrastive learning, NT-Xent loss  

*Graph algorithms*

- [dijkstra-viz](https://github.com/johnantonn/dijkstra-viz) — Dijkstra & A* pathfinding on a grid  
- [mst-viz](https://github.com/johnantonn/mst-viz) — minimum spanning tree, Kruskal & Prim  

*Probabilistic methods, state estimation & signal processing*

- [mcmc-viz](https://github.com/johnantonn/mcmc-viz) — Metropolis-Hastings MCMC sampling  
- [kalman-filter-viz](https://github.com/johnantonn/kalman-filter-viz) — Kalman filter predict/update tracking  
- [fft-viz](https://github.com/johnantonn/fft-viz) — Cooley-Tukey FFT, butterfly diagram  

*Reinforcement learning*

- [qlearning-viz](https://github.com/johnantonn/qlearning-viz) — Q-learning vs SARSA on a stochastic grid world  

**Personal notebooks & experiments** (self-directed; not part of a degree curriculum)

- [bias-variance-decomposition](https://github.com/johnantonn/bias-variance-decomposition) — bias–variance decomposition  
- [fair-binary-classification](https://github.com/johnantonn/fair-binary-classification) — fairness on Adult (AIF360)  
- [gaussian-bandits](https://github.com/johnantonn/gaussian-bandits) — multi-armed bandits  
- [example-level-gradient-analysis](https://github.com/johnantonn/example-level-gradient-analysis) — per-example gradients  
- [kepler-exoplanet-prediction](https://github.com/johnantonn/kepler-exoplanet-prediction) — Kepler / KOI classification notebook  
- [sorting](https://github.com/johnantonn/sorting) — Python sorting algorithms, pytest, benchmarks  

**KU Leuven — Master of Artificial Intelligence**

*Coursework*

- [cart](https://github.com/johnantonn/cart) — CART / decision trees  
- [grid-world-mdp](https://github.com/johnantonn/grid-world-mdp) — grid-world MDP, policy iteration  
- [taxi-rides-mapreduce](https://github.com/johnantonn/taxi-rides-mapreduce) — Hadoop MapReduce & Spark taxi analytics  
- [locality-sensitive-hashing](https://github.com/johnantonn/locality-sensitive-hashing) — LSH on Stack Overflow posts  

*Thesis & published research*

- [cash-for-unsupervised-ad](https://github.com/johnantonn/cash-for-unsupervised-ad) — Master’s thesis code extended to the **LIDTA 2022** (ECML/PKDD) paper: CASH / AutoML for unsupervised anomaly detection  

**Aristotle University**

*Diploma thesis*

- [insight-qa](https://github.com/johnantonn/insight-qa) — Semantic question answering (Java, Elasticsearch, LDA)  

*Coursework*

- [pagerank](https://github.com/johnantonn/pagerank), [octree-division](https://github.com/johnantonn/octree-division) — Parallel C (PageRank; octree spatial division)  

## Curriculum vitae

You can find my full CV [here](https://www.dropbox.com/scl/fi/8ivr3wr4eyzgz1rlop83s/iantoniadis_2026.pdf?rlkey=fkofbkvo55g7plw0ni17fajwk&dl=0).

## Contact

You can contact me by [email](mailto:ioannis.antoniadis.uk@gmail.com) or on [LinkedIn](https://www.linkedin.com/in/ioannis-antoniadis/).
