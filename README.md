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
  It has been rumored that the leagues are fed up with "souped up clients"
  and will possibly start banning anyone suspected of using anything other
  than the "official" builds. If such rule is in place, follow it! Do not use
  this client. We are not responsible if you get banned for using this.
  Given that, we hope these admins will realize that pure skill overrides
  any/all usage of a custom client and dismissing this particular one as
  "cheating" without a full understanding of how it works is, to put it as
  lightly as possible, f***ing ignorant. 
  
* Added cvars:
  - s_envSoundEnable [0|1] -- to enable or disable ambient background sounds.
  - com_nosplash [0|1]     -- enable/disable splash screen on client start
                              (set this in your autoexec.cfg)

* For those familiar with SACC, the defaults in UrtDevs client have been slightly increased.
  The default values are much higher but you may still tweak them to lesser
  values. YMMV depending on the throughput of your connection.

* What you can expect to hear / not hear:
  dmaHD greatly enhances sound quality and precision, and also adds
  doppler effect to moving entities and projectiles. It is similar to ikalizer,
  but is cross-platform. You will NOT hear your own player model breathe,
  swim, or use med-kit!!! But you can hear friends/foes do all such things.

* Be sure to direct the haters and accusers to our github so they can see
  that you're not wallhacking.

* respect!
  - Frozen Sand: For the mod we all love.
  - SACC: Slackin's Advanced Competitive Client [urtdevs]
  - dmaHD: p5ych0runn3r of apd 

* current maintainers of UrtDevs client
  - rjc862003
  - slackin
  - kbar(website)
  - SudoKing [SudoKing@github]
