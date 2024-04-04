# rofi-screenshot-tool
A GUI tool using Rofi, Maim, FFMPEG, and GPU-Screen-Recorder for ShareX-like functionality.  

Rofi Applets (https://github.com/adi1090x/rofi) includes a premade screenshot tool. I recommend starting there to get an idea of how it works and is incorporated into the overall Rofi installation. This repo is for my own personal screenshot applet setup, demonstrating how the default applet can be modified to suit your needs.

Dependencies:

Rofi (X11): https://github.com/davatorium/rofi 

Rofi (Wayland - Note, have not tested this on Wayland): https://github.com/lbonn/rofi#wayland-support 
Rofi Applets: https://github.com/adi1090x/rofi 

For my sample script, the following are required. You may use alternatives based on their purpose, and modify the script accordingly. 
Maim (A CLI screenshot tool): https://github.com/naelstrof/maim 
Xclip (An X11 clipboard tool): https://github.com/astrand/xclip 
Xprop (For getting active window) 
Kdialog (If on KDE Plasma, is already available. Change this to whatever you use for system notifications) 
gpu-screen-recorder (For capturing videos): https://git.dec05eba.com/gpu-screen-recorder/about/ 
ffmpeg (For encoding and transcoding captured videos) 

Install and setup Rofi, then install Rofi Applets.  
Browse through the screenshot applets to find one of your liking, and optionally configure your applet style. 

I have only used and tested this on X11. There will be differences in packages, commands and arguments for Wayland, so adjust accordingly. 
The provided scripts will also need adjustments, such as your desired output paths for captured screenshots and videos, your rofi config path, and your desired settings for the applet.  
Rofi Applets also provides a sample screenshot script, which I have based mine off of. The primary difference with mine is that I have added the gpu-screen-recorder functionality for capturing replays (shadowplay) and capturing videos.  

When you install gpu-screen-recorder, it comes with some sample scripts. These are very useful, if not for the very least getting an understanding of what its capable of. You may decide to use some of them in your screenshot applet. I recommend moving those scripts to a static location such as where you keep user scripts, but that is entirely optional. If you do, place my gpu-screen-recorder scripts in the same location, otherwise place them where you may typically keep user scripts.
