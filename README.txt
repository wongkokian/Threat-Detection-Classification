### README

## Model should be run on Google's Colaboratory. Testing time without GPU is about 5 minutes. 
## Notebook file provided in file but link is here: https://colab.research.google.com/drive/1VuKIeiTfGEHesfuPZrQK7C2-wL9ii1q_?usp=sharing
## Checkpoint for baseline and modified version provided, modified version is deprecated as results are subpar but still provided for your viewing in misc.

## Steps to run
1. Download the checkpoints and place them in your google drive at the path: "/content/drive/My Drive/{checkpoint name}"
2. Image data provided by Prof Amir should be located at: "/content/drive/My Drive/cs4243_smallest/" and contain 3 folders (normal, carrying, threat)
3. At the last cell in the notebook, the 4 commands are already there. 
4. train and modified_train performs training which can take up to 3 hours and might not run depending on Colab's current GPU. 
	If it fails to run, change batch size to 256 (result different from checkpoint)
5. test and modified_test performs evaluation of model. 
	Threshold can be set to reduce false positives for Normal. (results in poster used 0.9) (set threshold to 0 for baseline) 


## Group 10 members: Hope Leong, Chan Wa Wai, Ian Wong and Bryan Beh