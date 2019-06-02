# VGASignalProbe

This project utilises a 68HC908QT4 to digitise an analog signal, and generate a
corresponding VGA video signal representing the time sequence of the samples. This allows
a simple audio-bandwidth CRO to be implemented using two 8-pin ICs. The device includes
two buttons for toggling the acquisition mode between free running, and digital storage. In
free running mode, the acquisition is synchronised to the horizontal display frequency. In
digital storage mode, the buttons also act to adjust the time base, triggering voltage level and
edge polarity.
