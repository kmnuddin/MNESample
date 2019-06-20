The task and ERP dta are described in our paper:
https://www.memphis.edu/acnl/publications/pdfs/ejn207.pdf

These are single trial data from n=50 subjects (see spreadsheet) that performed a speeech categorization tasks (/u/ - /a/ vowel continuum)
EEGs were recorded from 64 electrodes along with trial-by-trial behavioral responses (% and RTs)

Data Notes:
1) If there is no behavResp or RT for a given trial, it is counted as a missing value (i.e., subject did not respond within time limit (2 sec). 
2) S1 (and some others) may have fewer than 1000 trials. 
3) Data are eyeblink corrected with PCA, filtered (1-100 Hz), and notch filtered @ 60 Hz. 
4) ​​Variables in MAT files:
subname - subject ID
behavResp - behavioral response for each trial (i.e., reported hearing 'oo' or 'ah')
RT - reaction time (ms). Speed of the response after the stimulus presentation at t=0
trigs - triggers for each trial (1- 5) for each of the 5 speech stimuli
epochs - EEG data (channel x sample x trial)
t - time vector for epoch [-200 800 ms]
Fs - sample rate (Hz)
NumChannels - # of EEG channels (64)
chanNames - names of channel