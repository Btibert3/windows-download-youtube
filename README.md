About this Repo
========================

I recently discovered a painfully simple and easy way to download `YouTube` videos from the command line.  In this case, I am going to highlight how do this in a `Windows` environment.  



## The Program

The used the [youtube-dl](http://rg3.github.io/youtube-dl/index.html) program below.

## The Quick-Start / Install Guide for Windows  

For those of us that do not like to read documentation, here is a quick-start checklist to get up and running.  It looks painful, but trust me, it's fairly straightforward and in truth, you probably won't break anything.

1.  Install the Windows EXE File, which can be found [here](http://rg3.github.io/youtube-dl/download.html)  
2.  Move the file from your `Downloads` folder to a better location.  I made a folder in `C:\Program Files` called `youtube-dl` and placed the downloaded `.exe` file in that path
3.  Copy the path to your clipboard  
4.  Click on Start
5.  Right-Click on Computer and select `Properties`  
6.  Select `Advanced System Settings` and Choose `Environment Variables`  
7.  Under `System Variables`, select `PATH`  
8.  Go to the end of the path (protip:  just hit `END` on your keyboard)  
9.  Paste in the directory where you saved the `.exe` file  
10. Click `OK` a few times until you exit the settings area  
11. 

If you aren't familar with modifying your `PATH`, that's ok.  We want to be able to pass commands to our computer.  For each command, our machine will need to know which program to use.  All we did was tell it to search for the `youtube-dl` program.  When we pass the appropriate command, our machine will ___magically___ know what to do.  


## Example  

Ohhh yeahhh......

```
chdir 
youtube-dl "https://www.youtube.com/watch?v=2iE4uEsaBF0"
ls -la
```
