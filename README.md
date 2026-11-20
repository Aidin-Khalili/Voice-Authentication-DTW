# Voice Authentication with Dynamic Time Warping

![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?logo=mathworks&logoColor=white) ![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

A speaker-authentication system (Multimedia course, B.Sc. in Computer Engineering) that decides whether two recordings come from the same speaker.

## How it works

1. **Voice activity detection** removes silence (`detectVoiced.m`).
2. **Feature extraction** computes acoustic features of each recording (`featuresExtract.m`).
3. **Dynamic Time Warping (DTW)** measures the distance between the two feature sequences; a threshold decides accept / reject (`Voice_part_matlab.m`, `different_speech.m`).

Requires MATLAB with the [VOICEBOX](http://www.ee.ic.ac.uk/hp/staff/dmb/voicebox/voicebox.html) toolbox. Put two `.wav` recordings next to the scripts and run `Voice_part_matlab.m`.

## License

Released under the [MIT License](LICENSE): free to use, modify and share with attribution.

## Author

**Aidin Khalili** — [GitHub](https://github.com/Aidin-Khalili)
