# 256-HW3-Basic-Synth-Plug-In
##Walker Davis
###Romain Michon and Tim O'Brien
####extensive help and explaing from Mark Hertensteiner and Prateek Murgai

[Link!](https://www.youtube.com/watch?v=tUZAfj_6Vvg)

Unfortunately, the plug-in I am submitting is pretty terrible.  I am unable to connect the visible plug-in slider to its corresponding faust parameter within the sawtone.h class.  I think this assignment requires a C++ and programming level of proficiency that far exceeds mine.  Fortunately, several of my classmates were nice and patient enough to walk me through the steps needed to make the plug-in work at a most basic level(thanks again Mark Hertensteiner, Prateek Murgai, Orchi Das, and Mike Olsen).  

Although I did not mess with it in the video, the one slider does not work.  As I could not get a gain slider to work, I decided not to bother adding the other visible sliders if they did not work.  Also, the plug-in itself does not register as a MIDI-specific plug-in; it can be opened as an Audio plug-in, but works at a more limited state as it only responds to mouse-clicks on the windowed keyboard.  Again, the faust saw-wave is really nice and thick, but I was unable to execute any adjustable ADSR or filter parameters, which would have been cool.  

Eventually, I would like to come back and rework this assignment.  I plan on taking 106B next quarter, hopefully after that I can make a more functional plug-in.


##Controls
-onscreen keyboard and external MIDI input communicate standard notes
-option box does although user to specify incoming MIDI information
-gain slider exists, but does not adjust gain



##Potential Improvements/things I do not know how to do
-add functional sliders for gain, filter freq and resonance, and ADSR
-make GUI look much nicer
-eventually get rid of onscreen keyboard
-make this plug-in a MIDI only plug-in

