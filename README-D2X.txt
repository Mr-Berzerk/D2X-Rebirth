                         __________
__________/ D2X-Rebirth /


http://www.dxx-rebirth.com


0. Introduction:
================

   DXX-Rebirth is based on the late D1X and D2X source ports (which, in turn, were based on the original
   Descent source and LDescent). The Rebirth Team has spent a lot of time working to improve the source code
   by fixing old bugs and adding some improvements, while always staying true to our philosophy: Keep it Descent!
   It is the goal of DXX-Rebirth to keep Descent 1 & 2 alive and well, updating them for modern PCs while also
   keeping them the same games you remember playing back in 1995!
   If you have any questions, comments, or suggestions, contact zico [at] dxx-rebirth [dot] com, or come to
   our forum: http://dxx-rebirth.com/frm
   Now Material Defender...Prepare for Descent!


1. Features:
============

   DXX-Rebirth has every little feature you may remember from the original Descent 1&2 and much more.

   For example:
   * Full compatibility with Descent and Descent 2, including all expansions and third-party levels.
   * DXX-Rebirth runs on your favourite Operating System. We officially support Linux (and other *NIXs), Mac OS X and Windows. The source code can also be compiled on many other systems!
   * OpenGL provides fast and smooth rendering - even on low-end systems.
   * Optionally you can enable several effects like Transparency, Colored Lighting, Texture Filtering, FSAA, etc.
   * Thanks to SDL, a wide variety of Joysticks are supported. Also you can use more Joysticks, buttons and axes than you can ever operate in your state of evolution.
   * Joystick, Keyboard and Mouse can be used simultaneously.
   * The games can display all resolutions and aspects supported by your monitor, including an option for VSync.
   * Besides MIDI and CD-Audio (Redbook), you can play your own custom Music from your hard drive or a separate AddOn.
   * Both games can utilize special AddOn packs to replace or expand the original game content.
   * Multiplayer via UDP protocol provides a fast and easy-to-use LAN and Online action. This includes reliable communication causing less glitches due to lost packets.
   * The ingame Demo-recording system has been improved. Demos are less glitchy and smaller while still still being backwards-compatible to earlier versions of the games.
   * Higher game speed will not cause glitches such as unacceptable fast homing projectiles, incredible high damage caused by several collisions or Fusion cannon, etc.
   * Player files, Savegames, Demos and Missions from DOS-Versions of the games can freely be used in DXX-Rebirth and vice versa.
   * Mac Command keys are now working - see F1 Help. Command-Q works much like a normal Mac program
   * Even more ...


2. Installation:
================

   Since DXX-Rebirth is a source port of the original Descent engine, you need to have the original game files to play it.
   If you already have the originals you can get the files from your CDs or from the installation directories.
   If you once bought the game(s) from GOG or Steam, you can use these files/installers as well.

   2a. D1X-Rebirth
   ===============

      To install D1X-Rebirth, unzip the release into a folder (i.e. C:\Games\D1X-Rebirth). You must then copy
      some game files from the original installation folders to your Rebirth installation folder. The default
      location of the game files from GOG.com are C:\GOG Games\Descent. The files that you will need are:

      descent.hog
      descent.pig

      Copy these files to either the main Rebirth folder (i.e. C:\Games\D1X-Rebirth) or a /Data subdirectory
      (i.e. C:\Games\D1X-Rebirth\Data). Then run d1x-rebirth.exe in the main folder, and you're all set!

   2b. D2X-Rebirth
   ===============

      To install D2X-Rebirth, unzip the release into a folder (i.e. C:\Games\D2X-Rebirth). You must then copy
      some game files from the original installation folders to your Rebirth installation folder. The default
      location of the game files from GOG.com are C:\GOG Games\Descent 2. The files that you will need are:

      descent2.ham
      descent2.hog
      descent2.s11
      descent2.s22
      alien1.pig
      alien2.pig
      fire.pig
      ice.pig
      water.pig
      groupa.pig
      intro-h.mvl and/or intro-l.mvl (-h is high quality, -l is low quality)
      robots-h.mvl and/or robots-l.mvl (-h is high quality, -l is low quality)
      other-h.mvl and/or other-l.mvl (-h is high quality, -l is low quality)

      Copy these files to either the main Rebirth folder (i.e. C:\Games\D2X-Rebirth) or a Data subdirectory
      (i.e. C:\Games\D2X-Rebirth\Data). Then run d2x-rebirth.exe in the main folder, and you're all set!

      NOTE: On the Descent 2 CD, these files (except the movie [.mvl] files) are archived in the file 'descent2.sow'.
            This file is an ARJ archive and can be extracted using 7zip: http://www.7-zip.org/ or by installing
            the game on a Windows/DOS system.


3. Multiplayer:
===============

   DXX-Rebirth supports Multiplayer over UDP/IP.Using UDP/IP works over LAN and Internet. 
   By default, each game communicates over UDP-Port 42424. This can be changed via the menus, command-line argument or .ini files. 
   Please be aware that if you host a game and players want to join your game online via direct IP connection, your specified game port should be forwarded on your router. 
   If you host your game on the Online Tracker and other players join via this method, port forwarding should not be necessary.
   If you only want to join a game, or host a game on LAN (not online), port forwarding should not be necessary. If you do experience problems, please check your NAT settings and/or Firewall.


4. Issues & Feedback:
=====================

   If you run into any issues, please report them to our issue tracker on GitHub:
   https://github.com/dxx-rebirth/dxx-rebirth/issues


5. Legal stuff:
===============

   See COPYING.txt


6. Contact:
===========

   http://www.dxx-rebirth.com/
   zico [at] dxx-rebirth [dot] com
