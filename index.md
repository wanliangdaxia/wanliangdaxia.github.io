g---
layout: default
---

# **Cross Domain Optimization for Speech Enhancement: Parallel or Cascade? Demo**

## **1. Performance comparison at each stage in parallel 2(Att).**

### SNR = -6

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**TF module 1**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Time module**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/1.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/1.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/1.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;**TF module 2**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/predict/ours/1.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/1.wav" type="audio/wav"></audio>

### SNR = -3

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**TF module 1**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Time module**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/2.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/2.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/2.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;**TF module 2**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/predict/ours/2.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/2.wav" type="audio/wav"></audio>

### SNR = -0

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**TF module 1**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Time module**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/3.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;**TF module 2**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/predict/ours/3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/3.wav" type="audio/wav"></audio>

### SNR = 3

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**TF module 1**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Time module**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/4.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/4.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/4.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;**TF module 2**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/predict/ours/4.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/4.wav" type="audio/wav"></audio>

### SNR = 6

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**TF module 1**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Time module**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/5.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;**TF module 2**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/predict/ours/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/clean/5.wav" type="audio/wav"></audio>

## **2. Performance comparison of different models**

In this part, we selected some old speech to repair their quality. Some samples are below.

### SNR = -6

" Science has profoundly altered the conditions of man's life both materially and in ways of the spirit as well. " - J. Robert Oppenheimer

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DCCRN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DPRNN**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/5.wav" type="audio/wav"></audio>
&emsp;&emsp;&emsp;&emsp;**FullSubNet**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Cascade 3**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Parallel 2(Att)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/5.wav" type="audio/wav"></audio>


### SNR = -3

" If someone, again who hadn't been here before, asked you ‘ Is it safe to come to Northern Ireland? ’ What would you say? " - From an old interview

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DCCRN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DPRNN**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/5.wav" type="audio/wav"></audio>
&emsp;&emsp;&emsp;&emsp;**FullSubNet**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Cascade 3**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Parallel 2(Att)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/5.wav" type="audio/wav"></audio>

### SNR = 0

" If someone, again who hadn't been here before, asked you ‘ Is it safe to come to Northern Ireland? ’ What would you say? " - From an old interview

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DCCRN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DPRNN**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/5.wav" type="audio/wav"></audio>
&emsp;&emsp;&emsp;&emsp;**FullSubNet**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Cascade 3**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Parallel 2(Att)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/5.wav" type="audio/wav"></audio>

### SNR = 3

" If someone, again who hadn't been here before, asked you ‘ Is it safe to come to Northern Ireland? ’ What would you say? " - From an old interview

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DCCRN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DPRNN**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/5.wav" type="audio/wav"></audio>
&emsp;&emsp;&emsp;&emsp;**FullSubNet**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Cascade 3**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Parallel 2(Att)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/5.wav" type="audio/wav"></audio>

### SNR = 6

" If someone, again who hadn't been here before, asked you ‘ Is it safe to come to Northern Ireland? ’ What would you say? " - From an old interview

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DCCRN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DPRNN**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/5.wav" type="audio/wav"></audio>
&emsp;&emsp;&emsp;&emsp;**FullSubNet**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Cascade 3**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Parallel 2(Att)**

<audio controls="" style="width: 250px; height: 50px"><source src="data/noisy/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/UNet+I-DTLN/5.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="data/predict/VoiceFixer/5.wav" type="audio/wav"></audio>

