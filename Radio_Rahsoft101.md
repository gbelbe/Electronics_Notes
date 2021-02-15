# Bandes:

VLF: 3-30Khz  (100km 10km)
LF: 30-300khz maritime radio navigation (10km a 1km)
MF: 300khz - 3mhz (am radio, navigation aviation) (1km a 100m)
HF: 3 - 30mhz (100m a 10m)
vhf: 30 - 300mhz (10m à 1m) fm radio...vhf tv...
uhf: 300 - 3ghz (1m à 10cm)  tv, mobile, gps, wifi 4g...
shf: 3ghz - 30ghz (10cm a 1cm) wifi - satellite
ehf: 30ghz - 300ghz (radio astronomy - satellite) 1cm 1mm
 
White noise: constant around all the frequencies
Pink noise, flickr noise, 1/f noise: noise that decrease with the frequency, higher the frequency, lower the pink noise

thermal noise: dominant at high frequency
phase noise: phase is changing = phase jitter, depending of the frequency at which are used elecronic components
flickr noise: 1/f noise ==> dominant at lower frequency: corner frequency is the frequency at which the flickr noise is disappearing

SNR =  Power of Signal / Power of Noise

Diffrent types of filters:
active filters are limited in frequency to up to 300mhz due to the non linearity of active components above their max freq. (they are no more linear on their higher bandwidth limit)

lc filters:  up to 2GHz
dielectric resonator: 500mhz => 2ghz
SAW => surface acoustic wave => 50mhz -> 2Ghz
Microstrip filter ==> 2Ghz - 30ghz
Heilical resonator ==> 100mhz --> 1ghz
Crystal filter --> 5mhz --> 50mhz
Ceramic MCF --> 250khz --> 10 mhz

Active filters => Switched capacitors, Gm-C 
Passive : LC, electro acoustic

Off chip filters => Higher Q, + precision,less noise , less loss, but can get more parasitics than on chip filters. 

LNA ==> used on receivers after antenna. Objective is increase the Signal amplitude while maintaining the SNR. (being cautious not to add noise from the amplifier itself)


Mixers ==> used for upconversion or down converstion. They are usually done after the signal has been modulated.
            input signal, fo (carrier frequency) ==> output signal
