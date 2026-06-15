This is a [Press Record](https://uvicpraxis.github.io/pressrecord.html) project file. Jentery Sayers created it on 19 May 2026 and last updated it on 15 June 2026 with feedback from the [Praxis Studio for Comparative Media Studies](https://uvicpraxis.github.io/) and the [Humanities Computing and Media Centre](https://www.uvic.ca/humanities/hcmc/index.php) at the University of Victoria (UVic). It is an incomplete draft and thus subject to change. We will version it 1.0 once it is ready for circulation. *Please do not cite this document* in the meantime.  

# Gameplay Metadata Schema (GPMS) (INCOMPLETE DRAFT)

Jentery Sayers and the Praxis Studio developed this metadata schema to describe video files in the [Press Record](https://uvicpraxis.github.io/pressrecord.html) Gameplay Footage Collection (GPFC), which is scheduled for release in 2026-27.

License: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## Table of Contents

1. [Sources](#1-sources)
2. [Abbreviation and Acronym Key](#2-abbreviation-and-acronym-key)
3. [Platform Edition Entity](#3-platform-edition-entity)
4. [Gameplay File Entity](#4-gameplay-file-entity)
5. [Gameplay Settings Entity](#5-gameplay-settings-entity)
6. [Gameplay Footage Entity](#6-gameplay-footage-entity)
7. [Gameplay Instruction Entity](#7-gameplay-instruction-entity)

## 1. Sources

The GPMS adapts the following projects for many of its entities, elements, and controlled vocabularies: 

* BoardGameGeek (n.d.). Board Game Mechanics. [https://boardgamegeek.com/browse/boardgamemechanic](https://boardgamegeek.com/browse/boardgamemechanic)
* Brazie, A. (2024). Game Progression and Progression Systems. [https://gamedesignskills.com/game-design/game-progression/](https://gamedesignskills.com/game-design/game-progression/)
* Coates, E. (2025). GameUI Database. [https://www.gameuidatabase.com/about.php](https://www.gameuidatabase.com/about.php)
* Ellis, B. et al. (n.d.). Game Accessibility Guidelines. [https://gameaccessibilityguidelines.com/](https://gameaccessibilityguidelines.com/)
* International Council of Museums (ICOM)'s International Committee for Documentation (CIDOC) (2011). Conceptual Reference Model (CRM). [https://cidoc-crm.org/](https://cidoc-crm.org/)
* International Federation of Library Associations and Institutions (IFLA) (2009). Functional Requirements for Bibliographic Records (FRBR). [https://www.ifla.org/wp-content/uploads/2019/05/assets/cataloguing/frbr/frbr.pdf](https://www.ifla.org/wp-content/uploads/2019/05/assets/cataloguing/frbr/frbr.pdf)
* J. Paul Getty Trust (2004). Art & Architecture Thesaurus Online: Full Record Display, "Theme." [https://www.getty.edu/vow/AATFullDisplay?find=theme&logic=AND&note=&english=N&prev_page=1&subjectid=300195523](https://www.getty.edu/vow/AATFullDisplay?find=theme&logic=AND&note=&english=N&prev_page=1&subjectid=300195523)
* Jan, M. (2017). Game Developer’s Guide to Graphical Projections. [https://medium.com/retronator-magazine/game-developers-guide-to-graphical-projections-with-video-game-examples-part-1-introduction-aa3d051c137d](https://medium.com/retronator-magazine/game-developers-guide-to-graphical-projections-with-video-game-examples-part-1-introduction-aa3d051c137d)
* Lee, J. H., Perti, A., Thirumalai, V., Welch, H., Zachary, A., & Nguyen, T. (2024). UW/SIMM Video Game Metadata Schema: Controlled Vocabulary for Theme. Version 1.2. [https://github.com/uwgamergroup/vocabulary-theme](https://github.com/uwgamergroup/vocabulary-theme)
* Lee, J. H., Schmalz, M., Newman, M., & Koughan, L.D. (2024). UW/SIMM Video Game Metadata Schema. Version 4.2. [https://github.com/uwgamergroup/video-game-metadata-schema](https://github.com/uwgamergroup/video-game-metadata-schema)
* --- (2024). UW/SIMM Video Game Metadata Schema: Controlled Vocabulary for Genre. Version 1.3. [https://github.com/uwgamergroup/vocabulary-gameplay-genre/](https://github.com/uwgamergroup/vocabulary-gameplay-genre/)
* --- (2024). UW/SIMM Video Game Metadata Schema: Controlled Vocabulary for Mechanics. Version 1.1. [https://github.com/uwgamergroup/vocabulary-mechanics](https://github.com/uwgamergroup/vocabulary-mechanics)
* --- (2024). UW/SIMM Video Game Metadata Schema: Controlled Vocabulary for Mood. Version 3.2. [https://github.com/uwgamergroup/vocabulary-mood](https://github.com/uwgamergroup/vocabulary-mood)
* --- (2024). UW/SIMM Video Game Metadata Schema: Controlled Vocabulary for Narrative Genre. Version 1.3. [https://github.com/uwgamergroup/vocabulary-narrative-genre](https://github.com/uwgamergroup/vocabulary-narrative-genre)
* ---. (2024). UW/SIMM Video Game Metadata Schema: Controlled Vocabulary for Protagonist. Version 1.0. [https://github.com/uwgamergroup/vocabulary-protagonist](https://github.com/uwgamergroup/vocabulary-protagonist)
* --- (2024). UW/SIMM Video Game Metadata Schema: Controlled Vocabulary for Setting. Version 2.3. [https://github.com/uwgamergroup/vocabulary-setting](https://github.com/uwgamergroup/vocabulary-setting)
* --- (2024). UW/SIMM Video Game Metadata Schema: Controlled Vocabulary for Tropes. Version 1.1. [https://github.com/uwgamergroup/vocabulary-tropes](https://github.com/uwgamergroup/vocabulary-tropes)
* Poff, T. & Atari (2025). MobyGames Genres and Other Classifications. [https://www.mobygames.com/genre/](https://www.mobygames.com/genre/)
* Shaw, A. et al. (2025). LGBTQ+ Game Archive: Types of Content. [https://lgbtqgamearchive.com/types-of-content/](https://lgbtqgamearchive.com/types-of-content/)
* Sicart, M. (2015). Defining Game Mechanics. *Game Studies* 15.2. [https://gamestudies.org/1502/articles/sicart](https://gamestudies.org/1502/articles/sicart)
* TV Tropes (2026). Video Game Tropes [https://tvtropes.org/pmwiki/pmwiki.php/Main/VideoGameTropes](https://tvtropes.org/pmwiki/pmwiki.php/Main/VideoGameTropes)
* Wikipedia (2026). Game Controller. [https://en.wikipedia.org/wiki/Game_controller](https://en.wikipedia.org/wiki/Game_controller)
* --- (2026). Glossary of Video Game Terms. [https://en.wikipedia.org/wiki/Glossary_of_video_game_terms](https://en.wikipedia.org/wiki/Glossary_of_video_game_terms)
* --- (2026). Item (game terminology). [https://en.wikipedia.org/wiki/Item_(game_terminology)](https://en.wikipedia.org/wiki/Item_(game_terminology))
* --- (2025). List of Game Engines. [https://en.wikipedia.org/wiki/List_of_game_engines](https://en.wikipedia.org/wiki/List_of_game_engines)
* --- (2026). List of Genres. [https://en.wikipedia.org/wiki/List_of_genres](https://en.wikipedia.org/wiki/List_of_genres)

See citations below for specific instances of adaptation. 

## 2. Abbreviation and Acronym Key

* Elements marked with [R] are required.
* Elements marked with [+] are repeatable.
* GPMS refers to the Gameplay Metadata Schema. 
* GPFC refers to the Press Record Gameplay Footage Collection. 
* NPC refers to a non-player character. 
* PC refers to a player character. 

## 3. Platform Edition Entity

Definition: "Denotes a particular instantiation of a video game. An edition may be a particular release of a game that is in some way different than another release of the same game" (Lee et al., "VGMS 4.2," 2024).

The platform edition played and recorded for the GPFC may or may not correspond with the game's initial release. For instance, *Journey* was initially released on PlayStation 3 in 2012. That release was the game's first platform edition. Other platform editions of *Journey* include iPad (2019), iPhone (2019), PlayStation 4 (2015), and Windows (2019). These four platform editions (later releases) are ports of the 2012 platform edition (the initial release). 

*The following elements of the Platform Edition Entity should describe the platform edition of the game played and recorded for the GPFC.*

* [Game Title](#3a-game-title-r) [R] (text input field)
* [Release Year](#3b-release-year-r) [R] (text input field)
* [Release Type](#3c-release-type-r) [R][+] (controlled vocabulary)
* [Platform](#3d-platform-r) [R][+] (controlled vocabulary)
* [Engine](#3e-engine-) [+] (controlled vocabulary)
* [Developer](#3f-developer-r) [R][+] (text input field)
* [Developer's Location](#3g-developers-location-r) [R][+] (controlled vocabulary)
* [Publisher](#3h-publisher-r) [R][+] (text input field)
* [Publisher Class](#3i-publisher-class-r) [R][+] (controlled vocabulary)
* [Platform Edition Note](#3j-platform-edition-note) (text input field)

### 3A. Game Title [R]

Definition: The proper name of the platform edition as assigned by its developer and/or publisher (Lee et al., "VGMS 4.2," 2024; CIDOC 2011)

Provide the complete, official game title. Avoid using an alternative, abbreviated, or colloquial title. 

*text input field* 

### 3B. Release Year [R]

Definition: The year the platform edition was publicly/commercially released (Lee et al., "VGMS 4.2," 2024) 

The edition's release year may differ from the game's initial release year. 

*text input field; format: YYYY* 

### 3C. Release Type [R][+]

Definition: The platform edition's release type as assigned by its developer, publisher, and/or distributor

Use existing scholarship, MobyGames, Wikipedia, Steam, and/or fansites to confirm the release type if it was not assigned by the developer, publisher, and/or distributor. 

<details>
<summary><i>controlled vocabulary</i></summary>
<ul>
<li>Alpha</li>
<li>Beta</li>
<li>Demo</li>
<li>Downloadable content (DLC)</li>
<li>Early access</li>
<li>Emulation</li>
<li>Expansion</li>
<li>Fan game</li>
<li>Initial release / original release</li>
<li>Port</li>
<li>Reboot</li>
<li>Remake</li>
<li>Remaster</li>
<li>Unfinished</li>
</ul>
</details>

### 3D. Platform [R][+]
Definition: The operating system, device, computer, console, and/or service on which the platform edition was played and recorded (Lee et al., "VGMS 4.2," 2024)

<details>
<summary><i>controlled vocabulary</i> (adapted, with minor changes, from Poff and Atari 2025)</summary>
<ul>
<li>1291 Advanced Programmable Video System</li>
<li>3DO</li>
<li>ABC 80</li>
<li>Acorn 32-bit</li>
<li>Adventure Vision</li>
<li>AirConsole</li>
<li>Alice 32/90</li>
<li>Altair 680</li>
<li>Altair 8800</li>
<li>Amazon Alexa</li>
<li>Amazon Luna</li>
<li>Amiga</li>
<li>Amiga CD32</li>
<li>Amstrad CPC</li>
<li>Amstrad PCW</li>
<li>Android</li>
<li>Anstream</li>
<li>APF MP1000 / Imagination Machine</li>
<li>Apple I</li>
<li>Apple II</li>
<li>Apple IIgs</li>
<li>Arcade</li>
<li>Arcadia 2001</li>
<li>Arduboy</li>
<li>Astral 2000</li>
<li>Atari 2600</li>
<li>Atari 5200</li>
<li>Atari 7800</li>
<li>Atari 8-bit</li>
<li>Atari ST</li>
<li>Atari VCS</li>
<li>Atom</li>
<li>Auto Response Board</li>
<li>bada</li>
<li>Bally Astrocade</li>
<li>Bandai RX-78 Gundam</li>
<li>BBC Micro</li>
<li>BeOS</li>
<li>BlackBerry</li>
<li>Blacknut</li>
<li>Blu-ray disc player</li>
<li>BREW</li>
<li>Browser</li>
<li>Bubble</li>
<li>Camputers Lynx</li>
<li>Casio FP-1000 / 1100</li>
<li>Casio Loopy</li>
<li>Casio Programmable Calculator</li>
<li>Casio PV-1000</li>
<li>CD-i</li>
<li>CDTV</li>
<li>Champion 2711</li>
<li>Channel F</li>
<li>ClickStart</li>
<li>Coleco Adam</li>
<li>ColecoVision</li>
<li>Colour Genie</li>
<li>Commodore 128</li>
<li>Commodore 16, Plus/4</li>
<li>Commodore 64</li>
<li>Commodore PET/CBM</li>
<li>Compal 80</li>
<li>Compucolor I</li>
<li>Compucolor II</li>
<li>Compucorp Programmable Calculator</li>
<li>COSMAC</li>
<li>CP/M</li>
<li>CreatiVision</li>
<li>Cybervision</li>
<li>DAI</li>
<li>Danger OS</li>
<li>Dedicated console</li>
<li>Dedicated handheld</li>
<li>Didj</li>
<li>digiBlast</li>
<li>DoJa</li>
<li>DOS</li>
<li>Dragon 32/64</li>
<li>Dreamcast</li>
<li>DVD Player</li>
<li>ECD Micromind</li>
<li>Electron</li>
<li>Enterprise</li>
<li>Epoch Cassette Vision</li>
<li>Epoch Game Pocket Computer</li>
<li>Epoch Super Cassette Vision</li>
<li>Evercade</li>
<li>Excelvision</li>
<li>ExEn</li>
<li>Exidy Sorcerer</li>
<li>Feature phone</li>
<li>Fire OS</li>
<li>FM Towns</li>
<li>FM-7</li>
<li>Freebox</li>
<li>FreeBSD</li>
<li>G-cluster</li>
<li>Galaksija</li>
<li>Game Boy</li>
<li>Game Boy Advance</li>
<li>Game Boy Color</li>
<li>Game Gear</li>
<li>Game Wave</li>
<li>Game.com</li>
<li>GameCube</li>
<li>GameStick</li>
<li>Genesis</li>
<li>GIMINI</li>
<li>Gizmondo</li>
<li>Gloud</li>
<li>Glulx</li>
<li>GNEX</li>
<li>GP2X</li>
<li>GP2X Wix</li>
<li>GP32</li>
<li>GVM</li>
<li>HD DVD player</li>
<li>Heath/Zenith H8/H89</li>
<li>Heathkit H11</li>
<li>Hitachi Basic Master</li>
<li>Hitachi Basic Master Level 3</li>
<li>Hitachi H68/TR</li>
<li>Hitachi SI</li>
<li>HP 9800</li>
<li>HP Oscilloscope</li>
<li>HP Programmable Calculator</li>
<li>HP Series 80</li>
<li>Hugo</li>
<li>HyperScan</li>
<li>IBM 5100</li>
<li>Ideal-Computer</li>
<li>iiRcade</li>
<li>Intel 8008</li>
<li>Intel 8080</li>
<li>Intel 8086 / 8088</li>
<li>Intellivision</li>
<li>Interact Model One</li>
<li>Interton Video 2000</li>
<li>iPad</li>
<li>iPhone</li>
<li>iPod Classic</li>
<li>J2ME</li>
<li>Jaguar</li>
<li>Jolt</li>
<li>Jupiter Ace</li>
<li>KaiOS</li>
<li>KIM-1</li>
<li>Kindle Classic</li>
<li>Laser 200</li>
<li>LaserActive</li>
<li>LeapFrog Explorer</li>
<li>Leapster</li>
<li>LeapTV</li>
<li>Linux</li>
<li>Lkit-16</li>
<li>Luna</li>
<li>Lynx</li>
<li>Macintosh</li>
<li>macOS</li>
<li>Maemo</li>
<li>Magic Leap</li>
<li>Mainframe</li>
<li>Marvel 2000</li>
<li>Matsushita / Panasonic JR</li>
<li>Mattel Aquarius</li>
<li>MeeGo</li>
<li>Memotech MTX</li>
<li>Meritum</li>
<li>Microbee</li>
<li>Microtan 65</li>
<li>Microvision</li>
<li>Mitsubishi Multi-8</li>
<li>Modular Game System</li>
<li>Mophun</li>
<li>MOS Technology 6502</li>
<li>Motorola 6800</li>
<li>Motorola 68k</li>
<li>MRE</li>
<li>MSX</li>
<li>N-Gage</li>
<li>N-Gage (service)</li>
<li>Nascom</li>
<li>NEC TK-80</li>
<li>Neo Geo</li>
<li>Neo Geo CD</li>
<li>Neo Geo Pocket</li>
<li>Neo Geo Pocket Color</li>
<li>Neo Geo X</li>
<li>NES</li>
<li>NetBSD</li>
<li>New Nintendo 3DS</li>
<li>NewBrain</li>
<li>Newton</li>
<li>Nintendo 3DS</li>
<li>Nintendo 64</li>
<li>Nintendo DS</li>
<li>Nintendo DSi</li>
<li>Nintendo Switch</li>
<li>Nintendo Switch 2</li>
<li>North Star</li>
<li>Noval 760</li>
<li>Nuon</li>
<li>Oculus Go</li>
<li>Odyssey</li>
<li>Odyssey 2</li>
<li>Ohio Scientific</li>
<li>OnLive</li>
<li>OOParts</li>
<li>OpenBSD</li>
<li>Orao</li>
<li>Oric</li>
<li>OS/2</li>
<li>Ouya</li>
<li>Palm OS</li>
<li>Pandora</li>
<li>PC Booter</li>
<li>PC-6001</li>
<li>PC-8000</li>
<li>PC-88</li>
<li>PC-98</li>
<li>PC-FX</li>
<li>Pebble</li>
<li>Philips P200</li>
<li>Philips VG 5000</li>
<li>Photo CD</li>
<li>PICO</li>
<li>Pippin</li>
<li>Playdate</li>
<li>Playdia</li>
<li>PlayStation</li>
<li>PlayStation 2</li>
<li>PlayStation 3</li>
<li>PlayStation 4</li>
<li>PlayStation 5</li>
<li>PlayStation Now</li>
<li>Plex Arcade</li>
<li>Pokitto</li>
<li>Pokémon Mini</li>
<li>Poly-88</li>
<li>PS Vita</li>
<li>PSP</li>
<li>Quest</li>
<li>RCA Studio II</li>
<li>Research Machines 380Z</li>
<li>Roblox</li>
<li>Roku</li>
<li>SAM Coupé</li>
<li>SC/MP</li>
<li>SD-200 / 270 / 290</li>
<li>SEGA 32X</li>
<li>SEGA CD</li>
<li>SEGA Master System</li>
<li>SEGA Pico</li>
<li>SEGA Saturn</li>
<li>SG-1000</li>
<li>Sharp MZ-80B / 2000 / 2500</li>
<li>Sharp MZ-80K / 700 / 800 / 1500</li>
<li>Sharp X1</li>
<li>Sharp X68000</li>
<li>Sharp Zaurus</li>
<li>Signetics 2650</li>
<li>Sinclair QL</li>
<li>SK-VM</li>
<li>SMC-777</li>
<li>SNES</li>
<li>Socrates</li>
<li>Sol-20</li>
<li>Solaris</li>
<li>Sord M5</li>
<li>SPC-1000</li>
<li>Spectravideo</li>
<li>SRI-500 / 1000</li>
<li>Stadia</li>
<li>Steam</li>
<li>Steam Deck</li>
<li>Super A'can</li>
<li>Super Vision 8000</li>
<li>SuperGrafx</li>
<li>Supervision</li>
<li>Sure Shot HD</li>
<li>SWTPC 6800</li>
<li>Symbian</li>
<li>TADS</li>
<li>Taito X-55</li>
<li>Tatung Einstein</li>
<li>Tektronix 4050</li>
<li>Tele-Spiel ES-2201</li>
<li>Telstar Arcade</li>
<li>TempleOS</li>
<li>Terminal</li>
<li>Thomson MO</li>
<li>Thomson TO</li>
<li>TI Programmable Calculator</li>
<li>TI-99 / 4A</li>
<li>TIC-80</li>
<li>Tiki 100</li>
<li>TIM</li>
<li>Timex Sinclair 2068</li>
<li>Tizen</li>
<li>Tomahawk F1</li>
<li>Tomy Tutor</li>
<li>Toshiba Ex-80</li>
<li>Toshiba Pasopia</li>
<li>Triton</li>
<li>TRS-80</li>
<li>TRS-80 CoCo</li>
<li>TRS-80 MC-10</li>
<li>TRS-80 Model 100</li>
<li>TurboGrafx CD</li>
<li>TurboGrafx-16</li>
<li>tvOS</li>
<li>V.Flash</li>
<li>V.Smile</li>
<li>Vectrex</li>
<li>Versatile</li>
<li>VIC-20</li>
<li>VideoBrain</li>
<li>Videopac+ G7400</li>
<li>Virtual Boy</li>
<li>VIS</li>
<li>visionOS</li>
<li>Wang 2200</li>
<li>watchOS</li>
<li>webOS</li>
<li>Wii</li>
<li>Wii U</li>
<li>Windows</li>
<li>Windows 16-bit</li>
<li>Windows Apps</li>
<li>Windows Mobile</li>
<li>Windows Phone</li>
<li>WIPI</li>
<li>WonderSwan</li>
<li>WonderSwan Color</li>
<li>XaviXPORT</li>
<li>Xbox</li>
<li>Xbox 360</li>
<li>Xbox Cloud Gaming</li>
<li>Xbox One</li>
<li>Xbox Series</li>
<li>Xerox Alto</li>
<li>Z-machine</li>
<li>Zeebo</li>
<li>Zilog Z80</li>
<li>Zilog Z8000</li>
<li>Zillions of Games</li>
<li>Zodiac</li>
<li>Zune</li>
<li>ZX Spectrum</li>
<li>ZX Spectrum Next</li>
<li>ZX80</li>
<li>ZX81</li>
</ul>
</details>

### 3E. Engine [+]

Definition: The software framework and/or development environment used to design the platform edition

Use existing scholarship, MobyGames, Wikipedia, Steam, fansites, official advertisements, the developer's official website, and/or the platform edition's official website, title screen, and/or credits sequence to confirm the engine.

<details>
<summary><i>controlled vocabulary</i> (adapted, with minor changes, from Wikipedia, "List of Game Engines," 2025)</summary>
<ul>
<li>4A Engine</li>
<li>A-FRAME (VR)</li>
<li>Adventure Game Interpreter</li>
<li>Adventure Game Studio</li>
<li>Aleph One</li>
<li>Amazon Lumberyard</li>
<li>Anvil</li>
<li>AppGameKit</li>
<li>Ardor3D</li>
<li>Aurora toolset</li>
<li>Babylon.js</li>
<li>bitsy</li>
<li>Blend4Web</li>
<li>Blender</li>
<li>Build Engine</li>
<li>Buildbox</li>
<li>C4 Engine</li>
<li>Chrome Engine</li>
<li>ClanLib</li>
<li>Clausewitz</li>
<li>Clickteam Fusion</li>
<li>Cobra Engine</li>
<li>Cocos2d / 2d-x / 2d-html5</li>
<li>Codea</li>
<li>Construct</li>
<li>Coretech</li>
<li>CraftStudio</li>
<li>Creation Engine</li>
<li>CryEngine</li>
<li>Crystal Space</li>
<li>Crystal Tools</li>
<li>Cube Engine</li>
<li>Cube 2 Engine</li>
<li>Custom-built engine</li>
<li>Dagor Engine</li>
<li>Dark Engine</li>
<li>Decima</li>
<li>Defold</li>
<li>Delta3D</li>
<li>Dim3</li>
<li>DimensioneX Multiplayer Engine</li>
<li>Divinity Engine</li>
<li>Dunia Engine</li>
<li>DX Studio</li>
<li>EGO</li>
<li>Electron toolset</li>
<li>Enforce</li>
<li>Enigma Engine</li>
<li>Essence Engine</li>
<li>Exult</li>
<li>Flame</li>
<li>Flare3D</li>
<li>Flash (Adobe)</li>
<li>Flixel</li>
<li>ForgeLight</li>
<li>Fox Engine</li>
<li>Freescape</li>
<li>Freespace 2</li>
<li>Frostbite</li>
<li>Future Pinball</li>
<li>Gamebryo</li>
<li>GameMaker</li>
<li>GameSalad</li>
<li>Gamestudio</li>
<li>GDevelop</li>
<li>Genie Engine</li>
<li>Godot</li>
<li>Gold Box</li>
<li>GoldSrc</li>
<li>Havok</li>
<li>HeroEngine</li>
<li>Horde3D</li>
<li>HPL Engine</li>
<li>id Tech</li>
<li>iMUSE</li>
<li>Infinity Engine</li>
<li>ioquake3</li>
<li>Iron Engine</li>
<li>Irrlicht</li>
<li>IW Engine</li>
<li>Jade</li>
<li>Jake2</li>
<li>Java 3D</li>
<li>Jedi</li>
<li>jMonkeyEngine</li>
<li>Kinectica</li>
<li>Kivy (framework)</li>
<li>LayaAir</li>
<li>Leadwerks</li>
<li>LibGDX</li>
<li>LithTech</li>
<li>LÖVE</li>
<li>Luminous Engine</li>
<li>LyN</li>
<li>M.U.G.E.N.</li>
<li>Marmalade</li>
<li>Messiah</li>
<li>Moai SDK</li>
<li>Monkey X</li>
<li>MonoGame / XNA</li>
<li>MT Framework</li>
<li>Northlight</li>
<li>NScripter</li>
<li>O3DE</li>
<li>Odyssey Engine</li>
<li>OGRE</li>
<li>OHRRPGCE</li>
<li>ONScripter</li>
<li>OpenClonk</li>
<li>OpenMW</li>
<li>OpenSimulator</li>
<li>ORX</li>
<li>Panda3D</li>
<li>Panta Rhei</li>
<li>Phaser</li>
<li>PhyreEngine</li>
<li>PICO-8</li>
<li>Pie in the Sky</li>
<li>Pixel Game Maker MV</li>
<li>PlayCanvas</li>
<li>PlayN</li>
<li>Pulp</li>
<li>Pygame</li>
<li>Pyrogenesis</li>
<li>Q</li>
<li>Qfusion</li>
<li>REDengine</li>
<li>Ren'Py</li>
<li>RenderWare</li>
<li>Roblox</li>
<li>Rockstar Advanced Game Engine</li>
<li>RPG Maker</li>
<li>S&box</li>
<li>SAGE</li>
<li>Scratch</li>
<li>SCUMM</li>
<li>Serious Engine</li>
<li>Shark 3D</li>
<li>Silent Storm Engine</li>
<li>Snowdrop</li>
<li>Solar2D</li>
<li>Solaris</li>
<li>Source</li>
<li>Source 2</li>
<li>Starling Framework</li>
<li>Stencyl</li>
<li>StepMania</li>
<li>Stingray (Autodesk)</li>
<li>Stratagus</li>
<li>Stride</li>
<li>Telltale Tool</li>
<li>Three.js</li>
<li>Torque3D</li>
<li>TOSHI</li>
<li>Treyarch NGL</li>
<li>Turbulenz</li>
<li>Twine</li>
<li>UbiArt Framework</li>
<li>Unigine</li>
<li>Unity</li>
<li>Unreal Engine</li>
<li>V-Play</li>
<li>Vengeance Engine</li>
<li>Vicarious Visions Alchemy</li>
<li>Virtools</li>
<li>Vision</li>
<li>Visual3D Game Engine</li>
<li>Visual Pinball</li>
<li>VRAGE</li>
<li>Wintermute Engine</li>
<li>Wolf RPG Editor</li>
<li>World Builder</li>
<li>WorldForge</li>
<li>XnGine</li>
<li>Zero</li>
</ul>
</details>

### 3F. Developer [R][+]

Definition: "An individual, organization, or group of individuals or organizations responsible for [the] creation, realization, [and/or] manufacture" of the platform edition (Lee et al., "VGMS 4.2," 2024; IFLA 2009)

Use existing scholarship, MobyGames, Wikipedia, Steam, fansites, official advertisements, and/or the platform edition's official website, title screen, and/or credits sequence to confirm the developer(s). 

*text input field* 

### 3G. Developer's Location [R][+]

Definition: The geographic location of the platform edition's developer(s)

Select the country for all developers except those in Canada.

For developers in Canada, select the country and province or territory: for example, Canada / British Columbia. 

Use existing scholarship, MobyGames, Wikipedia, Steam, fansites, official advertisements, the developer's official website, and/or the platform edition's official website, title screen, and/or credits sequence to confirm the developer's location. 

<details>
<summary><i>controlled vocabulary</i></summary>
<ul>
<li>Afghanistan</li>
<li>Albania</li>
<li>Algeria</li>
<li>Andorra</li>
<li>Angola</li>
<li>Antigua and Barbuda</li>
<li>Argentina</li>
<li>Armenia</li>
<li>Australia</li>
<li>Austria</li>
<li>Azerbaijan</li>
<li>Bahamas</li>
<li>Bahrain</li>
<li>Bangladesh</li>
<li>Barbados</li>
<li>Belarus</li>
<li>Belgium</li>
<li>Belize</li>
<li>Benin</li>
<li>Bermuda </li>
<li>Bhutan</li>
<li>Bolivia</li>
<li>Bosnia and Herzegovina</li>
<li>Botswana</li>
<li>Brazil</li>
<li>Brunei</li>
<li>Bulgaria</li>
<li>Burkina Faso</li>
<li>Burundi</li>
<li>Cambodia</li>
<li>Cameroon</li>
<li>Canada</li>
<li>Canada / Alberta</li>
<li>Canada / British Columbia</li>
<li>Canada / Manitoba</li>
<li>Canada / New Brunswick</li>
<li>Canada / Newfoundland and Labrador</li>
<li>Canada / Northwest Territories </li>
<li>Canada / Nova Scotia </li>
<li>Canada / Nunavut</li>
<li>Canada / Ontario </li>
<li>Canada / Prince Edward Island </li>
<li>Canada / Quebec</li>
<li>Canada / Saskatchewan</li>
<li>Canada / Yukon</li>
<li>Cape Verde</li>
<li>Central African Republic</li>
<li>Chad</li>
<li>Chile</li>
<li>China</li>
<li>Colombia</li>
<li>Comoros</li>
<li>Congo, Republic of the</li>
<li>Congo, Democratic Republic of the</li>
<li>Costa Rica</li>
<li>Croatia</li>
<li>Cuba</li>
<li>Curacao</li>
<li>Cyprus</li>
<li>Czech Republic</li>
<li>Denmark</li>
<li>Djibouti</li>
<li>Dominica</li>
<li>Dominican Republic</li>
<li>East Timor</li>
<li>Ecuador</li>
<li>Egypt</li>
<li>El Salvador</li>
<li>Equatorial Guinea</li>
<li>Eritrea</li>
<li>Estonia</li>
<li>Eswatini</li>
<li>Ethiopia</li>
<li>Fiji</li>
<li>Finland</li>
<li>France</li>
<li>Gabon</li>
<li>Gambia</li>
<li>Georgia</li>
<li>Germany</li>
<li>Ghana</li>
<li>Greece</li>
<li>Grenada</li>
<li>Guatemala</li>
<li>Guinea</li>
<li>Guinea-Bissau</li>
<li>Guyana</li>
<li>Haiti</li>
<li>Honduras</li>
<li>Hungary</li>
<li>Iceland</li>
<li>India</li>
<li>Indonesia</li>
<li>Iran</li>
<li>Iraq</li>
<li>Ireland</li>
<li>Israel</li>
<li>Italy</li>
<li>Ivory Coast</li>
<li>Jamaica</li>
<li>Japan</li>
<li>Jordan</li>
<li>Kazakhstan</li>
<li>Kenya</li>
<li>Kiribati</li>
<li>Kosovo</li>
<li>Kuwait</li>
<li>Kyrgyzstan</li>
<li>Laos</li>
<li>Latvia</li>
<li>Lebanon</li>
<li>Lesotho</li>
<li>Liberia</li>
<li>Libya</li>
<li>Liechtenstein</li>
<li>Lithuania</li>
<li>Luxembourg</li>
<li>Madagascar</li>
<li>Malawi</li>
<li>Malaysia</li>
<li>Maldives</li>
<li>Mali</li>
<li>Malta</li>
<li>Marshall Islands</li>
<li>Mauritania</li>
<li>Mauritius</li>
<li>Mexico</li>
<li>Micronesia</li>
<li>Moldova</li>
<li>Monaco</li>
<li>Mongolia</li>
<li>Montenegro</li>
<li>Morocco</li>
<li>Mozambique</li>
<li>Myanmar</li>
<li>Namibia</li>
<li>Nauru</li>
<li>Nepal</li>
<li>Netherlands</li>
<li>New Zealand</li>
<li>Nicaragua</li>
<li>Niger</li>
<li>Nigeria</li>
<li>North Korea</li>
<li>North Macedonia</li>
<li>Norway</li>
<li>Oman</li>
<li>Pakistan</li>
<li>Palau</li>
<li>Palestine</li>
<li>Panama</li>
<li>Papua New Guinea</li>
<li>Paraguay</li>
<li>Peru</li>
<li>Philippines</li>
<li>Poland</li>
<li>Portugal</li>
<li>Puerto Rico</li>
<li>Qatar</li>
<li>Romania</li>
<li>Russia</li>
<li>Rwanda</li>
<li>Saint Kitts and Nevis</li>
<li>Saint Lucia</li>
<li>Saint Vincent and the Grenadines</li>
<li>Samoa</li>
<li>San Marino</li>
<li>São Tomé and Príncipe</li>
<li>Saudi Arabia</li>
<li>Senegal</li>
<li>Serbia</li>
<li>Seychelles</li>
<li>Sierra Leone</li>
<li>Singapore</li>
<li>Slovakia</li>
<li>Slovenia</li>
<li>Solomon Islands</li>
<li>Somalia</li>
<li>South Africa</li>
<li>South Korea</li>
<li>South Sudan</li>
<li>Spain</li>
<li>Sri Lanka</li>
<li>Sudan</li>
<li>Suriname</li>
<li>Sweden</li>
<li>Switzerland</li>
<li>Syria</li>
<li>Taiwan</li>
<li>Tajikistan</li>
<li>Tanzania</li>
<li>Thailand</li>
<li>Togo</li>
<li>Tonga</li>
<li>Trinidad and Tobago</li>
<li>Tunisia</li>
<li>Turkey</li>
<li>Turkmenistan</li>
<li>Tuvalu</li>
<li>Uganda</li>
<li>Ukraine</li>
<li>United Arab Emirates</li>
<li>United Kingdom</li>
<li>United States</li>
<li>Uruguay</li>
<li>Uzbekistan</li>
<li>Vanuatu</li>
<li>Vatican City</li>
<li>Venezuela</li>
<li>Vietnam</li>
<li>Yemen</li>
<li>Zambia</li>
<li>Zimbabwe</li>
</ul>
</details>

### 3H. Publisher [R][+]

Definition: "An individual, organization, or group of individuals or organizations responsible for . . . [the] manufacture, marketing, and/or distribution" of the platform edition (Lee et al., "VGMS 4.2," 2024; IFLA 2009)

Both publishers and distributors may be included in this field. 

Use existing scholarship, MobyGames, Wikipedia, Steam, fansites, official advertisements, the developer's official website, and/or the platform edition's official website, title screen, and/or credits sequence to confirm the publisher(s) and distributor(s). 

*text input field*

### 3I. Publisher Class [R][+]

Definition: The size, profile, and/or budget of the publisher and, in some cases, the developer, too

Use existing scholarship, MobyGames, Wikipedia, Steam, and/or fansites to confirm the publisher class. 

This element rarely needs to be repeated. Exceptions include cases where the platform edition is both "indie" and "self-published." 
<details>
<summary><i>controlled vocabulary</i></summary>
<ul>
<li>AAA</li>
<li>AA</li>
<li>B</li>
<li>III</li>
<li>Indie</li>
<li>Self-published</li>
</ul>
</details>

### 3J. Platform Edition Note 

Definition: "Any other notable characteristics of the platform edition" that are "not captured in other fields" of this metadata schema (Lee et al., "VGMS 4.2," 2024)

*text input field*

## 4. Gameplay File Entity 

Definition: Denotes a video file containing gameplay footage of a particular instantiation (a ["platform edition"](#3-platform-edition-entity)) of a video game; also called "game capture" and "game recording"

For the fair-dealing purposes of the GPFC, the video file will typically be a "clip" that is 30 seconds to five minutes long.

*The following elements of the Gameplay File Entity should describe the gameplay video file intended for the GPFC.*

* [Clip Title](#4a-clip-title-r) [R] (text input field; )
* [Clip Length](#4b-clip-length-r) [R] (text input field) 
* [Date Recorded](#4c-date-recorded-r) [R] (text input field) 
* [Commentary](#4d-commentary-r) [R][+] (controlled vocabulary)
* [Chat](#4e-chat-r) [R][+] (controlled vocabulary)
* [Gameplay Attribution](#4f-gameplay-attribution-r) [R][+] (text input field)
* [Metadata Attribution](#4g-metadata-attribution-r) [R][+] (text input field) 
* [ID](#4h-id-r) [R] (text input field) 
* [Filename](#4i-filename-r) [R] (text input field) 
* [Gameplay File Note](#4j-gameplay-file-note) (text input field)

### 4A. Clip Title [R]

Definition: A public-facing, search-friendly description of the gameplay footage as assigned by the person who played the platform edition while the video was recorded

Provide a title that helps viewers anticipate what they will see, hear, read, and watch. Describe the content of the clip and the actions occurring in it. An example is, "Starting a New Game: Naming the Player Character, Encountering Emus and Hobgoblins, and Collecting Darts, Scrolls, and Potions on Level 1."

*text input field*

### 4B. Clip Length [R]

Definition: The length of the gameplay video in minutes and seconds 

*text input field; format: MM:SS* 

### 4C. Date Recorded [R]

Definition: The date the gameplay video was recorded

This date is presumably identical to the video file's "created" date.  

*text input field; format: YYYY-MM-DD* 

### 4D. Commentary [R][+]

Definition: The type of player commentary, if any, included in the gameplay footage of the platform edition

Commentary is reflective, and it typically addresses the video's audience. 

Select "No commentary" if the footage contains no commentary. 

<details>
<summary><i>controlled vocabulary</i></summary>
<ul>
<li>Avatar / VTubing</li>
<li>Captions / subtitles</li>
<li>Emotes</li>
<li>Face cam / facecam</li>
<li>No commentary</li>
<li>Voice over / voice-over / voiceover (VO)</li>
</ul>
</details>

### 4E. Chat [R][+]

Definition: The type of chat, if any, included in the gameplay footage of the platform edition

Chat typically occurs between players; however, in cases such as livestreams, it may also occur between players and audiences. 

Select "No chat" if the footage contains no chat.

<details>
<summary><i>controlled vocabulary</i></summary>
<ul>
<li>Emotes</li>
<li>No chat</li>
<li>Text chat</li>
<li>Video chat</li>
<li>Voice chat</li>
</ul>
</details>

### 4F. Gameplay Attribution [R][+]

Definition: The chosen or preferred name of the person who played the platform edition while the video was recorded

Multiple names may be included. Full names are optional. 

*text input field*

### 4G. Metadata Attribution [R][+]

Definition: The chosen or preferred name of the person who described the platform edition, the gameplay file, the gameplay settings, the gameplay footage, and/or the gameplay instruction and/or entered the metadata

Multiple names may be included. Full names are optional. 

*text input field*

### 4H. ID [R]

Definition: The internal reference number for the gameplay file and its metadata 

This number is used by the Press Record team to identify files and metadata in the GPFC. It is a five-character numeric string. 

*text input field; format: #####*

### 4I. Filename [R]

Definition: The filename of the video file containing gameplay footage of the platform edition

Use camelCasing to include the following information in the following order: gameTitlePlatformEditionReleaseYearClipTitleID. An example is rogue1985StartingANewGame00011.mp4. Abbreviate the clip's title to avoid long filenames. 

*text input field; format: gameTitlePlatformEditionReleaseYearClipTitleID.extension* 

### 4J. Gameplay File Note

Definition: "Any other notable characteristics of the" gameplay file that are "not captured in other fields" of this metadata schema (Lee et al., "VGMS 4.2," 2024)

*text input field*

## 5. Gameplay Settings Entity 

Definition: Denotes the settings of a particular instantiation (a ["platform edition"](#3-platform-edition-entity)) of a video game

*The following elements of the Gameplay Settings Entity should describe the platform edition's settings while it was played and recorded for the GPFC.*

* [Input Device](#5a-input-device-r) [R][+] (controlled vocabulary)
* [Connectivity](#5b-connectivity-r) [R][+] (controlled vocabulary) 
* [Number of Players](#5c-number-of-players-r) [R] (controlled vocabulary) 
* [Gameplay Mode](#5d-gameplay-mode-r) [R][+] (controlled vocabulary) 
* [Language](#5e-language-r) [R][+] (text input field) 
* [Accessibility](#5f-accessibility-) [+] (controlled vocabulary) 
* [Mods](#5g-mods-r) [R][+] (text input field) 
* [Gameplay Settings Note](#5h-gameplay-settings-note) (text input field)

### 5A. Input Device [R][+]

Definition: The equipment used to play the platform edition while the video was recorded (Lee et al., "VGMS 4.2," 2024)

<details>
<summary><i>controlled vocabulary</i> (adapted, with minor changes, from Wikipedia, "Game Controller," 2026)</summary>
<ul>
<li>Adaptive controller</li>
<li>Balance board</li>
<li>Camera</li>
<li>Crank</li>
<li>Dance pad</li>
<li>Exercise accessory</li>
<li>Fishing rod</li>
<li>Gamepad / joypad</li>
<li>Joystick</li>
<li>Keyboard</li>
<li>Light gun</li>
<li>Mechanical motion tracker</li>
<li>Microphone</li>
<li>Mouse</li>
<li>Optical motion tracker</li>
<li>Paddle</li>
<li>Pedals</li>
<li>Racing wheel / steering wheel</li>
<li>Rhythm game accessory</li>
<li>Touchscreen</li>
<li>Trackball</li>
<li>Wii remote</li>
</ul>
</details>

### 5B. Connectivity [R][+]

Definition: Whether and how the platform edition was online or networked while the video was recorded (Lee et al., "VGMS 4.2," 2024)

Select "Offline" if were no online or networked components. 

<details>
<summary><i>controlled vocabulary</i></summary>
<ul>
<li>Cloud gaming / gaming on demand</li>
<li>Offline</li>
<li>Online browser</li>
<li>Online computer / networked computer</li>
<li>Online console / networked console</li>
<li>Online features / networked features</li>
<li>Online mobile device / networked mobile device</li>
<li>Online play / networked play</li>
</ul>
</details>

### 5C. Number of Players [R] 

Definition: The number of players in the gameplay footage of the platform edition (Lee et al., "VGMS 4.2," 2024)

<details>
<summary><i>controlled vocabulary</i></summary>
<ul>
<li>1 player</li>
<li>2 players</li>
<li>3 players</li>
<li>4 players</li>
<li>5 players</li>
<li>6 players</li>
<li>7 players</li>
<li>8 players</li>
<li>9 players</li>
<li>10 players</li>
<li>11-50 players</li>
<li>51 or more players</li>
</ul>
</details>

### 5D. Gameplay Mode [R][+]

Definition: A distinct configuration of the platform edition's mechanics and gameplay in the gameplay footage

<details>
<summary><i>controlled vocabulary</i> (adapted, with minor changes, from Wikipedia, "Glossary of Video Game Terms," 2026)</summary>
<ul>
<li>Arena</li>
<li>Attract / display / show</li>
<li>Capture the flag</li>
<li>Career</li>
<li>Challenge</li>
<li>Control point</li>
<li>Deathmatch</li>
<li>Debug</li>
<li>Easy / beginner / casual</li>
<li>Endless</li>
<li>God / invincible / infinite health</li>
<li>Hard / expert</li>
<li>King of the hill</li>
<li>New game plus</li>
<li>Noclip</li>
<li>Normal / moderate / default</li>
<li>Permadeath</li>
<li>Photo / photography</li>
<li>Score attack</li>
<li>Skirmish</li>
<li>Spectator</li>
<li>Story / campaign</li>
<li>Survival / horde</li>
<li>Time attack</li>
</ul>
</details>

### 5E. Language [R][+]

Definition: The language appearing in the gameplay footage of the platform edition

Multiple languages, including constructed languages such as Simlish, may be included. 

Include languages that are read as well as heard, be they diegetic (read or heard by characters in the world) or non-diegetic (intended to be read or heard by players). 

*text input field*

### 5F. Accessibility [+]

Definition: A configuration or appearance of the platform edition's accessibility features in the gameplay footage

<details>
<summary><i>controlled vocabulary</i> (based on guidelines from Ellis et al. n.d.)</summary>
<ul>
<li>Alternate inputs</li>
<li>Arachnophobia mode</li>
<li>Assist mode</li>
<li>Auto aim</li>
<li>Auto float</li>
<li>Autosave</li>
<li>Customized audio</li>
<li>Customized background movement</li>
<li>Customized communications or chat</li>
<li>Customized control sensitivity</li>
<li>Customized colours</li>
<li>Customized cool-down period</li>
<li>Customized cursor or crosshair design</li>
<li>Customized font size</li>
<li>Customized game speed</li>
<li>Customized haptics</li>
<li>Customized interface</li>
<li>Customized motion tracking</li>
<li>Customized speed</li>
<li>Customized steering</li>
<li>Customized text formatting</li>
<li>Customized virtual keyboard</li>
<li>High contrast mode</li>
<li>In-game help / guidance / tips</li>
<li>Infinite items</li>
<li>Interactive tutorial</li>
<li>Manual save</li>
<li>No blood or gore</li>
<li>No button mashing</li>
<li>No camera movement</li>
<li>No flashing and strobing effects</li>
<li>No flickering images</li>
<li>No music</li>
<li>No permadeath</li>
<li>No quick time events</li>
<li>No sound effects</li>
<li>No triggering content</li>
<li>No unexpected movement or events</li>
<li>Practice level</li>
<li>Progress summary</li>
<li>Realtime speech-to-text</li>
<li>Realtime text-to-speech</li>
<li>Remapped controls</li>
<li>Screenreader</li>
<li>Sign language</li>
<li>Skip boss or enemy</li>
<li>Skip level</li>
<li>Skip scene</li>
<li>Subtitles / captions</li>
<li>Surround sound</li>
<li>Symbol-based chat</li>
<li>Text chat</li>
<li>Text highlighing</li>
<li>Thalassophobia mode</li>
<li>Visually indicated interactive object</li>
<li>Visually indicated movement</li>
<li>Visually indicated speech</li>
<li>Voice chat</li>
<li>Voiced global positioning</li>
<li>Voiceovers for menus</li>
<li>Voiceovers for text</li>
</ul>
</details>

### 5G. Mods [R][+]

Definition: A configuration or appearance of a player or fan-authored alteration of the platform edition in the gameplay footage

*text input field* 

### 5H. Gameplay Settings Note

Definition: "Any other notable characteristics of the" gameplay settings that are "not captured in other fields" of this metadata schema (Lee et al., "VGMS 4.2," 2024)

*text input field*

## 6. Gameplay Footage Entity

Definition: Denotes the recorded video material of a particular instantiation (a [“platform edition”](#3-platform-edition-entity)) of a video game

*The following elements of the Gameplay Footage Entity should describe recorded gameplay of the platform edition intended for the GPFC.*

* [Type of Play](#6a-type-of-play-r) [R][+] (controlled vocabulary) 
* [Gameplay Genre](#6b-gameplay-genre-r) [R][+] (controlled vocabulary) 
* [Gameplay Subgenre](#6c-gameplay-subgenre-r) [R][+] (controlled vocabulary)
* [Narrative Genre](#6d-narrative-genre-r) [R][+] (controlled vocabulary) 
* [Narrative Subgenre](#6e-narrative-subgenre-r) [R][+] (controlled vocabulary) 
* [Dimension and Perspective](#6f-dimension-and-perspective-r) [R][+] (controlled vocabulary) 
* [Location](#6g-location-r) [R][+] (controlled vocabulary) 
* [Time Period](#6h-time-period-r) [R][+] (controlled vocabulary) 
* [Biome](#6i-biome-r) [R][+] (controlled vocabulary) 
* [Built Environment](#6j-built-environment-r) [R][+] (controlled vocabulary) 
* [Mode of Transport](#6k-mode-of-transport-r) [R][+] (controlled vocabulary) 
* [Items](#6l-items-r) [R+][+] (controlled vocabulary)
* [Atmosphere](#6m-atmosphere-r) [R][+] (controlled vocabulary) 
* [Player Character](#6n-player-character-r) [R][+] (controlled vocabulary) 
* [Non-Player Character](#6o-non-player-character-r) [R][+] (controlled vocabulary) 
* [Mechanics](#6p-mechanics-r) [R][+] (controlled vocabulary) 
* [Timekeeping](#6q-timekeeping-r) [R][+] (controlled vocabulary) 
* [Progression](#6r-progression-r) [R][+] (controlled vocabulary) 
* [Theme](#6s-theme-r) [R][+] (controlled vocabulary)
* [Trope](#6t-trope-r) [R][+] (controlled vocabulary)
* [Stereotype](#6u-stereotype-r) [R][+] (controlled vocabulary)
* [Assets](#6v-assets-r) [R][+] (controlled vocabulary)
* [Style](#6w-style-r) [R][+] (controlled vocabulary)
* [Interface](#6x-interface-r) [R][+] (controlled vocabulary)
* [Experience](#6y-experience-r) [R][+] (controlled vocabulary)
* [Transaction](#6z-transaction-r) [R][+] (controlled vocabulary) 
* [Metagaming](#6aa-metagaming-r) [R][+] (controlled vocabulary)
* [Content Warning](#6bb-content-warning-r) [R] (text input field)
* [Gameplay Footage Note](#6cc-gameplay-footage-note) (text input field)

### 6A. Type of Play [R][+]

Definition: How players relate socially to each other and the game in the gameplay footage

<details>
<summary><i>controlled vocabulary</i></summary>
<ul>
<li>Asynchronous multiplayer</li>
<li>Collaborative</li>
<li>Competitive</li>
<li>Competitive teams</li>
<li>Cooperative</li>
<li>Cooperative teams</li>
<li>Geolocative</li>
<li>Local multiplayer</li>
<li>Massively multiplayer</li>
<li>Online multiplayer</li>
<li>Player versus environment (PvE)</li>
<li>Player versus player (PvP)</li>
<li>Single-player</li>
<li>Split screen</li>
<li>Synchronous multiplayer</li>
<li>Zero player</li>
</ul>
</details>

### 6B. Gameplay Genre [R][+]

Definition: "The overall nature of . . . interactivity" in the gameplay footage "based on [the platform edition's] objectives, types of rules, distinctive characteristics, modes of action, and manners of gameplay" (Lee et al., "VGMS 4.2," 2024)

Note: "Traditional" in the controlled vocabulary below denotes "games based on mechanics that exist in the real world and can be played in a physical setting." They include board, card, exercise, gambling, game show, maze, pinball, and trivia games (Lee et al., "Controlled Vocabulary for Genre," 2024). 

<details>
<summary><i>controlled vocabulary</i> (adapted from Poff and Atari 2025 and Lee et al., "Controlled Vocabulary for Genre," 2024)</summary>
<ul>
<li>Action</li>
<li>Adventure / story-driven</li>
<li>Compilation / collection</li>
<li>Educational</li>
<li>Idle</li>
<li>Puzzle</li>
<li>Racing / driving</li>
<li>Role-playing / RPG</li>
<li>Simulation</li>
<li>Social</li>
<li>Sports</li>
<li>Strategy</li>
<li>Traditional</li>
</ul>
</details>

### 6C. Gameplay Subgenre [R][+]

Definition: Patterns of interactivity appearing in the gameplay footage "based on [the platform edition's] objectives, types of rules, distinctive characteristics, modes of action, and manners of gameplay" (Lee et al., "VGMS 4.2," 2024)

<details>
<summary><i>controlled vocabulary</i> (adapted, with additions, from Poff and Atari 2025 and Lee et al., "Controlled Vocabulary for Genre," 2024)</summary>
<ul>
<li>4X</li>
<li>Abstract</li>
<li>American football</li>
<li>Arcade</li>
<li>Arena shooter</li>
<li>Artillery</li>
<li>Australian football</li>
<li>Auto battler / auto chess</li>
<li>Auto runner</li>
<li>Baseball</li>
<li>Basketball</li>
<li>Battle royale</li>
<li>Beat ‘em up / brawler</li>
<li>Blobber</li>
<li>Block breaking</li>
<li>Board game</li>
<li>Boardsports</li>
<li>Bowling</li>
<li>Bullet hell</li>
<li>Business sim / tycoon</li>
<li>Card battle</li>
<li>Casino / roulette</li>
<li>Castle defence / castle attack</li>
<li>Chess</li>
<li>City building / construction sim</li>
<li>Claw machine</li>
<li>Collect-a-thon</li>
<li>Combat sports / wrestling</li>
<li>Cooking sim</li>
<li>Choose your own adventure</li>
<li>Creature breeding / genetics</li>
<li>Cricket</li>
<li>Cryptic puzzle</li>
<li>Cue sports / billiards</li>
<li>Cycling</li>
<li>Darts</li>
<li>Dating sim</li>
<li>Deckbuilder</li>
<li>Dexterity</li>
<li>Dodgeball</li>
<li>Dungeon crawl</li>
<li>Escape room / exit game / riddle room</li>
<li>Extraction</li>
<li>Extreme sports</li>
<li>Fairy chess / unorthodox chess</li>
<li>Falling block / block fill</li>
<li>Farming sim</li>
<li>Fashion sim</li>
<li>Fighting</li>
<li>Fitness / exercise</li>
<li>Flight sim</li>
<li>Friendslop</li>
<li>Fumblecore</li>
<li>Gambling / gambling elements</li>
<li>Game show</li>
<li>Gashapon</li>
<li>Genetics</li>
<li>God game</li>
<li>Golf</li>
<li>Government sim</li>
<li>Graphic adventure</li>
<li>Guessing / charades</li>
<li>Hack and slash</li>
<li>Hero shooter</li>
<li>Hidden object</li>
<li>Hockey</li>
<li>Horde shooter / horde surivor</li>
<li>Horse racing</li>
<li>Hunting / hunting sim</li>
<li>Immersive sim</li>
<li>Incremental</li>
<li>Interactive book</li>
<li>Interactive fiction</li>
<li>Interactive movie / full-motion video</li>
<li>Japanese-style adventure</li>
<li>Japanese-style RPG / JRPG</li>
<li>Job sim</li>
<li>Karaoke / singing</li>
<li>Kart racing</li>
<li>Life sim / social sim</li>
<li>Looter shooter</li>
<li>Logic puzzle</li>
<li>Martial arts</li>
<li>Mascot</li>
<li>Massively multiplayer online RPG (MMPORG)</li>
<li>Math puzzle</li>
<li>Maze / maze chase</li>
<li>Mechanical puzzle</li>
<li>Medical sim</li>
<li>Mental training</li>
<li>Metroidvania / search action</li>
<li>Military sim / milsim</li>
<li>Mini-game / micro-game collection</li>
<li>Monster taming / raising</li>
<li>Movement shooter</li>
<li>Multi-user dungeon / MUD</li>
<li>Multiplayer online battle arean / MOBA</li>
<li>Obstacle course</li>
<li>Off-road racing / rally racing</li>
<li>Pachinko</li>
<li>Paddle / ball and paddle</li>
<li>Parkour</li>
<li>Parser adventure</li>
<li>Party / parlour</li>
<li>Physics sim / physics puzzle</li>
<li>Photography sim</li>
<li>Pinball</li>
<li>Pipe puzzle</li>
<li>Platform / platformer</li>
<li>Platform fighter</li>
<li>Point and click</li>
<li>Programming / hacking sim</li>
<li>Racing sim</li>
<li>Racket sports</li>
<li>Rail shooter</li>
<li>Real-time strategy</li>
<li>Rocks and diamonds</li>
<li>Roguelike / roguelite</li>
<li>Rhythm / music / dancing</li>
<li>Rugby</li>
<li>Run and gun</li>
<li>Sandbox / open world / falling sand</li>
<li>Shoot 'em up</li>
<li>Shooting gallery</li>
<li>Skating</li>
<li>Slot machine</li>
<li>Snake</li>
<li>Soccer / football</li>
<li>Social deduction / secret identity</li>
<li>Sokoban</li>
<li>Soulslike</li>
<li>Sports sim</li>
<li>Stealth</li>
<li>Surveillance</li>
<li>Survival</li>
<li>Tabletop card / tabletop tile</li>
<li>Tactics / tactical</li>
<li>Tennis</li>
<li>Text adventure</li>
<li>Tile matching</li>
<li>Tiling puzzle / jigsaw</li>
<li>Time management</li>
<li>Timed input</li>
<li>Tower defence</li>
<li>Track and field</li>
<li>Trading / collectible card</li>
<li>Tricks / stunts</li>
<li>Trivia / quiz</li>
<li>Turn-based strategy</li>
<li>Twin-stick shooter</li>
<li>Twitch skill</li>
<li>Vehicle combat / car combat</li>
<li>Vehicle sim</li>
<li>Virtual life</li>
<li>Virtual pet</li>
<li>Visual novel</li>
<li>Volleyball</li>
<li>Walking sim</li>
<li>Wargame / grand strategy</li>
<li>Water sports</li>
<li>Winter sports</li>
<li>Word construction / word puzzle / crossword</li>
</ul>
</details>

### 6D. Narrative Genre [R][+]

Definition: The overall nature of storytelling in the gameplay footage based on how the platform edition tells, plots, and arranges stories

Use "abstract / no narrative" for abstract games and games without narratives or narrative elements. 

<details>
<summary><i>controlled vocabulary</i> (adapted, with minor changes, from Poff and Atari 2025 and Lee et al., "Controlled Vocabulary for Narrative Genre," 2024)</summary>
<ul>
<li>Abstract / no narrative</li>
<li>Action</li>
<li>Adventure</li>
<li>Comedy</li>
<li>Documentary</li>
<li>Drama</li>
<li>Fantasy</li>
<li>Historical</li>
<li>Horror</li>
<li>Mystery</li>
<li>Nonsense</li>
<li>Romance</li>
<li>Satire</li>
<li>Science fiction</li>
<li>Speculative</li>
<li>Thriller</li>
<li>War</li>
<li>Western</li>
</ul>
</details>

### 6E. Narrative Subgenre [R][+]

Definition: Patterns of storytelling in the gameplay footage based on how the platform edition tells, plots, and arranges stories

Use "abstract / no narrative" for abstract games and games without narratives or narrative elements. 

<details>
<summary><i>controlled vocabulary</i> (adapted, with additions, from Lee et al., "Controlled Vocabulary for Narrative Genre," 2024 and Wikipedia, "List of Genres," 2026)</summary>
<ul>
<li>Abstract / no narrative</li>
<li>Alternate history</li>
<li>Bait-and-switch</li>
<li>Biography / memoir / autobiography</li>
<li>Body horror</li>
<li>Burlesque</li>
<li>Children's</li>
<li>Coming-of-age / Bildungsroman</li>
<li>Cosmic horror / eldritch horror</li>
<li>Crime / detective</li>
<li>Cyberpunk</li>
<li>Dark comedy</li>
<li>Dark fantasy</li>
<li>Fable</li>
<li>Folk horror</li>
<li>Folklore / fairy tale</li>
<li>Found footage / creepypasta</li>
<li>Ghost story</li>
<li>Heist</li>
<li>Heroic fantasy / sword and sorcery</li>
<li>High fantasy</li>
<li>Instructional / pedagogical</li>
<li>Isekai / portal fantasy</li>
<li>Literary / classic</li>
<li>Love story</li>
<li>Low fantasy</li>
<li>Melodrama</li>
<li>Metafiction</li>
<li>Military</li>
<li>Monster / kaiju</li>
<li>Myth / mythic</li>
<li>Observational comedy</li>
<li>Parody / spoof</li>
<li>Period piece</li>
<li>Physical comedy</li>
<li>Procedural generation / randomized</li>
<li>Psychological</li>
<li>Religious</li>
<li>Retropunk / steampunk / dieselpunk</li>
<li>Revisionist Western</li>
<li>Romantic comedy</li>
<li>Shenmo</li>
<li>Sitcom / situational comedy</li>
<li>Slasher horror</li>
<li>Slice of life</li>
<li>Space opera / space Western</li>
<li>Spy / espionage</li>
<li>Superhero</li>
<li>Supernatural</li>
<li>Suspense</li>
<li>Vampire</li>
<li>Variety show</li>
<li>Wuxia</li>
<li>Young adult / teen drama</li>
<li>Zombie</li>
</ul>
</details>

### 6F. Dimension and Perspective [R][+]

Definition: "The intended perception of the depth of the represented entities in" the gameplay footage and "[t]he [graphical projection, camera, and/or point of view] from which the player experiences the gameplay" (Lee et al., "VGMS 4.2," 2024)  

Two options for this element (free camera and cinematic camera) are defined here to avoid confusion. 

Select "free camera" if "the camera is not attached to a specific avatar and does not follow a specific target" (Poff and Atari 2025). Such cameras are common in strategy and sandbox games, where the "player is able to freely slide/scroll/rotate through the environment" (ibid). 

Select "cinematic camera" if "different, fixed camera positions are set during the game's creation for a maximum cinematic effect. These positions cannot be controlled by the player" (ibid). 

Don't select "free camera" or "cinematic camera" if they do not apply to the gameplay footage. 

This element will typically be repeated: for example, 3D, 1st-person, and perspective camera. 

<details>
<summary><i>controlled vocabulary</i> (adapted, with minor changes, from Poff and Atari 2025, Jan 2017, and Lee et al., "VGMS 4.2," 2024)</summary>
<ul>
<li>2.5D</li>
<li>2D</li>
<li>3D</li>
<li>1st-person / first-person</li>
<li>2nd-person / second-person</li>
<li>3rd-person / third-person</li>
<li>Audio game</li>
<li>Augmented reality</li>
<li>Behind view / over the shoulder</li>
<li>Breaks the fourth wall</li>
<li>Camera zoom / scaling</li>
<li>Cinematic camera</li>
<li>Curvilinear projection</li>
<li>Diagonal-down view / isometric / 3/4 projection</li>
<li>Fixed screen / flip-screen scrolling</li>
<li>Free camera</li>
<li>HD-2D</li>
<li>Oblique project / cabinet</li>
<li>Perspective projection</li>
<li>Side-scrolling / tracking camera</li>
<li>Side view / multiview projection</li>
<li>Stereoscopic 3D</li>
<li>Text-based / spreadsheet</li>
<li>Top-down view / multiview projection</li>
<li>Virtual reality</li>
</ul>
</details>

### 6G. Location [R][+]

Definition: The planet, continent, and/or country appearing the gameplay footage 

Select "Fictional" if the location is imaginary (that is, it originated in the video game or its franchise). 

Select "Unspecified" when the location (such as "outer space") is vague or cannot be determined.

Note that gameplay footage may combine actual and fictional locations: for example, the town of Tigland in Canada on Earth. It may also combine actual and unspecified locations: "somewhere on Earth," for instance. 

Use the "Gameplay Footage Note" to include a more specific location, such as an actual city or fictional town appearing in the gameplay footage. 

Use existing scholarship, MobyGames, Wikipedia, Steam, fansites, official advertisements, the developer's official website, and/or the platform edition's official website to confirm the location.

<details>
<summary><i>controlled vocabulary</i></summary>
<ul>
<li>Afghanistan</li>
<li>Africa</li>
<li>Albania</li>
<li>Algeria</li>
<li>Andorra</li>
<li>Angola</li>
<li>Antarctica</li>
<li>Antigua and Barbuda</li>
<li>Argentina</li>
<li>Armenia</li>
<li>Asia</li>
<li>Australia</li>
<li>Austria</li>
<li>Azerbaijan</li>
<li>Bahamas</li>
<li>Bahrain</li>
<li>Bangladesh</li>
<li>Barbados</li>
<li>Belarus</li>
<li>Belgium</li>
<li>Belize</li>
<li>Benin</li>
<li>Bermuda </li>
<li>Bhutan</li>
<li>Bolivia</li>
<li>Bosnia and Herzegovina</li>
<li>Botswana</li>
<li>Brazil</li>
<li>Brunei</li>
<li>Bulgaria</li>
<li>Burkina Faso</li>
<li>Burundi</li>
<li>Cambodia</li>
<li>Cameroon</li>
<li>Canada</li>
<li>Cape Verde</li>
<li>Central African Republic</li>
<li>Chad</li>
<li>Chile</li>
<li>China</li>
<li>Colombia</li>
<li>Comoros</li>
<li>Congo, Republic of the</li>
<li>Congo, Democratic Republic of the</li>
<li>Costa Rica</li>
<li>Croatia</li>
<li>Cuba</li>
<li>Curacao</li>
<li>Cyprus</li>
<li>Czech Republic</li>
<li>Denmark</li>
<li>Djibouti</li>
<li>Dominica</li>
<li>Dominican Republic</li>
<li>Earth</li>
<li>East Timor</li>
<li>Ecuador</li>
<li>Egypt</li>
<li>El Salvador</li>
<li>Equatorial Guinea</li>
<li>Eritrea</li>
<li>Estonia</li>
<li>Eswatini</li>
<li>Ethiopia</li>
<li>Europe</li>
<li>Fictional</li>
<li>Fiji</li>
<li>Finland</li>
<li>France</li>
<li>Gabon</li>
<li>Gambia</li>
<li>Georgia</li>
<li>Germany</li>
<li>Ghana</li>
<li>Greece</li>
<li>Grenada</li>
<li>Guatemala</li>
<li>Guinea</li>
<li>Guinea-Bissau</li>
<li>Guyana</li>
<li>Haiti</li>
<li>Honduras</li>
<li>Hungary</li>
<li>Iceland</li>
<li>India</li>
<li>Indonesia</li>
<li>Iran</li>
<li>Iraq</li>
<li>Ireland</li>
<li>Israel</li>
<li>Italy</li>
<li>Ivory Coast</li>
<li>Jamaica</li>
<li>Japan</li>
<li>Jordan</li>
<li>Jupiter</li>
<li>Kazakhstan</li>
<li>Kenya</li>
<li>Kiribati</li>
<li>Kosovo</li>
<li>Kuwait</li>
<li>Kyrgyzstan</li>
<li>Laos</li>
<li>Latvia</li>
<li>Lebanon</li>
<li>Lesotho</li>
<li>Liberia</li>
<li>Libya</li>
<li>Liechtenstein</li>
<li>Lithuania</li>
<li>Luxembourg</li>
<li>Madagascar</li>
<li>Malawi</li>
<li>Malaysia</li>
<li>Maldives</li>
<li>Mali</li>
<li>Malta</li>
<li>Mars</li>
<li>Marshall Islands</li>
<li>Mauritania</li>
<li>Mauritius</li>
<li>Mercury</li>
<li>Mexico</li>
<li>Micronesia</li>
<li>Moldova</li>
<li>Monaco</li>
<li>Mongolia</li>
<li>Montenegro</li>
<li>Morocco</li>
<li>Mozambique</li>
<li>Myanmar</li>
<li>Namibia</li>
<li>Nauru</li>
<li>Nepal</li>
<li>Neptune</li>
<li>Netherlands</li>
<li>New Zealand</li>
<li>Nicaragua</li>
<li>Niger</li>
<li>Nigeria</li>
<li>North America</li>
<li>North Korea</li>
<li>North Macedonia</li>
<li>Norway</li>
<li>Oceania</li>
<li>Oman</li>
<li>Pakistan</li>
<li>Palau</li>
<li>Palestine</li>
<li>Panama</li>
<li>Papua New Guinea</li>
<li>Paraguay</li>
<li>Peru</li>
<li>Philippines</li>
<li>Poland</li>
<li>Portugal</li>
<li>Puerto Rico</li>
<li>Qatar</li>
<li>Romania</li>
<li>Russia</li>
<li>Rwanda</li>
<li>Saint Kitts and Nevis</li>
<li>Saint Lucia</li>
<li>Saint Vincent and the Grenadines</li>
<li>Samoa</li>
<li>San Marino</li>
<li>São Tomé and Príncipe</li>
<li>Saturn</li>
<li>Saudi Arabia</li>
<li>Senegal</li>
<li>Serbia</li>
<li>Seychelles</li>
<li>Sierra Leone</li>
<li>Singapore</li>
<li>Slovakia</li>
<li>Slovenia</li>
<li>Solomon Islands</li>
<li>Somalia</li>
<li>South Africa</li>
<li>South America</li>
<li>South Korea</li>
<li>South Sudan</li>
<li>Spain</li>
<li>Sri Lanka</li>
<li>Sudan</li>
<li>Suriname</li>
<li>Sweden</li>
<li>Switzerland</li>
<li>Syria</li>
<li>Taiwan</li>
<li>Tajikistan</li>
<li>Tanzania</li>
<li>Thailand</li>
<li>Togo</li>
<li>Tonga</li>
<li>Trinidad and Tobago</li>
<li>Tunisia</li>
<li>Turkey</li>
<li>Turkmenistan</li>
<li>Tuvalu</li>
<li>Uganda</li>
<li>Ukraine</li>
<li>United Arab Emirates</li>
<li>United Kingdom</li>
<li>United States</li>
<li>Unspecified</li>
<li>Uranus</li>
<li>Uruguay</li>
<li>Uzbekistan</li>
<li>Vanuatu</li>
<li>Vatican City</li>
<li>Venezuela</li>
<li>Venus</li>
<li>Vietnam</li>
<li>Yemen</li>
<li>Zambia</li>
<li>Zimbabwe</li>
</ul>
</details>

### 6H. Time Period [R][+]

Definition: The general time period in which the gameplay footage is set

Select "Fictional" if the time period is imaginary (that is, it originated in the video game or its franchise). 

Select "Unspecified" when the time period is vague or cannot be determined.

Use the "Gameplay Footage Note" to include a specific date, year, period, moment, or event represented by the gameplay footage. 

Use existing scholarship, MobyGames, Wikipedia, Steam, fansites, official advertisements, the developer's official website, and/or the platform edition's official website to confirm the time period.

<details>
<summary><i>controlled vocabulary</i> (adapted, with changes and additions, from Lee et al., "Controlled Vocabulary for Setting," 2024)</summary>
<ul>
<li>Axial Age</li>
<li>Bronze Age</li>
<li>Contemporary</li>
<li>Copper Age / Chalcolithic</li>
<li>Classical antiquity</li>
<li>Early modern</li>
<li>Fictional</li>
<li>Future</li>
<li>Geologic time</li>
<li>Iron Age</li>
<li>Late antiquity</li>
<li>Late modern</li>
<li>Mesolithic</li>
<li>Neolithic</li>
<li>Paleolithic</li>
<li>Postclassical</li>
<li>Time immemorial</li>
<li>Unspecified</li>
</ul>
</details>

### 6I. Biome [R][+]

Definition: The ecological community type appearing in the gameplay footage

<details>
<summary><i>controlled vocabulary</i> (adapted, with changes and additions, from Lee et al., "Controlled Vocabulary for Setting," 2024)</summary>
<ul>
<li>Abstract</li>
<li>Aquatic / underwater</li>
<li>Beach / island</li>
<li>Cave / subterranean</li>
<li>Desert</li>
<li>Forest / woodlands</li>
<li>Grasslands / plains / savanna</li>
<li>Jungle</li>
<li>Lava / volcano</li>
<li>Mountains</li>
<li>Outer space</li>
<li>Ruins</li>
<li>Sky</li>
<li>Suburban / suburb</li>
<li>Swamp / marsh</li>
<li>Tundra / snow / ice</li>
<li>Urban / city</li>
</ul>
</details>

### 6J. Built Environment [R][+]

Definition: An artificial physical feature or edifice appearing in the gameplay footage that's typically meant to surround, structure, and/or guide the diegetic activities of characters in the platform edition 

<details>
<summary><i>controlled vocabulary</i> (adapted, with changes and additions, from Lee et al., "Controlled Vocabulary for Setting," 2024)</summary>
<ul>
<li>Alley</li>
<li>Amusement park / circus / carnival</li>
<li>Aquarium</li>
<li>Arcade</li>
<li>Arena / coliseum / stadium</li>
<li>Bank</li>
<li>Basement</li>
<li>Bathhouse / spa / sauna</li>
<li>Bathroom / washroom / water closet</li>
<li>Bedroom</li>
<li>Bridge</li>
<li>Castle / fortress</li>
<li>Church / cathedral / chapel / temple</li>
<li>Club / bar / saloon / pub</li>
<li>Computer / cyberspace / internet</li>
<li>Door</li>
<li>Dungeon</li>
<li>Factory</li>
<li>Farm / farmhouse</li>
<li>Funeral home / morgue</li>
<li>Garage</li>
<li>Graveyard</li>
<li>Gym / gymnasium</li>
<li>House / apartment / townhouse</li>
<li>Hospital / asylum</li>
<li>Hotel / inn</li>
<li>Invisible wall</li>
<li>Jail / prison</li>
<li>Kitchen</li>
<li>Laboratory / lab</li>
<li>Library</li>
<li>Longhouse</li>
<li>Mansion / palace</li>
<li>Maze</li>
<li>Military base</li>
<li>Mill</li>
<li>Mine</li>
<li>Monastery</li>
<li>Museum / archive / gallery</li>
<li>Office / office building</li>
<li>Park / nature reserve</li>
<li>Playground</li>
<li>Race track</li>
<li>Restaurant / cafe</li>
<li>Rooftop</li>
<li>School / classroom</li>
<li>Sewer</li>
<li>Shack</li>
<li>Ship</li>
<li>Shrine</li>
<li>Skyscraper</li>
<li>Space station</li>
<li>Stairs / ladder</li>
<li>Store</li>
<li>Street light / street lamp</li>
<li>Tower</li>
<li>Town</li>
<li>Training ground</li>
<li>University campus / college campus</li>
<li>Village</li>
<li>Visible wall</li>
<li>Window</li>
<li>Zoo</li>
</ul>
</details>

### 6K. Mode of Transport [R][+]

Definition: A means of conveyance or travel from one place to another appearing in the gameplay footage 

Select "No mode of transport" if the footage contains no means of conveyance or travel.

<details>
<summary><i>controlled vocabulary</i> (adapted, with changes and additions, from Poff and Atari 2025 and Lee et al., "Controlled Vocabulary for Setting," 2024)</summary>
<ul>
<li>Airplane</li>
<li>Airship</li>
<li>All-terrain vehicle</li>
<li>Bicycle / bike</li>
<li>Boat / sailboat / steamboat / yacht</li>
<li>Bovine / cow / buffalo</li>
<li>Buggy / carriage</li>
<li>Bus</li>
<li>Cable car</li>
<li>Camel</li>
<li>Canoe / kayak</li>
<li>Car / racecar</li>
<li>Caribou / reindeer</li>
<li>Cat</li>
<li>Chocobo</li>
<li>Dog</li>
<li>Elephant</li>
<li>Equine / horse / donkey / mule</li>
<li>Ferry</li>
<li>Fictional item</li>
<li>Fictional species</li>
<li>Fictional technology</li>
<li>Fictional vehicle</li>
<li>Gliding</li>
<li>Helicopter</li>
<li>Hot air balloon</li>
<li>Hoverboard</li>
<li>Hovercraft</li>
<li>Kart / go kart</li>
<li>Llama</li>
<li>Mecha / giant robot</li>
<li>Minecart</li>
<li>Motorcycle</li>
<li>Portal / fast travel / teleportation</li>
<li>Running</li>
<li>Skateboard</li>
<li>Skates</li>
<li>Skis</li>
<li>Sled</li>
<li>Snowboard</li>
<li>Snowmobile</li>
<li>Spacecraft / spaceship</li>
<li>Submarine</li>
<li>Swimming</li>
<li>Tank</li>
<li>Taxi</li>
<li>Time machine</li>
<li>Tractor</li>
<li>Train / subway</li>
<li>Trolley</li>
<li>Truck</li>
<li>Tube</li>
<li>Unicorn</li>
<li>Walking</li>
<li>Wheelchair</li>
<li>Wings / flight</li>
<li>Zipline</li>
</ul>
</details>

### 6L. Items [R][+]

Definition: Types of consumables, equipment, progression items, crafting materials, currencies, and valuables appearing in the gameplay footage (Wikipedia, "Item (game terminology)," 2026). 

Select "No items" if the footage contains no items.

<details>
<summary><i>controlled vocabulary</i></summary>
<ul>
<li>Accessory</li>
<li>Ammunition / ammo</li>
<li>Antidote</li>
<li>Armour</li>
<li>Blueprint</li>
<li>Book</li>
<li>Buff / boost</li>
<li>Coat</li>
<li>Collectible</li>
<li>Compact disc / CD</li>
<li>Compass</li>
<li>Computer / computer parts</li>
<li>Cooked food / prepared food</li>
<li>Cosmetic / skin</li>
<li>Credits</li>
<li>Digital optical disc / DVD</li>
<li>Dress</li>
<li>Drink</li>
<li>Dye / ink</li>
<li>Energy</li>
<li>Fabric / textile</li>
<li>Film / rolls of film</li>
<li>Fruit / fruit product</li>
<li>Hat</li>
<li>Health potion</li>
<li>Key / keycard</li>
<li>Letter / journal entry</li>
<li>Mana potion</li>
<li>Map</li>
<li>Meat / bone / animal product</li>
<li>Money / coins / cash</li>
<li>Monster parts</li>
<li>Mushroom / fungi</li>
<li>Musical instrument</li>
<li>No items</li>
<li>Oil</li>
<li>Ore / minerals / metals</li>
<li>Pants</li>
<li>Photograph</li>
<li>Recipe</li>
<li>Shirt</li>
<li>Shoes / boots</li>
<li>Skirt</li>
<li>Suit</li>
<li>Swimsuit</li>
<li>Tape / cassette / audio / video</li>
<li>Tool / technology</li>
<li>Underwear</li>
<li>Vegetable / herb / plant / plant product</li>
<li>Water</li>
<li>Wood</li>
<li>Weapon</li>
</ul>
</details>

### 6M. Atmosphere [R][+]

Definition: "The pervading [mood] or tone of the" world appearing in the gameplay footage; it "evokes or recalls a certain emotion or state of mind" (Lee et al., "VGMS 4.2," 2024) 

The controlled vocabulary for this element avoids duplicating terms used in vocabularies for other elements, such as "Narrative Genre," "Narrative Subgenre," and "Type of Play." 

<details>
<summary><i>controlled vocabulary</i> (adapted, with changes and additions, from Lee et al., "Controlled Vocabulary for Mood," 2024)</summary>
<ul>
<li>Accessible</li>
<li>Beautiful</li>
<li>Believable</li>
<li>Bleak</li>
<li>Bold</li>
<li>Bright</li>
<li>Brittle</li>
<li>Captivating</li>
<li>Cozy</li>
<li>Creative</li>
<li>Dangerous</li>
<li>Disturbing</li>
<li>Eerie</li>
<li>Energizing</li>
<li>Erotic</li>
<li>Gloomy</li>
<li>Haunting</li>
<li>Hopeful</li>
<li>Hostile</li>
<li>Intellectual</li>
<li>Intense</li>
<li>Intimate</li>
<li>Lonely</li>
<li>Mischievous</li>
<li>Mournful</li>
<li>Ominous</li>
<li>Opaque</li>
<li>Peaceful</li>
<li>Pensive</li>
<li>Punishing</li>
<li>Quotidian</li>
<li>Rigid</li>
<li>Sentimental</li>
<li>Serene</li>
<li>Snarky</li>
<li>Suspicious</li>
<li>Theatrical</li>
<li>Threatening</li>
<li>Toxic</li>
<li>Unpredictable</li>
<li>Violent</li>
<li>Welcoming</li>
<li>Whimsical</li>
</ul>
</details>

### 6N. Player Character [R][+]

Definition: A character in the gameplay footage whose actions are controlled by the player 

This element will typically be repeated. 

Select "No player character" if no player character appears in the footage. 

Use existing scholarship, MobyGames, Wikipedia, Steam, fansites, and/or related sources to substantiate metadata about the player character. 

Feature request (4 June 2026): select "implicit" when characters are implicitly coded and "explicit" when they are explicitly coded (Shaw et al. 2025). As Adrienne Shaw et al. note, these selections are a fraught process (ibid). We will update the GPMS and GPFC as both projects unfold, and we will correct our mistakes and learn from them as they occur. Many aspects of this element are thus subject to change. 

<details>
<summary><i>controlled vocabulary</i> (adapted, with changes and additions, from Shaw et al. 2025 and Lee et al., "Controlled Vocabulary for Protagonist" and "Controlled Vocabulary for Tropes," 2024)</summary>
<ul>
<li>African PC</li>
<li>Agender PC</li>
<li>Aromantic PC</li>
<li>Asexual PC</li>
<li>Asian PC</li>
<li>Australian PC / from Oceania</li>
<li>Autistic PC</li>
<li>Avatar</li>
<li>Bisexual PC</li>
<li>Black PC</li>
<li>Blank slate / cipher</li>
<li>Blind PC</li>
<li>Canadian PC</li>
<li>Customizable age</li>
<li>Customizable character model</li>
<li>Customizable complexion</li>
<li>Customizable gender</li>
<li>Customizable hair</li>
<li>Customizable PC</li>
<li>Customizable race/ethnicity</li>
<li>Customizable relationships</li>
<li>Customizable species</li>
<li>Deaf PC</li>
<li>Demisexual PC</li>
<li>Disabled PC</li>
<li>Entitled PC</li>
<li>European PC</li>
<li>Female PC</li>
<li>Fictional species</li>
<li>Gay PC</li>
<li>Gender non-conforming PC</li>
<li>Genderfluid PC</li>
<li>Genderqueer PC</li>
<li>Hearing-impaired PC</li>
<li>Heterosexual PC / straight PC</li>
<li>Indigenous PC</li>
<li>Intersex PC</li>
<li>Lesbian PC</li>
<li>Male PC</li>
<li>Neurodivergent PC</li>
<li>No player character</li>
<li>Non-binary PC</li>
<li>Nonhuman PC</li>
<li>North American PC</li>
<li>Original character</li>
<li>Overpowered PC</li>
<li>Pansexual PC</li>
<li>Party member</li>
<li>PC can die</li>
<li>PC cannot die</li>
<li>PC cannot be customized</li>
<li>PC has amnesia</li>
<li>PC has great hair</li>
<li>PC is a brawler</li>
<li>PC is a builder</li>
<li>PC is a child</li>
<li>PC is a collector</li>
<li>PC is a colonizer / settler</li>
<li>PC is a fundamentalist</li>
<li>PC is a heretic</li>
<li>PC is a hero</li>
<li>PC is a hostage</li>
<li>PC is a hunter</li>
<li>PC is a hivemind</li>
<li>PC is a magic user</li>
<li>PC is a migrant</li>
<li>PC is a parent / guardian</li>
<li>PC is a pirate</li>
<li>PC is a ranger</li>
<li>PC is a revolutionary</li>
<li>PC is a rogue</li>
<li>PC is a shapeshifter</li>
<li>PC is a spy</li>
<li>PC is a stereotype</li>
<li>PC is a stranger / visitor</li>
<li>PC is a student</li>
<li>PC is a tank</li>
<li>PC is a teenager</li>
<li>PC is a twin</li>
<li>PC is a villain</li>
<li>PC is a war veteran</li>
<li>PC is an adult</li>
<li>PC is an elder</li>
<li>PC is an immigrant</li>
<li>PC is an outlaw</li>
<li>PC is an overlord</li>
<li>PC is funny</li>
<li>PC is non-corporeal</li>
<li>PC is poor</li>
<li>PC is pregnant</li>
<li>PC is strong</li>
<li>PC is undead</li>
<li>PC is weak</li>
<li>PC is wealthy</li>
<li>Queer PC</li>
<li>Racialized PC</li>
<li>Religious PC</li>
<li>Roleplay</li>
<li>Silent protagonist</li>
<li>South American PC</li>
<li>Trans PC</li>
<li>Two-spirit PC</li>
<li>Visually-impaired PC</li>
<li>White PC</li>
</ul>
</details>

### 6O. Non-Player Character [R][+]

Definition: A character in the gameplay footage whose actions are not controlled by the player 

This element will typically be repeated. 

Select "No non-player character" if a non-player character does not appear in the footage. 

Use existing scholarship, MobyGames, Wikipedia, Steam, fansites, and/or related sources to substantiate metadata about the non-player character. 

Feature request (4 June 2026): select "implicit" when characters are implicitly coded and "explicit" when they are explicitly coded (Shaw et al. 2025). As Adrienne Shaw et al. note, these selections are a fraught process (ibid). We will update the GPMS and GPFC as both projects unfold, and we will correct our mistakes and learn from them as they occur. Many aspects of this element are thus subject to change. 

<details>
<summary><i>controlled vocabulary</i> (adapted, with changes and additions, from Shaw et al. 2025 and Lee et al., "Controlled Vocabulary for Protagonist" and "Controlled Vocabulary for Tropes," 2024)</summary>
<ul>
<li>African NPC</li>
<li>Agender NPC</li>
<li>Aromantic NPC</li>
<li>Asexual NPC</li>
<li>Asian NPC</li>
<li>Australian NPC / from Oceania</li>
<li>Autistic NPC</li>
<li>Bisexual NPC</li>
<li>Black NPC</li>
<li>Blind NPC</li>
<li>Boss</li>
<li>Canadian NPC</li>
<li>Companion / buddy</li>
<li>Customizable NPC</li>
<li>Deaf NPC</li>
<li>Demisexual NPC</li>
<li>Disabled NPC</li>
<li>Entitled NPC</li>
<li>European NPC</li>
<li>Familiar</li>
<li>Female NPC</li>
<li>Fictional species</li>
<li>Gay NPC</li>
<li>Gender non-conforming NPC</li>
<li>Genderfluid NPC</li>
<li>Genderqueer NPC</li>
<li>Hearing-impaired NPC</li>
<li>Heterosexual NPC / straight NPC</li>
<li>Imaginary NPC</li>
<li>Indigenous NPC</li>
<li>Intersex NPC</li>
<li>Lesbian NPC</li>
<li>Male NPC</li>
<li>Neurodivergent NPC</li>
<li>No non-player character</li>
<li>Non-binary NPC</li>
<li>Nonhuman NPC</li>
<li>North American NPC</li>
<li>NPC can die</li>
<li>NPC cannot die</li>
<li>NPC has amnesia</li>
<li>NPC has great hair</li>
<li>NPC is a brawler</li>
<li>NPC is a builder</li>
<li>NPC is a child</li>
<li>NPC is a collector</li>
<li>NPC is a colonizer / settler</li>
<li>NPC is a fetch quest</li>
<li>NPC is a fundamentalist</li>
<li>NPC is a guide</li>
<li>NPC is a helper</li>
<li>NPC is a heretic</li>
<li>NPC is a hero</li>
<li>NPC is a hivemind</li>
<li>NPC is a hostage</li>
<li>NPC is a hunter</li>
<li>NPC is a magic user</li>
<li>NPC is a migrant</li>
<li>NPC is a parent / guardian</li>
<li>NPC is a pirate</li>
<li>NPC is a protagonist</li>
<li>NPC is a ranger</li>
<li>NPC is a revolutionary</li>
<li>NPC is a rival</li>
<li>NPC is a rogue</li>
<li>NPC is a shapeshifter</li>
<li>NPC is a spy</li>
<li>NPC is a stereotype</li>
<li>NPC is a student</li>
<li>NPC is a tank</li>
<li>NPC is a teenager</li>
<li>NPC is a twin</li>
<li>NPC is a villain</li>
<li>NPC is a war veteran</li>
<li>NPC is an adult</li>
<li>NPC is an elder</li>
<li>NPC is an enemy / monster</li>
<li>NPC is an immigrant</li>
<li>NPC is an outlaw</li>
<li>NPC is an overlord</li>
<li>NPC is hostile </li>
<li>NPC is funny</li>
<li>NPC is non-corporeal</li>
<li>NPC is PC's grandparent</li>
<li>NPC is PC's mentor / adviser</li>
<li>NPC is PC's roommate</li>
<li>NPC is PC's parent / guardian</li>
<li>NPC is PC's partner </li>
<li>NPC is PC's sibling</li>
<li>NPC is PC's teacher</li>
<li>NPC is poor</li>
<li>NPC is pregnant</li>
<li>NPC is undead</li>
<li>NPC is wealthy</li>
<li>Overpowered NPC</li>
<li>Pansexual NPC</li>
<li>Party member</li>
<li>Pet</li>
<li>Queer NPC</li>
<li>Racialized NPC</li>
<li>Religious NPC</li>
<li>Shopkeeper</li>
<li>South American NPC</li>
<li>Trans NPC</li>
<li>Tutorial NPC</li>
<li>Two-spirit NPC</li>
<li>Visually-impaired NPC</li>
<li>White NPC</li>
</ul>
</details>

### 6P. Mechanics [R][+]

Definition: A method or "verb" players use to interact with the state of the platform edition as it appears in the gameplay footage (Sicart 2015; Lee et al., "VGMS 4.2," 2024)

Select "No mechanic" if a mechanic is not used in the gameplay footage. 

This element will typically be repeated. Select only significant mechanics in cases where five or more options in the controlled vocabulary apply. 

<details>
<summary><i>controlled vocabulary</i> (adapted, with changes and additions, from BoardGameGeek n.d. and Lee et al., "Controlled Vocabulary for Mechanics," 2024)</summary>
<ul>
<li>Accelerating</li>
<li>Aiming</li>
<li>Aligning</li>
<li>Attacking (melee)</li>
<li>Attacking (ranged)</li>
<li>Auctioning</li>
<li>Avoiding</li>
<li>Balancing</li>
<li>Barricading</li>
<li>Bidding</li>
<li>Blocking</li>
<li>Bluffing</li>
<li>Breaking</li>
<li>Building</li>
<li>Buying</li>
<li>Capturing</li>
<li>Caring</li>
<li>Carrying</li>
<li>Chaining</li>
<li>Choosing</li>
<li>Cleaning / washing</li>
<li>Climbing</li>
<li>Closing</li>
<li>Collecting</li>
<li>Communicating noverbally</li>
<li>Communicating verbally</li>
<li>Cooking / making food</li>
<li>Crafting</li>
<li>Crawling / dungeon crawling</li>
<li>Dancing</li>
<li>Dating</li>
<li>Dealing</li>
<li>Deckbuilding</li>
<li>Decoding</li>
<li>Defenestrating</li>
<li>Delivering</li>
<li>Destroying</li>
<li>Digging</li>
<li>Disk-flicking</li>
<li>Dodging</li>
<li>Drawing</li>
<li>Drinking</li>
<li>Driving</li>
<li>Eating</li>
<li>Eavesdropping</li>
<li>Emoting</li>
<li>Equipping</li>
<li>Exercising</li>
<li>Exploring</li>
<li>Falling</li>
<li>Farming</li>
<li>Fetching</li>
<li>Fighting / kicking / punching</li>
<li>Fishing</li>
<li>Flying</li>
<li>Foraging / gathering</li>
<li>Grabbing</li>
<li>Hacking</li>
<li>Healing</li>
<li>Hiding</li>
<li>Hitting</li>
<li>Inputting text</li>
<li>Jumping / leaping</li>
<li>Locking</li>
<li>Managing</li>
<li>Matching</li>
<li>Mining</li>
<li>Moving</li>
<li>Negotiating</li>
<li>No mechanic</li>
<li>Opening</li>
<li>Parrying</li>
<li>Pausing</li>
<li>Photographing</li>
<li>Piloting</li>
<li>Placing workers</li>
<li>Playing cards</li>
<li>Playing music</li>
<li>Pool building</li>
<li>Positioning</li>
<li>Programming</li>
<li>Pulling</li>
<li>Pushing</li>
<li>Raising creatures</li>
<li>Releasing</li>
<li>Researching</li>
<li>Rewinding</li>
<li>Riding</li>
<li>Rolling</li>
<li>Rolling dice</li>
<li>Romancing</li>
<li>Rotating</li>
<li>Running</li>
<li>Sailing</li>
<li>Saving</li>
<li>Searching</li>
<li>Sharing</li>
<li>Shooting</li>
<li>Signing</li>
<li>Singing</li>
<li>Skateboarding</li>
<li>Skating</li>
<li>Skiing</li>
<li>Sneaking</li>
<li>Spellcasting</li>
<li>Spinning</li>
<li>Stealing</li>
<li>Storytelling</li>
<li>Swimming</li>
<li>Swiping</li>
<li>Talking / speaking</li>
<li>Taming</li>
<li>Throwing</li>
<li>Timing</li>
<li>Trading</li>
<li>Travelling</li>
<li>Unlocking</li>
<li>Voting</li>
<li>Walking</li>
<li>Wandering</li>
<li>Writing</li>
</ul>
</details>

### 6Q. Timekeeping [R][+]

Definition: How the platform edition handles the passage of time in the gameplay footage; approaches to timekeeping inevitably influence narrative pacing as well as the timing and rhythm of both players and games 

Two options for this element ("meditative / zen" and "persistent") are defined here to avoid confusion. 

Select "meditative / zen" if the game "tr[ies] to calm or relax players. These types of games often have no goals and players can't do anything wrong inside the game" (Poff and Atari 2025). 

Select "persistent" if the game's "mechanics continue even when the player is not playing the game. Either the game state is simulated on a remote server or the changes over time are calculated when the player returns to playing" (ibid). 

Don't select "meditative / zen" or "persistent" if they do not apply to the gameplay footage. 

<details>
<summary><i>controlled vocabulary</i> (adapted from Poff and Atari 2025)</summary>
<ul>
<li>Meditative / zen</li>
<li>Persistent</li>
<li>Real-time</li>
<li>Turn-based</li>
</ul>
</details>

### 6R. Progression [R][+]

Description: How, as demonstrated by the footage, the platform edition allows players to advance, acknowledges their attempts to advance, or affords them with a sense of progress, achievement, or productivity (Lee et al., "VGMS 4.2," 2024)

Forms or systems include horizontal progression (unlocking options), vertical progression (earning upgrades), player progression (developing skills and knowledge), character progression (levelling and new abilities), world progression (new levels, locations, and enemies), journey / mission progression (tasks or quests to be completed), narrative progression (from exposition to resolution), and gamification (achievements or trophies) (Brazie 2024). 

<details>
<summary><i>controlled vocabulary</i></summary>
<ul>
<li>Achievement / trophy / badge</li>
<li>Aha moment</li>
<li>Act structure</li>
<li>Branching narrative</li>
<li>Checkpoint</li>
<li>Choice-and-consequence system</li>
<li>Climax</li>
<li>Cognitive development</li>
<li>Collectible</li>
<li>Core loop</li>
<li>Cutscene</li>
<li>Death</li>
<li>Dialogue tree</li>
<li>Elimination / team wipe</li>
<li>Embedded story</li>
<li>Enacted story</li>
<li>Endless game</li>
<li>Environmental storytelling / story breadcrumbs</li>
<li>Evoked story</li>
<li>Exposition</li>
<li>Falling action</li>
<li>Flashback / analepsis</li>
<li>Flashforward / prolepsis</li>
<li>Gating</li>
<li>Highlight reel / replay reel</li>
<li>Horizontal movement</li>
<li>Hub / home base</li>
<li>In-game reward</li>
<li>Level complete</li>
<li>Levelling up</li>
<li>Loading screen</li>
<li>Mini-game</li>
<li>Mission complete / quest complete</li>
<li>Motor development</li>
<li>New ability / skill</li>
<li>New character</li>
<li>New cosmetic / skin</li>
<li>New game plus</li>
<li>New item</li>
<li>New level</li>
<li>New location</li>
<li>New mission / quest</li>
<li>New round</li>
<li>Platinum / 100% achievements</li>
<li>Procedural generation / randomization</li>
<li>Progression map / player path</li>
<li>Quick time event</li>
<li>Resolution / ending</li>
<li>Respawning</li>
<li>Rising action</li>
<li>Rolling credits</li>
<li>Round complete</li>
<li>Save point</li>
<li>Scripted event</li>
<li>Skill tree / tech tree</li>
<li>Upgrade</li>
<li>Vertical movement</li>
</ul>
</details>

### 6S. Theme [R][+]

Definition: "A common thread, motif, subject, or idea that recurs in" the gameplay footage (Getty 2004; Lee et al., "VGMS 4.2," 2024)

This element will typically be repeated. Select only significant themes in cases where five or more options in the controlled vocabulary apply. 

<details>
<summary><i>controlled vocabulary</i> (adapted, with additions, from Lee et al., "Controlled Vocabulary for Theme," 2024)</summary>
<ul>
<li>2SLGBTQIA+ / queer</li>
<li>Abandonment / trust</li>
<li>Ableism</li>
<li>Alienation / isolation / solitude</li>
<li>Abduction</li>
<li>Addiction</li>
<li>Aging</li>
<li>Alter-ego</li>
<li>Anti-capitalism</li>
<li>Anti-colonial</li>
<li>Anti-war</li>
<li>Apocalypse / post-apocalypse</li>
<li>Arrogance / hubris</li>
<li>Athletics</li>
<li>Beauty / attraction</li>
<li>Belonging / inclusion</li>
<li>Betrayal / heartbreak</li>
<li>Binaries</li>
<li>Biphobia</li>
<li>Blackness</li>
<li>Blasphemy</li>
<li>Bravery / courage</li>
<li>Capitalism</li>
<li>Catastrophe</li>
<li>Chance / certainty</li>
<li>Chaos / order</li>
<li>Childhood</li>
<li>Circle of life</li>
<li>Cisnormativity</li>
<li>Civilization</li>
<li>Class / wealth</li>
<li>Companionship / friendship</li>
<li>Competition / winning / losing</li>
<li>Connecting with nature / land / water</li>
<li>Conquest / colonization</li>
<li>Conservation</li>
<li>Conspiracy</li>
<li>Convention / rebellion</li>
<li>Corruption</li>
<li>Cult</li>
<li>Curse</li>
<li>Decolonization</li>
<li>Democracy</li>
<li>Destruction</li>
<li>Diplomacy</li>
<li>Disability</li>
<li>Displacement</li>
<li>Dreams / hopes</li>
<li>Drugs and alcohol / intoxication</li>
<li>Duty / responsibility</li>
<li>Dystopia</li>
<li>East / West</li>
<li>Economy / economics</li>
<li>Education / learning / pedagogy</li>
<li>Empire</li>
<li>Equality / equity</li>
<li>Evolution</li>
<li>Failure</li>
<li>Faith / doubt</li>
<li>Family</li>
<li>Fascism</li>
<li>Fate / free will</li>
<li>Fatphobia</li>
<li>Fear</li>
<li>Feminism</li>
<li>Freedom</li>
<li>Gender / gender expression</li>
<li>Gods / goddesses</li>
<li>Good versus evil </li>
<li>Grace / humility</li>
<li>Greed / ambition</li>
<li>Grotesque</li>
<li>Guilt/ conscience</li>
<li>Happiness / joy</li>
<li>Harassment</li>
<li>Hate / hate crime</li>
<li>Health / healing / medicine</li>
<li>Help from others</li>
<li>Heroism</li>
<li>Heteronormativity</li>
<li>Hierarchies</li>
<li>Holiday / vacation</li>
<li>Homophobia</li>
<li>Human rights / civil rights</li>
<li>Humans versus machine</li>
<li>Humans versus nature</li>
<li>Humour / laughter</li>
<li>Identity / self-image</li>
<li>Illuminati</li>
<li>Illusion / disillusionment</li>
<li>Indigeneity </li>
<li>Intersectionality</li>
<li>Interspecies friendship</li>
<li>Intrigue</li>
<li>Invasion / alien invasion</li>
<li>Jealousy</li>
<li>Justice / injustice</li>
<li>Knowledge / ignorance</li>
<li>Light and darkness</li>
<li>Logic / common sense</li>
<li>Loss / grief</li>
<li>Loss of innocence</li>
<li>Love / everlasting love / forbidden love</li>
<li>Loyalty</li>
<li>Lust / desire</li>
<li>Marginalization / discrimination</li>
<li>Masking</li>
<li>Matriarchy</li>
<li>Memory / amnesia</li>
<li>Mercy / ruthlessness</li>
<li>Miscommunication</li>
<li>Mistaken identity</li>
<li>Monarchy / kings / queens</li>
<li>Morality</li>
<li>Mortality / immortality</li>
<li>Murder</li>
<li>Nationalism / patriotism</li>
<li>Neoliberalism</li>
<li>Nonviolence</li>
<li>North / South</li>
<li>Nostalgia</li>
<li>Obscenity</li>
<li>Occult / witchcraft</li>
<li>Oppression / internalized oppression</li>
<li>Othering</li>
<li>Pandemic</li>
<li>Paranormal</li>
<li>Parenthood</li>
<li>Passing</li>
<li>Patriarchy</li>
<li>Peer pressure</li>
<li>Perseverance</li>
<li>Personal growth / maturity</li>
<li>Police / policing</li>
<li>Polyamory</li>
<li>Power / regime change</li>
<li>Pride</li>
<li>Privacy</li>
<li>Privilege</li>
<li>Productivity</li>
<li>Progress</li>
<li>Prophecy</li>
<li>Race </li>
<li>Racism</li>
<li>Rebirth</li>
<li>Redemption / forgiveness</li>
<li>Regret</li>
<li>Religion</li>
<li>Resistance</li>
<li>Reunion</li>
<li>Revenge / honour / reputation</li>
<li>Rivalry</li>
<li>Sacred / profane</li>
<li>Sacrifice / dedication</li>
<li>Sanity / madness</li>
<li>Secrecy</li>
<li>Self-harm</li>
<li>Self-reliance / will to survive</li>
<li>Sex</li>
<li>Sexism / misogyny </li>
<li>Sexuality</li>
<li>Slavery</li>
<li>Simplicity / simple living</li>
<li>Social mobility</li>
<li>Social norms / conformity</li>
<li>Socialism</li>
<li>Spirituality</li>
<li>Stranger</li>
<li>Sublime</li>
<li>Succession</li>
<li>Technological determinism</li>
<li>Temptation</li>
<li>Tokenism</li>
<li>Totalitarianism</li>
<li>Tradition</li>
<li>Transitioning</li>
<li>Transphobia / Transmisogyny</li>
<li>Trauma</li>
<li>Treachery / deception</li>
<li>Truth</li>
<li>Tyranny</li>
<li>Urban / rural</li>
<li>Utopia</li>
<li>Vanity</li>
<li>Violence / combat / war</li>
<li>Vulnerability</li>
<li>White supremacy</li>
<li>Whiteness</li>
<li>Wisdom</li>
<li>Wrath / anger</li>
<li>Work / labour</li>
<li>Xenophobia</li>
</ul>
</details>

### 6T. Trope [R][+]

Definition: "A generally recognizable narrative device or [gameplay] convention [appearing in the footage]. Tropes rely on culturally mediated expectations to expedite the development of [gameplay], events, characterization, or narrative. When overused or oversimplified, tropes often come at the expense of fair and inclusive representations of vulnerable identities [see 6U. Stereotypes]" (Lee et al., "VGMS 4.2," 2024)

This element will typically be repeated. Select only significant tropes in cases where five or more options in the controlled vocabulary apply. 

See [TV Tropes](https://tvtropes.org/pmwiki/pmwiki.php/Main/VideoGameTropes) for definitions and examples of most elements in this controlled vocabulary. 

<details>
<summary><i>controlled vocabulary</i> (adapted, with changes and additions, from Lee et al., "Controlled Vocabulary for Tropes," 2024, and TV Tropes 2026)</summary>
<ul>
<li>Ability required to proceed</li>
<li>Acceptable break from reality</li>
<li>Action-based mission</li>
<li>Action commands</li>
<li>Addressing the player</li>
<li>Adventure-friendly world</li>
<li>Alchemic elementals</li>
<li>Animal sidekick</li>
<li>Announcer chatter</li>
<li>Another side, another story</li>
<li>Antepiece for the setpiece</li>
<li>Arbitrary mission restriction</li>
<li>Area of effect</li>
<li>Art shift</li>
<li>Attack its weak point</li>
<li>Back from the brink</li>
<li>Backtracking</li>
<li>Bats won't leave you alone</li>
<li>Battle intro</li>
<li>Battle theme music</li>
<li>Big bad</li>
<li>Big first choice</li>
<li>Blacksmith upgrade service</li>
<li>Blamed for being railroaded</li>
<li>Boss battle</li>
<li>Boss runback</li>
<li>Bottle episode</li>
<li>Bottomless fuel tanks</li>
<li>Breather level</li>
<li>Bright and colourful war</li>
<li>Broken bridge</li>
<li>Brutal bonus level</li>
<li>But thou must! / it's up to you</li>
<li>Calling your shots</li>
<li>Calvinball</li>
<li>Catastrophic countdown</li>
<li>Character-specific dialogue</li>
<li>Character class system / job system</li>
<li>Character customization</li>
<li>Character portrait</li>
<li>Checkpoint starvation</li>
<li>Chess motif</li>
<li>Choices don't matter</li>
<li>Choices matter</li>
<li>Clairvoyant security force</li>
<li>Collision damage</li>
<li>Colour-coded armies or groups</li>
<li>Colour-coded multiplayer</li>
<li>Com mon / common monster</li>
<li>Combat resuscitation</li>
<li>Comeback mechanic</li>
<li>Commander is you</li>
<li>Completion mockery</li>
<li>Computer is lying to me</li>
<li>Computer shall taunt you</li>
<li>Concealed customization</li>
<li>Context-sensitive button</li>
<li>Control room puzzle</li>
<li>Controllable helplessnes</li>
<li>Cooldown</li>
<li>Cooperation versus competition</li>
<li>Corridor cubbyhole run</li>
<li>Coup de grâce cutscene</li>
<li>Cranium ride</li>
<li>Crate expectations / crates everywhere</li>
<li>Critical hit</li>
<li>Critical status buff</li>
<li>Cruelty is the only option</li>
<li>Damage is fire</li>
<li>Dangerous relative / family member</li>
<li>Deadly game of chance</li>
<li>Defeat means playable</li>
<li>Defeating the cheating opponent</li>
<li>Deliberate game crash</li>
<li>Delivery quest</li>
<li>Demonic spiders</li>
<li>Designated victim</li>
<li>Destruction-proof fire exit</li>
<li>Dev is smarter than me</li>
<li>Developer's desired date</li>
<li>Dialogue during gameplay</li>
<li>Diegetic character creation</li>
<li>Diegetic simulation</li>
<li>Difficulty spike</li>
<li>Disembodied dialogue / voice</li>
<li>Drop-in-drop-out multiplayer</li>
<li>Dueling player characters</li>
<li>Dynamic loading</li>
<li>Early game hell</li>
<li>Earn your bad ending</li>
<li>Earn your fun</li>
<li>Earn your happy ending</li>
<li>Easy EXP</li>
<li>Elaborate equals effective</li>
<li>Emergent gameplay</li>
<li>Empty room psych</li>
<li>Empty room until the trap</li>
<li>Enemy-detecting radar</li>
<li>Enemy chatter / enemy barks</li>
<li>Enemy overconfidence</li>
<li>Enjoy the story, skip the game</li>
<li>Enter the solution here</li>
<li>Entrepreneur is you</li>
<li>Escort mission</li>
<li>Essence drop</li>
<li>Event flag</li>
<li>Everything breaks</li>
<li>Everything is smashable</li>
<li>Everything is trying to kill you</li>
<li>Excuse plot</li>
<li>Expository gameplay limitation</li>
<li>Expressive health bar</li>
<li>Extra turn</li>
<li>Fame gate</li>
<li>Fake trap</li>
<li>Fatigue mechanic</li>
<li>Faux symbolism</li>
<li>Fetch quest</li>
<li>First-person ghost</li>
<li>Fog of war</li>
<li>Follow the money</li>
<li>Foreboding architecture / malevolent architecture</li>
<li>Frictionless ice</li>
<li>Frustration simulator</li>
<li>Game-breaking bug</li>
<li>Game lobby</li>
<li>Game of chicken</li>
<li>Game within a game</li>
<li>Gameplay-guided amnesia</li>
<li>Gameplay automation</li>
<li>Gameplay protagonist, story protagonist</li>
<li>Glitch / glitch entity</li>
<li>Good-all-along character</li>
<li>Gravity barrier</li>
<li>Grimy water</li>
<li>Grinding / stat grinding / level grinding</li>
<li>Groundhog day loop</li>
<li>Healing boss</li>
<li>Hide-and-seek horror</li>
<li>Hide your children / no children anywhere</li>
<li>Highly visible landmark</li>
<li>Historical revisionism</li>
<li>Hit flash</li>
<li>Hit points</li>
<li>Hit spark</li>
<li>Hitbox dissonance</li>
<li>Hold the line</li>
<li>Holiday mode</li>
<li>Home field advantage</li>
<li>How we got here</li>
<li>Hyperactive metabolism</li>
<li>Hyperactive sprite</li>
<li>I can't reach it</li>
<li>I fought the law and the law won</li>
<li>Ignorance is the only option</li>
<li>Impassable desert</li>
<li>In-game banking services</li>
<li>In-game novel</li>
<li>In-game tv</li>
<li>In-universe game clock</li>
<li>Inconveniently-placed conveyor belt</li>
<li>Inescapable ambush</li>
<li>Infallible character</li>
<li>Infodump / lore dump</li>
<li>Informing the fourth wall</li>
<li>Instant death</li>
<li>Insurmountable fence</li>
<li>Intercom villainy</li>
<li>Interior designer is you</li>
<li>Intoxication mechanic</li>
<li>Involuntary group split</li>
<li>Kill screen</li>
<li>Kingmaker scenario</li>
<li>Last lousy point</li>
<li>Late character syndrome</li>
<li>Late to the tragedy</li>
<li>Level editor</li>
<li>Level gate</li>
<li>Level scaling</li>
<li>Light and mirrors puzzle</li>
<li>Limited-use magical device</li>
<li>Live-action cutscene</li>
<li>Living statue</li>
<li>Loading screen message gag</li>
<li>Lock and key puzzle</li>
<li>Locked door</li>
<li>Loot boxes</li>
<li>Luck stat</li>
<li>MacGuffin</li>
<li>Magical mystery doors</li>
<li>Magnet hands</li>
<li>Mirror match</li>
<li>Misaimed realism</li>
<li>Misère game</li>
<li>Monsters everywhere</li>
<li>Morale mechanic</li>
<li>Morality pet / morality chain</li>
<li>Multiple game openings</li>
<li>Multiple persuasion modes</li>
<li>Musical gameplay</li>
<li>Musical spoiler</li>
<li>New weapon target range</li>
<li>New world tease</li>
<li>Nice day, deadly night</li>
<li>No campaign for the wicked</li>
<li>No canon for the wicked</li>
<li>No exploration / no sidepaths</li>
<li>No plot? no problem!</li>
<li>No such thing as dehydration / hunger</li>
<li>No such thing as drowning</li>
<li>Notice this / made of shiny</li>
<li>NPC scheduling</li>
<li>Old area, new enemies</li>
<li>One game, one boss</li>
<li>Only one save file</li>
<li>Only smart people may pass</li>
<li>Optional party member</li>
<li>Optional sexual encounter</li>
<li>Overheating</li>
<li>Overly generous time limit</li>
<li>Painting the medium</li>
<li>Pass through the rings</li>
<li>Password save</li>
<li>Path of most resistance</li>
<li>Pawn debut cutscene</li>
<li>Pawn maker</li>
<li>Pawns but no bosses</li>
<li>Pawns go first</li>
<li>Personality mechanic</li>
<li>Philosophical choice ending</li>
<li>Pixel hunt</li>
<li>Play the game, skip the story</li>
<li>Player and protagonist integration</li>
<li>Player death is dramatic</li>
<li>Plot lock</li>
<li>Point of no return</li>
<li>Poison mushroom</li>
<li>Pop quiz</li>
<li>Power-up motif</li>
<li>Power equals rarity</li>
<li>Press X not to die</li>
<li>Pressure plate</li>
<li>Prince or princess in disguise</li>
<li>Protagonist without a past</li>
<li>Purely aesthetic gender</li>
<li>Puzzle pan</li>
<li>Quest giver is you</li>
<li>Racing ghost</li>
<li>Raid</li>
<li>Railroading</li>
<li>Random drop</li>
<li>Random event</li>
<li>Ratchet scrolling</li>
<li>Real-place background</li>
<li>Real-time with pause</li>
<li>Recollection sidequest</li>
<li>Regenerating health</li>
<li>Regenerating mana</li>
<li>Renovating the player headquarters</li>
<li>Repeatable quest</li>
<li>Replay value</li>
<li>Respawn point</li>
<li>Respawning enemies</li>
<li>Rock, paper, scissors</li>
<li>Romance option</li>
<li>Romance sidequest</li>
<li>Rubber-band AI</li>
<li>Running-out-of-time warning</li>
<li>Safe space / bonfire</li>
<li>Saw blades of death</li>
<li>Scavenger hunt</li>
<li>Scenery as you go</li>
<li>Score chasing</li>
<li>Screen shake</li>
<li>Secret AI moves</li>
<li>Secret character</li>
<li>Secret expanded epilogue</li>
<li>Secret final campaign</li>
<li>Secret police</li>
<li>Shall I repeat that?</li>
<li>Shoplift and die</li>
<li>Simon says</li>
<li>Simple rescue mechanic</li>
<li>Smashing survival / struggle sim</li>
<li>Some dexterity required</li>
<li>Songs in the key of panic</li>
<li>Sound-coded for your convenience</li>
<li>Sound of no damage</li>
<li>Space marine is you</li>
<li>Speaking simlish / speaking a conlang</li>
<li>Spikes of doom</li>
<li>Spiteful AI</li>
<li>Springs, springs everywhere!</li>
<li>Static role, exchangeable character</li>
<li>Steam vent obstacle</li>
<li>Step one: escape</li>
<li>Stock puzzle</li>
<li>Story-driven invulnerability</li>
<li>Story branch favoritism</li>
<li>Suddenly-harmful harmless object</li>
<li>Suspiciously cracked wall</li>
<li>Tactical door use</li>
<li>Tank controls</li>
<li>Taste of power</li>
<li>Taunt button</li>
<li>Temporary platform</li>
<li>Ten-second flashlight</li>
<li>That one achievement</li>
<li>That one boss</li>
<li>That one level</li>
<li>That one puzzle</li>
<li>That one sidequest</li>
<li>There are no tents, only inns</li>
<li>This is the final battle</li>
<li>Three-approach system</li>
<li>Three trials / three goals</li>
<li>Threshold guardian</li>
<li>Tiebreak round</li>
<li>Time trial</li>
<li>Timed mission</li>
<li>Title theme drop</li>
<li>Training dummy</li>
<li>Training stage</li>
<li>Treacherous checkpoint</li>
<li>Trick shot</li>
<li>Tutorial failure</li>
<li>Unbroken first-person perspective</li>
<li>Unexpected shmup level</li>
<li>Unexpectedly realistic gameplay</li>
<li>Unending end card </li>
<li>Unlosable</li>
<li>Unpopular mechanic / scrappy mechanic</li>
<li>Unreliable narrator</li>
<li>Unwinnable by design</li>
<li>Useless item / joke item</li>
<li>Variable player goals</li>
<li>Victory pose / victory quote</li>
<li>Video game cruelty punishment</li>
<li>Video game geography</li>
<li>Video game physics</li>
<li>Video game vista</li>
<li>Villain shoes</li>
<li>Violation of common sense</li>
<li>Visible silence</li>
<li>Voice grunting</li>
<li>Wait around for a while</li>
<li>Wandering you</li>
<li>War sequence</li>
<li>Warp zone</li>
<li>We cannot go on without you</li>
<li>Weather effects / weather gameplay mechanic</li>
<li>Whack-a-monster</li>
<li>What the hell, player?</li>
<li>When all else fails, go right</li>
<li>Who forgot the lights?</li>
<li>Winner is you</li>
<li>Wrap around</li>
<li>You will not evade me</li>
<li>Zip mode</li>
</ul>
</details>

### 6U. Stereotype [R][+]

Definition: 

controlled vocabulary

### 6V. Assets [R][+]

Definition: audio, visual, and functional elements, including individual pieces of content, appearing in the gameplay footage

This element will typically be repeated. Select only significant assets in cases where five or more options in the controlled vocabulary apply. 

<details>
<summary><i>controlled vocabulary</i> (informed by game assets available at itch.io)</summary>
<ul>
<li>3D models</li>
<li>Action animation</li>
<li>Adaptive lighting</li>
<li>Adaptive music</li>
<li>Ambient sound / soundscape</li>
<li>Articulated animation</li>
<li>Character art</li>
<li>Destructible objects</li>
<li>Environment art / scenery</li>
<li>Exteriors</li>
<li>Flavour text</li>
<li>Fluid dynamics</li>
<li>Foley sound</li>
<li>Foliage / terrain</li>
<li>Fonts / typography</li>
<li>Free-form animation</li>
<li>Gauges</li>
<li>Haptics</li>
<li>Icons / buttons</li>
<li>Idle animation</li>
<li>Interiors</li>
<li>Items / clothes / equipment</li>
<li>Level art</li>
<li>Licensed music</li>
<li>Locomotion animation</li>
<li>Motion capture / mocap</li>
<li>No audio</li>
<li>No visuals</li>
<li>Original soundtrack</li>
<li>Parallax scrolling </li>
<li>Particle effects</li>
<li>Photographs</li>
<li>Pre-recorded audio</li>
<li>Pre-recorded video</li>
<li>Previews</li>
<li>Props</li>
<li>Ragdoll physics</li>
<li>Ray tracing</li>
<li>Rigid animation</li>
<li>Rigid body dynamics</li>
<li>Shaders</li>
<li>Skyboxes</li>
<li>Soft body dynamics</li>
<li>Sound effects / SFX</li>
<li>Sprites</li>
<li>Text boxes</li>
<li>Textures</li>
<li>Tilesets</li>
<li>Vector graphics</li>
<li>Visual art / drawings</li>
<li>Visual effects / VFX</li>
<li>Voice acting / barks</li>
<li>Voice-over / VO </li>
</ul>
</details>

### 6W. Style [R][+]

controlled vocabulary 

photorealism; social realism; surrealism; magical realism; epic; experimental; adaptation / homage; mashup; cel shading; 
Abstract art
Anime
Cartoon
Cel-shaded 3D
Flat
Stylized 3D
Surrealism
Saturated colours
Realistic 3D
High fidelity
Hand-drawn / hand-painted
Low fidelity
Low-poly 3D
Manga
Maximalism
Minimalism
Monochrome
Motion graphics
Pixel art (8-bit / 16-bit) 
Voxel art
Cutout
ASCII art
Chiptune / 8-bit music
Stop motion

### 6X. Interface [R][+]

controlled vocabulary 

playable menu, game over

### 6Y. Experience [R][+]

controlled vocabulary

monsters everywhere, Better as a Let's Play

### 6Z. Transaction [R][+]

controlled vocabulary 

ad reward, 30-day free trial, microtransactions 

### 6AA. Metagaming [R][+]

controlled vocabulary

soft reset, not the intended use, house rules, cheat code, sequence breaking, script breaking, cheese strategy, save scumming, self-imposed challenge

### 6BB. Content Warning [R]

text input field 

### 6CC. Gameplay Footage Note

text input field 

## 7. Gameplay Instruction Entity 

### 7A. Game Studies Topic [R][+]

controlled vocabulary 

liminal spaces, ludonarrative dissonance / resonance, player-centric, player-agnostic, player-antagonistic

### 7B. Gameplay Instruction Note 

text input field
