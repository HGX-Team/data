# Bitcoin_2014 HYPERTEXT

We use three bitcoin transaction hypergraphs, bitcoin-2014, bitcoin-2015, and bitcoin-2016. The original datasets are provided by Wu et al. (2021), and they contain frst 1,500,000 transactions in 11/2014, 06/2015, and 01/2016, respectively. 
We model each account as a node, and we model each transaction as a hyperarc. As
multiple accounts can be involved in a single transaction, the accounts from which
the coins are sent compose the tail set, and the accounts to which the coins sent
compose the head set. We remove all transactions where the head set and the tail set
are exactly the same

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

@article{wu2021detecting,
  title={Detecting mixing services via mining bitcoin transaction network with hybrid motifs},
  author={Wu, Jiajing and Liu, Jieli and Chen, Weili and Huang, Huawei and Zheng, Zibin and Zhang, Yan},
  journal={IEEE Transactions on Systems, Man, and Cybernetics: Systems},
  volume={52},
  number={4},
  pages={2237--2249},
  year={2021},
  publisher={IEEE}
}
```
