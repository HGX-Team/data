# Email_eu 

We use two email hypergraphs, email-enron and email-eu. We consider each email as a
single hyperarc. Specifcally, the head set is composed of the receiver(s) and cc-ed
user(s), and the tail set is composed of the sender. The Email-eu dataset is from
SNAP (Leskovec and Krevl 2014). The original dataset is a dynamic graph where
each temporal edge from a node u to a node v at time t indicates that u sent an email
to v at time t. The edges with the same source node and timestamp are replaced by
a hyperarc, where the tail set consists only of the source node and the head set is the
set of destination nodes of the edges. Note that every hyperarc in these datasets has a
unit tail set.

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

@article{chodrow2020annotated,
  title={Annotated hypergraphs: models and applications},
  author={Chodrow, Philip and Mellor, Andrew},
  journal={Applied network science},
  volume={5},
  number={1},
  pages={9},
  year={2020},
  publisher={Springer}
}

@book{leskovec2008dynamics,
  title={Dynamics of large networks},
  author={Leskovec, Jurij},
  year={2008},
  publisher={Carnegie Mellon University}
}

```
