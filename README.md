# Harmonization-Visual
A real-time harmonic visualizer that listens through your microphone, detects the fundamental pitch, and displays the overtone series live. It color-codes odd versus even harmonics to reveal the clarinet’s closed-pipe signature and other instrument/voices, with a spectrogram, register indicator, and odd/even ratio meter.

Part 1: Clarinet Sound Analysis (Brief)

The key fact: The clarinet acts as a closed-open cylindrical pipe (reed end effectively closed, bell end open). That geometry strongly favors odd harmonics (1st, 3rd, 5th, 7th...) and suppresses the even ones, especially in the low register. This is what gives the chalumeau its hollow, woody sound.

Overblowing: Because of the odd-harmonic structure, the clarinet overblows at the twelfth (an octave plus a fifth, the 3rd harmonic), not the octave like a flute or sax. That’s why the register key (speaker key) jumps you up a 12th, and why the instrument needs so many extra keys to cover the “break” between registers.

Registers and where energy lives:

Register	Approx. range (written)	Spectral character (In the Key of the Clarinet played)
Chalumeau	E3 to F#4	Fundamental plus strong 3rd, 5th, 7th. Even harmonics very weak (~20-40 dB down). Dark, hollow.
Throat tones	G4 to Bb4	Weak, unstable, fuzzy. Open tone holes disturb the odd-harmonic pattern.
Clarion	B4 to C6	Overblown 12th. Fundamental is much weaker, 3rd harmonic dominates. Even harmonics start creeping in as you go higher. Brighter.
Altissimo	above C6	Upper partials dominate. Fundamental is minimal, fingerings are “venting” tricks to force high partials. Even and odd harmonics more mixed.

Dynamics: Louder playing (ff) adds a lot of upper-harmonic energy (brighter, more “buzzy”). pp is closer to a pure odd-harmonic series with a strong fundamental.
Formants: There’s a broad resonance region around 1500-2000 Hz (shaped by bell and tone holes) that boosts harmonics falling in that band regardless of pitch. Tone holes also act as a high-pass filter above the “cutoff frequency” (~1500 Hz), above which sound radiates out of the tone holes rather than the bell.
Even-harmonic leakage: The ratio of even-to-odd harmonics is a good proxy for embouchure/mouthpiece/reed differences.
Inharmonicity: Slight stretching of partials due to bore taper at the bell and tone-hole effects.
