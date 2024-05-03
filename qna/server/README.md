

# Qna_math

We use two question answering hypergraphs, qna-math and qna-server. We create
directed hypergraphs from the log data of a question answering site, stack exchange,
provided at Archive (2022). Among various domains, we choose math-overfow,
which covers mathematical questions, and server-fault, which treats server related
issues. The original log data contains the posts of the site, and one questioner and
one or more answerers are involved with each post. We ignore all posts without any
answerer. We treat each user as a node, and we treat each post as a hyperarc. For
each hyperarc, the questioner of the corresponding post composes the head set, and
the answerer(s) compose the tail set. Note that every hyperarc in these datasets has a
unit head set.

Data is available here: https://archive.org/details/stackexchange
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

```
