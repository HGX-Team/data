# Metabolic_iaf1260b 

We use two metabolic hypergraphs, iAF1260b and iJO1366, which are provided
by Yadati et al. (2020). They are provided in the form of directed hypergraphs, and
they do not require any pre-processing. We remove one hyperarc from each dataset
since their head set or tail set is abnormally large. Specifcally, the size of their head
sets is greater than 20, while the second largest one is 8. Each node corresponds to
a gene, and each hyperarc indicates a metabolic reaction among them. Specifcally,
a hyperarc e_i indicates that a reaction among the genes in the tail set T_i results in the
genes in the head set H_i.
* [Download]()

When this data is used in published research or for visualization purposes, please cite the following papers:

```
@article{kim2023reciprocity,
  title={Reciprocity in directed hypergraphs: measures, findings, and generators},
  author={Kim, Sunwoo and Choe, Minyoung and Yoo, Jaemin and Shin, Kijung},
  journal={Data Mining and Knowledge Discovery},
  volume={37},
  number={6},
  pages={2330--2388},
  year={2023},
  publisher={Springer}
}

@inproceedings{yadati2020nhp,
  title={Nhp: Neural hypergraph link prediction},
  author={Yadati, Naganand and Nitin, Vikram and Nimishakavi, Madhav and Yadav, Prateek and Louis, Anand and Talukdar, Partha},
  booktitle={Proceedings of the 29th ACM international conference on information \& knowledge management},
  pages={1705--1714},
  year={2020}
}
```
