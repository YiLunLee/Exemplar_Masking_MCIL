# Exemplar Masking for Multimodal Incremental Learning
Official PyTorch implementaton of paper "[Exemplar Masking for Multimodal Incremental Learning](https://arxiv.org/abs/2412.09549)".  
You can visit our project website [here](https://yilunlee.github.io/Exemplar_Masking_MCIL/).

## Introduction
Multimodal incremental learning needs to digest the information from multiple modalities while concurrently learning new knowledge without forgetting the previously learned information. There are numerous challenges for this task, mainly including the larger storage size of multimodal data in exemplar-based methods and the computational requirement of finetuning on huge multimodal models. In this paper, we leverage the parameter-efficient tuning scheme to reduce the burden of fine-tuning and propose the exemplar masking framework to efficiently replay old knowledge. Specifically, the non-important tokens are masked based on the attention weights and the correlation across different modalities, significantly reducing the storage size of an exemplar and consequently saving more exemplars under the same memory buffer. Moreover, we design a multimodal data augmentation technique to diversify exemplars for replaying prior knowledge. In experiments, we not only evaluate our method in existing multimodal datasets but also extend the ImageNet-R dataset to a multimodal dataset as a real-world application, where captions are generated by querying multimodal large language models (e.g., InstructBLIP). Extensive experiments show that our exemplar masking framework is more efficient and robust to catastrophic forgetting under the same limited memory buffer.

<div align="center">
  <img src="fig/model.png"/>
</div>


## Usage
To Do
### Enviroment
To Do
#### Prerequisites
To Do
#### Other requirements
```
To Do
```

### Prepare Dataset
To Do


### Evaluation
```
To Do 
```

### Train
To Do

```
To Do

```

## Acknowledgements
This code is based on [ViLT](https://github.com/dandelin/ViLT.git).

## Citation
If you find this work useful for your research, please cite:
```Bibtex
@article{lee2024exemplarmasking,
  title={Exemplar Masking for Multimodal Incremental Learning},
  author={Yi-Lun Lee and Chen-Yu Lee and Wei-Chen Chiu and Yi-Hsuan Tsai},
  journal={arXiv preprint arXiv:2412.09549},
  year={2024}
}
```


<!-- ```Bibtex
@inproceedings{lee2021bmvc,
 title = {Learning to Hide Residual for Boosting Image Compression},
 author = {Yi-Lun Lee and Yen-Chung Chen and Min-Yuan Tseng and Yi-Hsuan Tsai and Wei-Chen Chiu},
 booktitle = {British Machine Vision Conference (BMVC)},
 year = {2021}
}
``` -->

