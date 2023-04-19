# LVP-M3
EMNLP 2022 "LVP-M3 : Language-aware Visual Prompt for Multilingual Multimodal Machine Translation"

### Dataset

1. Download M3_Multi30K and M3_M3_AmbigCaps text data

   Multilingual text data can be [downloaded from Google Drive] (https://drive.google.com/drive/folders/11U-KL8_R7t9DrC5w4FU7q3q1i8fJ1ZjR?usp=share_link) extended from the repo [Multi30k](https://github.com/multi30k/dataset) and the repo [vision-matters-when-it-should](https://github.com/jiaodali/vision-matters-when-it-should).

2. Download image data

   Images can be download from the repo [Multi30k](https://github.com/multi30k/dataset) and the repo [vision-matters-when-it-should](https://github.com/jiaodali/vision-matters-when-it-should).


3. Visual features extraction

Given the image, we extract the feature by [CLIP](https://github.com/openai/CLIP). This repo provides the API for image encoding.

### Code
Our implement is based on [fairseq](https://github.com/facebookresearch/fairseq). The complete code is coming soon.


### Reference

Please kindly cite this paper in your publications if it helps your research:

```
@inproceedings{guo-etal-2022-lvp,
    title = "{LVP}-{M}3: Language-aware Visual Prompt for Multilingual Multimodal Machine Translation",
    author = "Guo, Hongcheng  and
      Liu, Jiaheng  and
      Huang, Haoyang  and
      Yang, Jian  and
      Li, Zhoujun  and
      Zhang, Dongdong  and
      Cui, Zheng",
    booktitle = "Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing",
    year = "2022",
    url = "https://aclanthology.org/2022.emnlp-main.184",
    pages = "2862--2872",
}
```

