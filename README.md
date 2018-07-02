## Overview
This is a reference client for the playback of MPEG-DASH via JavaScript and compliant browsers.Decoding part uses dash.js(https://github.com/Dash-Industry-Forum/dash.js).

## Documentation
Our work extend the code (dash.all.debug.vr.js) and bulid a reference client(index.html) to play VR videos.
We extend the function getAdaptationsForPeriod(voPeriod) in Dash.js,  we Define two new variables srd that represents the location of the video in mpd, and flag that represents the position of the video in the player. The voAdaptationSet's attributes change with the variable srd. Where the video plays is determined by the varible flag.

## Getting Started
First place your page under a web server (do not try to run from the file system) and load it via http in a MSE-enabled browser. The video will start automatically. Switch out the manifest URL to your own manifest once you have everything working. The reference player supports mouse drag to switch viewing angle.

## Demos
![figure1](https://raw.githubusercontent.com/sjtu-medialab/dash4vr.js/master/image/1.png)
Figure 1 shows the main view of the videos in the player.
![figure2](https://raw.githubusercontent.com/sjtu-medialab/dash4vr.js/master/image/2.png)
Figure 2 shows the video of the main view.
![figure3](https://raw.githubusercontent.com/sjtu-medialab/dash4vr.js/master/image/3.png)
Figure 3 shows the video after the view is dragged up.
![figure4](https://raw.githubusercontent.com/sjtu-medialab/dash4vr.js/master/image/4.png)
Figure 4 shows the video after the view is dragged down.
![figure5](https://raw.githubusercontent.com/sjtu-medialab/dash4vr.js/master/image/5.png)
Figure 5 shows the video after the view is dragged left.
![figure6](https://raw.githubusercontent.com/sjtu-medialab/dash4vr.js/master/image/6.png)
Figure 6 shows the video after the view is dragged right.
![figure7](https://raw.githubusercontent.com/sjtu-medialab/dash4vr.js/master/image/7.png)
Figure 7 shows the main view after changed main view.
![figure8](https://raw.githubusercontent.com/sjtu-medialab/dash4vr.js/master/image/8.png)
Figure 8 shows the video of the changed main view.
