# ZEP; Spoken Sentence Identification
## Description:

Purpose of this ZEP experiment is to measure a participant's ability
to identify (speech) sounds. For each trial a sound is presented.
Participant's task is to jugdge whether a prespecified property is
present in the stimulus or not. In this case it is if a sentence
is negative or positive. Experiment is self-paced, has visual
appealing features, and auditory instruction (Dutch).

Reaction time is measured from the `critical_word_onset` of the `critical_word`.
This onset time needs to be defined per audio file in the input lists.

## Output: chosen value.

Author:
Chris van Run (UiL-OTS) <labman.gw@uu.nl>

Client:
Niloofar Hashemzadeh

Supervisors:
* Prof. dr. Frank Wijnen
* Prof. dr. Hugo Quené
* Anne van Leeuwen MA

## Pseudo randomisation
Stimuli are build up out of pairs. Each pair either carries a negative
or a positive type of critical word. Randomisation is such that there are never
more than 3 pairs in a row with the same type of critical word.

## Installing and starting
* Download and install zep (1.12) [here](http://beexy.org/zep/wiki) for either Windows OS or a Debian based Linux OS.
* Download and unpack this repository
* Run either `windows-terminal.bat` or `linux-terminal.sh` to start up a _command-line interface_ within the unpacked repository
* You can then start up the experiment by typing: `zep ident_pn` or `zep-1.12 ident_pn`

## Acknowledgements
* Speaker of the audio: Dr. Frans Adriaans..
* https://www.vecteezy.com/ for the original owl artwork that was modified by Chris.

## About Zep
Zep is a system for implementing and running (psycholinguistic) experiments. Zep delivers auditory, visual and cross modal stimuli, and provides interfacing with external hardware such as eye-trackers and button boxes. It is based on a multipurpose programming language (also called Zep) which enables you to implement not only experiments but other applications as well.

DISCLAIMER

This experiment script is released under the terms of the GNU General Public
License (see http://www.gnu.org/licenses/gpl-2.0.html). It is distributed in
the hope that it will be useful, but with absolutely no warranty. It is your
responsibility to carefully study and test the script before using it with
real participants.

## To do
* [x] Update output and input lists
* [x] Create visual appealing test-page
* [x] Create visual appealing tutorial page
* [ ] Introduce pseudo-randomisation for stimuli
* [x] Credit speaker of audio
* [ ] Incorporate stimuli files
