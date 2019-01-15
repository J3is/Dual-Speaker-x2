# Dual-Speaker-x2
<p>Magisk module to enable the earpiece to output media audio on LeEco Le Max 2.</p>

<p>Module name: "DualSpeaker for Le Max 2 - Treble"<br>
Module ID: "dslex2"<br>
Module description: "Systemless Way of Enabling DualSpeaker/PseudoStereo SoundMod for LeEco Le Max 2 (only Treble-enabled devices supported)."</p>

<p>This module enables the earpiece speaker to output media audio on the LeEco Le Max 2, creating a pseudostereo effect.<br>
It is meant to be installed on Treble custom ROMs.</p>


<p>This module replaces "mixer-paths-tasha.xml" inside the "etc" folder of the vendor partition with a modified one.<br>
The file comes from an unmodified vendor partition from the AOSP Extended ROM.<br>
The file contains the following modifications:<br>
<ul>
	<li> "RX0 Digital Volume" has been set to 90;</li>
	<li> A new audio device named "earpiece" has been added;</li>
	<li> "SLIMBUS_0"'s MUX value has been set to "RX0" by default;</li>
	<li> "SLIMBUS_0" has been added to the "smartpa" (speaker) section of "deep-buffer-playback", "low-latency-playback" and "compress-offload-playback".</li>
</ul>
</p>
	
<p>When the module is enabled, the effect is subtle, since the earpiece speaker is not powerful enough to output high volumes.<br>
Speaker's gain value is within safe limits, but the module could still cause damage to the earpiece, <b>USE AT YOUR OWN RISK.</b></p>


<p>Thanks to Dante63@XDA-Developers for his great video, which helped a lot in making this module.</p>
