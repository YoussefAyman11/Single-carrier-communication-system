# Single-carrier-communication-system
The project's purpose is to simulate a single carrier communication system.
The system consists of three blocks:

The Mapper  
The first block in the communication system under consideration is the mapper. The 
mapper takes the I/P data bits and produces the symbols to be transmitted on the channel. 
The modulation schemes under consideration are the BPSK, QPSK, 8PSK, BFSK and 
16QAM systems.

The channel 
The channel is an AWGN channel. In this model, the channel just adds noise to the 
transmitted signal. In MATLAB, the command “randn” should be used to generate the AWGN.

The Demapper 
The simple demapper in the model under consideration will take the output of the channel 
and decide on the symbol transmitted. The output bit stream of the receiver is compared to 
the input bit stream and the BER is calculated. 
