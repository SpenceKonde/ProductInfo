# RN2483(A)/RN2903(A) Breakout Board

## PCB revision history
Prior to Rev. F careful records were not kept, those are not covered here. 

### Rev. G
* First major revision in a very long time.
* Added 7-pin alternate header. Just a different arrangement of the pins - but you can just plug an 3.3v "FTDI" style serial adapter in and use it, complete with DTR tied to reset so you can reset it easily from the computer (note: A serial console that allows you to control DTR directly is needed for this, as a "dumb" serial console will assert DTR as long as the port is open, holding the part in reset; if you want or need to use software that does that, just don't connect the DTR pin)
* Clarified silkscreen markings for HF antenna.
* Added "check box" for the RN2xx3 version on back silkscreen. 
* When we ship a 1117-series regulator, for some time now we have been using the LDL1117-series, which has lower dropout voltage and quiescent (0.35V typical, 0.6V max, and less at the loads typical with this sort of device, and 250~500uA Iq), with the high maximum input voltages that are typical of 1117-series. The AP2114 is still offered however. While it will be damaged by input voltages in excess of 6v, it's quiescent current is one tenth that of the LDL1117, making it far better suited for use on batteries (to bring the output of LiPo batteries down to 3.3V)
* Improved layout, both of traces, and with additional vias around the antenna connectors. 
* Starting with the Rev. G, assembled boards will all be 100% ROHS compliant!

### Rev. F
* Correct defect in Rev. E where top silkscreen was omitted. First version to use V-Groove panelization.
