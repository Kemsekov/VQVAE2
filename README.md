This project contains implementation of vector-quantized autoencoder with exponential-moving average for codebook update and rotation trick for vector restoration.
![image](https://github.com/user-attachments/assets/f3dffff7-f033-4b4d-83d1-df31d9a356bb)

To train model see `train.ipynb` notebook. You only need to change path to images folder. In it.
To see how to get latents/code indices see `eval.ipynb` codebook.

The provided model weights are pretrained on diverse dataset with medical, animals, furniture, flowers, buildings, clothes images.
It achieved 0.977 r2 score on test set. Resulting model can be used to discretize continious domain of images.

![image](https://github.com/user-attachments/assets/9c315f6c-725d-4bae-8f95-20523c376c8f)
![image](https://github.com/user-attachments/assets/4422d28b-f083-4166-8663-fdd6ffee4cd5)


![image](https://github.com/user-attachments/assets/d8a3da8a-e1dc-4974-8a48-04fc3f797d3b)
![image](https://github.com/user-attachments/assets/4d3aa1d3-25bc-4c4e-9c65-1fd89277df03)
