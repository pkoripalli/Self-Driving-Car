# Self Driving Car

A TensorFlow implementation of this [Nvidia paper](https://arxiv.org/pdf/1604.07316.pdf) with some changes.

### How to Use
Download the [dataset](https://drive.google.com/file/d/0B-KJCaaF7elleG1RbzVPZWV4Tlk/view) and extract into the repository folder Size: 25 minutes = 256030 = 45,000 images ~ 2.3 GB

Use `python train.py` to train the model

Use `python run_dataset.py` to run the model on the dataset

To visualize training using Tensorboard use tensorboard --logdir=./logs, then open http://0.0.0.0:6006/ into your web browser.

### Demo

![](self_driving_car_gif.gif)

* Credits: https://github.com/SullyChen/Autopilot-TensorFlow

* Research paper: End to End Learning for Self-Driving Cars by Nvidia. [https://arxiv.org/pdf/1604.07316.pdf]

* NVidia dataset: 72 hrs of video => 726060*30 = 7,776,000 images

* Nvidia blog: https://devblogs.nvidia.com/deep-learning-self-driving-cars/

#### If you want to try on a slightly large dataset: 70 minutes of data ~ 223GB

* Refer: https://medium.com/udacity/open-sourcing-223gb-of-mountain-view-driving-data-f6b5593fbfa5
* Youtube:https://www.youtube.com/watch?v=qhUvQiKec2U
* Further reading and extensions: https://medium.com/udacity/teaching-a-machine-to-steer-a-car-d73217f2492c
* More data: https://medium.com/udacity/open-sourcing-223gb-of-mountain-view-driving-data-f6b5593fbfa5
