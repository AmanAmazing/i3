# i3
i3 setup 
After installing i3-wm 

you have to choose your superkey (mod key). Usually either alt or windows key

next steps: 
1)	Opening terminal - pressing super + enter  
2) Changing the terminal that i3 uses -
	edit the file "~/.config/i3/config." 
	change "bindsym $mod+Return exec i3-sensible-terminal"
	to 	 "bindsym $mod+Return exec alacritty" 
	You can change alacritty to a different terminal of your choosing.
	Remember to download alacritty. 
3) Refresh i3 by - super + shift + r 
4) Now any terminal you open will be alacritty. 
5) Also change the font from 8 to 10-14 since 8 is rather small 

Some of the other keybindings: 
1) kill focused window - super + shift + q 
2) open dmenu - super + d 

Changing wallpaper - Nitrogen 
On ubuntu and debian you can install by using the commands - 
"sudo apt install nitrogen" 
To make nitrogen always open on i3 startup add the following 
to the i3 config file. "exec_always nitrogen --restore" 
You can then use the dmenu to find nitrogen and change the wallpaper 

Changing the bar
The bar is configured in the i3 config file. 
Go on the i3wm.org documentation on how to customise it. 
It'll allow you to change what you are displaying on the bar and 
its location e.t.c 
also add "position top" 


customising alacritty 
find sample config file - "locate alacritty.yml" 
should be in the "/home/username/.config/alacritty" folder
