# Version v1-9-48-84

**Source Commit:** `c6ff7be` (Based on `c6ff7be09df03a6a06b81d7cf3d43fd55c3ee43c` in `ucritair-firmware`)
**Build Date:** 2025-12-26 13:00:22 CST

## Changes

* c6ff7be0 Aseprite cleanup
* f662908d Minor glyph update
* 504a9509 Locked game behind password
* bc39acdf Added an erase logs option and made everything more difficult
* 1cd9a41e Added SD config option
* f19afa92 Added time config screen
* d67733e3 Added battery indicator
* f9175564 Fixed some bugs
* e1aeb895 First research version ready for testing on embedded
* 4eea3200 Added eink display and build flags
* d49673b5 Minor build changes
* b8d837b4 New e-ink code working on embedded
* 0737d4dd Full eink impl working on desktop
* f80a7938 E-ink sim on desktop
* 0fc87177 Edited python reqs
* f1f71094 Compatibility changes for graphing on desktop
* 7cc7d957 Changes made while working on docs
* 973485ca Moved B64 de/en-code to editor and removed
* d2d5a5a3 Further cleaned up CMAKE
* ddf1354e Cleaned up CMAKE
* a2bd5d6e All asset gen moved to new system
* 92ee2f38 Items done
* 4a6d4312 Only items and sprites remain
* 296dc0dd Reforming asset gen
* 639b3926 Made editor external
* c0c1a88b Editor ensmallification
* 900e2231 Editor tool framework
* 553a2ee6 Requirements file
* 91ccb0a1 Merged main
* fb983e18 1.9.48.84 incorporated radio and wifi code
* df562ce4 Merge branch 'wifi-development'
* 23de7d1a Build modifications
* 2b572122 Merged in docs deletion
* bd9575ed Tore out docs
* 1d237313 WIP
* 5a1a24af Merge branch 'wifi-development' of github.com:EntropicEngineering/cat_software into wifi-development
* 907d416e Pre-flash commit
* efd816bc added helper meshtastic PSK conversion scripts
* 1b233e53 Cleanup
* 0be89bd6 New build utils
* 63adb05d WIP
* a6f0a480 WIP
* a42ea792 Hex shortnames
* b88865bb Usernames not showing up
* d6d82f78 Merged in radio channel stuff
* a0cc8009 editor changes
* 0b6d4a15 Improved prop editor
* b0cde175 Removed dev skip from stroop
* 66858846 Assets
* 1ec79156 Merge branch 'mini_assets' into wifi-development
* 19575407 Merge branch 'editor-improvements' into wifi-development
* 0ad80644 Debug output
* 856c810f Inverted survey scores
* 87c6de73 Fix to AQ related bytes -- not sure if survey is fixed
* 47815496 More robust sprite previewing
* d6dd631b QR encoder works
* 2eab4220 Removing legacy preview code
* b60ded47 Cleanup
* 28b11b7c Better scoring
* f25c5ecb More stable menu text
* 0e76bc59 Better survey graphics
* b8751b84 Automatic auth in stroop
* 4c5e8736 added channel configuration, nodeinfo, channel index tx,rx
* fbbad72e Survey WIP
* 07fd2220 Survey WIP
* 51020ca3 Add guanaco and theme (devconnect 2/3)
* 73597820 Add more crafting ingredients (devconnect 1/3)
* 0b154ad9 Added timer to stroop
* 7cd32ae9 Amended NRF to RP values again
* 3776b02d Adjusted values sent to RP
* 3d512027 Patch to credits, more sensible combined stroop
* 90b37aa1 Always-awake option, data upload
* 32136f86 Merge branch 'wifi-development' of github.com:EntropicEngineering/cat_software into wifi-development
* 9e7175f3 WIP
* 9c076089 WIPgit add -A
* 6a99430f DM fixes
* 30accfaf More chat GUI
* a7fd1bff More chat graphics
* 2e853eb3 Start of public/private message distinction -- weak polling for node info. Keyboard UX
* 7b0b2b0a Chat MVP
* 58e304d0 Added build flags for radio/wifi, added radio api
* e4b46100 Took out useless menus
* d2fc9cf1 sensor readings
* a048fc04 fixed RNG for packet id issue
* 67fadb45 WIPgit add -A
* 53878cd8 WIPgit add -A
* 3b8dd37c added test text decode callback
* 27b6bf5d Edited out LoRa stuff and popped RP back in
* 419fea71 Commit before taking out LoRa prior to flash
* 3085ec2a WIPgit add -A
* a84e0d80 increased the ring buffer size, added timeout to msht_process(), decreased startup wait, etc
* 5f66a48c Added in auth button
* 1ad9a93a Merge branch 'e2e-comms-wip-nrf' into wifi-development
* 29256040 WIP
* 7daa7ac8 Authenticate with cloud
* c6bcea99 WIPgit add -A
* 48362405 WIPgit add -A
* a5a12987 Merge remote-tracking branch 'origin/meshtastic-development' into wifi-development
* fd558107 Laying groundwork for radio chat
* 4d784c52 this is truly awful but got TX tested working, needs to be cleaned up heavily, and RX added
* edd8fcc5 rebased meshtastic code to wifi-development (via patch) as it already has protobufs
* b6cabba9 Autoconnect
* 0c79c323 Developer-only draft of persistent wifi
* 509e081c Fixed some stupid bugs
* 2f1afb90 There is a weird freeze bug while messing with wifi connection after connecting
* 72f0c72d First working WiFi connection. Minor UX improvements starting
* db722eaa Merged with conflicts
* 0fece2f7 e2e comms with RP
* 687fe25d e2e comms with RP
* 90458865 1.8.48.84 Added uCritAir splash
* 39dc807a Merge branch 'development'
* 67a58234 1.8.48.83 typo fix
* eccc2f3c 1.8.48.82 Stroop testing
* d5f93ac8 1.7.48.82 added back button flipping
* 0dcd074a 1.7.47.82 safer food positioning
* 870c38f2 1.7.46.82 reverted config to fix e-ink, hid garbage sparkline data
* 2987a58e Fix wood ingredient to be balanced
* c2be645d Added some images to docs
* 0fbfb7a1 Merge branch 'aq-restyle' into docs-update
* 082dadae Docs content
* 9fb9666c Docs content
* 19671ede Docs content
* 80c1e4a7 Docs content
* bacf0823 More content

---
*Based on ucritair-firmware commit: c6ff7be09df03a6a06b81d7cf3d43fd55c3ee43c
