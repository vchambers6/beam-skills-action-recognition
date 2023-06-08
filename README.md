# Beam Skills Action Recognition
This is my final project for the MIT 6.8300 Advances in Computer Vision. This project uses deep learning to perform action recognition to classify gymnastics balance beam skills. 

## Project overview
I created a dataset of 10 different skills on the balance beam apparatus, and I collected 100 different videos of gymnastics performing each skill, resulting in 1000 total videos. I then pre-processed the data by extracting keypoint sequences for each skill using OpenPose. This repository includes the jupyter notebook I used that loads OpenPose and can be used to get keypoints. 
I then built a reccurant neural network, using LSTM and attention layers to learn to classify the different keypoint sequences. 

## Running the Project
The OpenPose notebook is only necessary if you are seeking to run the model on a new video that has not had its pose estimated. Otherwise, the only relevant files are keypoint_sequences_ordered.txt and BeamNet10.ipynb. Download and load these two files into your Jupyter notebook editor. 
### Training the model 
Skip to this cell if successfully downloaded keypoint_sequences_ordered.txt and BeamNet10.ipynb. Run the subsequent cells. 
<img width="802" alt="Screen Shot 2023-06-08 at 5 20 27 PM" src="https://github.com/vchambers6/beam-skills-action-recognition/assets/35242014/fecfe922-456a-4b0b-af71-166299dbd338">
