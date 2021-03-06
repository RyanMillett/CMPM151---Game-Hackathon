# CMPM151---Hackathon

Created in PureData and Unity over the course of two days.

Our scene is from an ​Asteroids-​like game that features both diegetic sound effects and non-diegetic score. The sound effect elements function by mirroring the on-screen visual events (e.g. explosions and laser blasts) whereas the dynamic music system provides dramatic emphasis influenced by the underlying game state as well as general thematic considerations.

To parallel the game’s feeling of weightlessness, the core musical material is based on probabilistic chromatic mediant relationships between conventional tertian chords—-the idea being that familiar harmonic shapes (i.e. major/minor/augmented triads) would “float” around roving key centers unmoored from a sense of stable tonal gravity.

During non-combat states, the music takes on a more ambient, quasi-meterless character featuring lush pad sweeps created through various additive and FM techniques and generative melodic lines performed by a triangle oscillator meant to evoke the timbral quality of a theremin or ondes Martenot. The laser sound in this state is  a simple cosine wave tuned to the current root in the music. 

The arrival of enemy ships triggers a combat state marked by contrasting musical materials composed of alternating asymmetric meters of jagged, ostinato percussive elements. In this state, the lyrical melody is replaced with a staccato phasor an octave higher and the pad sweeps are removed entirely in order to heighten the player’s sense of danger but also to make room for the influx of combat sound effects. A phase distortion synth is embedded in the lower register to create dissonant sci-fi effects that deliberately elide the distinction between sound-effects and music. The laser switches from the cosine wave to a sawtooth to sound rougher and more aggressive in the more stressful environment.

I designed the game’s dynamic music system. Synth instruments were created through a combination of Pure Data’s native oscillators as well as pre-built patches such as a physically modeled membrane and a replica Casio CZ-101.


Video Demonstration:

https://youtu.be/8q8Q8HTFnD0

![alt text](https://github.com/RyanMillett/CMPM151---Game-Hackathon/blob/main/screen_shot.png)
