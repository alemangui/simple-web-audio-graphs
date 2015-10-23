# simple-web-audio-graphs

Simple web audio examples for the Paris.JS meetup presentation "Web Audio Jam".

All graphs contain an analyser node before the context's destination that is used to display the time domain data in a canvas.

##Graph 1
Contains a simple oscillator node connected to a gain node.

##Graph 2
We get the input from the user media - usually the microphone, but also possibly a line-in device. In this graph, we add a delay node looping through a feedback gain node.

##Graph 3
Loading and playing an external file with a buffer source node.
