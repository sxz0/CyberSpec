# CyberSpec
Code and datasets for CyberSpec paper

**CyberSpec: Intelligent Behavioral Fingerprinting to Detect Attacks on Crowdsensing Spectrum Sensors**
_Alberto Huertas Celdrán, Pedro Miguel Sánchez Sánchez, Gérôme Bovet, Gregorio Martínez Pérez, Burkhard Stiller_
https://arxiv.org/abs/2201.05410

## Dataset
Each dataset models the internal behavior of a Raspberry Pi acting as an IoT spectrum sensor. The name of each file is the device MAC address. Each dataset models the behavior of that device (looking at Linux kernel events belonging to usage of CPU, Memory, Network interface, File system, Scheduler, drivers, and Random number generation) when it is running in a normal manner and when it is affected by eight spectrum sensing data falsification (SSDF) attacks and configurations.

The devices are connected to four LANs according to:

LAN_1: One Raspberry Pi 3 --> RP3 (b8_27_eb_63_5b_27).
LAN_2: One Raspberry Pi 4 --> RP4 (dc_a6_32_e4_48_cb).
LAN_3: Two Raspberry Pis 3 & one Raspberry Pi 4 --> RP3_1 (b8_27_eb_10_a7_e6), RP3_2 (b8_27_eb_a9_15_d1), RP4 (dc_a6_32_4c_9a_d0).
LAN_4: Three Raspberry Pis 3 \& one Raspberry Pi 4 --> RP3_1 (b8_27_eb_55_3d_95), RP3_2 (b8_27_eb_45_3f_c5), RP3_3 (b8_27_eb_e0_85_25), RP4 (e4_5f_01_15_dd_f2).

In each dataset, the following timestamps indicate the starting and end of each behavior

Normal: 	1637578547000 - 1638281248758

Noise_20k: 	1634091300000 - 1634098500000
Noise_200k:  	1639499851331 - 1639507051331
Noise_2M:  	1639689114465 - 1639696314465
Noise_20M:	1639529420078 - 1639536620078
Noise_80M:	1639558871523 - 1639566071523
Noise_160M:	1639588297538 - 1639595497538


Delay_20k:  	1636585242000 - 1636592442000
Delay_200k:  	1638809715000 - 1638816915000
Delay_2M:  	1638873523000 - 1638880723000
Delay_20M:	1639043946000 - 1639051146000
Delay_80M:	1639258059000 - 1639265259000
Delay_160M:	1639353084000 - 1639360284000


Spoof_20k: 	1634584200000 - 1634591400000
Spoof_200k:  	1639507344866 - 1639514544866
Spoof_2M:  	1639698299157 - 1639705499157
Spoof_20M:	1639536783235 - 1639543983235
Spoof_80M:	1639566227524 - 1639573427524
Spoof_160M:  	1639595653590 - 1639602853590


Mimic_20k:	1637006442000 - 1637013642000
Mimic_200k:	1638825148000 - 1638832348000
Mimic_2M:	1638888205000 - 1638895405000
Mimic_20M:	1639060436000 - 1639067636000
Mimic_80M:	1639272702000 - 1639279902000
Mimic_160M:	1639367733000 - 1639374933000


Confusion_20k:	1635471000000 - 1635478200000
Confusion_200k:	1639514701938 - 1639521901938
Confusion_2M:	1639705655398 - 1639712855398
Confusion_20M:	1639544145992 - 1639551345992
Confusion_80M:	1639573584011 - 1639580784011
Confusion_160M:	1639603010791 - 1639610210791


Repeat_20k:	1635751800000 - 1635759000000
Repeat_200k:	1639522060524 - 1639529260524
Repeat_2M:	1639713007186 - 1639720207186
Repeat_20M:	1639551508810 - 1639558708810
Repeat_80M:	1639580941337 - 1639588141337
Repeat_160M:	1639610368534 - 1639617568534
