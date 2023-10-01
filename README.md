# OFDM_system
The OFDM system is implemented using discrete Fourier transform (DFT) and inverse DFT (IDFT) processes. 
Which can be implemented efficiently by using fast Fourier transform (FFT) and inverse fast Fourier transform (IFFT) respectively [1].
It does not use oscillators for each subchannel, and it doesn’t require filters to separate sub-bands in the receiver side, thanks to orthogonality between subcarriers.

## Cyclic_prefix
Due to multipath channel, the receiver has many versions of the transmitted data which causes inter symbol interference  (ISI).
OFDM can simply overcome ISI by adding a Guard interval called Cyclic Prefix, as shown in fig.4. 
CP is to extend the OFDM symbol by copying the last samples of the OFDM symbol into its front. CP must be longer than maximum delay spread of the channel. 

![image](https://github.com/Metwaly-yahia/OFDM_system/assets/81784667/9423a428-8e96-4c89-9dd6-cd5cb7d52e82)

![image](https://github.com/Metwaly-yahia/OFDM_system/assets/81784667/45ac3846-b2db-4cae-b3c7-1b71688741b5)



## Implementation of OFDM system

![image](https://github.com/Metwaly-yahia/OFDM_system/assets/81784667/f7e4a90e-87ac-4e90-9539-7da0627ea5dc)

![image](https://github.com/Metwaly-yahia/OFDM_system/assets/81784667/8f83f990-e171-417a-8c07-3317023a7678)
