Original question: [https://community.netgear.com/t5/Cell-Service-Mobile-Hotspot/Nighthawk-M6-Pro-Hotspot/td-p/2327394](https://community.netgear.com/t5/Cell-Service-Mobile-Hotspot/Nighthawk-M6-Pro-Hotspot/td-p/2327394)

My response:

I am going to preference this that I made this in a insomniac stupor from 4am to 6am.

Also there is a far cheaper solution to this setup if you go down to the bottom in the final notes.

The Orbi system would work for you, but I think just running wires would be a far better solution.

And if you have COAX (TV LINES) running through the property your setup can be done even cheaper.

 

For background I am a junior network technician, and I have setup networks for family, friends, and enterprise in all kinds of situations from rural to tower apartments.

Personally I would advise you contact a network technician to setup the location for proper coverage and reliability, but in lack of on-site technical support, I will provide a layout you can follow if you wish to continue doing the setup yourself, or have not done the setup already.

 

This is a similar setup I did for my cousin's Barndominium, I will be referring to it as barn for short. 

 

 

# Equipment

**Nighthawk® M6 Pro Mobile Router with Antenna**

[https://www.netgear.com/home/mobile-wifi/hotspots/mr6550/](https://www.netgear.com/home/mobile-wifi/hotspots/mr6550/)

We will be using this for your internet connection since I am to the understanding that it is what is used on ATnT's first responder network and since it has an ethernet jack passthrough.

 

**Suction Cup hangers/mounter (if installed indoors at window)**

[https://a.co/d/91QSdWd](https://a.co/d/91QSdWd)

Used to mount antenna on the inside window.

*You can also use tape if you want, this will not leave residue.*

*This was the first kit I found on amazon when searching "Suction Cup Mounts"*

*You may discover a better solution to mounting the antenna than this, I am putting this here as an option.*

 

**RBK864S — Orbi Tri-band Mesh WiFi 6 System – 860 Series**

[https://www.netgear.com/support/product/rbk864s/](https://www.netgear.com/support/product/rbk864s/)

We will be using this for the main networking of your barn.

*I also chose it since I have heard good things about its Mesh system and because this was the item you made your original post on.*

*I personally prefer TP-Link systems, but this will work the same.*

 

**APC Back-UPS 450VA, 120V, 6 NEMA outlets (2 surge) (OPTIONAL)**

[https://www.apc.com/us/en/product/BN450M/apc-backups-450va-120v-6-nema-outlets-2-surge-battery-is-not-user-replaceable/](https://www.apc.com/us/en/product/BN450M/apc-backups-450va-120v-6-nema-outlets-2-surge-battery-is-not-user-replaceable/)

This is for ensuring the Orbi units have power in the event of a power loss. You can still have internet for a few hours before it actually goes down.

One batter per Orbi location. Or at least a unit at all the critical locations.

*Note that these have to be replaced every few years, but having that redundant power supply is important for internet uptime. Generally cellular and internet services have their own power grid so they should stay up in the event of a power outage. Buying these will ensure your wifi stays up too.*

 

**Planning**

Read through the entire instruction set and make a plan.

Measure twice, cut once; is the best practice when setting up a network. You can't really go back, you have to start from the beginning every time.

Make sure you have enough outlets for when you are going to install the devices.

Making diagrams of the placement is always best.

Even a rough sketch can help you save time in the future and help you keep track of what you are trying to do.

r/homenetworking on reddit is a great place to go to ask questions on this sort of stuff.

[https://www.reddit.com/r/HomeNetworking/](https://www.reddit.com/r/HomeNetworking/)

 

#  Mobile Router

**Placement of the Mobile Router**

Starting off with the Nighthawk® M6 Pro Mobile Router (Mobile Router).

*General rule of thumb, the higher the window, the better, so if you have multiple floors, the top floor is the best floor.*

*Note that electronics also hate getting hot, so the room the Mobile Router is installed should also have cooling.*

*Cooling is a bigger factor than height.*

 

In this setup the Mobile Router will not be designed to move.

**Start Placement Option 1: Install Indoors near Window**

Assuming your barn has windows.

Find the window that is closest to the ATnT tower or gets the best signal.

Install the antenna on the window.

*You can achieve this with suction cups or tape.*

**Start Placement Option 2: Install on a wall and do not drill through the wall.**

Find the side of the barn that is closest to the ATnT tower or gets the best signal.

Place the antenna up as high as possible on the wall.

Tape it or screw it into place.

**Start Placement Option 3: Install on a wall and drill through the wall.**

**Under the assumption you know how to properly drill holes through walls.**

*Make sure there is nothing on that can intrude the holes or you may drill into.*

*Make sure to not have the hole near power lines.*

*Make sure to not install the antenna near power lines. This may degrade the signal.*

*Would advise using putty or some other filler when finished.*

 

Find the side of the barn that is closest to the ATnT tower or gets the best signal.

Find a place to put the Mobile Router, drill a hole from the outside big enough to pass the cables from the antenna through close to the location of the Mobile Router.

Install the cable on the outside, feed it inside.

**Finish Placement**

Route the antenna cables into the Mobile Router.

Ensure the Mobile Router has power and its SIM card installed.

*It is advised to have the Mobile Router out side of the direct sunlight for this can degrade performance due to the sun being the sun and can head up the device causing thermal throttling in the device to stay cool, so put it off to the side if possible.*

*Again make sure the room it is in can stay cool. The closer it is to optimal temperature, the better performant it can be. Note if it gets too cold it can shut down. Also note that the room it is in should not be humid. Humidity can kill electronics, even if sealed.*

 

 

**Mobile Router Setup**

Find the routers user manual. 

For the Nighthawk® M6 Pro Mobile Router, it can be found here:

[https://www.downloads.netgear.com/files/GDC/MR6500/MR6500\_MR6110\_UM\_EN.pdf?\_ga=2.20578744.1249255028.1715421878-937367102.1715421878](https://www.downloads.netgear.com/files/GDC/MR6500/MR6500_MR6110_UM_EN.pdf?_ga=2.20578744.1249255028.1715421878-937367102.1715421878)

*Would highly advise reading it over once.*

 

The plan is to make it used as a data entry point, similar to how a modem would work. We are not going to use it for wireless signals or network processing. It is just going to pass the signal along to the Orbi system.

 

Make sure the Mobile router is plugged in.

*If you bought the APC batter backup unit, plug it into the backup unit.*

 

Connect to the Mobile Router via your phone via the app or use the touch screen, 

*below are touch screen instructions*

*use your best intuition for the app.*

*User Manual Page 18 to connect via the app.*

*You can also connect via the web application on your laptop, but note that we are disabling most of the connectivity settings that would allow you to connect via your laptop and possibly the app; hence why I am emphasizing the touch screen method; so chose your setup methods at your own digression. Again I will give instruction via reference to the touch screen in the manual.*

 

Put the Mobile Router's power mode into Plugged IN.

*User Manual Page 40*

 

 

Disable Mobile Router Wifi

*User Manual Page 38*

 

It may be prudent to add a screen lock, I'll leave that up to you

*user manual page 41*

 

Make sure that Ethernet is enabled

*User Manual Page 50*

*This should be turned on when you put the Mobile Router into Plug-In mode but it might not enable automatically.*

 

Enable IP passthrough

User manual page 51

*99% sure the user manual is incorrect on the setup, but find something that says IP Passthrough and enable it. If you can't find it, I guess set roaming to on.* 

This will be used to allow for the Orbi to work on its own and not need any funky setup.

 

There are far more settings to enable/disable to get the most optimal setup, but for now this should be good enough to get everything working.

 

 

#  Orbi Stations

**Placement - Orbi Home Station**

Place Orbi Home Station by the Mobile Router

*The Home Station is the node with the yellow port. The other Orbi station are just AP nodes also called* satellites\*.\*

 

 

**Orbi Home Station Setup**

Power up the Orbi Home Station

*If you bought the APC back up unit, plug it into that.*

 

Read over the manual found here

[https://www.downloads.netgear.com/files/GDC/RBK863S/RBR860\_RBS860\_UM\_EN.pdf](https://www.downloads.netgear.com/files/GDC/RBK863S/RBR860_RBS860_UM_EN.pdf)

[https://www.netgear.com/support/product/rbk864s/#docs](https://www.netgear.com/support/product/rbk864s/#docs)

 

Pass Internet cable from Mobile Router to Orbi Home Station yellow port.

 

The setup will be just like any normal router setup, from this point forward.

I’m a bit tired so I am not going to add this section, lmk if you need help on this.

 

**Placement - Orbi Satellites**

Place each one with 2 wifi bars on your laptop or phone. 1 bar might not be enough signal and can get wiped out by people walking about. 

The Satellites can hop off each other. So let’s say you have one on the far side of the property, it can jump from one satellite to the next to the next and hit home. It does not need a direct path to home.

 

# Final Notes

You can also achieve a cheaper and better result if you just use normal routers like a TP-Link Archer A7 and just put wire everywhere. So one Archer A7 in router mode at the Mobile Router, run a long ethernet cable to the other side of the barn, put another Archer A7 in AP mode. And bobs your uncle you have full coverage.

If you have coax cable (TV CABLE) you can use that instead of the internet cable and use a MOCA converter instead. Less work and hassle if you have COAX running around the property. This is what I use on my property. 

I have APC backups on all the routers and AP connections.

During black outs we have a full 23 hours of internet before we go full black out.

Works like a charm and costs a whole lot less than 1.3k.

 

If you give me a layout of your property, I can advise you on a much more specialized and cheaper option for you put it will take some time for me to draw up. 

 

 But ultimately, I would greatly advise having a network technician come out and look at your setup. Any junior technician could do it.

 

Lmk if you have questions.

-Aaron
