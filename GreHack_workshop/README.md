# GreHack 2019

Here are some resources of the SDR workshop made at GreHack 2019.

## Content

You will find 2 directories:

* Simulation: some GRC projects we have made to understand what is GnuRadio, what the sample rate is, data types, CPU problems and thresold, but also how to generate signals and a valid OOK data ready to be transmitted;
* Transmission: a GRC project to show how transmission works with a simple FM raw music data.

There is also a `HW_SDR_devices-Comparison.pdf` file showing the comparison of affordable and famous HW devices. And as we saw, all depend of the target, budget, used frequencies, bandwidth, and also clock precision. And there is no generic device, at least not very good one. But generally bladeRF is a good compromise as well as LimeSDR, but USRP B210 can be used for a larger set of purposes and has a lot of supports.

## Presented tools

We have talked the RF explorer to discover signals, but also ways to do it with GnuRadio, and talked about GQRX. 
Thanks to one attendie (Kévin), we could also discover a nice tool called Qspectrum Analyzer as well.

To decode our generated OOK signal, as well as captured ones, we have also seen how URH (Universal Radio Hacker) works and how it could be convenient for decoding simple modulated and encoded data.


## Some good resources to check online

Go further:

* RF Hacking with Software-Defined Radio (SDR) training: https://advancedsecurity.training/events/berlin-rfhacking-spring-2020/
* Very nice and online book about Digital Processing: http://www.dspguide.com/
* Good resources and explanation about antennas (French): https://f5zv.pagesperso-orange.fr/RADIO/RM/RM08/RM08a/RM08a.html
* Intercom hacking: https://www.synacktiv.com/ressources/33c3_Intercoms_presentation_en.pdf
* GnuRadio tutorials: https://wiki.gnuradio.org/index.php/Tutorials
* Software Defined Radio with HackRF: http://greatscottgadgets.com/sdr/ 
