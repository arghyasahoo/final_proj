# Twitter Sentiment Analysis with GNN

- Colab Notebook: https://colab.research.google.com/drive/134F5mplNblAZhYLu06emr0GRXTbCGn0-?usp=sharing
- Base Repo: https://github.com/pangsg/DM-GCN
- Glove Word Embedding: https://www.kaggle.com/datasets/takuok/glove840b300dtxt
- Dataset: https://github.com/songyouwei/ABSA-PyTorch/tree/master/datasets/acl-14-short-data
- Potential GNN from Scratch: https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/tutorial7/GNN_overview.html

### Changes
Change paths in line 93 and 110; remove `'/home/yanzehao/'+`

## Results
- test_loss: 18.637226104736328
- test_acc: 72.24431818181819
- f1_score: 0.6996091418460807

### Dataset Citation
@inproceedings{dong2014adaptive,
 title={Adaptive recursive neural network for target-dependent twitter sentiment classification},
 author={Dong, Li and Wei, Furu and Tan, Chuanqi and Tang, Duyu and Zhou, Ming and Xu, Ke},
 booktitle={Proceedings of the 52nd annual meeting of the association for computational linguistics (volume 2: Short papers)},
 pages={49--54},
 year={2014}
}
