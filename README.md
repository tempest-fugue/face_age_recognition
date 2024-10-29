# face_age_recognition
Notebook trains on face dataset in order to check if a person is older than 21 for the purpose of buying alcohol.

The folders for the notebook can be found in the accessible google drive folder linked below:
https://drive.google.com/drive/folders/1fsmsIiYdyWvKjV5ZlCBqy_pQzn2xWJ_T?usp=sharing

The faces and labels used to train the notebook are in the link but use too much storage for Github to host. The computer vision model was run with a CPU and using an online GPU platform.

## Conclusions

- The GPU model was able to run with 20 epochs which would have been impractical with mine. My model consistently crashed the Jupyter kernel with 1 epoch while running on a CPU.
- This model would be useful in any situation wherein you need to confirm the age of a customer/user/member.
- This notebook shows the difference between running a computer vision model on a CPU vs. a GPU and how to go about training a model that ensures some level of image recognition.
