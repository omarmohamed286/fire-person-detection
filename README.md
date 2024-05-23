## fire-person-detection

In this project I fine tuned yolov8 for fire and person detection, I've trained a model for fire detection in my repo "fire-detection-yolov8", but in one sample I got this result:

![Screenshot_3](https://github.com/omarmohamed286/fire-person-detection/assets/125928590/1debcdb7-5164-406b-88a5-e3a34aa992fe)

The model was kinda racist and predicted the person's face and hands as fire, and the problem happened because the data had no negative samples with no fire.

so in this repo I trained another model with people and fire so the model can recognize both and this was the inference on the same image:

![man_and_fire_2](https://github.com/omarmohamed286/fire-person-detection/assets/125928590/1a507ae6-dcfa-47ec-8850-1462794cd308)

I've used kaggle in this project and leveraged kaggle's GPU Tesla 4 2x and used the two gpu instances for training which gave a reasonable training time.
