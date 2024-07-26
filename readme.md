# FInal project: elephants recogniser
Many people cannot recognise the African elephants and the Asian elephants. My project is able to classify the African elephants and the Asian elephants in service today, and help the people who want to classify the diffierent of the elephants to study, do research or do some protecting job. My classification accuacy converged to 52.97% on the test data used; User can take a photo of the elephants they are about to board and upload it to their Jetson Nano to recive rapid classification. 

![af_tr1](https://github.com/user-attachments/assets/e490be70-5d1e-4268-8cbd-8fe29cf6e071)
![as_tr53](https://github.com/user-attachments/assets/0ed11b83-6730-4ee4-801e-1ad5689b233a)


Add short description of project here > 

![add image descrition here](direct image link here)
![image](https://github.com/user-attachments/assets/c43fe7d4-e4e8-475e-b067-293cd12fcd49)

## The Algorithm

Add an explanation of the algorithm and how it works. Make sure to include details about how the code works, what it depends on, and any other relevant info. Add images or other descriptions for your project here. 

Our agorithm works as a classification neural network. We work. We used tranfer learning to retrain the resnet-18 based imagenet classifier. We ran training on over 300 images of each type of aircraft. Over the course of the hour, our test accuary reached 52.97% over 34 epocs. Our model started at 15% accurac. If we were able to run our training for longer, we likely would have reached much higher accurary.
## Running this project

1. Navigate to jetson-inference, and input 'echo 1 | sudo tee /proc/sys/vm/overcommit_memory'
2. input './docker/run.sh'
3. then navigate to python/training/classification
4. set bash environment variable 'NET=/model/elephant
5. input DATASET=data/elephants

[View a video explanation here](video link)
https://youtu.be/0D_EOa8aQ2E
