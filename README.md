

## Block Silent Speech
Blocking the use of "silent speech" communications.
<br>
<br>

### Playing a sweeping tone, in this case a sine wave moving from 1 to 17 hz can confuse silent/whispered speech recognition software:
```
play -V0 -n synth 1 sine 1:17 synth 1 sine 17:1 synth 0.5 sine 1 repeat 100000
```
<br>
<br>

### Playing a 4hz tone can have a muting effect on [silent speech](https://en.wikipedia.org/wiki/Subvocal_recognition) devices.

<br>

***Generate 4hz Tone In A Browser:***
<br>
<a href="https://www.szynalski.com/tone#4,v0.5" target="_blank">Online Tone Generator</a>
<br>
<br>

***Download 'mute-silent-speech.wav' as a .wav file:***
<br>
<a href="https://github.com/amritabithi/Block-Silent-Speech/blob/main/mute-silent-speech.wav" target="_blank">mute-silent-speech.wav</a>
<br>
<br>

***Linux Command Line With speaker-test:***
<br>
```
speaker-test -f 4 -r 4 -t sine -X
```
<hr>
<br>
<br>

### A descending tone can help to reduce high-pitched feedback by guiding the tone lower via predictive algorithms used in the transceiver's software:
<br>

***Download 'lower-feedback.wav' as a .wav file:***
<br>
<a href="https://github.com/amritabithi/Block-Silent-Speech/blob/main/lower-feedback.wav" target="_blank">lower-feedback.wav</a>
<hr>
<br>
