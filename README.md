# rofi-screenshot-tool
A GUI tool using Rofi, Maim, FFMPEG, and GPU-Screen-Recorder for ShareX-like functionality.

Dependencies:

Rofi (X11): https://github.com/davatorium/rofi
Rofi (Wayland - Note, have not tested this on Wayland): https://github.com/lbonn/rofi#wayland-support
Rofi Applets: https://github.com/adi1090x/rofi

Install and setup Rofi, then install Rofi Applets. Browse through the screenshot applets to find one of your liking, and optionally configure your applet style.

For my sample script, the following are required. You may use alternatives based on their purpose, and modify the script accordingly.
Maim (A CLI screenshot tool)
Xclip (An X11 clipboard tool)
Kdialog (If on KDE Plasma, is already available. Change this to whatever you use for system notifications)
gpu-screen-recorder (For capturing videos)
ffmpeg (For encoding and transcoding captured videos)
