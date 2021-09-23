# SpeechCommandRecognition

## Required Libraries
1. Python 3.6
2. kapre 0.1.7
3. Tensorflow 2.2.0
4. Scikit_Learn
5. Soundfile


### Data
1. Set 16KHz as sampling rate
2. Record 80 utterances of each command.
3. Save samples of each command in different folders
- Data/forward
- Data/back
- Data/left
- Data/right
- Data/stop

### Run
The Code is written using  __Google Colab__
1. Open ColabNotebook.ipynb and change Runtime to GPU
2.  Upload Data to Google drive and mount Google drive in Colab.
3.  Run the cells in the same order in Notebook.

### Test 
1. Locate the folder where you save your model.h5 file.
2. Start speaking when you see mic in the bottom right pane of the task bar or see red blinking dot in the title bar.
3. If still facing some error try to set the mic recorder time in the previous record function up to 3 sec.
