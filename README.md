<hr>

:warning: **The maintenance and support of this project has been moved to a [new repository](https://github.com/Spellhold-Studios/Sword-of-Noober).**

<hr><br>

![Latest Release](https://img.shields.io/github/v/release/SpellholdStudios/TheSwordofNoober?include_prereleases&color=darkred)<a name="top" id="top"> </a>
![Platform](https://img.shields.io/static/v1?label=platform&message=windows%20%7C%20macos%20%7C%20linux&color=informational)
![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20French%20%7C%20Russian&color=limegreen)

<div align="center"><h1></a>The Sword of Noober</h1>

<h3>A mod for Baldur's Gate II (classical and EE games), Baldur's Gate Trilogy and EET</h3>

</div><br />


**Original Authors:** Pex657 (aka BalanceRD) and Kerintok  
**Mod Website and Forum:** <a href="http://www.shsforums.net/topic/36038-the-sword-of-noober/">Spellhold Studios</a><br /><br />


<div align="center">
<a href="#intro">Overview</a> &#x2B25; <a href="#compat">Compatibility</a> &#x2B25; <a href="#installation">Installation</a> &#x2B25; <a href="#components">Components</a> &#x2B25; <a href="#faq">FAQ</a> &#x2B25; <a href="#credits">Credits</a> &#x2B25; <a href="#versions">Versions History</a></br>
</div>

<hr>


## <a name="intro" id="intro"></a>Overview

Are you looking for adventure, romance, quests, character development? Then you have downloaded the wrong mod. If you are looking to laugh and giggle like a school girl, then you have downloaded the right mod.  
The Sword of Noober introduces a brand new sword to the game. This sword talks too much, is overly powerful, and is pretty useless, but it might make you laugh or even smile.


<hr>


## <a name="compat" id="compat"></a>Compatibility

This mod is designed to work on the following Infinity Engine games: the original Baldur's Gate II (BG2 or just SoA) with or without the Throne of Bhaal (ToB) expansion, Baldur's Gate II: Enhanced Edition (BG2EE), the conversion projects Baldur's Gate Trilogy (BGT) and Enhanced Edition Trilogy (EET).

This is a WeiDU mod, and therefore should be compatible with all WeiDU mods. If you encounter any bugs, please report them on the forum!<br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Notes

*If you've previously installed the mod, remove it before extracting the new version. To do this, run **`setup-tnoober.exe`**, un-install the previously installed main component and delete the :file_folder: tnoober folder.*

*When installing or un-installing, **do not close the DOS window** by clicking on the **X** button! Instead, press the **Enter** key whenever instructed to do so.*

**Disable any antivirus** or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.

## 

#### Enhanced Editions Note

The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.

## 

#### Windows

Extract the contents of the mod archive into the folder of the game you wish to modify (*the folder which contains the "CHITIN.KEY" file*), using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. On successful extraction, there should be a :file_folder: tnoober folder and a setup-tnoober.exe file in your game folder. To install, simply double-click **`setup-tnoober.exe`** and follow the instructions on screen.

Run **`setup-tnoober.exe`** in your game folder to reinstall, uninstall or otherwise change the component settings.

## 

#### Mac OS X

The Sword of Noober for Mac OS X is distributed in the same compressed archive than the Windows one.

First, extract the files from the archive into your game directory. On successful extraction, there should be a :file_folder: tnoober folder, setup-tnoober and setup-tnoober.command files in your game folder. To install, simply double-click **`setup-tnoober.command`** and follow the instructions on screen.

Run **`setup-tnoober.command`** in your game folder to reinstall, uninstall or otherwise change the components settings.

## 

#### Linux

The Sword of Noober for Linux is distributed in the same compressed archive than the Windows one and does not include a WeiDU installer.

Extract the contents of the mod to the folder of the game you wish to modify.

Download the latest version of WeiDU for Linux from <a href="https://github.com/WeiDUorg/weidu/releases">WeiDU.org</a> and copy weidu and weinstall to /usr/bin. Following that, open a terminal, **cd** to your game installation directory, run tolower and answer 'Y' to both queries. You can avoid running the second option (linux.ini) if you've already ran it once in the same directory. To save time, the archive is already tolowered, so there's no need to run the first option (lowercasing file names) either if you've extracted only this mod since the last time you lowercased file names. If you're unsure, running tolower and choosing both options is the safe bet.

To install, run **`weinstall setup-tnoober`** in your game folder. Then run **`wine bgmain.exe`** (or **`wine baldur.exe`** for EE games) and start playing.

## 

#### Note for Complete Un-installation

In addition to the methods above for removing individual components, you can completely un-install the mod using **`setup-tnoober --uninstall`** at the command line to remove all components without wading through prompts.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="components" id="components"></a>Components

The installer includes one single component, the main component.


<hr>


## <a name="faq" id="faq"></a>Frequently Asked Questions

**Q: How do I get The Sword of Noober?**  
A: Talk with Neeber.

**Q: Talking items are lame!, We don't need another talking item**  
A: Agree and agree. This was more for me to learn some coding and to have a little fun.
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

#### Authors: Pex657 (aka <a href="http://www.shsforums.net/user/10778-balancerd/">BalanceRD</a>) and Kerintok


#### Special Acknowledgements to:

- Lady Margolotta, Shed, Jyzabyl, Andyr, Lord-Jyssev, Sir Kalthorine, Grey Acumen, Cmorgan for dialog suggestions and help with coding.
- Gwendolyne: Fixed translations and released version 2.0.0.
- AL|EN: Wrote process which automatically provides Windows, Linux and Mac versions in the same archive file.
- Deratiseur: Provided native compatible version (v1.2).
- MacksimSl: Provided Russian translation.
- Le Marquis (the d'Oghmatiques): Provided French translation.
- <a href="http://www.spellholdstudios.net/">Spellhold Studios</a> team for hosting the mod (<a href="http://www.shsforums.net/topic/36038-the-sword-of-noober/">Forum</a>).

If you wish to translate the mod, have a suggestion, or should encounter any bugs, please report them to the maintainers at the <a href="http://www.shsforums.net/topic/36038-the-sword-of-noober/">mod forum</a>.</br>


#### Copyrights Information

###### The Sword of Noober is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by Pex657 and Kerintok, based on material from the game Baldur's Gate II and its expansion.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp.
###### All other trademarks and copyrights are the property of their respective owners.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="versions" id="versions"></a>Version History

##### Version 2.1.1 (April 05, 2023)

- Fixed russian language label

## 

##### Version 2.1.0 (July 10, 2020)

- Fixed a typo in `HANDLE_CHARSETS` function (replaced *infer_charset* with *infer_charset<ins>s</ins>*)
- Added Russian translation (by MacksimSl).
- Added archive libiconv-1.9.2-1-src.7z with iconv licence info.

## 

##### Version 2.0.1 (December 14, 2019)

- Fixed an issue with *Auto-Package Generator tool*: new version of MacOS (Catalina) prevented the mod to be installed.

## 

##### Version 2.0.0 (November 17, 2019)

- Added *tnoober.ini* metadata file to support AL|EN's "Project Infinity".
- Renamed *Setup-TNoober.tp2* -> *tnoober.tp2* to support AL|EN's "Project Infinity".
- Replaced `AUTHOR` keyword with `SUPPORT`.
- Added component `DESIGNATED` number and "*the_sword_of_noober*" `LABEL`.
- Added `REQUIRE_PREDICATE` process to avoid installing the mod in inaccurate games.
- Added `README` command.
- Rewrote itemdial.2da appending in a more "cosmetic" way.
- Append baldur25.bcs: give me one single reason why The Sword of Noober should be mute in ToB extension. :innocent:
- The sword of Noober (tson#p.itm): fixed wrong header icon, added missing opcodes for a full Sleep effect (#142, #141, #139 and #174). Fixed item description: added missing kit restrictions.
- Converted inventory BAMs to EE: This feature attempts to modify traditional inventory BAMs so that both the large and small icons are utilized by the EE games. The inventory BAM must have two sequences, the first containing the "large" inventory icon frame and the second containing the "small" inventory icon frame to be processed. Inventory icon BAMs in the bam folder that meet these requirements are patched and saved back to the override folder.
- Updated and renamed readme file to *tnoober-readme-english.txt*, then moved it into new "*readme*" folder.
- Updated French and English translations (Gwendolyne).
- Reorganized mod architecture tree: created folders to sort files according to their types.
- Included Linux and Mac versions in the same package (thanks AL|EN!).
- Transferred mod to Spellhold Studios GitHub account.

## 

##### Version 1.2 (July 31, 2019)

- Added native BG2EE compatibility (By deratiseur)
- Updated WeiDU installer to v246.

## 

##### Version 1.1 (February 20, 2011)

- Added French translation by Le Marquis (of the d'Oghmatiques).
- Added version flag.
- Updated WeiDU installer to v227.

## 

##### Version 1.0 (August 22, 2008)

- Initial release.
<div align="right"><a href="#top">Back to top</a></div>
