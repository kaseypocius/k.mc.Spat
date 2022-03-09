# k.mc.Spat
A few bpatcher abstractions to spatialize audio using amplitude modulation by an arbitrary number of phase offset oscillators.

The patcher takes one argument, which declares the amount of channels.

The first inlet takes a mono audio input, the second inlet takes a float which controls the rate of the modulator. The third inlet takes 2 floats (0. - 1) as a list, declaring the phase offset between channels of the modulators. The fourth inlet takes a multichannel audio signal. 

The multisilder in the GUI can also be used to modify the phase offset. The float box can be used to modify the rate of modulator. 
