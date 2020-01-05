# audio-codec-with-negative-losses
extracting wave signal information from audio data and using it in codec/audio editing/restoring, communication, industrial vibration analysis, visualizing/rapid filtering/directional positioning voices in virtual reality

_______________________________________________________________________________________________________

Audio signal statistical analysis  concept idea for:
audio compression, that may be considered to have "negative losses"; or output audio quality may be better, than contained in original data stream;
(well, "The True Original Audio" ends at microphone membrane anyway)

audio (music) conversion to note list and lyrics text, audio signal analogue to "optical character recognition"

"separating" single instruments or their sub-components (single drum, guitar string tone,…) from music stream and option to edit/replace/move_around and re-inject modified data

processes, that may be called "singers voice swap" and ""edit song lyrics" in existing audio stream"

mechanical world usage: failure analysis and signalization/localisation of misbehaving elements in various systems (production lines, cars, planes, rockets, buildings…)

visualization of (option to be frequency-filtered) audio source directions as overlay layer in military or law enforcement FPV-optical devices; "replay function": rewind audio data of environment and locate precise direction of a gunshots, explosions; or in infra-sound weapon usage suspicions…

_______________________________________________________________________________________________________
Process:

input is digitized audio stream, both real-time or  pre-recorded stereo or more channels, with known microphone 3D positions

First process element is converting audio to second order differential stream(?)
( (Xi)-(Xi-1) + (Xi)-(Xi+1) ), this function's sign swap should give locations for 'almost all' and 'almost exact' different sine wave positions in audio data stream timeline.


Second step is statistically finding "probably missing"(cancelling out) and overlapped wave peaks and correcting the "wave peak location data" stream – its should be extremely simple step, by grouping 'peak locations' into groups, based on constant time length between them.

There are also audio signals, that have frequency sweep ; processed from remains after 'constant frequency' wave separation, as signals, that 'did not fit into pure tone wave list'.

And mixed waves, that build up from original+reflection from surface… (Removal of reflected part with keeping data for later processing??)

And harmonics…

Third step is rebuilding amplitudes, as minimal amount of waves with their own amplitudes, that is needed to rebuild original signal.


Final data format:

[time frame number][frequency data, two for sweep][starting amplitude, end amplitude][wave duration][signal source coordinates X Y Z][wave's harmonics: N-ht,amplitude]…

Other features: grouping of different waves as "named instruments" and further optimizing their storage, for example periodical drumbeats have their [count] and [interval]; grouped instruments benefit: example: swap instruments or changing/editing singer's voice afterwards.
