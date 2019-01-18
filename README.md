# Dual-Speaker-x2
<p>Magisk module to enable the earpiece to output media audio on LeEco Le Max 2.</p>

<p>

## Module details
<ul>
	<li> Module name: "DualSpeaker for Le Max 2 - Treble"</li>
	<li> Module ID: "dslex2"</li>
	<li> Module description: "Systemless Way of Enabling DualSpeaker/PseudoStereo SoundMod for LeEco Le Max 2 (only Treble-enabled devices supported)."</li>
</ul></p>

<p>This module enables the earpiece speaker to output media audio on the LeEco Le Max 2, creating a pseudostereo effect.<br>
It is meant to be installed on Treble custom ROMs.</p>


<p>

### What does it do?
This module replaces "mixer-paths-tasha.xml" inside the "etc" folder of the vendor partition with a modified one.<br>
The file comes from an unmodified vendor partition from the AOSP Extended ROM.<br>
<br>
The latest release of the module comes in two versions: 
<ul>
	<li> The normal one, which has gain for the earpiece set to 92: quieter and less noticeable, but with no distortion.</li>
	<li> The "HighVolume" one, which has the gain set to 100: the earpiece is louder, but the sound could get distorted, especially with bass-heavy music. Also, it has a higher risk of damaging your speaker.</li>
</ul>
</p>
	
<p>

### Better to know...
When the module is enabled, the effect is subtle, since the earpiece speaker is not powerful enough to output high volumes.<br>
Speaker's gain value is within safe limits, but the module could still cause damage to the earpiece, <b>USE AT YOUR OWN RISK.</b></p>


<p><br>Thanks to Dante63@XDA-Developers for his great video, which helped a lot in making this module.</p>
