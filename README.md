## Constrained Decoding for Neural NLG from Compositional Representations in Task-Oriented Dialogue

Code and dataset supporting the paper:

Anusha Balakrishnan, Jinfeng Rao, Kartikeya Upasani, Michael White and Rajen Subba. [Constrained Decoding for Neural NLG from Compositional Representations in Task-Oriented Dialogue](https://arxiv.org/abs/1906.07220). To appear in *Proc. ACL-19*.

If you find this code or dataset useful in your research, please consider citing our paper.

## Reference

```
@InProceedings{Balakrishnan2019constrainednlg,
author = {Anusha Balakrishnan and Jinfeng Rao and Kartikeya Upasani and Michael White and Rajen Subba},
title = {Constrained Decoding for Neural {NLG} from Compositional Representations in Task-Oriented Dialogue},
booktitle = {Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics},
month = {July},
year = {2019},
note = {To appear}
}
```

## Data
Our dataset contains ~31K examples of complex natural language responses in the **weather** domain, and ~51k examples from the **[E2E challenge](https://github.com/tuetschek/e2e-dataset)**, both for English. Each response was collected by providing annotators, who are native English speakers, with a *user query*, a *compositional meaning representation* (with discourse relations and dialog acts), and a *context*. Currently *context* is not provided yet but we will release soon. All of these are made available in our dataset. See our linked paper for more details.

#### Data Statistics

Dataset  |  Train |  Val  |  Test  |  Disc_Test  
---------|--------|-------|--------|-----------
Weather  | 25390  |  3078 |  3121  |  454        
E2E      | 42061  |  4672 |  4693  |  230        

`Disc_Test` is a more challenging subset of our test set that contains discourse relations, which is also the subset we report results in `Disc` column in Table 7 in our paper. Note that there are some minor differences of data statistics to our paper, please use the statistics above.

#### We are currently preparing code for release, and plan to add it to this repository as soon as possible. Stay tuned for updates!
