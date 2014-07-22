About this Repo
========================

I recently discovered a painfully simple and easy way to download `YouTube` videos from the command line.  In this case, I am going to highlight how do this in a `Windows` environment.  



## The Program

I used the [youtube-dl](http://rg3.github.io/youtube-dl/index.html) program below.

## Requirements  

The only requirement is that you have `python` installed.  More specifically, versions `2.6, 2.7, or 3.3`.  

To ensure that you are OK, if you can type `python` at the Command Line and get a python interpreter to fire, you are good to go.  

1.  Go to Start, type `cmd` in the search box  
2.  At the `>`, type `python`  


You should see the interpreter.  If not, you will need to install `python`.  

I highly recommend Continuum IO's version of `python`.  The Windows installer can be [found here](https://store.continuum.io/cshop/anaconda/)  

Add your email to their mailing list, it's worth it.  I am in no way affiliated with them, but their open-source version of `python` is by far the best IMO.

## The Quick-Start / Install Guide for Windows  

For those of us that do not like to read documentation, here is a quick-start checklist to get up and running.  It looks painful, but trust me, it's fairly straightforward and in truth, you probably won't break anything.

1.  Install the Windows EXE File, which can be found [here](http://rg3.github.io/youtube-dl/download.html)  
2.  Move the file from your `Downloads` folder to a better location.  I made a folder in `C:\Program Files` called `youtube-dl` and placed the downloaded `.exe` file in that path
3.  Copy the path to your clipboard.  In my case, this is what I copied: `C:\Program Files\youtube-dl`
4.  Click on Start
5.  Right-Click on Computer and select `Properties`  
6.  Select `Advanced System Settings` and Choose `Environment Variables`  
7.  Under `System Variables`, select `PATH`  
8.  Go to the end of the path (protip:  just hit `END` on your keyboard)  
9.  Paste in the directory where you saved the `.exe` file.  Again, I simply pasted: `C:\Program Files\youtube-dl`
10. Click `OK` a few times until you exit the settings area  


If you aren't familar with modifying your `PATH`, that's ok.  We want to be able to pass commands to our computer.  For each command, our machine will need to know which program to use.  All we did was tell it to search for the `youtube-dl` program.  When we pass the appropriate command, our machine will ___magically___ know what to do.  


## Example  

Click the `Start` button, and in the search box, simply type `cmd`.

When you get the command prompt, type the commands below.


```
chdir 
youtube-dl "https://www.youtube.com/watch?v=2iE4uEsaBF0"
ls -la
```


Ohhh yeahhh......
