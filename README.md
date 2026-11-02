
# Choco-Master-Menu for Chocolate Doom, Heretic, Hexen and Strife.

![choco 2.0-1.jpg](https://github.com/nicoku007/Choco-Master-Menu-v1.2/blob/main/choco%202.0-1.jpg?raw=true )

![choco 2.0-2.jpg](https://github.com/nicoku007/Choco-Master-Menu-v1.2/blob/main/choco%202.0-2.jpg?raw=true )


Choco-Master-Menu is a launcher built in C# with Windows Forms, designed for Chocolate Doom. Originally created to provide a native menu for the Master Levels, it evolved into a comprehensive frontend that eliminates the need for manual command-line execution. This new version 2.0 introduces dynamic support for Chocolate Heretic, Hexen, and Strife.

Main Features

• Multi-Game Support: Launch and manage Doom, Heretic, Hexen, and Strife from a single unified interface.

• IWAD Management: Directly select your official IWADs without configuring the engine setup or duplicating folders. It automatically detects plutmidi.wad.

• WAD Combining: Cleanly load secondary files (.wad, .deh, Heretic's .hhe patches, Hexen's .hex patches and strife's .seh patches ), perfect for mixing maps with custom texture. To select more than one custom WAD, hold down the CTRL key.

• Direct Setup Access: Dedicated button to instantly launch chocolate-doom.setup without needing to close the launcher.

• Quick Controls: Press F1 for full screen mode and Escape to return to windowed mode.

Special Modes (Doom / Doom 2)

• Master Levels Menu: Run any Master Levels for Doom 2 map directly without typing cumbersome parameters. Fully integrates Peter Lawrence's Master MIDI Pack.

• Campaign Mode: Automatically sequences levels by generating temporary scripts in Windows Temp to protect your original files, featuring a garbage collector that wipes them on exit. Includes a custom sky with dark blue clouds.

• Maximum Doom: Dedicated section with separate folders (maximum1 and maximum2) programmed to work exclusively with their respective IWADs.

Multiplayer, Parameters & Demos

• Advanced Multiplayer: Independent options per session (Cooperative, Deathmatch, Deathmatch 2.0, private server, IP, UDP port, server name, and auto-join). Lets you query the Chocolate Doom Master Server or search the local area.

• Simplified Player Name: Reads your chocolate-doom.cfg file to change your name from the menu. The code handles the necessary quotation marks (" ") automatically.

• Engine Parameters: Direct toggles for No monsters, Fast monsters, Respawn monsters, and Turbo, along with an Extra Parameters text box for any other command argument.

• Demo Recorder: Session-specific tools to record or play back your .lmp files with a dedicated file browser.

Visual Customization (Retro Tribute)

• Smart Retro Layout: Default Deep Charcoal Blue design with Cyan borders as a visual tribute to the classic setup tool. Harsh pure white backgrounds were replaced with a subdued white to reduce eye strain.

• Native Color Tuning: Tab featuring independent 16-color MS-DOS CGA/EGA/VGA style selection ListBoxes for fonts, backgrounds, and launcher borders. Includes a brightness selector to protect your eyesight.


Installation Instructions

1. Extract the entire "choco-master-menu" folder from the ZIP archive and place it anywhere on your system.

2. Run Choco-Master-Menu.exe and use the Browse buttons to select your game executables.
   * The button to find "chocolate-doom.exe" is inside the "Locate .exe" section.
   * The button for Heretic, Hexen, and Strife is located inside the "SPECIAL GUESTS" section.
   * Note for Special Guests: Once you have located the three executables (chocolate-heretic.exe,    
      chocolate-hexen.exe, and chocolate-strife.exe), simply change the title in the Game combobox, 
      and the launcher will automatically switch to the corresponding executable.

3. Portability Note: The master-wads, maximum1, and maximum2 folders must remain in the same directory as Choco-Master-Menu.exe for the Master Levels and Maximum Doom features to work properly. It is no longer necessary to place them next to chocolate-doom.exe.

4. Place your Master Levels files inside the master-wads folder.

5. Place your Maximum Doom files inside their respective folders: maximum1 (for Doom 1) and maximum2 (for Doom 2).

6. Keep your official IWADs (DOOM.WAD, DOOM2.WAD, TNT.WAD, PLUTONIA.WAD, HERETIC.WAD, HEXEN.WAD, STRIFE1.WAD) in the same directory as their respective game executables to allow the launcher to detect them.


Credits

• Developer: Nicokugame007

• Master MIDI Pack: Peter Lawrence
