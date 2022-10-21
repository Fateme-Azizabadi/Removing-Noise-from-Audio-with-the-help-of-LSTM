# Removing Noise from Audio with the help of LSTM

**Removing Noise from Audio with the help of LSTM**

In this project, we deal with audio noise reduction with recurrent networks.

## **Dataset**

In this part, we first read the audio from the input, which is 4 minutes and 19 seconds, and its sampling frequency is 22050 Hz. First, we recorded half of this audio as one signal.

The two images below show the audio file's waveform and its power spectrum. 

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Audio-with-the-help-of-LSTM/blob/main/Images/Waveform.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Signals-with-the-help-of-RNN-LSTM/blob/main/Images/Power.Spectrum.png)

Then we add Gaussian noise with zero mean and one variance to audio and draw its waveform and power spectrum.


The two images below show the noisy audio file's waveform and power spectrum. 

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Audio-with-the-help-of-LSTM/blob/main/Images/Noisy.Waveform.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Audio-with-the-help-of-LSTM/blob/main/Images/Noisy.Power.Spectrum.png)

Then we set aside 129 seconds for train data, 10 seconds for validation data, and 89 seconds for test data.

## **Network**

We designed the LSTM Network with the below features. 

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Audio-with-the-help-of-LSTM/blob/main/Images/LSTM.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Audio-with-the-help-of-LSTM/blob/main/Images/output.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Audio-with-the-help-of-LSTM/blob/main/Images/Results.png)

## **Increase the length of the audio signal**

Now we consider the entire audio signal as input, i.e., 4 minutes and 19 seconds.
The below figures show the output of networks.

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Audio-with-the-help-of-LSTM/blob/main/Images/Waveform2.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Audio-with-the-help-of-LSTM/blob/main/Images/Power.Spectrum2.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Audio-with-the-help-of-LSTM/blob/main/Images/output2.png)

![](https://github.com/Fateme-Azizabadi/Removing-Noise-from-Audio-with-the-help-of-LSTM/blob/main/Images/Results2.png)




 
 
