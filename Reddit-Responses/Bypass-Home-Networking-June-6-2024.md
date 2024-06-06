Answer to: [https://www.reddit.com/r/HomeNetworking/comments/1d9g6a5/comment/l7f3yts/?utm\_source=share&utm\_medium=web3x&utm\_name=web3xcss&utm\_term=1&utm\_content=share\_button](https://www.reddit.com/r/HomeNetworking/comments/1d9g6a5/comment/l7f3yts/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)

Depends on where you are and what plan you are on. Using the Verizon Bypass for hotspot and tethering:

If you are on Visible basic:

In high congested areas like down town, you won't get that good of a connection. You are on the lowest level of Verizon's data hierarchy so you are the last to get data. I would not expect to get better than a few megabits a second here.

In areas like a neighborhood you can expect decent speeds. I generally experienced 30 Mbps down 10 Mbps up. This is enough to stream games to twitch.

If you are on Visible Plus:

You are on the highest tier of the hierarchy of Verizon for 50 GB then dropped down to normal. So you go first to get data to 2nd or 3rd. In 5GUW I have seen speeds up to 1500 Mbps down 200 Mbps up. On average I saw 200 Mbps down 50 Mbps up. Never had a connection loss in any area.

Downloading games and streaming to twitch will use a lot of data. And if you use too much visible will shut down your account, though I have heard most people just make a new account. I would advise metering your account to 1TB a month, most people who go over that get a message from Visible. I personally do 500 GB.

For twitch I would advise using 720p30 at 5-5.5 mbps with a constant rate. This will make the stream look sharp. 1080p60 at 6 mbps is too blurry.

I would advise adding a heatsink to your phone, because it will get hot and it will kill your battery if it gets too hot. This one here should be big enough for most phones and has thermal compound applied.

[https://a.co/d/hFsGNrX](https://a.co/d/hFsGNrX)

"150mm heatsink + pre applied" is what I looked up for that. You can buy the heatsink and thermal pad separately. You can also find bigger heatsinks if you look up 150mmx70mmxYmm where Y is the height you want, 60mm should be more than enough.

Just add the headsink to the back of the phone from the bottom of the camera (where it is flat) to the bottom of the phone were the charging port is. Most phones that distance is less than 150mm, if you phone is bigger, get a bigger one. You also want this directly on the phone itself with nothing in-between the thermal compound (pad) and the back of the phone. If you have something like a flip phone or an all screens phone, use your own digression. You want as much of the back of the phone covered, in some cases you may want to use two heat syncs, one for the main part and one from the side of the camera to the top.

And a fan to go with it:

[https://a.co/d/cSLlz25](https://a.co/d/cSLlz25)

Realistically any small usb fan with a swivel will work. You just need air flow that will go over the top and the back of the phone where the heatsink is. So a fan that is slightly taller than the phone, pointing the fan downwards towards the phone is the goal.

How the verizon hotspot/tether bypass works:

[https://www.reddit.com/r/Android/comments/cmxp66/2019\_bypass\_verizon\_hotspot\_throttle\_no\_root](https://www.reddit.com/r/Android/comments/cmxp66/2019_bypass_verizon_hotspot_throttle_no_root)

Script for bypass if you are on windows:  
[https://github.com/szybnev/TTL-Changer](https://github.com/szybnev/TTL-Changer)

Script for bypass if you are on MacOS/Linux or any OS with a bash shell:

[https://github.com/chessset5/MacOS-TTL-script](https://github.com/chessset5/MacOS-TTL-script)

You can also add a VPN to the computer which will also help with stability. I personally use PIA, but proton is also a good (probably better) option.

How to have other devices go through your computer into the phone so they too get the bypass via WiFi sharing:

Macos:

[https://support.apple.com/guide/mac-help/share-internet-connection-mac-network-users-mchlp1540/mac](https://support.apple.com/guide/mac-help/share-internet-connection-mac-network-users-mchlp1540/mac)

Windows:

[https://support.microsoft.com/en-us/windows/use-your-windows-pc-as-a-mobile-hotspot-c89b0fad-72d5-41e8-f7ea-406ad9036b85](https://support.microsoft.com/en-us/windows/use-your-windows-pc-as-a-mobile-hotspot-c89b0fad-72d5-41e8-f7ea-406ad9036b85)

Ubuntu:

[https://askubuntu.com/questions/318973/how-do-i-create-a-wifi-hotspot-sharing-wireless-internet-connection-single-adap](https://askubuntu.com/questions/318973/how-do-i-create-a-wifi-hotspot-sharing-wireless-internet-connection-single-adap)

Or look up "<OS> wifi sharing" to find the operating system you are using.

# On linux type operating systems, so Macos and the like, you have to use tethering for this to work.

Note you can also connect your phone to a PFSense machine or OpenWRT DDWRT made router and do it that way too.

"usb wan TLL rules <router OS>" in your browser if you want to find other, probably better, guides than these.

OpenWRT: [https://www.maroonmed.com/ttl-modification-for-outgoing-traffic-with-openwrt/](https://www.maroonmed.com/ttl-modification-for-outgoing-traffic-with-openwrt/)

PFSense: [https://docs.netgate.com/pfsense/en/latest/wireless/configuration-wan.html](https://docs.netgate.com/pfsense/en/latest/wireless/configuration-wan.html)

You can also add a VPN which will help with connection stability via OpenVPN or WireGaurd if your VPN service has those config files.

Btw look up Visible Referral Code on their subreddit if you are looking to get $20 off your first month. Note this only works if you do not take the free trial first. If you do take the free trial the referral link is invalid.