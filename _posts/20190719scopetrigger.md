During my debugging recently, I found a problem in using oscilloscope.
I wanted to detect a SPWM waveform but the display was always wrong.
At the beginning, I thought it was my code's error. but no matter how I modified my code, the problem still exsited.
![Image](img/20190719waveform1.JPG)
Finally, I found it was because the triggering mode of oscilloscope was set as rising edge mode as default.
So I switch the source to a square wave，the display became normal.
![Image](img/20190719waveform2.JPG)
