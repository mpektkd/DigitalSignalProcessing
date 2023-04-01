## DigitalSignalProcessing
NTUA

  - **Part 1:** _Tracking telephone touch-tones_
    - Describe each digit as the sum of two sines
    - Record a sequence in a .wav file
    - Plot the recorded signal using hamming and rectangular windows
    - Calculate the coordinates of the peak of each digit by calculating the frequency from crossings
    - Evaluation by decoding two different signals, as input, into digits 

  - **Part 2:** _Short Time Fourier Transform (STFT) and Wavelets Transform (Discrete Time CWT)_ 
    - Plot the STFT of a signal and then its absolute CWT in the fields of both time and frequency 
    - Compare the analysis quality of each transform
    - By adding some white noise and dirac deltas, after same coparison tasks, we conclude that DTCWT is inferior to the STFT due to the noise.

  - **Part 3:** _Short Term Energy and Crossing Rate of voice and music signals_
    - Using a hamming window we calculate the above from the speech_utterance.wav file
    - Compare them with the respective results from the music.wav file.
    - Conclusion: 
      - Wider window means less precise short term energy
      - Gaussian Noise reduces the crossing rate of the silent spots. This is why we cannot distinguish loud(periodical and wide) from silent 
        noises(aperiodical).
