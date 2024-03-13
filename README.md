![F4FEVR](https://raw.githubusercontent.com/ajantaju/F4FEVR/main/f4fevr_2.webp)

# F4FEVR
Fundamental Evolutionary VR Wabbajack for Fallout4VR.

Features: Three profiles to choose from: Full F4FEVR, Lite and Lite-NoGuns.

Mostly quality of life improvements/visual upgrading/bug fixes and mods that require tricky installations to work in VR. For example [FallUI](https://www.nexusmods.com/fallout4/mods/48758), [Sim Settlements 2](https://www.nexusmods.com/fallout4/mods/73394) and [Point Lookout](https://www.nexusmods.com/fallout4/mods/73394)

Differences: Full includes [Another Pine Forest](https://www.nexusmods.com/fallout4/mods/54027) and [NAC X](https://www.nexusmods.com/fallout4/mods/46722) weather/lighting mod. Lite is more vanilla with [Lightweight Lighting](https://www.nexusmods.com/fallout4/mods/57680) mod and pines disabled. Lite-NoGuns also disables 7 additional lore friendlyish weapon mods.


## Installation:

[Video instructions of clean installation for normal Fallout 4.](https://youtu.be/zwTJ3jImCiQ) Follow procedure but delete Fallout 4VR related folders.

Backup your /my games/fallout4vr/ folder.

Delete your /my games/fallout4vr/ folder.

Delete your appdata/local/fallout4vr/ folder.

Do clean installation of Fallout 4VR. Do not install under /Program Files/ directory, MO2 cannot access files that are in there.

Run Fallout 4 VR once and change setting:

  - Item highlighting set to OFF
  
  - Character lighting set to OFF
  
  - TAA set to ON
  
  - Turn Off [Motion Smoothing](https://steamcommunity.com/app/250820/discussions/0/2251182852569611901/) in SteamVR.


Copy DLC from Fallout 4 To Fallout 4VR.


  - in /data/ folder copy all 32 files that start with DLC


Run [Wabbajack.](https://www.wabbajack.org/ "Remember to install!")


  - Find F4FEVR (in Fallout4VR and check "show unofficial lists") and install into same hard drive where Fallout 4VR is (Make new folder "WabbaF4FEVR" to disks root)
  
  - Hope that it just works.


Open folder where you installed.

Copy the files from "Game Folder Files" to your Fallout 4VR game folder. If updating: backup game folder and delete unwanted files from game folder, then verify files with steam (or equivalent).

Open MO2 that was just downloaded.

- Select profile "A New Start!" in MO2.

- Run F4FEVR from MO2.


Start new game.

Create character.

When you get out of the vault it's time to decide which profile you are going to use. F4FEVR, Lite or NoGuns variant.

While pondering this choice let the game run for about 5 minutes (for all the scripts to finish), then do a manual save and quit the game.

- Select profile "F4FEVR" "F4FEVR lite" or F4FEVR Lite-NoGuns" in MO2 and run it.

Load your manually saved game. (It's always good idea to save manually and load that game, instead of loading quick saves or autosaves from quitting. They can be, let's say "problematic" later.)

If you have selected Full F4FEVR: open NAC X configuration holotape (in Armor/Clothes section of the pipboy)

  - Disable vignette (Visual Setting)
  
  - Disable noise (Visual Setting)
  
  - Disable functional sunglasses (NAC Options Settings)

If using Lite versions ignore previous procedure, and continue.

- Open FRIK settings from pipboys misc section and calibrate. Remember to save to ini when you have good settings.
- Read how to use and configure [Virtual Chems](https://www.nexusmods.com/fallout4/mods/53625/ "Configured with Holotape") and [Virtual Holsters](https://www.nexusmods.com/fallout4/mods/51224/ "Hold favorites button to assign weapon to holster").
- Configure [Bullet Time VATS VR](https://www.nexusmods.com/fallout4/mods/72502) via holotape.
- (Optional) Enable and configure [Fallout4 Upscaler VR - DLSS FSR2 XeSS](https://www.nexusmods.com/fallout4/mods/73715) by pressing END button on keyboard.
- ~~(Optional/Legacy) Enable [VR FPS Stabilizer](https://www.nexusmods.com/fallout4/mods/65961?tab=description) in VR Specific section. Default installation is set to 90 Hz, if you use different refresh rate (or opencomposite) you need to reinstall (right click/reinstall) ands select options that suit your setup.~~
- Save your game. All settings should be now saved and you can continue your game.

Enjoy your adventure!

## Tips

- You can visit mods Nexus page by right clicking on a mod on the list and selecting "Visit on Nexus" (3rd from the bottom)
- Do not save in power armor.
- Power armor helmet can be configured with KabutoVR/PA Helmet Configuration holotape.
- If aiming with scopes seems off, edit BetterScopes.ini eyeOffset value (Default was 2.65) This may depend on headset and/or your pupil distance. You can also set your dominant eye here.
- Activate "Right Grip to Interact - UI fix" in Optional section/MO2 if you use SteamVR to change right hands A and Grip buttons.
- Virtual holsters:
  - Have a weapon in your hand. Move it over a holster sphere, feel light buzz on the controller.
  - Hold Favorites button until bigger buzz, now the weapon is assigned to that holster.
  - Now you can pick up the weapon from holster with Grip Or A button.<sup>aka "Use" button, same that opens doors.</sup> Same button to put the weapon pack to holster.
  - To remove/empty weapon from holster, hold Favorites button with empty hands over the holster sphere until a big buzz informs that holster is empty and ready for a different weapon.
- Virtual chems:
  - With your left hand pick up stimpaks from your left ear and stab em in your right hand! Inhale all accidentally picked up jets!
 - Join the [F4FEVR Discord](https://discord.gg/Mn8FPYtGCK) for terrible support and customization tips.
 - Fork and do your own version of this! Also please fix my load order.

## Testing Phase

- Customize survival with Advanced Needs 76 Holotape. Do not select vanilla Survival difficulty if you want to use this. Activate in MO2 and start testing.
- Portable Junk Recycler Mk 2 is added as untested mod, go test them!

## Notes:
This version does not include Luxor HD textures to keep download size reasonable and fast as we're in testing phase. You could try downloading [Alternative versions](https://github.com/ajantaju/F4FEVR/tree/main/Alternatives) and then update from the main branch.

Made ["FRIK F4FEVR"](https://raw.githubusercontent.com/ajantaju/F4FEVR/main/images/FRIKF4FEVRIndexController.png) Valve Index controller profile to steamVR based on /u/rollingrock16 setup. Use "Right Grip to Interact - UI fix" with this.

I do not know what are good for other controllers.

## Issues/Bugs

- Point Lookout is causing crashing in non-english versions of the game. Disable Point Lookout related stuff before starting a new game or [set game language to english.](https://youtu.be/kvmeHaTfquU?t=51)
