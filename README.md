# Screencaps-Generator
Generates folder of interesting screencaps and capture sheet / gallery grid from a video, a little bit smarter than just evenly spaced screenshots (it checks for faces, eyes, blur, blinking, etc).  Useful for having a quick set of options for thumbnails, etc.

Download here: https://github.com/pftq/Screencaps-Generator/releases/tag/20261104


Example from a music video I worked on here: https://youtu.be/f7r2H5q5LpE
<img width="1920" height="864" alt="contact-sheet" src="https://github.com/user-attachments/assets/16c73cdb-9ca7-430d-9cca-01dcca21ad99" />

Credits:
- Python / Tcl-Tk, application and interface
- PyAV / FFmpeg, video decoding
- OpenCV / NumPy, frame analysis
- Pillow, gallery and contact sheet
- MediaPipe, facial landmarks and expression checks
- MozJPEG, JPG encoding
- PyInstaller, Windows packaging
