# Open68000Relocator
Open68000Relocator is an Open Hardware adapter PCB that changes the orientation of a 68000 DIP CPU.

![Board](https://raw.githubusercontent.com/SukkoPera/Open68000Relocator/master/doc/render-top.png)

### Summary
[AwesomeInferno](https://github.com/AwesomeInferno/68000Relocator) originally created a 68000 relocator in order to allow the [TerribleFire TF530 accelerator board](https://github.com/terriblefire/tf530) to better fit within an Amiga 500 case. It worked very well, but it slightly obstructed the Kickstart ROM socket, making it almost impossible to use any kind of Kickstart switcher. So I set to rework it, in order to free up some space and applied my standard PCB design practices while I was at it: the main modification was connecting the copper pours on both layers to the GND net and to stitch them here and there, while the original board had a GND pour on the bottom and a VCC pour on the top.

Other minor modifications were the rerouting of some traces and the porting of the project to KiCad 5. Finally, signal names for all the CPU pins were added to the board, making it a useful tool for troubleshooting broken mainboards as well.

The board has been tested and proved to be working perfectly with a TF530 card running at 50 MHz. The Kickstart ROM socket does not get obstructed on A500 mainboard revisions 6A and 8A.1, while on older revisions (3 and 5) it still gets in the way, so it is not recommended for use with them (although it still works perfectly).

### License
Open68000Relocator is Open Hardware released under the GNU General Public License (GPL) v3. If you make any modifications to the board, **you must** contribute them back.

Open68000Relocator is provided to you ‘as is’ and without any express or implied warranties whatsoever with respect to its functionality, operability or use, including, without limitation, any implied warranties of merchantability, fitness for a particular purpose or infringement. We expressly disclaim any liability whatsoever for any direct, indirect, consequential, incidental or special damages, including, without limitation, lost revenues, lost profits, losses resulting from business interruption or loss of data, regardless of the form of action or legal theory under which the liability may be asserted, even if advised of the possibility or likelihood of such damages.

### Support the Project
Since the project is open you are free to get the PCBs made by your preferred manufacturer, however in case you want to support the development, you can order them from PCBWay through this link:

[![PCB from PCBWay](https://www.pcbway.com/project/img/images/frompcbway.png)](https://www.pcbway.com/project/shareproject/Open68000Relocator_V1.html)

You get my gratitude and cheap, professionally-made and good quality PCBs, I get some credit that will help with this and [other projects](https://www.pcbway.com/project/member/shareproject/?bmbid=41100). You won't even have to worry about the various PCB options, it's all pre-configured for you!

Also, if you still have to register to that site, [you can use this link](https://www.pcbway.com/setinvite.aspx?inviteid=41100) to get some bonus initial credit (and yield me some more).

Again, if you want to use another manufacturer, feel free to, don't feel obligated :). But then you can buy me a coffee if you want:

<a href='https://ko-fi.com/L3L0U18L' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi6.png?v=6' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

### Get Help
If you need help or have questions, you can join [the official Telegram group](https://t.me/joinchat/HUHdWBC9J9JnYIrvTYfZmg).
