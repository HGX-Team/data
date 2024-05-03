# Citation_dm 

We use two citation hypergraphs, citation-data mining and citation-software,
which we create from pairwise citation networks, as suggested by Yadati et  al. Nodes are the authors of publications. Assume that a paper A, which is coauthored by {v1, v2, v3}, cited another paper B, which is co-authored by {v4, v5}.
Then, this citation leads to a hyperarc where the head set is {v4, v5} and the tail set is
{v1, v2, v3}. As pairwise citation networks, we use subsets of a DBLP citation dataset
(Sinha et al. 2015). The subsets consist of papers published in the venues of data mining and software engineering, respectively.
In addition, we flter out all papers
co-authored by more than 10 authors to minimize the impact of such outliers.

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

@inproceedings{yadati2021graph,
  title={Graph neural networks for soft semi-supervised learning on hypergraphs},
  author={Yadati, Naganand and Gao, Tingran and Asoodeh, Shahab and Talukdar, Partha and Louis, Anand},
  booktitle={Pacific-Asia Conference on Knowledge Discovery and Data Mining},
  pages={447--458},
  year={2021},
  organization={Springer}
}

@inproceedings{sinha2015overview,
  title={An overview of microsoft academic service (mas) and applications},
  author={Sinha, Arnab and Shen, Zhihong and Song, Yang and Ma, Hao and Eide, Darrin and Hsu, Bo-June and Wang, Kuansan},
  booktitle={Proceedings of the 24th international conference on world wide web},
  pages={243--246},
  year={2015}
}
```
