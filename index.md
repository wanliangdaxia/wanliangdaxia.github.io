
# **Cross Domain Optimization for Speech Enhancement: Parallel or Cascade?**

## **1. Performance comparison at each stage in parallel 2(Att).**

### SNR = -6

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**TF module 1**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Time module**

<audio controls="" style="width: 250px; height: 50px"><source src="demopage1/noisy_-6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/TF1_-6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/Time_-6.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;**TF module 2**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="demopage1/TF2_-6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/clean_-6.wav" type="audio/wav"></audio>

### SNR = -3

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**TF module 1**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Time module**

<audio controls="" style="width: 250px; height: 50px"><source src="demopage1/noisy_-3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/TF1_-3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/Time_-3.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;**TF module 2**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="demopage1/TF2_-3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/clean_-3.wav" type="audio/wav"></audio>

### SNR = 0

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**TF module 1**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Time module**

<audio controls="" style="width: 250px; height: 50px"><source src="demopage1/noisy_0.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/TF1_0.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/Time_0.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;**TF module 2**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="demopage1/TF2_0.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/clean_0.wav" type="audio/wav"></audio>

### SNR = 3

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**TF module 1**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Time module**

<audio controls="" style="width: 250px; height: 50px"><source src="demopage1/noisy_3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/TF1_3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/Time_3.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;**TF module 2**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="demopage1/TF2_3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/clean_3.wav" type="audio/wav"></audio>
### SNR = 6

&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**TF module 1**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Time module**

<audio controls="" style="width: 250px; height: 50px"><source src="demopage1/noisy_6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/TF1_6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/Time_6.wav" type="audio/wav"></audio>

&emsp;&emsp;&emsp;&emsp;**TF module 2**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Clean(Reference)**

<audio controls="" style="width: 250px; height: 50px"><source src="demopage1/TF2_6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="demopage1/clean_6.wav" type="audio/wav"></audio>

## **2. Performance comparison of different models**

In this part, we will present the enhanced speech of our proposed model compared to other models.

### SNR = -6



&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DCCRN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DPRNN**

<audio controls="" style="width: 250px; height: 50px"><source src="noisy_-6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="DCCRN_-6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="DPRNN_-6.wav" type="audio/wav"></audio>
&emsp;&emsp;&emsp;&emsp;**FullSubNet**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Cascade 3**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Parallel 2(Att)**

<audio controls="" style="width: 250px; height: 50px"><source src="fullsubnet_-6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="cascade_-6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="parallel_-6.wav" type="audio/wav"></audio>


### SNR = -3



&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DCCRN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DPRNN**

<audio controls="" style="width: 250px; height: 50px"><source src="noisy_-3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="DCCRN_-3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="DPRNN_-3.wav" type="audio/wav"></audio>
&emsp;&emsp;&emsp;&emsp;**FullSubNet**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Cascade 3**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Parallel 2(Att)**

<audio controls="" style="width: 250px; height: 50px"><source src="fullsubnet_-3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="cascade_-3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="parallel_-3.wav" type="audio/wav"></audio>

### SNR = 0


&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DCCRN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DPRNN**

<audio controls="" style="width: 250px; height: 50px"><source src="noisy_0.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="DCCRN_0.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="DPRNN_0.wav" type="audio/wav"></audio>
&emsp;&emsp;&emsp;&emsp;**FullSubNet**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Cascade 3**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Parallel 2(Att)**

<audio controls="" style="width: 250px; height: 50px"><source src="fullsubnet_0.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="cascade_0.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="parallel_0.wav" type="audio/wav"></audio>

### SNR = 3



&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DCCRN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DPRNN**

<audio controls="" style="width: 250px; height: 50px"><source src="noisy_3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="DCCRN_3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="DPRNN_3.wav" type="audio/wav"></audio>
&emsp;&emsp;&emsp;&emsp;**FullSubNet**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Cascade 3**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Parallel 2(Att)**

<audio controls="" style="width: 250px; height: 50px"><source src="fullsubnet_3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="cascade_3.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="parallel_3.wav" type="audio/wav"></audio>

### SNR = 6



&emsp;&emsp;&emsp;&emsp;**Noisy(at 16kHz)**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DCCRN**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**DPRNN**

<audio controls="" style="width: 250px; height: 50px"><source src="noisy_6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="DCCRN_6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="DPRNN_6.wav" type="audio/wav"></audio>
&emsp;&emsp;&emsp;&emsp;**FullSubNet**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Cascade 3**&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;**Parallel 2(Att)**

<audio controls="" style="width: 250px; height: 50px"><source src="fullsubnet_6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="cascade_6.wav" type="audio/wav"></audio><audio controls="" style="width: 250px; height: 50px"><source src="parallel_6.wav" type="audio/wav"></audio>

