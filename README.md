# KICK-GNR8R GUI BY DIGITAL DIVINITY

Run/Install using start_windows.bat or start_unix.sh.<br>
This will Install requirements and create a VENV.<br>
Mainly tested on Windows. Should work on OSX/Linux.<br>



### GIT & FFMPEG is required. <br>
OSX users can install by using homebrew: ```brew install ffmpeg```<br>

for windows: start_windows.bat will automatically check for ffmpeg and download icedterminals MSI package. <br>

Requires Python 3.10

Includes additional features such as:<br>
- Model merging
- Instant input load for variation
- Batch looping
- Local model training
- Input Wave Generation
- Model Trimming

Features are made accessible through an extension API; look in the extensions folder for examples!

## Note:
- Local Model Training is not recommended for systems with less than 8GB of VRAM.
- Please import your models through the included model importer. This ensures the models are trimmed and have the correct format for the filenames for use in     auto-complete.
- ```launch_script.py``` can be ran directly from your python interpreter if you do not want to use a venv.







