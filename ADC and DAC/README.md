# Analog-to-Digital & Digital-to-Analog Conversion
ADC and DAC are the processes that allow our computers to interact with these everyday signals. Digital information is different from its continuous counterpart in two important respects: it is *sampled*, and it is *quantized*. This dictates the selection of the sampling frequency, number of bits, and type of analog filtering needed for converting between the analog and digital realms.

## Digitization Process
When digitizing signals, there are two part: Sample-and-Hold (S/H) and the Analog-to-Digital Converter (ADC). The sample-and-hold is to keep the voltage entering the ADC constant while the conversion is taking place. 

**Sampling** converts the *independent variable* (time in this example) from continuous to discrete. 

**Quantization** converts the *dependent variable* (voltage in this example) from continuous to discrete.

![Waveforms illustrating the digitization process](image.png)

### Effects of the Quantization
Any sample in the digitized signal can have a maximum error of $\pm \frac{1}{2}$ **LSB (Least Significant Bit)**.

The digital output will have the continuous input plus a quantization error. In most cases, the results will have a specific amount of random noise to the signal. The additive noise is uniformly distributed between $\pm \frac{1}{2}$ LSB, mean of 0, and a standard devaition of $\frac{1}{\sqrt{12}}$ LSB. 
