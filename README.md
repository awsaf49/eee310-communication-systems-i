# Design of BPSK and ASK Modulator and Demodulator with MatLab Simulink
> EEE 310 - Communication Systems I Laboratory

# Abstract
This project presents the implementation of Binary Phase Shift Keying (BPSK) modulation and demodulation in MATLAB Simulink environment. The main aim of the communication system is the accurate transmission and reception of data/signals. The selection of modulation and demodulation techniques depends on the low Bit Error Rate (BER), high data rate, small power requirement, and design simplicity. The BPSK modulation and demodulation technique is widely used in many areas because it satisfies most of the above criteria. The BPSK modulated signal is produced by modulating carrier according to the Bernoulli binary code generator and by noisy Additive White Gaussian Noise (AWGN) channel. The demodulation is performed in different techniques like using Integrate and Dump filter, low pass filter, and BPSK Demodulator block with suitable block parameters. Digital modulation and demodulation systems are an important part of digital communication systems, and their research is necessary. Based on the analysis of 2ASK digital band-pass system transmission characteristics, SIMULINK software is used to simulate the digital band-pass transmission system. Having fully considered the possible factors affecting the 2ASK signal in the transmission process, a basic model of the 2ASK digital band-pass transmission system is established. This system model can simulate and realize the function of 2ASK digital band-pass signal transmission. Debugging and testing show that the waveforms of the system are consistent with the theoretical analysis and error-free code transmission can be achieved; the symbol error rate is rising with the increase of noise, which indicates that the system design is effective and reasonable. It is worth reference for related research and the improvement of such a system, and also provides a new way for system design and experimental teaching.

# Binary Phase Shift Keying (BPSK)

## Modulation
![image](https://github.com/awsaf49/eee310-communication-systems-i/assets/36858976/b6d2239e-d52d-4cb1-953d-178dad08bac1)

![image](https://github.com/awsaf49/eee310-communication-systems-i/assets/36858976/34c56d70-b448-4117-bfcc-b14a0e31ef2c)


## Demodulation
![image](https://github.com/awsaf49/eee310-communication-systems-i/assets/36858976/e6d3101e-e5cc-4543-9e4a-604f06042c4b)

## Demodulation with AWGN Channel
![image](https://github.com/awsaf49/eee310-communication-systems-i/assets/36858976/825cc96f-04c8-43cf-a137-59519f66d615)

![image](https://github.com/awsaf49/eee310-communication-systems-i/assets/36858976/4188bd2e-d5a0-4b0b-95fe-026fc3001da0)


# Amplitude Shift Keying (ASK)

## Modulation
![image](https://github.com/awsaf49/eee310-communication-systems-i/assets/36858976/3fe4ce29-0559-4bb7-b0ba-08cc7594e9ab)

![image](https://github.com/awsaf49/eee310-communication-systems-i/assets/36858976/5b224a01-8fb0-4741-a451-a578733c560a)

![image](https://github.com/awsaf49/eee310-communication-systems-i/assets/36858976/0c85ae50-4851-46f0-b687-6cfc786122c2)

![image](https://github.com/awsaf49/eee310-communication-systems-i/assets/36858976/d22e99ac-628d-412f-8ff4-7eac45ccbbc7)



## Demodulation

![image](https://github.com/awsaf49/eee310-communication-systems-i/assets/36858976/76f6936c-6b3a-40f1-bd49-7fc4dbde0185)

![image](https://github.com/awsaf49/eee310-communication-systems-i/assets/36858976/061130ea-e279-4e6a-859e-b6ec81afaf37)


![image](https://github.com/awsaf49/eee310-communication-systems-i/assets/36858976/26ea6798-3047-4195-a904-74fb15c195dc)






