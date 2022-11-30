# myWiki


- [myWiki {ignore=true}](#mywiki-ignoretrue)
- [Git](#git)
- [Python](#python)
- [Linux](#linux)

# Crash Stuff

## CFC Filter Additional Reading
[Low Pass Filter](https://medium.com/analytics-vidhya/how-to-filter-noise-with-a-low-pass-filter-python-885223e5e9b7)  
[CFC Filters](https://zone.ni.com/reference/en-XX/help/370858P-01/crash/misc_cfc/)

### Table
CFC Filter | 3db cutoff freq | stop damping | Sampling Frequency
--- | --- | --- | --- 
CFC 60 | 100 Hz | -30 dB | <600 Hz
CFC 180| 300 Hz | -30 dB | <1800 Hz
CFC 600| 1000 Hz | -40 dB | <6000 Hz
CFC 1000| 1650 Hz | -40 dB | <10000 Hz

## Git
Command | Quick Help
--- | ---
git add . | Add all files for tracking
git remote refUtils git@github.com:sathearvind/refUtils.git | Create connection to github remote refUtils repository
git commit -m "message" | commit added files to repo



## Python
Command | Description
 --- | ---
https://www.youtube.com/watch?v=UU995a1Abok | Create a local python env in vscode.
df = pd.read_csv('filename') | read csv into a dataframe


## Linux
Command | Quick Help
| --- | ---
find . -name '*.jpg' \| xargs cp -t Pictures2 | Find files recursively and copy them to a target folder. we use the ‘xargs’ command to make ‘cp’ consider the output of ‘find’ as its arguments. Also, we use the '-t' flag of cp, to specify the target directory, without which the program considers the output of ‘find’ as the target directory.
