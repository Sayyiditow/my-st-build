# my-st-build
Simple Terminal from Suckless and Luke (https://github.com/lukesmithxyz/st) adapted for Manjaro.

How this build is slightly different from Luke's:

1. Changes back the copy and paste keys to vanilla CTRL+SHIFT+C and CTRL+SHIFT+V
2. Colors have been changed for a smoother look.
3. Uses xterm-256color in stead of the st-256color to fix issues I got with ssh and vim.
4. Uses Source Code Pro fonts.

Other functions such as following urls, copyout command outputs and copy urls from terminal still exist. 

Find full features here:
https://github.com/lukesmithxyz/st

- git clone https://github.com/Sayyiditow/my-st-build.git 
- cd my-st-build
- make
- start using ./st or make a link to this build using sudo ln -s /bin/st st
