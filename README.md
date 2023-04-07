# Speaker Recognition model

based on ResNet with Multi-Frequency Information Enhanced Channel Attention Module from the paper:
https://www.isca-speech.org/archive/pdfs/interspeech_2022/sang22_interspeech.pdf

## Dataset 
The VOXceleb1 dataset contains over 120,000 voice recordings from over 1200 celebrities such as actors, singers, athletes, TV hosts and more. Each speaker in the VOXceleb1 dataset is represented by several audio recordings that can be used to train speech recognition systems and other related tasks.

## Main Idea
Paper proposes a new Channel Attention Module (CAM) that integrates information from different frequencies to improve the presentation of the speaker (Figure 2.1). This approach is an improvement on existing methods such as Self-Attention Pooling (SAP) and Attentive Statistics Pooling (ASP) and offers greater accuracy and efficiency in speaker representation training. The authors claim that the proposed channel attention module is able to better adapt to various voice conditions such as noise, accent, and emotions, and thus provides higher performance in speaker identification and verification tasks.

## Metrics
ResNet without MFCS got EER: 6.212%
ResNet with MFCS got EER: 4.747%

- You can read more about the architecture of the solution and analysis of the results in the speaker_recognition.docx file 
