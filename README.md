# jlearman.jRhodes3d

1977 Rhodes Mark I Stage 73, full-length samples

70 Mb disk space

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

jRhodes3**d** has UNlooped full-length samples (up to 25 sec), with two stereo effect options.
few seconds, to save memory and disk space.

* The stereo effect is a mild pitch-shift doubling to create a stereo image, applied in mid-side effect so that it cancels out when summed to mono.
* The stereo vibrato effect is similar to the classic Suitcase Rhodes stereo vibrato, except that the vibrato applies to each note individually rather than the whole mix.  This makes it sound very different from the classic effect, but nonetheless it's a very interesting effect.

The width for either of these effects is controlled via the MOD wheel.

Three .szf files are included:
* _jRhodes3d-both.sfz - stereo is MIDI Program 1, stereo vibrato is MIDI program 2
* _jRhodes3d-st.sfz - stereo effect
* _jRhodes3d-sv.sfz - stereo vibrato effect

## How-to

Click the green "Clone or download" button above, and choose
"Download ZIP".  Unpack the .zip file into a folder of your choice,
and load the result into your sample player.  I use Sforzando, which
supports FLAC.

You only need the jRhodes3d folder.  The rest can be discarded.

## Sampling Details

The samples were recorded around 2006, from a Rhodes I had bought
new in 1978.  The samples were recorded directly from the harp
connector, with EQ applied to give the tone I usually used, enhancing
the bell-like quality and carving out low mids.  The stereo samples have
a stereo image added to by applying a 2 cent pitch shift using mid-side
technique (so the effect cancels completely when summed to mono).
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
(Actually, this set does not include mono samples, but they can be
created by taking either SV or ST samples and summing them to mono,
since the effect is applied using mid-side technique.)
The "d" stereo samples have the same effect applied as "c" but
using different tools (SoX library rather than r8brain.)

I lost the original sample recordings in a home fire, but fortunately
I did have distribution copies of the original looped and unlooped
soundfont files, and these sample sets are recreated from them.
