# git-st

Nicer git status. It combines the output of ```git diff --stat``` with ```git status -sb```.

![Alt text](Screenshot.png?raw=true "Screenshot")

## To install

Download the [git-st](https://github.com/rec/git-st/blob/master/git-st) file and save it to your computer, then give it execute permissions with ```chmod -x git-st```.
From there you can either add an alias to the file or add it to you path. Run it from your git repos and rejoice at the sight.

## Integrate with git

Finally, as long as you saved the file as ```git-st``` then you can add it to your PATH (or save it in ```/usr/local/bin/``` for Mac OS users), and then running it with ```git st```, it will find it in the PATH and run it like any other git command.




---
**Note for Mac OS users**

Mac users will need to ```brew install gawk```, as ```awk``` on Mac doesn't have proper support for the ```-v``` option.
Then replace ```awk``` with ```gawk``` in the script.