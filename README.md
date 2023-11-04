# IDC-409-Speech_to_text

## Introduction:
This repository contains a Jupyter notebook, having code of a speech to text (stt) model (similar to Deepspeech_2), written as past of the assessment project for IDC 409 Intro to data sciences course. Futhermore, it also contains a Google Colab notebook, with the a test example of a pre trained model, similar to Deepspeech_2, called **Coqui English STT model**.  

This stt model is a neural network built to take in preprocessed input audio data and give a text output of the speech for ONLY English language. TensorFlow package was used to do the pre-processing of the data, and further to add layers to the model. 

## Details about the data and packages used
The details of each line of code has been added in the notebook itself. Any and all comments are welcomed so as to how we could improve the model and make it more efficient.

The audio data being used is from the LJ speech dataset, by **Librivox project**. More info can be found on the given links :
https://keithito.com/LJ-Speech-Dataset/
https://www.kaggle.com/datasets/mathurinache/the-lj-speech-dataset/data
https://data.keithito.com/data/speech/LJSpeech-1.1.tar.bz2
The following packages were used:
1. NumPy
2. TensorFlow (Keras mainly) (https://www.tensorflow.org/api_docs/python/tf)
3. Pandas
4. jiwer (https://pypi.org/project/jiwer/)

## Discussion 
The dataset consists of over 13000+ hours of audio which can be used to train the model. Due to time and computation restrictions, we were not able to train the model much. Training even one epoch, was approximated to be atleast 20+hours on Google Colab and over 10+ hours on an Apple M1 macbook air (2020). Therefore, the dataset was restricted to only ~130 files for an epoch, which led to an untrained model, and inaccurate predictions. With more training, on larger datasets, it should be able to predict the text with a word error rate of less than 30%.
A pre-trained model from Coqui STT was then downloaded to give an example of what we had planned to get closer to. It was also trained on LibriVox dataset. More on Coqui : https://github.com/coqui-ai/STT 
---
## References
1. https://youtu.be/ZqpSb5p1xQo?si=kbx38SSX9PI-tK86
2. https://youtu.be/qKz_lmgad3o?si=pS21Hxs_ngRVTweW
3. https://distill.pub/2017/ctc/
4. https://github.com/ml4devs/ml4devs-notebooks/blob/master/speech/asr/deepspeech/mozilla_deepspeech_api_notebook.ipynb
5. https://medium.com/visionwizard/train-your-own-speech-recognition-model-in-5-simple-steps-512d5ac348a5
6. https://www.section.io/engineering-education/speech-to-text-transcription-model-using-deep-speech/
7. https://www.ijedr.org/papers/IJEDR1404035.pdf
8. https://www.youtube.com/watch?v=U0XtE4_QLXI
---

### Indian Institute of Science Education and Research (IISER), Mohali, India
### Semester: August-December 2023 monsoon semester  
### IDC409 : Intro to data sciences  
#### Instructor: Dr. Vishal Bhardwaj  
---
#### Contributions to this git repository made by:
Vatsal Kabra (M21008) : Major part of the code (Jupyter and Colab Notebook), setting up of the git repository, presentation  
Kunal Rajput (MS21009) : Jupyter and colab notebook, presentation  
Anuj Kumar (MS21068) : Jupyter notebook, presentation  




