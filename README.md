# ThreeLS - threelipsync

Computes the weights of THREE blend shapes (kiss, lips closed and mouth open/jaw) from an audio stream in real-time. The algorithm calculates the energies of THREE frequency bands and maps them to the blend shapes with simple equations.

To use the microphone call startMic(). To use an external audio file from an URL use startSample(URL). Remember that the webpage should be https in order to use the microphone.

An explanation about the theory behind the algorithm can be found here:
https://www.youtube.com/watch?v=89pBiGKXpZI

Here is the package for Unity:
https://doi.org/10.5281/zenodo.5765691
