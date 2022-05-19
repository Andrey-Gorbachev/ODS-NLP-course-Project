# ODS-NLP-course-Project

The goal of the project is to implement ASR, based on the SprechBrain framework, for Russian speech recognition.

Automatic speech recognition, or ASR, is the use of machine learning or artificial intelligence (AI) technology to process human speech into readable text.

## SpeechBrain:

- Website: https://speechbrain.github.io/
- Code: https://github.com/speechbrain/speechbrain/
- HuggingFace: https://huggingface.co/speechbrain/

## Russian Speech Datasets
Russian Speech Datasets are provided by Microsoft Corporation with CC BY-NC license. Instructions by downloading - https://github.com/snakers4/open_stt The CC BY-NC license requires that the original copyright owner be listed as the author and the work be used only for non-commercial purposes We used buriy-audiobooks-2-val dataset

buriy-audiobooks-2-val was chosen as the main dataset, which contains 7,850 ãtterances, 4.9 Hours of total recording time, 1 Gb of volume and 99\% accuracy with manual annotation.



Achieved WER 2.07e+02 after 12 training epochs of 35-40 minutes each on a Tesla K80x24Gb.

Pre-trained models are saved on HuggingFace - 
https://huggingface.co/AndyGo/speechbrain-asr-crdnn-rnnlm-buriy-audiobooks-2-val
https://huggingface.co/AndyGo/speechbrain-asr-transformer-transformerlm-buriy-audiobooks-2-val
