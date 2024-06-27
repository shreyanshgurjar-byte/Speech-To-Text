# Automatic Speech Recognition Model

**Speech-to-Text Conversion Model**

This repository hosts a robust speech-to-text conversion model utilizing the Word2Vec algorithm. It excels in accurately transcribing spoken language, adeptly handling diverse accents including Indian accents, and varying noise levels. Implemented in Python, this model is ideal for integrating into voice assistants, transcription services, and other speech recognition systems.

**Installation**<br>
To install the necessary dependencies and set up the environment, follow these steps:

Create and activate a virtual environment (optional but recommended):<br>
python3 -m venv venv<br>
cd venv\Scripts\activate

Install the required dependencies:<br>
pip install -r requirements.txt

**Dataset**

Nptel pure data of used in this model.<br>
https://github.com/AI4Bharat/NPTEL2020-Indian-English-Speech-Dataset<br>

**Results**

**Average Character Error Rate (ACER) :-  0.1966**

**Examples**


1)<br>
[INFO] Processing file: 0001f271b10ea14c9ec69da59d26f63f86aa2530e6fc475d99ee090b.wav
       Reference : IN POSITION AND ORIENTATION AND THEN THE DRILLING HAS TO BE DONE BUT THE DRILL IS A VERY SLENDER TOOL
       Transcription : IN PODITION AND ORIENTATION AND THEN THE DRILLING HAS TO BE DONE BUT THE DRILL IS A VERY SLENDER TOOL
       **CER : 0.0099**

2)<br>
[INFO] Processing file: 0009e5bbb08d2ec013048507a693708a67929c2e0b485633a75d520a.wav
       Reference : SO CREATING THIS NEW SEQUEL COMMANDS ESSENTIALLY SO WE WRITE THE COMMAND PROCEDURE IN C SO
       Transcription: O CREATING THIS NEW TICKL COMMANDS ESSENTIALLY SO A WE WRITE THE COMMAND PROCEDER IN C SO
       **CER : 0.1111**
 
