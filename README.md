# MediaPlayerFrameMoveInconsistentBehavior
Demonstration of Inconsistent behavior of MediaPlayer StepForwardOneFrame and StepBackOneFrame methods
# Issue
Repeatedly calling `MediaPlayer.StepForwardOneFrame()` and `MediaPlayer.StepBackOneFrame()` should switch
between two frames, but video is **moving slightly back**.
