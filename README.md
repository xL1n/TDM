# Time division mutipluxer 
Built a TDM on breadboard implementing combining different signals (AC and DC) from multiplexer and reconstructing the AC signal back from demultiplexer with academic teacher’s support. 
In general, I used a oscillator to create square wave signal with balanced duty cycle (implemented by connecting capacitors to the oscillator) in order to generate initial "counter" signal. This oscillator is then connected to a binary counter which is used to select the signals on multiplexer. Finally, I connected the binary counter to multiplexer and demultiplexer to implementing Time Division multiplexing.
To check the working ability of TDM, I used AC signal and DC signal to separate each channel of multiplexer/demultiplexer and to see the different outputs with time
To see the difference with how the demultiplexer reconstruct AC signal. I have also tested with different frequency of oscillator, and the results as expected, the higher frequency (“sampling frequency”), the more accurate the signal can be reconstructed.
(Integrated devices used: SE555P, CD4520, CD4052B)
