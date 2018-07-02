## Overview
This is a reference client for the playback of MPEG-DASH via JavaScript and compliant browsers.Decoding part uses dash.js(https://github.com/Dash-Industry-Forum/dash.js).

## Documentation
Our work extend the code (dash.all.debug.vr.js) and bulid a reference client(index.html) to play VR videos.
We extend the function getAdaptationsForPeriod(voPeriod) in Dash.js,  we Define two new variables srd that represents the location of the video in mpd, and flag that represents the position of the video in the player. The voAdaptationSet's attributes change with the variable srd. Where the video plays is determined by the varible flag.

## Getting Started
First place your page under a web server (do not try to run from the file system) and load it via http in a MSE-enabled browser. The video will start automatically. Switch out the manifest URL to your own manifest once you have everything working. The reference player supports mouse drag to switch viewing angle.
