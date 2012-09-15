# UrtDevs-Client

UrtDevs-Client v4.0 (ioquake3 svn 2306)

* UrtDevs-Client is a customized version of ioquake3 for Urban Terror 4.x by Frozen Sand. It includes enhancements that may or may not cause people to ragecry
   

* More specifically, UrtDevs client is bleeding edge ioquake3 with networking cvar overides and dmaHD. Also, there are additional tweaks that improve performance and hit-reg and overall performance

## Features and Improvements:
  
### Added cvars:
  - ```com_nosplash [0|1]``` enables/disables splash screen on client start (set this in your autoexec.cfg)
  - New Networking settings for better performance and more hits:
   * ```*net_maxpackets [30-125]``` (default 62) relates directly to frame rate if you get framerates BELOW, this value adjust it accordingly else if you get a consistent 90/125FPS you may increase it.
   * ```*net_packetdup [0-3]``` (default 1) setting it to 0 has been reported to improve things, but only if you have an extremely stable connection and ping less then 50ms
   * ```*net_rate [25000-125000]``` (Bits persecond) (default 125000) has no effect on bandwith usage, bandwith usage IS directly related to net_maxpackets and net_packetdup 

   
### dmaHD
dmaHD greatly enhances sound quality and precision, and also adds doppler effect to moving entities and projectiles.

### Additional Notes
makefile currently defaults to ```-O2 -mmx -msse -msse2 -msse3``` if your pc is old and suck remove the *msse* and recompile

## Respect!
  - Pugbot and the community 
  - strata for doing most of the work 
  - slackin for testing and coding
  - dmaHD: p5ych0runn3r of apd 
  
## Current maintainers of UrtDevs client
  - [rjc862003] - terrible coder, village idiot, idea bank, maintainer
  - slackin - sacc transparnet console and input leetness
  - [kbar](fly) - website
  - [SudoKing] - coder, maintainer, QVM
  - [TheRick](therick) - server hosting and the occasional random banning 
