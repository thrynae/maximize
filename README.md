This function tries multiple solutions for maximizing the figure window, so it should work on nearly all releases of Matlab and Octave on nearly all OSes (Windows/Mac/Unix). If you know more solutions, please contact me, so I can add it to the list.

1. attempt to set the WindowState property to maximized
2. use JavaFrame to maximize the figure
3. press alt-space followed by x (Windows/Linux hotkey)
4. ugly solution: set the position to the screen size minus a small margin (this includes an attempt to check for a multiple monitor set up, which has a flaky success-rate)

Licence: CC by-nc-sa 4.0

British English SEO:
maximise figure window