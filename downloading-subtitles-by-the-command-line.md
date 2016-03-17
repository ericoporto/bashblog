Downloading subtitles by the command line

Today I want to show you guys the awesome tool that's 
[Subliminal, by Diaoul](https://github.com/Diaoul/subliminal). Subliminal allow you to download a
subtitle for a downloaded series or movie by using the command line (did you bought Angry Video 
Game Nerd or PHD Movie and was surprised it had no subtitles in your language?).

First you have to install it. Assuming you have pip and python on your system:

    sudo pip install -U subliminal

After the instalation, you can use the follow command from command line to download a 
subtitle (I'm going to use brazilian portuguese):

    subliminal download -l pt-BR movie-filename.extension

And that's it! Use `-l en` for english subtitles. The software also has a Nautilus extension that
gives cool right click subtitle download for movie files - you can check on the project's webpage
on github.

I just use the command line, right now trying to bake a script to automate subtitle downloading. 

Tags: command-line-tools
