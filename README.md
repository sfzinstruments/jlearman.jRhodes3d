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

jRhodes3**d** has UNlooped full-length samples (up to 25 sec), with mono and two stereo
effect options.  In each case, it's provided with and without velocity crossfade.
(Velocity crossfade blends velocity layers to make timbre transition more smoothly
with velocity.  However, this also causes some phase issues in low notes, so you
get your choice.)

* The stereo effect is a mild pitch-shift doubling to create a stereo image, applied in mid-side effect so that it cancels out when summed to mono.
* The stereo vibrato effect is similar to the classic Suitcase Rhodes stereo vibrato, except that the vibrato applies to each note individually rather than the whole mix.  This makes it sound very different from the classic effect, but nonetheless it's a very interesting effect.

The width for either of these effects is controlled via the MOD wheel.
MOD wheel at zero is mono; at 50% gives 100% stereo, and pushed higher
provides "extra stereo".  When you load the soundfont, you get 100%
stereo by default, and if you move the MOD wheel, it adjusts accordingly.

Six .szf files are included:
* jRhodes3d-mono.sfz - mono only
* jRhodes3d-mono-no-xfade.sfz - mono only, without velocity crossfades
* jRhodes3d-st.sfz - stereo effect
* jRhodes3d-st-no-xfade.sfz - stereo effect, without velocity crossfades
* jRhodes3d-sv.sfz - stereo vibrato effect
* jRhodes3d-sv-no-xfade.sfz - stereo vibrato effect, without velocity crossfades

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
