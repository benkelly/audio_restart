# audio_restart
For MacOS/OSX, ever open your Mac from sleep or hibernation to discover that you have no sound? Too lazy to restart? Who isn't!

This is just a simple bash script with the two command to terminate and reload the audio drivers so you don't have to close all your tabs!

### Don't know how to runs scripts?
No problem! their not too tricky! Lets start with saving this audio_restart.sh file somewhere easy to get at. I like to have my Scripts in a folder called, you guessed it 'scripts' in my User directory.
`/Users/ben/scripts`

So when you open up your terminal window all you need to "cd" "sc" "TAB" and ENTER and your there with your precious little scripts!
`cd scripts/`

So now before the for the first time you can run the script you are going to need to give it pirmission to be able to run. This a simple command you do in the folder that you saved the script.
`chmod -x audio_restart.sh`

Now you should be already to hear your rock again, all you need to enter is
`./audio_restart.sh`

you'll be ask for your user password due to the command needing sudo permission, but you should be able to hear again (hopefully!)! Happy days! 
