# What is PHANTOM?
PHANTOM is a toolbox for generating Psychophyscis High Accuracy No-disTOrtion Movie, it is a user-friendly program for making and playing movie, by PHANTOM you can make any kind of movie you want in a psychophysics research, and play it in a high time precision guaranted by the implemented Psychphysics Toolbox as well as a high spatial accuracy. With the geometry transformation algorithm, you can project the movie generated by PHANTOM into a cylndrical surface without distortion.
## Purpose
PHANTOM's primary purpose is to generate psychophysics movies in 1 click, and project it with the correct position setting. It is designed for visual neural network research. Software also support triggering control and marker with supported Microscope system.
## Hardware and software Requirement
### Hardware
Run smoothly on the following setting

Laptop: i7-5500U 2.4GHz,GTX 860M, 16GB RAM, Windows 10 pro,  512GB SSD.

Desktop: i7-4790K 4GHz,GTX 970,24GM RAM, Ubuntu 14.04, 512GB SSD.

Trigger system is tested on a *Zen* Microscope platform with a *Nitional Instrument* IO Box (NI USB 6501).
### Software dependency
PHANTOM require a MATLAB version newer than R2015b,Physicphysics ToolBox 3, GStreamer 1.10 or later version. (Optional) NI-DAQmx toolbox is required for triggering system. 

For detail please see the installtion in  [Userguide](https://github.com/stardust-t/ZebrafishGUI/blob/master/UserGuide/User%20Guide%20for%20Zebreafish%20Projector%20GUI.pdf) or [Zacs Userguide](https://github.com/stardust-t/ZebrafishGUI/blob/master/UserGuide/ZACS%20User%20Guide%20for%20Zebreafish%20Projector%20GUI.pdf).


## For Users
Detailed user guide can be found [Userguide](https://github.com/stardust-t/ZebrafishGUI/blob/master/UserGuide/User%20Guide%20for%20Zebreafish%20Projector%20GUI.pdf) or [Zacs Userguide](https://github.com/stardust-t/ZebrafishGUI/blob/master/UserGuide/ZACS%20User%20Guide%20for%20Zebreafish%20Projector%20GUI.pdf).There are many sample movies in the **Movie** folder, including various kinds of spot and bar stimulation. Report any bug with a reproduce procedure to me by [Github Issues](https://github.com/stardust-t/ZebrafishGUI/issues).

## For Developers
Pull request welcome, also you can e-mail me by havens.teng@gmail.com for more information.

## Copyright
PHANTOM is originally created and developed by **Haotian Teng**.