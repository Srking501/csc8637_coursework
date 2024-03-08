# CSC8637 Deep Learning

The CycleGAN model is from:-

* https://keras.io/examples/generative/cyclegan/

```bibtex
@inproceedings{CycleGAN2017,
  title={Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks},
  author={Zhu, Jun-Yan and Park, Taesung and Isola, Phillip and Efros, Alexei A},
  booktitle={Computer Vision (ICCV), 2017 IEEE International Conference on},
  year={2017}
}
```

The datasets used:-

For Task 1 CycleGAN:
* UTK Face Cropped: https://www.kaggle.com/datasets/abhikjha/utk-face-cropped
* Inceptionv3: https://www.kaggle.com/code/bmarcos/image-recognition-gender-detection-inceptionv3/data
* Dog Face Dataset: https://images.cv/dataset/dog-face-image-classification-dataset
* Cat Dataset: https://www.kaggle.com/datasets/spandan2/cats-faces-64x64-for-generative-models

For Task 2 Fine-grained image classification:
* https://www.kaggle.com/datasets/seryouxblaster764/fgvc-aircraft/code

For Task 3 is a dataset made by the University:-

The file is a comma separated value (CSV) file with the following columns:
* Date and time of the event
* The event type – either LOGIN or LOGOUT
* The cluster on which the event occurred
* The duration – for a LOGIN this is the number of milli-seconds the user was logged in for, for a LOGOUT this is zero
* The total number of users logged in at that point in time