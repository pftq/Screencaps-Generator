# Screencaps-Generator
Generates folder of interesting screencaps and capture sheet / gallery grid from a video, a little bit smarter than just evenly spaced screenshots (it checks for faces, eyes, blur, blinking, etc).  Useful for having a quick set of options for thumbnails, etc.

Download here: https://github.com/pftq/Screencaps-Generator/releases/tag/20261104

You may also find these useful (one-click to download all [here](https://drive.google.com/drive/folders/1nvQFC5uwsZlf-82LuskCP-qut9xHw-lt?usp=sharing)):
- [Video Debanding](https://github.com/pftq/Video-Debanding) (fixes quality issues with repeat re-processing/compression)
- [Video Compare](https://github.com/pftq/Video-Compare) (to check export errors, differences, etc)
- [MP4 Audio Delay Fix](https://github.com/pftq/MP4-Audio-Delay-Fix) (20ms delay at start of file)
- [Video Frame Sync](https://github.com/pftq/Video-Frame-Sync) (syncing 2 files that drift out of sync)
- [Video Color Match](https://github.com/pftq/VideoColorMatch) (correcting color grading drift)


Example from a music video I worked on here: https://youtu.be/f7r2H5q5LpE
<img width="1145" height="734" alt="image" src="https://github.com/user-attachments/assets/d181878a-e252-437a-b615-2ca7f87901b1" />

<img width="1920" height="864" alt="contact-sheet" src="https://github.com/user-attachments/assets/16c73cdb-9ca7-430d-9cca-01dcca21ad99" />

Credits:
- Python / Tcl-Tk, application and interface
- PyAV / FFmpeg, video decoding
- OpenCV / NumPy, frame analysis
- Pillow, gallery and contact sheet
- MediaPipe, facial landmarks and expression checks
- MozJPEG, JPG encoding
- PyInstaller, Windows packaging
