# Stryker Hackathon - Final Round

## :gear: Problem Statement 
Tasked with developing deep learning models that can perform the task of segmenting and recognizing the instruments shown in the videos. In each frame, a variety of surgical tools are present (Instruments, Clamps, threads). These tools need to be segmented according to their category along with the tissue appearing in the background.

## :detective: Surgical-Tool-Detector 
-> Built a surgical video segmentation pipeline by fine-tuning Detectron2, a modular framework by Meta AI Research, and Mask-RCNN for 
binary classification and surgical tool recognition. 

-> Developed Pipeline for automated conversion of segmented video frames to quantifiable files and used GPT-3.5 for real-time inferencing.


## :tv: Demo
![Live Demo](https://github.com/Patil-Ojas/Surgical-Tool-Detector/blob/main/demo/demo.gif?raw=true)


## :hourglass_flowing_sand: Workflow 
![image](https://github.com/Patil-Ojas/Surgical-Tool-Detector/assets/128805590/879e4051-bb38-4cba-b3c5-10058dc544ca)

## :open_file_folder: Dataset
The training dataset is made up of 16 robotic procedures. The original video data was recorded at 60 Hz and to reduce labelling cost they have been subsampled to 2 Hz. Sequences with little or no motion are manually removed to leave 149 frames per procedure. Video frames are 1280x1024 for which labeling is provided.  

The classes found in the training and test are:  
 - Instrument   
 - Drop in Ultrasound Probe  
 - Suturing Needles  
 - Suturing thread  
 - Clips/clamps  
 - Background tissue  
  
Each class will have a distinct numerical label in a ground truth image. A supplied json file will contain the class name to numerical label mapping.

<!--
## :warning: Framework & TechStack used

-> [PyTorch](https://pytorch.org/)

-> [Openai-gym](https://openai.com/index/openai-gym-beta/)

-> [PPO](https://openai.com/index/openai-baselines-ppo/)

-> [SB-3](https://stable-baselines3.readthedocs.io/en/master/)

-> [Optuna](https://optuna.org/)
-->
  
## Inferencing using GPT-3.5
![image](https://github.com/Patil-Ojas/Surgical-Tool-Detector/assets/128805590/9dedc893-94f1-4bc9-973d-b3960ed17fbc)
![image](https://github.com/Patil-Ojas/Surgical-Tool-Detector/assets/128805590/103d1dc0-cf9c-4717-b7cb-8315ac548914)

<!--
## :handshake: Contribution
Feel free to **file a new issue** with a respective title and description on the the [Street-Fighter-AI](https://github.com/Patil-Ojas/Street-FIghter-AI/issues) repository.
Please do not hesitate to contact me on any socials if you need the ROM or trained model files, have fun!
--> 

## :handshake: Team Xerneas
- Ojas Patil
- Garvita Kesarwani

## :fountain_pen: License
[Achape-License-2](https://github.com/Patil-Ojas/Surgical-Tool-Detector/blob/main/LICENSE)

