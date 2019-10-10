# LTR-DG

Data and code used for paper "Distractor Generation for Multiple Choice Questions Using Learning to Rank" (Liang, BEA'18). 

## Dataset
Datasets can be found under "data".

## Code
To be updated.

# Data Preparation

1. Download [glove.840B.300d.txt](https://nlp.stanford.edu/projects/glove/) to folder `data_embeddings`

2. Convert json format data to txt format data

```
./dataConvertDistractor.sh
```

# Train and Test
```
./train_distractor.sh
```
```
./test_distractor.sh
```

# Credits
We thank the Wang et al. 2017 for their [IRGAN implementation](https://github.com/geek-ai/irgan).

## Reference
```
@inproceedings{Liang2018distractor,
  author = {Liang, Chen and
            Yang, Xiao and
            Dave, Neisarg and
            Wham, Drew and
            Pursel, Bart and
            Giles, C. Lee},
  title={Distractor Generation for Multiple Choice Questions Using Learning to Rank},
  booktitle = {Proceedings of the 13th Workshop on Innovative Use of NLP for Building Educational Applications, BEA@NAACL},
  pages={284--290},
  year={2018},
  organization={ACL}
}
```
