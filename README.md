Infinity Conky for ElementaryOS Luna by @raerpo

Screenshot:
https://dl.dropbox.com/u/42476216/ConkyElementaryOS.png

Installation Intructions:
- Open a terminal and run this commands in order:

```
sudo apt-get install conky conky-all
wget -O ConkyInfinityElementary.zip https://dl.dropbox.com/u/42476216/ConkyInfinityElementary.zip
unzip ConkyInfinityElementary.zip
rm ConkyInfinityElementary.zip
chmod +x .start-conky.sh
```
- You can close the terminal.
- In System Settings go to Startup Applications and clic in Add button. In the command box insert `./.start-conky.sh` and clic "Add"
- Close session and enter again.


Modifications from Infinity Conky:
- Remove lua scripts (analog clock)
- Changes in the rev-eng.png image
- fixed size in the /home partition problem
- Time to start conky reduced from 20 seconds to 4 seconds
- Add elementaryOS logo
- Add temperature monitor

---------------------------------------------------------------------------------------------------

Infinity Conky Customized by: www.NoobsLab.com

Customization: Remove many cpu, only 1 processor support added because it can't work for those who own only 1 cpu.
also make this available for Gnome Shell 

Orginal Author
http://harshit1990.deviantart.com/art/Infinity-306921086
