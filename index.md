---
layout: default
---

# **SDNet Demo**

## **1. Test Set Samples**

### Sample 1

&emsp;&emsp;&emsp;&emsp;**Noisy(at 8kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**UNet + I-DTLN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**VoiceFixer**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/1.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/1.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/1.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;&emsp;**Ours**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/predict/ours/1.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/1.wav" type="audio/wav"></audio>

### Sample 2

&emsp;&emsp;&emsp;&emsp;**Noisy(at 8kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**UNet + I-DTLN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**VoiceFixer**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/2.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/2.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/2.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;&emsp;**Ours**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/predict/ours/2.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/2.wav" type="audio/wav"></audio>

### Sample 3

&emsp;&emsp;&emsp;&emsp;**Noisy(at 8kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**UNet + I-DTLN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**VoiceFixer**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/3.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;&emsp;**Ours**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/predict/ours/3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/3.wav" type="audio/wav"></audio>

### Sample 4

&emsp;&emsp;&emsp;&emsp;**Noisy(at 8kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**UNet + I-DTLN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**VoiceFixer**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/4.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/4.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/4.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;&emsp;**Ours**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/predict/ours/4.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/4.wav" type="audio/wav"></audio>

### Sample 5

&emsp;&emsp;&emsp;&emsp;**Noisy(at 8kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**UNet + I-DTLN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**VoiceFixer**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/5.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;&emsp;**Ours**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/predict/ours/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/5.wav" type="audio/wav"></audio>

## **2. Real World Samples**

In this part, we selected some old speech to repair their quality. Some samples are below.

### Sample 1

" Science has profoundly altered the conditions of man's life both materially and in ways of the spirit as well. " - J. Robert Oppenheimer

&emsp;&emsp;&emsp;&emsp;**Source**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Output**

<audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/1.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/1_pr.wav" type="audio/wav"></audio>

Spectrogram: 

<img src="img\real_1.png" alt="real_1" style="zoom: 50%;" /><img src="img\real_1_pr.png" alt="real_1_pr" style="zoom: 50%;" />

### Sample 2

" If someone, again who hadn't been here before, asked you ‘ Is it safe to come to Northern Ireland? ’ What would you say? " - From an old interview

&emsp;&emsp;&emsp;&emsp;**Source**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Output**

<audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/2.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/2_pr.wav" type="audio/wav"></audio>

Spectrogram: 

<img src="img\real_8.png" alt="real_8" style="zoom:50%;" /><img src="img\real_8_pr.png" alt="real_8_pr" style="zoom:50%;" />

### Sample 3

" Begin the day with Able Mabel. She'll wake you at your preset time. " - From an old TV advertisement

&emsp;&emsp;&emsp;&emsp;**Source**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Output**

<audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/realworld/3_pr.wav" type="audio/wav"></audio>

Spectrogram:

<img src="img\real_9.png" alt="real_9" style="zoom: 50%;" /><img src="img\real_9_pr.png" alt="real_9_pr" style="zoom: 50%;" />

## **3. Settings of Each Layer**

Layers are listed in order of precedence, from top to bottom. The last dimension and batchsize dimension may be different based on the duration of input speech and batchsize.

<img src="img\Network Settings.PNG" alt="Network Settings" style="zoom:100%;" />

## **4. Acknowledgement**

Our work was built based on AERO (<https://github.com/slp-rl/aero>). 

The following repositories also help us a lot.

<https://github.com/zkx06111/WSRGlow>

<https://github.com/maum-ai/nuwave2>

<https://github.com/haoheliu/voicefixer>

<https://github.com/lhwcv/DTLN_pytorch>

<https://github.com/ncarraz/AFILM>

Thanks for all these great work.
