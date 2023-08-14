

Use HxD (float, 4bytes, big endian)


GAME TIMER
\System\PC\SC4Specific.u
6546 5d0a 0952 6563 6f76 6572 7900 384d
3e22 b004
b004 controls the game timer in seconds:
BYTE2 BYTE1
default game timer is 04b0 = 1200 seconds = 20 minutes


5802 is 10 minutes
b0a3 is 698 minutes
c003 is 16 minutes



C:\\dev\\Unreal-Library\\CLI\\bin\\Debug\\SC4Specific.u


\System\PC\SC4Specific.u
Play_Beep_raUF_nextFlag_prox


PROXY SENSOR
\Packages\_Common\Sounds
LD_Common.uax
Play was replaced with Dont in 2 places
Switching them back to Play makes the 




DRONES
\System\PC\SC4Inventory.u
0115 e302 5b04 5ea5 0101 017d 0360 a501
220 5
5 controls drone count


GRENADES COUNT
045e a501 0104 7104 5fa5 01d3 007d 0360
a501 220 5
5 controls grenade count


JAMMERS COUNT
2a73 0101 0000 0049 3ed1 e403 0a4d 5e0f
1510 1485 0a4d 5e00 007d 0360 a501 220 6
6 controls number

JAMMER DURATION
0100 0000 1f1a 3dd4 030a 4d5e 0f15 1014
850a 4d5e 0000 7e0a 48a5 0124 0000 3442
2400003442 is 45 seconds
240000a041 is 20 seconds (big endian)

JAMMER TEXTURE
Jammer texture removed in
\Packages\_Common\Textures\Interface_txt.utx
Jammer renamed



VISION Movement Detection sound
\Packages\_Common\Sounds\SFO_Equipment.uax

Disabled via Play_Vision_mov_detect renamed to Dont_Vision_mov_detect



REMOVE GOGGLES
Interface_STM.usx
goggle_total and UH_MERC_Helmet renamed
so mercs dont have as big a hud




Engine.u
MERCINARY JUMPING disabled in by renaming bPCJumpMerc



REORDER MAPS
Menu_Text.ute










OLD
Joshhhuaaa's Double Agent tweaks guide. Includes a standalone download of SvM and fixes for framerate and resolution among other common problems you may encounter.
https://steamcommunity.com/sharedfiles/filedetails/?id=935210001

Patch 1.02 of Double Agent required for online play:
https://drive.google.com/uc?id=1lkaUnUi_AQ2PfDizpJFQo7aUqj0UrZDX



