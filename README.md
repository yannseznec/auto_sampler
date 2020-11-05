# auto_sampler
 simple minimalist automatic multisampler

Made for some experiments with MICA Game Lab and Tinderbox, in an attempt to make an interesting musical system that is playable over Zoom.

One core idea is to have very minimal controls. 

By default there are 12 sample banks, each with the same length (set globally by the array_size object, in seconds). These have two arguments, a sequential number and the speed at which it will loop (1 is no change, .5 is half speed, 2 is double speed, etc).

the "auto_sample" toggle sets the recording going. Every two seconds audio (from input 1 by default) is recorded into a random array. 

Playback is looped by all arrays. The "number_of_loops_playing" slider controls how many of them you hear, in order (from 0-11 by default)

