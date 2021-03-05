# FF7Sound
Replacement soundfont for the PC release of Final Fantasy VII. Two kinds of font are available, one which expects access to EMU8000 ROM samples (and will only work with Creative soundcards produced after 1994) and another which has those samples. Use the ROM-dependent fonts if you have a Creative card, else use the non-dependent fonts (which have the ROM  samples included) with a softsynth.

May sound like crap without reverb. Also bass. Lots of bass.


### Technique

20 years ago I got the PC version of FF VII for my birthday. I loved the game but was disappointed in the music. I had a soundcard which conceivably could play it, but not enough onboard RAM. Upgrading was expensive and not an option, so I made a custom font. My strategy was to use ROM samples as much as possible and tweak their playback params such that they more closely behaved like Nobuo Uematesu's instrumentation. To compensate for the lower amplitude and comparative weakness of the ROM samples, I doubled up the number of samples and/or instruments per preset and increased the volume release envelope, creating something of an echo effect (which FFVII's samples have a lot of).
