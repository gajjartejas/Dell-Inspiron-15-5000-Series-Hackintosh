 
 [<img align="right" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/instagram.svg" width="50" height="50" />](http://www.instagram.com/gajjartejas)
 [<img align="right" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/twitter.svg" width="50" height="50" />](http://www.twitter.com/gajjartejas)
 [<img align="right" src="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/reddit.svg" width="50" height="50" />](http://www.reddit.com/u/gajjartejas)

# Dell-Inspiron-15-5000-Series-Hackintosh
Dell Inspiron 15 5000 Series Hackintosh

# Status
Everything working except Intel wireless LAN. The installation was super easy. I have used Lilu and Whatevergreen kext for Intel hd graphics. AppleALC for audio.

# Screenshot
![Screenshot](CLOVER_INSPIROR_15_5000_SERIES_10.14.4.jpg)


# Pro tips

Let me know if with this tutorial you can correctly map the fn keys. [Reddit thread ink](https://www.reddit.com/r/hackintosh/comments/c7zcv5/dell_inspiron_15_5000_series_mojave_success/esre4ot?utm_source=share&utm_medium=web2x)

https://www.insanelymac.com/forum/topic/305030-guide-how-to-fix-brightness-hotkeys-in-dsdt/


## TLDR; Don't buy DW1820A, Buy DW1550 or DW1560 

A comment from reddit thread: 
>  None of intel wifi cards are supported on hackintoshes. I use dell dw1510 card for mine and my mothers latitude. Probably a good choice would be a dw1550 or dw1560 card or google for a compatible non intel card.
[Reddit thread ink](https://www.reddit.com/r/hackintosh/comments/c7zcv5/dell_inspiron_15_5000_series_mojave_success/esk22rn?utm_source=share&utm_medium=web2x)

> WiFi is headache. Recently I have brought Dell DW1820A wireless M.2 adaptor from AliExpress but sadly not properly working with Mojave. Generally DW1820A is 3 types of card available. I choose wrong part no, which is not working properly. There are kernal panic with it.
There are other card available but it is expensive.
So recently I have ordered correct part from AliExpress. I will check when it arrives probably with in a day.[Reddit thread ink](https://www.reddit.com/r/hackintosh/comments/c7zcv5/dell_inspiron_15_5000_series_mojave_success/esk8ogb?utm_source=share&utm_medium=web2x)

> I asked to send me the version with serial number CN-OVW3T3. When configuring Hackintosh, it turned out that the subsystem code is 1028: 0023 (typical for CN-08PKF4), not 1028: 0021. The adapter turned on 2 times, saw the network, but hung up after 5 minutes, which is also characteristic of the CN-08PKF4 series modules. MAC address does not match the one indicated on the label. This product is tampered with and does not work.[Reddit thread ink](https://www.reddit.com/r/hackintosh/comments/c7zcv5/dell_inspiron_15_5000_series_mojave_success/esr2qlm?utm_source=share&utm_medium=web2x)

## Credits
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [goodwin](https://github.com/goodwin) for ALCPlugFix.
 - [RehabMan](https://github.com/RehabMan) for some patches.
 - [Steve Zheng](https://github.com/stevezhengshiqi) for some patches.
 - [Sniki](https://github.com/Sniki) for some patches.
 - [daliansky](https://github.com/daliansky) for some patches.
 - [Moh_Ameen](https://github.com/ameenjuz) for some patches.
 - [al3xtjames](https://github.com/al3xtjames) for clover-theme-oss theme.
 - [ImmersiveX](https://github.com/ImmersiveX) for clover-theme-minimal-dark theme.
 - And anyone else that helped to develop and improve hackintoshing.
