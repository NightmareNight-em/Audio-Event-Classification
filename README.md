# Audio-Event-Classification

Labeling of audio files

The entire project is based on the YouTube tutorial on Audio Event Classification by Seth Adams.The link to the playlist is,
https://www.youtube.com/watch?v=Z7YM-HAz-IY&list=PLhA3b2k8R3t2Ng1WW_7MiXeh1pfQJQi_P

I also worked with CRNN in the project which proved to work well on audio files with less number of parameters as compared to CNNs.
However,CNNs won the race with a whooping 97% accuracy but with comparatively more number of parameters.
I have also provided .h5 model for CNN,RNN,CRNN models for 10 class classification.

I picked my dataset from here,
https://www.kaggle.com/c/freesound-audio-tagging/data

It contained around 9.5k samples with .wav files from 41 classes.

Due to less computational power of my laptop , I constrained the classification under 10 categories of instruments.

However,I tried working on data with 41 classes.Keeping the training set constant , I tried to improve my metric(accuracy) through hand-engineering , that is , tuning hyperparameters or overcoming overfitting through dropouts and regularization.

I am open to any ideas which could help improve the metric provided less amount of data to train.

Also,the slide are borrowed from https://github.com/seth814/Audio-Classification.
Here,you can also get the wavfiles(audio files) for 10 classes of instruments.

Have a look at AudioEventClassification.pdf to get more information on the project.
