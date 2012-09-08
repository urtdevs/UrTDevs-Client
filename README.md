UrtDevs_client
===========

UrtDevs client v4.0 (ioquake3 svn 2306)

* UrtDevs client is a customized version of ioquake3 for Urban Terror 4.x
  by Frozen Sand. It includes enhancements that may or may not cause people to ragecry
   

* More specifically, UrtDevs client is bleeding edge ioquake3 with networking cvar overides and dmaHD.
  Also, there are additional tweaks that improve performance and hit-reg and overall performance

  
* Added cvars:
  - com_nosplash [0|1]     -- enable/disable splash screen on client start
                              (set this in your autoexec.cfg
*New Networking settings for better performance and more hits
   *net_maxpackets 30-125 (default 62) relates directly to frame rate if you get framerates BELOW,
   this value adjust it accordingly else if you get a consistent 90/125FPS you may increse it 
   *net_packetdup  0-3    (default 1) setting it to 0 has been reported to improve things,
   but only if you have a PERFECT CONNECTION AND pingless then 50MS
   *net_rate 25000-125000 (Bits persecond) (default 125000 has no effect on bandwith usage,
   thats related to net_maxpackets and net_packetdup 

   
* What you can expect to hear / not hear:
  dmaHD greatly enhances sound quality and precision, and also adds
  doppler effect to moving entities and projectiles. It is similar to ikalizer,
  but is cross-platform. You will NOT hear your own player model breathe,
  swim, or use med-kit!!! But you can hear friends/foes do all such things.

*addional notes
makefile currectly defaults to -O2 -mmx -msse -msse2 -msse3 if you'r pc is old and suck remove the *msse* and recompile
* respect!
  - Pugbot and the community 
  - strata for doing most of the work 
  - slackin for testing and coding
  - dmaHD: p5ych0runn3r of apd 
  
 *haters can eat bag of baby dick's: if anyone has a problem with this client go bitch at frozensand for not knowing what the f*** they are doing 

* current maintainers of UrtDevs client
  - rjc862003(terrible coder, channle troll,idea bank, maintainer,)
  - slackin(sacc transparnet console and input leetness)
  - kbar(website)
  - SudoKing [SudoKing@github] (coder, maintainer,QVM HAX0R)
  - TheRick server hosting and the occsional random banning 
