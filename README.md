# YouTube-Download-Helper
Addon for YouTube-DL. Makes using YouTube-DL easier.       ![GitHub version](https://img.shields.io/badge/Version-2.2019.3.15-brightgreen.svg)
#### Start of File
### YouTube Download Helper (YtDL-H) Version 2.0 (2.2019.3.15.001)
(C) Copyright 2016-2019 cherioux.
### Getting Started
 This is an addon for YouTube-dl that was built to assist you in downloading videos easier than with just YouTube-dl. 
 
 Note that flora.dll is not up for download yet. It is being worked on as an easter egg. It is not required for proper functionality.
 
 This addon, really a program, which is a bundled combination of two (.exe) and one (.dll) program files, is property of DarkuSoft. All rights are reserved.
 
To run YtDL-H, you must download the binarys from the github page. Place both executables into %windir%, or you can add them to your PATH file. You don't have to add flora.dll to %windir% or the PATH, by the way. That's just an easter egg and can be seen by placing flora.dll and ytdl.exe in any folder. Placing the executables into %windir% makes the experience even better. If you choose to place both binarys into %windir%, you must have YouTube-DL in %windir% also.

You don't have to add any of them to the Windows folder or path if you don't want to. It's better to be skeptical of software you download on the internet that to be niave and let your guard down. For it to work, however, you need to at least put ytdl.exe, ytdlreq.exe, youtube-dl.exe and flora.dll in a folder together. Adding them to PATH or the Windows folder is just for convinence, as you don't have to cd to the folder the files are contained in, as you just type the file name and it just works. 
You can also type 'cmd' into a folder's path (in explorer) and the command interperter will start. Just saying.

For YtDL-H to work properly, you must have YouTube-DL and FFMPEG installed. For the program to work, install YouTube-DL to the Windows directory(%windir%)(or add it to the PATH file..). When you install FFMPEG, the location does not matter. Be sure to note the location, however, as you will need the path to FFMPEG's bin folder when you add FFMPEG to your PATH file.

Once you have installed all 4 components, run the Command Interperter (usually Super Key + X then A, hit yes to the uas prompt.) run the prompt with admin perms, and run 'YouTube-DL -U' (without quotes) to update YouTube-DL to the current version.

Next, type 'ytdl.exe' into the prompt. It should bring up a red ui with the title 'YtDL-H--HomePage(US-Based)V.2.2019.3.15.001'. Note the ending, where it says 'V__'. That is the version and build numbers. These will change. Since this is the first version, however, that's what i'm putting.

If you get past that step (good job),  type a single 's' into the prompt. It does not matter if it is CAPTIAL or lowercase. You should see the prompt return to it's normal state, and see a little 'H' in the bottom of your screen, at the  notification tray. Generally the bottom left.

This means that you have correctly installed all of the programs. To test if you installed FFMPEG correctly, type "FFMPEG" into the command prompt. You should have to wait for a moment then see the usage of FFMPEG. Good job, you installed everything right. That should up your Spirit.

Also note, this will work on windows 10 and XP. XP won't work correctly (that's what im typing this on), but it will work nontheless. The only thing that won't work on Windows XP is FFMPEG because one of the dll files that it requires does not exist for Windows XP. Will work fine on Windows 10, however.

Take a few minutes and familiarize yourself with the keybindings and what to type to start the initial program. Oh yeah, and if you choose to download flora.dll too, and type 'scp' into ytdl.exe, well, just try it. It's not that hard, it's an Opportunity.

### Usage:
Before starting YtDL-H, it's generally a good idea to run an admin prompt. That way, YouTube-DL won't have issues with problems like updating.

Another good idea to do before starting the program (or after, it doesn't really matter--) is to run "youtube-dl -U" (without quotes) into the command prompt. That way, YouTube-DL can grab the latest update if there is one avaliable.

It would also be a good idea to create a shortcut to ytdl.exe and the Command Prompt with Admin perms. That way, you don't have to type as much. If you have some basic knowlege of AutoHotKey, you can make a script to do that for you. 

(If you want the 'H.elp' option to work in ytdl.exe, then place this readme into the same directory as ytdl.exe).

### Okay, Real Usage:
.Start the command prompt, with admin perms. 

.Type "ytdl.exe" (without quotes, of course) into the prompt.

.Press the 'S' key and hit enter. This will start the program.

.Ctrl + Alt + Shift + 1: is the default for YtDL-H. it types 'youtube-dl' into the program. You are expected to paste the link yourself. Will download video at 720p or 1080p.

.Ctrl + Alt + 1: the recommended key combo. This will type out 'youtube-dl', but paste the most recent clipboard content into the command prompt. Press enter. Will download video at 720p or 1080p.

.Ctrl + Alt + 2: the recommended for downloading audio from YouTube. Downloads DASH-M4A at 128kbps. Does not paste clipboard content.

.Ctrl + Alt + Shift + 2: Downloads audio, at a higher bitrate (if avaliable). Downloads Webm Opus at 160kbps. Some players might treat as a video. Does not paste clipboard content. Not recommended unless you want the slightly higher quality.

.Ctrl + Alt + Shift + F2: Downloads video, but at the highest avaliable quality. Downloads the videos audio at the highest avaliable quality. Requires FFMPEG. Does not past clipboard content. 


#### Copyright and eula
 By downloading this program, you agree to not sell, reverse engineer, reupload, distribute in any other way then providing the official download link, and cannot modifiy the source then sell.
 
 You agree that this program is for personal use only, and while you can provide people with download links, it must be a link to the official download. You may modifiy the code if you so happen to have the know-how to reverse engineer the source code, but any modifications you make cannot be redistributed, including but not limited to, changes to ytdl.exe, ytdlreq.exe, and flora.dll.
  
 If you do decide to make modifications to the program, and want to implement them, you can do so by creating a pull request.
  
This program, YtDL-H, is an addon for YouTube-DL. I do not own YouTube-DL, and YouTube-DL is owned by another party. I'm just here to make the experience even easier than it already is.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

I do not condone piracy. Use this for personal use only.

Last updated: March 20th, 2019 at 8:12:57PM.
