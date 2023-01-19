# **AnANet**: *Association and Alignment Network for Modeling Implicit Relevance in Cross-modal Correlation Classification*

This code is part of the paper: _Association and Alignment Network for Modeling Implicit Relevance in Cross-modal Correlation Classification_ published at IEEE Transactions on Multimedia. [[PDF]](https://ieeexplore.ieee.org/document/9991062)

## Dataset
In this paper, we expand the image-text pair dataset constructed by [Vempala
](https://aclanthology.org/P19-1272.pdf) and use Twitter as our data source to collect more image-text pairs, getting a larger scale Cross-modal Correlation Dataset, namely CCD ([Download](https://pan.baidu.com/s/1Lac2jglMEd2bAx6qssliaA), extract code: uw46). We classify the types of image-text pairs into explicitly relevant, implicitly relevant and irrelevant. We randomly divide this dataset into the training set, development set, and test set. 
```
/train_data.csv includes training set,
/dev_data.csv includes the development set,
/test_data.csv includes test set,
/image.zip includes all supporting images
```
The detailed statistics are as follows.
|  Types   |  Train  |  Dev  |  Test |  All  |
| :-------:| :-----: | :-----: | :-----: | :-----: |
| Explicitly Relevant | 5779 | 542 | 558 | 6879 |
| Implicitly Relevant | 1070 | 110 | 106 | 1286 |
| Irrelevant | 3445 | 323 | 319 | 4087 |
| All | 10294 | 975 | 983 | 12252 |

## Citation

> ```
>@ARTICLE{9991062,
>  author={Xu, Nan and Wang, Junyan and Tian, Yuan and Zhang, Ruike and Mao, Wenji},
>  journal={IEEE Transactions on Multimedia}, 
>  title={AnANet: Association and Alignment Network for Modeling Implicit Relevance in Cross-modal Correlation Classification}, 
>  year={2022},
>  volume={},
>  number={},
>  pages={1-13},
>  doi={10.1109/TMM.2022.3229960}}
> ```

## Copyright
The copyright of this dataset belongs to the authors, and the dataset is only used for research purposes. Display, reproduction, transmission, distribution or publication of this dataset is prohibited.