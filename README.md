# 1_GHz_Active_Differential_Probe

Instead of paying a few thousand $ to the unnecessarily expensive probes from textronix or rigol, i made an Differential Probe which cost
15$ for 4 layer pcb and 45$ for components and it works just fine.

Mosfet source follower is used as voltage buffer which has 20dB attenuation (1/10) and an opamp subtractor is used at the end. Copper pour at the input of the pcb is removed
to reduce input capacitance of the probe for high speed signals. Design needs usb input power for powering the circuit and 50 Ohm SMA connector
is used. BNC 50 Ohm feedthrough connector can be used for connection to Oscilloscope if it does not have 50 Ohm option.

![1 GHz](https://user-images.githubusercontent.com/61315249/96349553-17d8a400-10b9-11eb-9e47-c789896db852.png)

