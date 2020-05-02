### MIDI2txt v1.0.0 ###

Thank you for downloading MIDI2txt. This python program is designed to convert a MIDI file (.mid) into a list of numbers separated by a comma corresponding to the notes played in the order that they are played. The program will take all MIDI files in the same directory and output a corresponding text file (with the same name as the MIDI file).


### For example ###

If a MIDI files contains the notes (in order of being played): 
C3,C3,D3,E3,C3

the program will produce a text file (.txt) that will have one line:
60,60,62,64,60


### Requirements ###

- Python 3 installed

- Mido library installed (if you don't have it type 'pip install mido' into a terminal for unix systems) 


### Instructions for Unix systems ###

- Move the MIDI2txt.py and run.sh files into the same folder (any folder you wish)

- Move the MIDI files you want to convert into the same folder as the MIDI2txt.py and run.sh files

- Double-click the run.sh file and the text files will be generated

- for ease of viewing/selecting the text files, make sure to view the folder in order of 'Kind'.


### Instructions for Windows ###

- Move the MIDI2txt.py into any folder you wish

- Move the MIDI files you want to convert into the same folder as the MIDI2txt.py file

- Run command prompt

- Change the directory to the folder containing MIDI2txt.py

- Run the python script 'python MIDI2txt.py'

- for ease of viewing/selecting the text files, make sure to view the folder in order of 'Type'.


### Questions ###

If you have any questions feel free to email me at theaussietinker@gmail.com


