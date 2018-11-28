# gyro_acc_ppg
For the experiment, we developed a watch-type PPG measuring device. The developed device includes a 3-channel PPG sensor, an accelerometer and a gyroscope. For the acquisition of the PPG signal, photosensors (NJL5310R, NJR Corporation, Japan) integrating two green LEDs(wavelength: 525nm) and a photodetector was used. Three PPG sensors were placed at intervals of 6 mm. Acceleration and gyro values were collected using a 6-axis inertial measurement unit (IMU; LSM6DSMUSTR, STMicroelectronics). Three digital signals were stored using a micro-SD card. The three digital signals are simultaneously stored on a micro-SD card at a frequency of 50 Hz.

We conducted experiments with a modified version of the Bruce protocol, which consists of 2 min of walking as a warm-up, 3 min of running, 2 min of walking, 3 min of running, and 2 min of walking to cool down, all on a treadmill. During the running, the speed was set to 6.0 to 7.0 km/h. In the experiment, 24 healthy subjects at Wonkwang University were recruited by trained study personnel. In total, 10 males and 14 females with an average age of 26.9 ± 4.8 years participated. The protocol for data collection and analysis was approved by the Institutional Review Board of Wonkwang University. All participants provided written informed consent.

Citation and copyright 
==================================================
Hooseok Lee, Heewon Chung, and Jinseok Lee (Professor) a member of BAMI LAB.   
https://sites.google.com/site/bamilab/biosignal-lab   
Last updated 2018.09.27 (September 27, 2018)

All datasets have copyrights. But you can freely use them for the Signal Processing Cup or your own academic research, as long as you suitably cite the data in your works. Please do not cite this competition website, because it may not be available after this competition. Instead, please cite the following paper, since all training datasets come from it: 

H. Lee, H. Chung and J. Lee, "Motion Artifact Cancellation in Wearable Photoplethysmography Using Gyroscope," in IEEE Sensors Journal.
doi: 10.1109/JSEN.2018.2879970

URL: http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8529266&isnumber=4427201

Exercise Experiment Protocol
==================================================
Measurements were taken using an ECG placed on the chest together with a PPG placed on the wrist during treadmill exercise. ECG data were recorded simultaneously using a 24-hour Holter monitor (SEER Light; GE Healthcare, Milwaukee, WI, USA). PPG and motion data were recorded using a wearable device which we developed. Participants were asked to perform the exercise according to the exercise protocol, we have designed. 
  1) Stay (Resting)      : 1minutes
  2) Walking             : 2minutes, treadmill (2.5km/h)
  3) Running             : 3minutes, treadmill (6km/h)
  4) Walking             : 2minutes, treadmill (3km/h)
  5) Running             : 3minutes, treadmill (7km/h)
  6) Walking             : 2minutes, treadmill (2.5km/h)
  7) Stay (Resting)      : 1minutes

Data Description
==================================================
This database contains wrist PPGs recorded during stay, walking, and running.
Accelerometers and Gyroscopes are collected to remove the motion artifact from the PPGs.
A reference chest ECG is included to allow a gold-standard comparison of heart rate during treadmill exercise.

●ECG sampling rate : 125Hz   
●PPG sampling rate : 50Hz  
●Acc sampling rate : 50Hz  
●Gyro sampling rate : 50Hz   

Matlab Data
==================================================
●bpmECG    : ECG heart rate   
●timeECG   : ECG times  
●sigPPG    : 3-channel PPG signal   
●sigAcc    : 3-axis accelerometer signal, An uncorrected digital value, with a value of 32768 added to remove the negative number.   
●sigGyro   : 3-axis gyroscope signal,  An uncorrected digital value, with a value of 32768 added to remove the negative number.    
