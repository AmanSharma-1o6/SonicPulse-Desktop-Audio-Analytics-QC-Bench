# SonicPulse-Desktop-Audio-Analytics-QC-Bench
- Built a live audio analyzer measuring RMS, THD, and peak frequencies at 60 FPS using Python &amp; PySide6.  
- Engine processes 1,024-sample blocks via sounddevice and PyAudioWPatch for WASAPI loopback capture.  
- Integrated a 120-bar FFT log-spectrum, 5-band parametric EQ (±24 dB), and oscilloscope trace. 
- Developed rolling Z-score anomaly detection flagging signal spikes outside ±3σ into an SQLite database.  
- Included 1-click CSV export of recorded logs and built portable executable via PyInstaller and OX Alpha AI.
- [Download](https://drive.google.com/file/d/1Ii7M68Jku2SX1LXInAdeecvii4lGvCcD/view?usp=sharing)
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/ab6e366c-4ab8-4635-8ad7-501602124684" />
