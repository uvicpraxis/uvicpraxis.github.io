This is a [Press Record](https://uvicpraxis.github.io/pressrecord.html) project file. Jentery Sayers created it on 19 May 2026 and updated it on 21 May 2026 with feedback from the Praxis Studio and Humanities Computing and Media Centre at the University of Victoria. It is an incomplete draft and thus subject to change. We will version it 1.0 once it is ready for circulation. **Please do not cite this document** in the meantime.  

# Gameplay Metadata Schema (GPMS) (INCOMPLETE DRAFT)

This metadata schema is licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). It was developed by Jentery Sayers and the Praxis Studio for Comparative Media Studies at the University of Victoria. It adapts the following projects for the purposes of describing files in the Press Record Gameplay Footage Collection: 

* Coates, E. (2025). GameUI Database. [https://www.gameuidatabase.com/about.php](https://www.gameuidatabase.com/about.php)
* International Council of Museums (ICOM)'s International Committee for Documentation (CIDOC) (2011). Conceptual Reference Model (CRM). [http://www.cidoc-crm.org/index.html](http://www.cidoc-crm.org/index.html)
* International Federation of Library Associations and Institutions (IFLA) (2009). Functional Requirements for Bibliographic Records (FRBR). [https://www.ifla.org/wp-content/uploads/2019/05/assets/cataloguing/frbr/frbr.pdf](https://www.ifla.org/wp-content/uploads/2019/05/assets/cataloguing/frbr/frbr.pdf)
* Lee, J. H., Schmalz, M., Newman, M., & Koughan, L. (2024). UW/SIMM Video Game Metadata Schema. Version 4.2. [https://github.com/uwgamergroup/video-game-metadata-schema](https://github.com/uwgamergroup/video-game-metadata-schema)
* Poff, T. & Atari (2025). MobyGames Standards. [https://www.mobygames.com/info/standards/](https://www.mobygames.com/info/standards/)
* Wikipedia (2025). List of Game Engines. [https://en.wikipedia.org/wiki/List_of_game_engines](https://en.wikipedia.org/wiki/List_of_game_engines)

See citations below for specific instances of adaptation. 

"PRGFC" refers to the Press Record Gameplay Footage Collection. 

Elements marked with [R] are required.
Elements marked with [+] are repeatable.

* [Platform Edition Entity](#platform-edition-entity)
* [Gameplay File Entity](#gameplay-file-entity)
* [Gameplay Settings Entity](#gameplay-settings-entity)
* [Gameplay Footage Entity](#gameplay-footage-entity)
* [Gameplay Instruction Entity](#gameplay-instruction-entity) 

## Platform Edition Entity

Definition: "Denotes a particular instantiation of a video game. An edition may be a particular release of a game that is in some way different than another release of the same game" (Lee et al. 2024).

*The following aspects of the Platform Edition Entity should describe the platform edition of the game played and recorded for the PRGFC.*

* [Game Title](#game-title)
* [Release Year](#release-year)
* [Release Type](#release-type)
* [Platform](#platform)
* [Engine](#engine)
* [Developer](#developer)
* [Developer's Location](#developers-location)
* [Publisher](#publisher)
* [Publisher Class](#publisher-class)
* [Edition Note](#edition-note)

### Game Title

Definition: The proper name used to refer to the platform edition as assigned by its developer and/or publisher (Lee et al. 2024; CIDOC 2011).

Provide the complete game title. Avoid using an alternative, abbreviated, or colloquial title. 

text input field [R]

### Release Year

Definition: The year the platform edition was publicly/commercially released (Lee et al. 2024). 

The edition's release year may differ from the game's initial release year. 

text input field; format: YYYY [R]

### Release Type

Definition: The platform edition's release type as assigned by its developer and/or publisher. 

controlled vocabulary [R][+]

* Alpha
* Beta
* Demo
* Downloadable content (DLC)
* Early access
* Emulation
* Fan game
* Initial release
* Patch
* Port
* Reboot
* Remake
* Remaster
* Unfinished

### Platform

Definition: The operating system, device, computer, console, and/or service on which the platform edition was played and recorded (Lee et al. 2024).

controlled vocabulary (adapted from Poff and Atari 2025) [R][+]

* 1291 Advanced Programmable Video System
* 3DO
* ABC 80
* Acorn 32-bit
* Adventure Vision
* AirConsole
* Alice 32/90
* Altair 680
* Altair 8800
* Amazon Alexa
* Amiga
* Amiga CD32
* Amstrad CPC
* Amstrad PCW
* Android
* Anstream
* APF MP1000 / Imagination Machine
* Apple I
* Apple II
* Apple IIgs
* Arcade
* Arcadia 2001
* Arduboy
* Astral 2000
* Atari 2600
* Atari 5200
* Atari 7800
* Atari 8-bit
* Atari ST
* Atari VCS
* Atom
* Auto Response Board
* bada
* Bally Astrocade
* Bandai RX-78 Gundam
* BBC Micro
* BeOS
* BlackBerry
* Blacknut
* Blu-ray disc player
* BREW
* Browser
* Bubble
* Camputers Lynx
* Casio FP-1000 / 1100
* Casio Loopy
* Casio Programmable Calculator
* Casio PV-1000
* CD-i
* CDTV
* Champion 2711
* Channel F
* ClickStart
* Coleco Adam
* ColecoVision
* Colour Genie
* Commodore 128
* Commodore 16, Plus/4
* Commodore 64
* Commodore PET/CBM
* Compal 80
* Compucolor I
* Compucolor II
* Compucorp Programmable Calculator
* COSMAC
* CP/M
* CreatiVision
* Cybervision
* DAI
* Danger OS
* Dedicated console
* Dedicated handheld
* Didj
* digiBlast
* DoJa
* DOS
* Dragon 32/64
* Dreamcast
* DVD Player
* ECD Micromind
* Electron
* Enterprise
* Epoch Cassette Vision
* Epoch Game Pocket Computer
* Epoch Super Cassette Vision
* Evercade
* Excelvision
* ExEn
* Exidy Sorcerer
* Feature phone
* Fire OS
* FM Towns
* FM-7
* Freebox
* FreeBSD
* G-cluster
* Galaksija
* Game Boy
* Game Boy Advance
* Game Boy Color
* Game Gear
* Game Wave
* Game.com
* GameCube
* GameStick
* Genesis
* GIMINI
* Gizmondo
* Gloud
* Glulx
* GNEX
* GP2X
* GP2X Wix
* GP32
* GVM
* HD DVD player
* Heath/Zenith H8/H89
* Heathkit H11
* Hitachi Basic Master
* Hitachi Basic Master Level 3
* Hitachi H68/TR
* Hitachi SI
* HP 9800
* HP Oscilloscope
* HP Programmable Calculator
* HP Series 80
* Hugo
* HyperScan
* IBM 5100
* Ideal-Computer
* iiRcade
* Intel 8008
* Intel 8080
* Intel 8086 / 8088
* Intellivision
* Interact Model One
* Interton Video 2000
* iPad
* iPhone
* iPod Classic
* J2ME
* Jaguar
* Jolt
* Jupiter Ace
* KaiOS
* KIM-1
* Kindle Classic
* Laser 200
* LaserActive
* LeapFrog Explorer
* Leapster
* LeapTV
* Linux
* Lkit-16
* Luna
* Lynx
* Macintosh
* macOS
* Maemo
* Magic Leap
* Mainframe
* Marvel 2000
* Matsushita / Panasonic JR
* Mattel Aquarius
* MeeGo
* Memotech MTX
* Meritum
* Microbee
* Microtan 65
* Microvision
* Mitsubishi Multi-8
* Modular Game System
* Mophun
* MOS Technology 6502
* Motorola 6800
* Motorola 68k
* MRE
* MSX
* N-Gage
* N-Gage (service)
* Nascom
* NEC TK-80
* Neo Geo
* Neo Geo CD
* Neo Geo Pocket
* Neo Geo Pocket Color
* Neo Geo X
* NES
* NetBSD
* New Nintendo 3DS
* NewBrain
* Newton
* Nintendo 3DS
* Nintendo 64
* Nintendo DS
* Nintendo DSi
* Nintendo Switch
* Nintendo Switch 2
* North Star
* Noval 760
* Nuon
* Oculus Go
* Odyssey
* Odyssey 2
* Ohio Scientific
* OnLive
* OOParts
* OpenBSD
* Orao
* Oric
* OS/2
* Ouya
* Palm OS
* Pandora
* PC Booter
* PC-6001
* PC-8000
* PC-88
* PC-98
* PC-FX
* Pebble
* Philips P200
* Philips VG 5000
* Photo CD
* PICO
* Pippin
* Playdate
* Playdia
* PlayStation
* PlayStation 2
* PlayStation 3
* PlayStation 4
* PlayStation 5
* PlayStation Now
* Plex Arcade
* Pokitto
* Pokémon Mini
* Poly-88
* PS Vita
* PSP
* Quest
* RCA Studio II
* Research Machines 380Z
* Roblox
* Roku
* SAM Coupé
* SC/MP
* SD-200 / 270 / 290
* SEGA 32X
* SEGA CD
* SEGA Master System
* SEGA Pico
* SEGA Saturn
* SG-1000
* Sharp MZ-80B / 2000 / 2500
* Sharp MZ-80K / 700 / 800 / 1500
* Sharp X1
* Sharp X68000
* Sharp Zaurus
* Signetics 2650
* Sinclair QL
* SK-VM
* SMC-777
* SNES
* Socrates
* Sol-20
* Solaris
* Sord M5
* SPC-1000
* Spectravideo
* SRI-500 / 1000
* Stadia
* Steam
* Steam Deck
* Super A'can
* Super Vision 8000
* SuperGrafx
* Supervision
* Sure Shot HD
* SWTPC 6800
* Symbian
* TADS
* Taito X-55
* Tatung Einstein
* Tektronix 4050
* Tele-Spiel ES-2201
* Telstar Arcade
* TempleOS
* Terminal
* Thomson MO
* Thomson TO
* TI Programmable Calculator
* TI-99 / 4A
* TIC-80
* Tiki 100
* TIM
* Timex Sinclair 2068
* Tizen
* Tomahawk F1
* Tomy Tutor
* Toshiba Ex-80
* Toshiba Pasopia
* Triton
* TRS-80
* TRS-80 CoCo
* TRS-80 MC-10
* TRS-80 Model 100
* TurboGrafx CD
* TurboGrafx-16
* tvOS
* V.Flash
* V.Smile
* Vectrex
* Versatile
* VIC-20
* VideoBrain
* Videopac+ G7400
* Virtual Boy
* VIS
* visionOS
* Wang 2200
* watchOS
* webOS
* Wii
* Wii U
* Windows
* Windows 16-bit
* Windows Apps
* Windows Mobile
* Windows Phone
* WIPI
* WonderSwan
* WonderSwan Color
* XaviXPORT
* Xbox
* Xbox 360
* Xbox Cloud Gaming
* Xbox One
* Xbox Series
* Xerox Alto
* Z-machine
* Zeebo
* Zilog Z80
* Zilog Z8000
* Zillions of Games
* Zodiac
* Zune
* ZX Spectrum
* ZX Spectrum Next
* ZX80
* ZX81

### Engine 

Definition: The software framework and/or development environment used to design the platform edition.

controlled vocabulary (adapted from Wikipedia 2025) [+]

* 4A Engine
* A-FRAME (VR)
* Adventure Game Interpreter
* Adventure Game Studio
* Aleph One
* Amazon Lumberyard
* Anvil
* AppGameKit
* Ardor3D
* Aurora toolset
* Babylon.js
* bitsy
* Blend4Web
* Blender
* Build Engine
* Buildbox
* C4 Engine
* Chrome Engine
* ClanLib
* Clausewitz
* Clickteam Fusion
* Cobra Engine
* Cocos2d / 2d-x / 2d-html5
* Codea
* Construct
* Coretech
* CraftStudio
* Creation Engine
* CryEngine
* Crystal Space
* Crystal Tools
* Cube Engine
* Cube 2 Engine
* Custom-built engine
* Dagor Engine
* Dark Engine
* Decima
* Defold
* Delta3D
* Dim3
* DimensioneX Multiplayer Engine
* Divinity Engine
* Dunia Engine
* DX Studio
* EGO
* Electron toolset
* Enforce
* Enigma Engine
* Essence Engine
* Exult
* Flame
* Flare3D
* Flash (Adobe)
* Flixel
* ForgeLight
* Fox Engine
* Freescape
* Freespace 2
* Frostbite
* Future Pinball
* Gamebryo
* GameMaker
* GameSalad
* Gamestudio
* GDevelop
* Genie Engine
* Godot
* Gold Box
* GoldSrc
* Havok
* HeroEngine
* Horde3D
* HPL Engine
* id Tech
* iMUSE
* Infinity Engine
* ioquake3
* Iron Engine
* Irrlicht
* IW Engine
* Jade
* Jake2
* Java 3D
* Jedi
* jMonkeyEngine
* Kinectica
* Kivy (framework)
* LayaAir
* Leadwerks
* LibGDX
* LithTech
* LÖVE
* Luminous Engine
* LyN
* M.U.G.E.N.
* Marmalade
* Messiah
* Moai SDK
* Monkey X
* MonoGame / XNA
* MT Framework
* Northlight
* NScripter
* O3DE
* Odyssey Engine
* OGRE
* OHRRPGCE
* ONScripter
* OpenClonk
* OpenMW
* OpenSimulator
* ORX
* Panda3D
* Panta Rhei
* Phaser
* PhyreEngine
* PICO-8
* Pie in the Sky
* Pixel Game Maker MV
* PlayCanvas
* PlayN
* Pulp
* Pygame
* Pyrogenesis
* Q
* Qfusion
* REDengine
* Ren'Py
* RenderWare
* Roblox
* Rockstar Advanced Game Engine
* RPG Maker
* S&box
* SAGE
* Scratch
* SCUMM
* Serious Engine
* Shark 3D
* Silent Storm Engine
* Snowdrop
* Solar2D
* Solaris
* Source
* Source 2
* Starling Framework
* Stencyl
* StepMania
* Stingray (Autodesk)
* Stratagus
* Stride
* Telltale Tool
* Three.js
* Torque3D
* TOSHI
* Treyarch NGL
* Turbulenz
* Twine
* UbiArt Framework
* Unigine
* Unity
* Unreal Engine
* V-Play
* Vengeance Engine
* Vicarious Visions Alchemy
* Virtools
* Vision
* Visual3D Game Engine
* Visual Pinball
* VRAGE
* Wintermute Engine
* Wolf RPG Editor
* World Builder
* WorldForge
* XnGine
* Zero

### Developer 

Definition: "An individual, organization, or group of individuals or organizations responsible for [the] creation, realization, [and/or] manufacture" of the platform edition (Lee et al. 2024; IFLA 2009)

text input field [R][+]

### Developer's Location

Definition: The geographic location of the platform edition's developer(s)

<details>

<summary>

#### controlled vocabulary for Developer's Location [R][+]

</summary>

* Afghanistan
* Albania
* Algeria
* Andorra
* Angola
* Antigua and Barbuda
* Argentina
* Armenia
* Australia
* Austria
* Azerbaijan
* Bahamas
* Bahrain
* Bangladesh
* Barbados
* Belarus
* Belgium
* Belize
* Benin
* Bermuda 
* Bhutan
* Bolivia
* Bosnia and Herzegovina
* Botswana
* Brazil
* Brunei
* Bulgaria
* Burkina Faso
* Burundi
* Cambodia
* Cameroon
* Canada
* Canada / Alberta
* Canada / British Columbia
* Canada / Manitoba
* Canada / New Brunswick
* Canada / Newfoundland and Labrador
* Canada / Northwest Territories 
* Canada / Nova Scotia 
* Canada / Nunavut
* Canada / Ontario 
* Canada / Prince Edward Island 
* Canada / Quebec
* Canada / Saskatchewan
* Canada / Yukon
* Cape Verde
* Central African Republic
* Chad
* Chile
* China
* Colombia
* Comoros
* Congo, Republic of the
* Congo, Democratic Republic of the
* Costa Rica
* Croatia
* Cuba
* Curacao
* Cyprus
* Czech Republic
* Denmark
* Djibouti
* Dominica
* Dominican Republic
* East Timor
* Ecuador
* Egypt
* El Salvador
* Equatorial Guinea
* Eritrea
* Estonia
* Eswatini
* Ethiopia
* Fiji
* Finland
* France
* Gabon
* Gambia
* Georgia
* Germany
* Ghana
* Greece
* Grenada
* Guatemala
* Guinea
* Guinea-Bissau
* Guyana
* Haiti
* Honduras
* Hungary
* Iceland
* India
* Indonesia
* Iran
* Iraq
* Ireland
* Israel
* Italy
* Ivory Coast
* Jamaica
* Japan
* Jordan
* Kazakhstan
* Kenya
* Kiribati
* Kosovo
* Kuwait
* Kyrgyzstan
* Laos
* Latvia
* Lebanon
* Lesotho
* Liberia
* Libya
* Liechtenstein
* Lithuania
* Luxembourg
* Madagascar
* Malawi
* Malaysia
* Maldives
* Mali
* Malta
* Marshall Islands
* Mauritania
* Mauritius
* Mexico
* Micronesia
* Moldova
* Monaco
* Mongolia
* Montenegro
* Morocco
* Mozambique
* Myanmar
* Namibia
* Nauru
* Nepal
* Netherlands
* New Zealand
* Nicaragua
* Niger
* Nigeria
* North Korea
* North Macedonia
* Norway
* Oman
* Pakistan
* Palau
* Palestine
* Panama
* Papua New Guinea
* Paraguay
* Peru
* Philippines
* Poland
* Portugal
* Puerto Rico
* Qatar
* Romania
* Russia
* Rwanda
* Saint Kitts and Nevis
* Saint Lucia
* Saint Vincent and the Grenadines
* Samoa
* San Marino
* São Tomé and Príncipe
* Saudi Arabia
* Senegal
* Serbia
* Seychelles
* Sierra Leone
* Singapore
* Slovakia
* Slovenia
* Solomon Islands
* Somalia
* South Africa
* South Korea
* South Sudan
* Spain
* Sri Lanka
* Sudan
* Suriname
* Sweden
* Switzerland
* Syria
* Taiwan
* Tajikistan
* Tanzania
* Thailand
* Togo
* Tonga
* Trinidad and Tobago
* Tunisia
* Turkey
* Turkmenistan
* Tuvalu
* Uganda
* Ukraine
* United Arab Emirates
* United Kingdom
* United States
* Uruguay
* Uzbekistan
* Vanuatu
* Vatican City
* Venezuela
* Vietnam
* Yemen
* Zambia
* Zimbabwe
</details>

### Publisher 

Definition: "An individual, organization, or group of individuals or organizations responsible for . . . [the] manufacture, marketing, and/or distribution" of the platform edition (Lee et al. 2024; IFLA 2009)

text input field [R][+]

### Publisher Class 

Defintion: A term used to describe the size, profile, and/or budget of the publisher and, in some cases, the developer, too

controlled vocabulary [R][+]

* AAA
* AA 
* B
* Indie
* Self-published 

### Edition Note 

Definition: "Any other notable characteristics of the platform edition" that are "not captured in other fields" of this metadata schema (Lee et al. 2024). 

text input field 

## Gameplay File Entity 

Description coming soon. 

### Title of Clip

text input field [R]

### Length of Clip

text input field [R]

### Date Recorded

text input field [R]

### Commentary

controlled vocabulary [R]

### Gameplay Attribution 

text input field [R][+]

### Metadata Attribution

text input field [R][+]

### ID 

text input field [R]

### Filename

text input field [R]

## Gameplay Settings Entity 

Description coming soon. 

### Input Device

controlled vocabulary [R][+]

### Networked Feature

controlled vocabulary [R][+]

### Number of Players 

controlled vocabulary [R][+]

### Type of Play

controlled vocabulary [R][+]

### Mode of Play

controlled vocabulary [R][+]

### Language 

text input field [R][+]

### Accessibility

controlled vocabulary [R][+]

### Technical

controlled vocabulary [R][+]

### Mods

text input field [R][+]

### Settings Note

text input field 

## Gameplay Footage Entity

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

## Gameplay Instruction Entity 

### Pertinent Topics

controlled vocabulary [R][+]

### Instruction Note 

text input field
