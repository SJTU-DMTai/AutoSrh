## AutoSrh: An Embedding Dimensionality  Search Framework for Tabular Data Prediction

This repository is the official implementation of our TKDE paper: "AutoSrh: An Embedding Dimensionality  Search Framework for Tabular Data Prediction"
This paper proposes a novel end-to-end embedding dimensionality search framework named AutoSrh, which searches for mixed features embedding dimensions in a differentiable manner through gradient descent.
The key idea of AutoSrh is the adaptive dimensionality search process which introduces a soft selection layer that controls the significance of each embedding dimension and optimizes the parameters according to model’s validation performance. AutoSrh further
employs a fine-grained pruning procedure to produce a flexible mixed embedding dimension scheme for different features and performs model retraining to improve the predictive performance. AutoSrh is model-agnostic, which can be applied to various architectures of deep learningbased
models for tabular data prediction.



#### Paper Citation

```
@ARTICLE{9807387,
  author={Kong, Shuming and Cheng, Weiyu and Shen, Yanyan and Huang, Linpeng},
  journal={IEEE Transactions on Knowledge and Data Engineering}, 
  title={AutoSrh: An Embedding Dimensionality Search Framework for Tabular Data Prediction}, 
  year={2023},
  volume={35},
  number={7},
  pages={6673-6686},
  keywords={Predictive models;Data models;Deep learning;Costs;Analytical models;Training;Numerical models;Embedding dimensionality search;representation learning;tabular data prediction},
  doi={10.1109/TKDE.2022.3186387}}
```

