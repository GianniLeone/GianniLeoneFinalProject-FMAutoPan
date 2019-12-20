# GianniLeoneFinalProject DESIGN

 With permission from Akito, I used his AutoPanner as a starting point for my idea of an FM autopan. 

 Stereo panning is the sensation of changing the location of a sound purely by changing the amplitude of the signal in the left and right channels.
 
 The program is capable of reading a Wave file (non-realtime) to a buffer in the computer’s memory, panning 
 the audio signal along the path of a sine wave with an amplitude of -1-1, and lastly writing the newly 
 edited buffer to a new Wave file. 

 Lines 75-83 are where the panning occurs. A for loop iterates over the entire size of the buffer changing the amplitude of the left and right channels with every new sample. Because the amplitude of audio signals are scaled when multiplied by a constant, the signal can also be continually varied by trigonomic function, in this case a sine wave. This concept can be applied again by multiplying the first sine wave with another wave. This creates a frequency modulated pan signal.

 The amplitude range of digital audio is from -1 to 1. Because there is no code compensating for this, certain combinations of pan depth can lead to values greater than -1 and 1 causing digital clipping. For the purposes of exploration, I decided to leave this phenomenon because it can sound cool if done right.




 