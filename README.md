# 🦜 Mockingjay
## Our Implementation is now moved into the new repo: [The S3PRL project](https://github.com/s3prl/s3prl)

---
* **IMPORTANT: Codes are now moved into the new open source project:** [S3PRL: Self-Supervised-Speech-Pretraining-and-Representation-Learning](https://github.com/s3prl/s3prl)
---
* Mockingjay, a self-supervised algorithm for learning speech representations, first introduced and described in the paper ["Mockingjay: Unsupervised Speech Representation Learning with Deep Bidirectional Transformer Encoders"](https://arxiv.org/abs/1910.12638), which is accepted as a Lecture session in [ICASSP 2020](https://2020.ieeeicassp.org/).
* Codes are now incoporated into the new project repo: https://github.com/s3prl/s3prl
* We compare our speech representations with the [APC](https://arxiv.org/abs/1904.03240) and [CPC](https://arxiv.org/abs/1807.03748) approach, evaluating on 3 downstream tasks including: phone classification, speaker recognition, and sentiment classification on spoken content.
* Feel free to use or modify them, any bug report or improvement suggestion will be appreciated. If you have any questions, please contact tingweiandyliu@gmail.com. If you find this project helpful for your research, please do consider to [cite this paper](#Citation), thanks!
* Below we illustrate the proposed Masked Acoustic Model pre-training task, where 15% of input the frames are masked to zero at random during training. Which is reminiscent of the Masked Language Model task of [BERT](https://arxiv.org/abs/1810.04805)-style pre-training from the NLP ccommunity.
<img src="https://github.com/s3prl/s3prl/blob/master/file/training.png">

## Citation
```
@article{Liu_2020,
   title={Mockingjay: Unsupervised Speech Representation Learning with Deep Bidirectional Transformer Encoders},
   ISBN={9781509066315},
   url={http://dx.doi.org/10.1109/ICASSP40776.2020.9054458},
   DOI={10.1109/icassp40776.2020.9054458},
   journal={ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
   publisher={IEEE},
   author={Liu, Andy T. and Yang, Shu-wen and Chi, Po-Han and Hsu, Po-chun and Lee, Hung-yi},
   year={2020},
   month={May}
}
```
