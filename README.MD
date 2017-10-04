Classification of music into their genre will help to limit the music to the choice of the listener. It can be used for recommendation purposes as well. Music genres are hard to describe systematically and consistently due to their inherent subjective nature.
# DataSet
We have 2530 instances which are distributed among four genres (which is our target variable).
The genres are as following:
* Classical
* Jazz
* Pop
* Metal

We initially did for 10 genres but due to huge data size we reduced our target categories to 4. We selected the above mentioned four genres because they have distinct style of music.
# Data source
We collected the data from a website which provides free and legal download of music tracks based on
their genres.Instead of downloading tracks manually we designed a web crawler using Selenium framework, a web automation tool, in java.
We upgraded our crawler so that it loads dynamically the webpage and download the tracks.
We ran our crawler on 4 different computers simultaneously due to the huge size of the data. It took around roughly 7 hours for each genre to be downloaded.
# Target variable
For our classification task we selected 4 target variables which are the genres. Target variables are as
follows:
* Classical
* Pop
* Metal
* Jazz

# Features
We choose 5 features which are
* Pitch (Chromagram)
In music, the pitch of a note means how high or low a note is.
* RMS
The RMS (Root-Mean-Square) value is the effective value of the total waveform.
* Tempo
Tempo is the speed or pace of a given piece or subsection.
* Roll-Off
Roll-off is the steepness of a transmission function with frequency.
* Zero Crossing Rate
The zero-crossing rate is the rate of sign-changes along a signal.
