# jlearman.jRhodes3d

1977 Rhodes Mark I Stage 73, full-length samples, FLAC format

90 Mb disk space (separable mono: 22MB, stereo: 36MB, stereo vibrato: 33MB)

- Source: https://github.com/sfzinstruments/jlearman.jRhodes3d
- For a wav format version, see https://github.com/jlearman/jRhodes3d-wav

## jRhodes3 family

jRhodes3 is my sampling of my 1977 Rhodes Mark I Stage 73 electric piano, which
I purchased new back in 1978. This sample set is not intended to be a jack-of-all-trades
Rhodes, but rather, it's how I usually set up and used my Rhodes. It was recorded with EQ,
with a treble boost and low-mid scoop, emphasizing the bell tones, and with
substantial bark on the higher velocity layers. There are 5 layers, sampled
to peak at 3dB difference per layer at on the low notes and to maintain volume
throughout each layer. Not all layers are full-keyboard width, as higher notes
don't change timbre as much.

The set includes 67 16-bit full-length samples, with up to 5 velocity layers,
sampling every 4th white key.
The samples were recorded directly from the harp connector.
Samples are encoded in lossless FLAC format to reduce disk space.

## This version: jRhodes3d

jRhodes3**d** has UNlooped full-length samples (up to 25 sec), with mono and two stereo
effect options.  In each case, it's provided with and without velocity crossfade.
(Velocity crossfade blends velocity layers to make timbre transition more smoothly
with velocity.  However, this also causes some phase issues in low notes, so you
get your choice.)

A single SFZ is included with 4 instrument versions via keyswitch:

  * `G7  ` - stereo with velocity crossfade (default)
  * `Ab7 ` - stereo without velocity crossfade (default for Zynthian)
  * `A7  ` - mono with velocity crossfade
  * `Bb7  ` - mono without velocity crossfade

##Effects:

The stereo effect is a mild pitch-shift doubling to create a stereo image, applied in mid-side effect so that it cancels out when summed to mono.
The width for either of these effects is controlled via CC76. CC76 at zero is mono; at 50% gives 100% stereo, and pushed higher
you get "extra stereo."

Tremolo and Autopan are implemented using SFZ opcodes. 

The assigned CC numbers:

- CC7: Main Volume
- CC10: Pan
- CC76: Stereo Width (0 - 200%)
- CC1 (Mod wheel): Tremolo Amplitude (0 - 6 dB)
- CC92: Tremolo Frequency (0.1 - 10 Hz)
- CC94: AutoPan Depth (0 - 100%)
- CC95: AutoPan Frequency (0.1 - 10 Hz)
- CC97: FX delay - Start Time (0 - 2 secs)
- CC98: FX delay - Fade-in Time (0 - 2 secs)

## How-to

Click the green "Code" button above, and choose "Download ZIP". Unpack the .zip
file into a folder of your choice, and load the result into your sample player.  I use Sforzando,
which supports FLAC.  You only need the jSteelDrum-flac-sfz folder and its contents.
The .sfz file in there is what you load into your player.

In addition to the .sfz files in this folder, each sample folder also has
two .sfz files (one with crossfades and one without), so if you only want
one version, you can simply drag that folder wherever you want and it
will have everything you need (but these instructions.)

## Sampling Details

The samples were recorded around 2006, from a Rhodes I had bought
new in 1978.  The samples were recorded directly from the harp
connector, with EQ applied to give the tone I usually used, enhancing
the bell-like quality and carving out low mids.  The stereo samples have
a stereo image added to by applying a 2 cent pitch shift, using mid-side
technique so the effect cancels completely when summed to mono.
Noise was removed from the samples using CoolEdit 96.

This is not intended to be the authentic original unprocessed Rhodes;
it's intended to be what I wanted the Rhodes to sound like most of
the time.

Regarding the naming convention: the 3 is because this was my
third sampling attempt.  (The first was a single-velocity sampling
for dev test purposes only.  The second was aborted for technical
reasons I don't recall.)  The "d" identifies this as the 4th
attempt at processing the samples or mapping the keyboard.

The "d" mono samples are identical to the "c" samples but full-length.

I lost the original sample recordings in a home fire, but fortunately
I did have distribution copies of the original looped and unlooped
soundfont files, and these sample sets are recreated from them.

## Issues

If you have an issue, please open an issue on this github: github.com/sfzinstruments/jlearman.jRhodes3d .
