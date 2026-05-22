This is a [Press Record](https://uvicpraxis.github.io/pressrecord.html) project file. Jentery Sayers created it on 19 May 2026 and last updated it on 22 May 2026 with feedback from the [Praxis Studio for Comparative Media Studies](https://uvicpraxis.github.io/) and the [Humanities Computing and Media Centre](https://www.uvic.ca/humanities/hcmc/index.php) at the University of Victoria. It is an incomplete draft and thus subject to change. We will version it 1.0 once it is ready for circulation. *Please do not cite this document* in the meantime.  

# Gameplay Metadata Schema (GPMS) (INCOMPLETE DRAFT)

This metadata schema is licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). It was developed by Jentery Sayers and the Praxis Studio for Comparative Media Studies at the University of Victoria. It adapts the following projects for the purposes of describing video files in the [Press Record](https://uvicpraxis.github.io/pressrecord.html) Gameplay Footage Collection (GPFC), which is scheduled for early-access release in 2026-27: 

* Coates, E. (2025). GameUI Database. [https://www.gameuidatabase.com/about.php](https://www.gameuidatabase.com/about.php)
* International Council of Museums (ICOM)'s International Committee for Documentation (CIDOC) (2011). Conceptual Reference Model (CRM). [http://www.cidoc-crm.org/index.html](http://www.cidoc-crm.org/index.html)
* International Federation of Library Associations and Institutions (IFLA) (2009). Functional Requirements for Bibliographic Records (FRBR). [https://www.ifla.org/wp-content/uploads/2019/05/assets/cataloguing/frbr/frbr.pdf](https://www.ifla.org/wp-content/uploads/2019/05/assets/cataloguing/frbr/frbr.pdf)
* Lee, J. H., Schmalz, M., Newman, M., & Koughan, L. (2024). UW/SIMM Video Game Metadata Schema. Version 4.2. [https://github.com/uwgamergroup/video-game-metadata-schema](https://github.com/uwgamergroup/video-game-metadata-schema)
* Poff, T. & Atari (2025). MobyGames Standards. [https://www.mobygames.com/info/standards/](https://www.mobygames.com/info/standards/)
* Wikipedia (2025). List of Game Engines. [https://en.wikipedia.org/wiki/List_of_game_engines](https://en.wikipedia.org/wiki/List_of_game_engines)

See citations below for specific instances of adaptation. 

Notes:

* Elements marked with [R] are required.
* Elements marked with [+] are repeatable.
* "GPFC" refers to the Press Record Gameplay Footage Collection. 

Table of Contents: 

1. [Platform Edition Entity](#1-platform-edition-entity)
2. [Gameplay File Entity](#2-gameplay-file-entity)
3. [Gameplay Settings Entity](#3-gameplay-settings-entity)
4. [Gameplay Footage Entity](#4-gameplay-footage-entity)
5. [Gameplay Instruction Entity](#5-gameplay-instruction-entity)

## 1. Platform Edition Entity

Definition: "Denotes a particular instantiation of a video game. An edition may be a particular release of a game that is in some way different than another release of the same game" (Lee et al. 2024).

The platform edition played for the GPFC may or may not correspond with the game's initial release. For instance, *Journey* was initially released on PlayStation 3 in 2012. That release was the game's first platform edition. Other platform editions of *Journey* include iPad (2019), iPhone (2019), PlayStation 4 (2015), and Windows (2019). These four platform editions (later releases) are ports of the 2012 platform edition (the initial release). 

*The following aspects of the Platform Edition Entity should describe the platform edition of the game played and recorded for the GPFC.*

* [Game Title](#1a-game-title) (text input field)
* [Release Year](#1b-release-year) (text input field)
* [Release Type](#1c-release-type) (controlled vocabulary)
* [Platform](#1d-platform) (controlled vocabulary)
* [Engine](#1e-engine) (controlled vocabulary)
* [Developer](#1f-developer) (text input field)
* [Developer's Location](#1g-developers-location) (controlled vocabulary)
* [Publisher](#1h-publisher) (text input field)
* [Publisher Class](#1i-publisher-class) (controlled vocabulary)
* [Edition Note](#1j-edition-note) (text input field)

### 1A. Game Title

Definition: The proper name used to refer to the platform edition as assigned by its developer and/or publisher (Lee et al. 2024; CIDOC 2011)

Provide the complete game title. Avoid using an alternative, abbreviated, or colloquial title. 

*text input field* [R]

### 1B. Release Year

Definition: The year the platform edition was publicly/commercially released (Lee et al. 2024) 

The edition's release year may differ from the game's initial release year. 

*text input field; format: YYYY* [R]

### 1C. Release Type

Definition: The platform edition's release type as, where applicable, assigned by its developer, publisher, and/or distributor

<details>
<summary><i>controlled vocabulary</i> [R][+]</summary>
<ul>
<li>Alpha</li>
<li>Beta</li>
<li>Demo</li>
<li>Downloadable content (DLC)</li>
<li>Early access</li>
<li>Emulation</li>
<li>Fan game</li>
<li>Initial release</li>
<li>Patch</li>
<li>Port</li>
<li>Reboot</li>
<li>Remake</li>
<li>Remaster</li>
<li>Unfinished</li>
</ul>
</details>

### 1D. Platform
Definition: The operating system, device, computer, console, and/or service on which the platform edition was played and recorded (Lee et al. 2024)

<details>
<summary><i>controlled vocabulary</i> (adapted from Poff and Atari 2025) [R][+]</summary>
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

### 1E. Engine 

Definition: The software framework and/or development environment used to design the platform edition

<details>
<summary><i>controlled vocabulary</i> (adapted from Wikipedia 2025) [+]</summary>
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

### 1F. Developer 

Definition: "An individual, organization, or group of individuals or organizations responsible for [the] creation, realization, [and/or] manufacture" of the platform edition (Lee et al. 2024; IFLA 2009)

*text input field* [R][+]

### 1G. Developer's Location

Definition: The geographic location of the platform edition's developer(s)

<details>
<summary><i>controlled vocabulary</i> [R][+]</summary>
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

### 1H. Publisher 

Definition: "An individual, organization, or group of individuals or organizations responsible for . . . [the] manufacture, marketing, and/or distribution" of the platform edition (Lee et al. 2024; IFLA 2009)

Both publishers and distributors may be included in this field. 

*text input field* [R][+]

### 1I. Publisher Class 

Definition: A term used to describe the size, profile, and/or budget of the publisher and, in some cases, the developer, too
<details>
<summary><i>controlled vocabulary</i> [R][+]</summary>
<ul>
<li>AAA</li>
<li>AA</li>
<li>B</li>
<li>III</li>
<li>Indie</li>
<li>Self-published</li>
</ul>
</details>

### 1J. Edition Note 

Definition: "Any other notable characteristics of the platform edition" that are "not captured in other fields" of this metadata schema (Lee et al. 2024)

*text input field*

## 2. Gameplay File Entity 

Definition: Denotes a video file containing gameplay footage of a video game; also called "game capture" and "game recording"

For the fair-dealing purposes of the GPFC, the video file will typically be a "clip" that is 30 seconds to five minutes long.

*The following aspects of the Gameplay File Entity should describe the gameplay video file intended for the GPFC.*

* [Clip Title](#2a-clip-title) (text input field)
* [Clip Length](#2b-clip-length) (text input field) 
* [Date Recorded](#2c-date-recorded) (text input field) 
* [Commentary](#2d-commentary) (controlled vocabulary)
* [Chat](#2e-chat) (controlled vocabulary)
* [Gameplay Attribution](#2f-gameplay-attribution) (text input field)
* [Metadata Attribution](#2g-metadata-attribution) (text input field) 
* [ID](#2h-id) (text input field) 
* [Filename](#2i-filename) (text input field) 
* [Gameplay File Note](#2j-gameplay-file-note) (text input field)

### 2A. Clip Title

Definition: A public-facing, search-friendly description of the gameplay footage as assigned by the person who played the game while the video was recorded

Provide a title that helps viewers anticipate what they will see, hear, read, and watch. Describe the content of the clip and the actions occurring in it. An example is, "Starting a New Game: Naming the Player Character, Encountering Emus and Hobgoblins, and Collecting Darts, Scrolls, and Potions on Level 1."

*text input field* [R]

### 2B. Clip Length

Definition: The length of the video in minutes and seconds 

*text input field; format: MM:SS* [R]

### 2C. Date Recorded

Definition: The date the video was recorded

This date is presumably identical to the video file's "created" date.  

*text input field; format: YYYY-MM-DD* [R]

### 2D. Commentary

Definition: The type of player commentary, if any, included in the footage

Commentary is reflective, and it typically addresses the video's audience. 

Select "No commentary" if the footage contains no commentary. 

<details>
<summary><i>controlled vocabulary</i> [R][+]</summary>
<ul>
<li>Avatar / VTubing</li>
<li>Captions / subtitles</li>
<li>Emotes</li>
<li>Face cam / facecam</li>
<li>No commentary</li>
<li>Voice over / voice-over / voiceover (VO)</li>
</ul>
</details>

### 2E. Chat

Definition: The type of chat, if any, included in the footage

Chat typically occurs between players; however, in cases such as livestreams, it may also occur between players and audiences. 

Select "No chat" if the footage contains no chat.

<details>
<summary><i>controlled vocabulary</i> [R][+]</summary>
<ul>
<li>Emotes</li>
<li>No chat</li>
<li>Text chat</li>
<li>Video chat</li>
<li>Voice chat</li>
</ul>
</details>

### 2F. Gameplay Attribution 

Definition: The chosen or preferred name of the person who played the game while the video was recorded

Multiple names may be included. Full names are optional. 

*text input field* [R][+]

### 2G. Metadata Attribution

Definition: The chosen or preferred name of the person who described the gameplay and entered the metadata

Multiple names may be included. Full names are optional. 

*text input field* [R][+]

### 2H. ID 

Definition: The internal reference number for the file and its metadata 

This number is used by the Press Record team to identify files in the GPFC. It is a five-character numeric string. 

*text input field; format: #####* [R]

### 2I. Filename

Definition: The filename of the video file 

Use camelCasing to include the following information in the following order: gameTitlePlatformEditionReleaseYearClipTitleID. An example is rogue1985StartingANewGame00011.mp4. Abbreviate the clip's title to avoid long filenames. 

*text input field; format: gameTitlePlatformEditionReleaseYearClipTitleID.extension* [R]

### 2J. Gameplay File Note

Definition: "Any other notable characteristics of the" gameplay file that are "not captured in other fields" of this metadata schema (Lee et al. 2024)

*text input field*

## 3. Gameplay Settings Entity 

Description coming soon. 

* [Input Device](#3a-input-device) (controlled vocabulary)
* [Networked Feature](#3b-networked-feature) (controlled vocabulary) 
* [Number of Players](#3c-number-of-players) (controlled vocabulary) 
* [Type of Play](#3d-type-of-play) (controlled vocabulary) 
* [Mode of Play](#3e-mode-of-play) (controlled vocabulary) 
* [Language](#3f-language) (text input field) 
* [Accessibility](#3g-accessibility) (controlled vocabulary) 
* [Technical](#3h-technical) (controlled vocabulary) 
* [Mods](#3i-mods) (text input field) 
* [Settings Note](#3j-settings-note) 

### 3A. Input Device

controlled vocabulary [R][+]

### 3B. Networked Feature

controlled vocabulary [R][+]

### 3C. Number of Players 

controlled vocabulary [R][+]

### 3D. Type of Play

controlled vocabulary [R][+]

### 3E. Mode of Play

controlled vocabulary [R][+]

### 3F. Language 

text input field [R][+]

### 3G. Accessibility

controlled vocabulary [R][+]

### 3H. Technical

controlled vocabulary [R][+]

### 3I. Mods

text input field [R][+]

### 3J. Settings Note

text input field 

## 4. Gameplay Footage Entity

Description coming soon. 

### Gameplay Genre

controlled vocabulary [R][+]

### Narrative Genre 

controlled vocabulary [R][+]

### Dimension 

controlled vocabulary [R][+]

### World

controlled vocabulary [R][+]

### Place

controlled vocabulary [R][+]

### Time Period

controlled vocabulary [R][+]

### Atmosphere

controlled vocabulary [R][+]

### Perspective

controlled vocabulary [R][+]

### Player Characters

controlled vocabulary [R][+]

### Non-Player Characters

controlled vocabulary [R][+]

### Hostile Characters

controlled vocabulary [R][+]

### Objects

controlled vocabulary [+]

### Mechanics 

controlled vocabulary [R][+]

### Activity

controlled vocabulary [R][+]

### Pacing

controlled vocabulary [R][+]

### Progression 

controlled vocabulary [R][+]

### Theme

controlled vocabulary [R][+]

### Tropes

controlled vocabulary [R][+]

### Art 

controlled vocabulary [R][+]

### Style 

controlled vocabulary [R][+]

### Interfaces

controlled vocabulary [R][+]

### Experience

controlled vocabulary [R][+]

### Transactions 

controlled vocabulary [R][+]

### Metagaming 

controlled vocabulary [R][+]

### Gameplay Footage Note

text input field 

## 5. Gameplay Instruction Entity 

### Pertinent Topics

controlled vocabulary [R][+]

### Instruction Note 

text input field
