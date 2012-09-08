UrtDevs_client
===========

UrtDevs client v4.0 (ioquake3 svn 2306)

* UrtDevs client is a customized version of ioquake3 for Urban Terror 4.x
  by Frozen Sand. It includes enhanced sound hacks that may or may not be
  accepted for league use.

* More specifically, UrtDevs client is bleeding edge ioquake3 with SACC and dmaHD.
  Also, there are additional tweaks that allow you to remove ambient background
  noise and music in all base maps and most third-party maps.

* NEW INFORMATION REGARDING AMBIENT NOISE REMOVAL !!! READ !!!
  It is not possible to add extra sounds or hear things further away unless
  a server is modified to allow it. All "play a sound" commands are sent by
  the server and are ONLY played when the client receives them. The same
  sounds one hears with background noise will be exactly the same without it.
  Some are making assumptions that this is an unfair advantage, yet they are
  possibly fans of other custom clients such as Mitsubishi and would gladly
  use ikalizer. Because of this unneccessary controversy, all builds released
  by the maintainers will have the sound removal feature completely disabled.
  If you want it, compile it in yourself!
 
  
* Added cvars:
  - s_envSoundEnable [0|1] -- to enable or disable ambient background sounds.
  - com_nosplash [0|1]     -- enable/disable splash screen on client start
                              (set this in your autoexec.cfg)

* For those familiar with SACC, the defaults in UrtDevs client have been slightly increased.
  The default values are much higher but you may still tweak them to lesser
  values. YMMV depending on the throughput of your connection.
  as of version 4.0 all the networking related cvars have been RENAMED THIS EFFECTS 4.1.1 AND 4.2.1 use the new cvars or you won't see any effect!
  
  *New Networking settings for better performance and more hits
   *net_maxpackets 30-125 (default 62) relates directly to frame rate if you get framerates BELOW this value adjust it accordingly else if you get a consistent 90/125FPS you may increse it 
   *net_packetdup  0-3    (default 1) setting it to 0 has been reported to improve things but only if you have a PERFECT CONNECTION and pingless then 50MS
   *net_rate 25000-125000 (Bits persecond) (default 125000 has no effect on bandwith usage thats related to net_mapackets and net_packetdup Probly should be locked to 125000

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
  - SACC: Slackin's Advanced Competitive Client [urtdevs]
  - dmaHD: p5ych0runn3r of apd 
  
 *haters can eat bag of baby dick's: if anyone has a problem with this client go bitch at frozensand for not knowing what the f*** they are doing 

* current maintainers of UrtDevs client
  - rjc862003(terrible coder, channle troll, idea bank maintainer,)
  - slackin(sacc transparnet console and input leetness)
  - kbar(website)
  - SudoKing [SudoKing@github] (coder, maintainer,QVM HAX0R)
  - TheRick servers and the occsional random banning 
