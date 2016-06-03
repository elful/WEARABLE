# Wearable

This wearable is an IR detector that is connected to a Smart Bluetooth device acting as a link between the detector and mobile phone application. The choice for an wearable was forced by the poor performance of the scanning frequency (30 Hz) of the actual front cameras of mobile phones. The target hardware architecture is to use a LED bulb that is modulated at a frequency of at least 100 cycles/s = 100 Hz. The bulb will be controlled via bluetooth. Until then, we estimate 3-5 years, we will be using "calssic" infra red transmitter and receiver.  
The receiver is a standard IR receiver for 36-42 kHz that is used for remotes also. The circuit diagram is:  
`TODO - Insert cirtuit diagram here`  
The signal from IR receiver is directed to a Lilypad Nano 51822 that is capable of processing and decoding the input signal. Also it has a SoC BLE 4.0 that allows pairing and communication with other BLE devices, like a smart phone. The signal strength depends on the receiver position, the ambient IR radiation and on bulb poistion.  

# Installation

`TODO`

# Usage

`TODO`

# Integration with other systems

`TODO`

# References

`TODO`
