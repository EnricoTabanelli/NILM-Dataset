# NILM-Dataset

The repository contains the Dataset collected and deployed in the paper "Exploring Frequency-domain Features for Lightweight Non-Intrusive Load Monitoring On Edge-Devices."
Non-Intrusive Load Monitoring (NILM) implies disaggregating the power consumption of individual appliances from a single power measurement point. 
The Dataset has been recorded employing a MCU-based measurement node. 
The appliances collected in the Dataset are the following:

 0: 'Nothing',\n
 1: 'LightBulb',
 2: 'ElectricMoka',
 3: 'HeadPhones',
 4: 'PowerBank',
 5: 'WaveFormGenerator',
 6: 'Fan1',
 7: 'Fan2',
 8: 'Fan3',
 9: 'Microwaveidle',
10: 'MicrowaveStarting',
11: 'MicrowaveOn',
12: 'Laptop',
13: 'Monitor',
14: 'SmartPhoneCharger',
15: 'MACthread1',
16: 'MACthreads2',
17: 'MACthreads3',
18: 'MACthreads4',
19: 'MACVideo'

The folders hold the following contents:

- logs: Raw current and voltage 
- labeled: Raw current and voltage + appliance labels
- data: Extracted features
