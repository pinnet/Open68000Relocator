# Open68000Relocator
Open68000Relocator is an Open Hardware adapter PCB that changes the orientation of a 68000 DIP CPU.

![Board](https://raw.githubusercontent.com/SukkoPera/Open68000Relocator/master/doc/render-top.png)

### Summary
[AwesomeInferno](https://github.com/AwesomeInferno/68000Relocator) originally created a 68000 relocator in order to allow the [TerribleFire TF530 accelerator board](https://github.com/terriblefire/tf530) to better fit within an Amiga 500 case. It worked very well, but it slightly obstructed the Kickstart ROM socket, making it almost impossible to use any kind of Kickstart switcher. So I set to rework it, in order to free up some space and applied my standard PCB design practices while I was at it.

Apart from the slightly different form factor, the main modification was to connect the copper pours on both layers to the GND net and to stitch them here and there, while the original board had a GND pour on the bottom and a VCC pour on the top. Now, I'm not a PCB design expert (actually I'm 100% self-taught) so I'm not sure if my change does any good or bad to the board, but that's the way I see most boards out there are done and the way I always do, so I just did it without much thought. I guess we'll see :).

Other minor modifications were the rerouting of some traces and the porting of the project to KiCad 5.

**NOTE THAT THIS BOARD HAD NOT BEEN TESTED YET - USE AT YOUR OWN RISK!!!**

### License
Open68000Relocator is Open Hardware released under the GNU General Public License (GPL) v3. If you make any modifications to the board, **you must** contribute them back.

### Disclaimer
Open68000Relocator is provided to you ‘as is’ and without any express or implied warranties whatsoever with respect to its functionality, operability or use, including, without limitation, any implied warranties of merchantability, fitness for a particular purpose or infringement. We expressly disclaim any liability whatsoever for any direct, indirect, consequential, incidental or special damages, including, without limitation, lost revenues, lost profits, losses resulting from business interruption or loss of data, regardless of the form of action or legal theory under which the liability may be asserted, even if advised of the possibility or likelihood of such damages.

### Get Support
If you need help or have questions, you can join [the official Telegram group](https://t.me/joinchat/HUHdWBC9J9JnYIrvTYfZmg).
