# threelipsync

Computes the weights of THREE blend shapes (kiss, lips closed and mouth open/jaw) from an audio stream in real-time. The algorithm calculates the energies of THREE frequency bands and maps them to the blend shapes with simple equations.

To use the microphone call startMic(). To use an external audio file from an URL use startSample(URL). Remember that the webpage should be https in order to use the microphone.
