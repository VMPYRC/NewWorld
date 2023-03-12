# Settings

+ These settings are based on my personal preference and what works for me.
+ Focus -- High Performance, Low Quality, Low-End PC

## Where New World is Installed

1. Open Steam
2. Library
3. Right click New World
4. Properties
5. Local Files
6. Browse
7. Sample Locations
	+ Program Files (x86)\Steam\steamapps\common\New World
	+ SteamLibrary\steamapps\common\New World

## In-Game Settings

+ Game
	+ Bandwidth Mode -- HIGH
	+ Emit Client Telemetry Data -- OFF
+ Visuals
	+ Window Mode
	+ Video Quality -- LOW
	+ Dynamic Resolution Scaling -- OFF
	+ VSync -- OFF
	+ Cap FPS in Background -- ON

## Windows Settings

+ Download and install the latest version of Windows
	1. Start
	2. Search
	3. Update
	4. Check for updates
+ Background Apps -- OFF
	1. Start
	2. Search
	3. Background Apps
	4. Let apps run in the background
	5. OFF
+ Startup Apps -- OFF
	1. Start
	2. Search
	3. Startup Apps
	4. Turn off the unnecessary ones
+ Game Mode -- ON
	1. Start
	2. Search
	3. Game Mode Settings
	4. ON
+ Xbox Game Bar -- OFF
	1. Start
	2. Search
	3. Xbox Game Bar
	4. OFF, unless you use the feature
+ Advanced Scaling Settings -- OFF
	1. Start
	2. Search
	3. Fix apps that are blurry
	4. Let Windows try to fix apps so they're not blurry
	5. OFF
+ GPU Settings / Graphic Settings
	1. Start
	2. Search
	3. Graphics Settings
	4. Hardware-accelerated GPU scheduling
	5. ON
	6. Graphics Performance Preference
	7. Browse
	8. Navigate to where New World is
	9. Go into the Bin64 folder
	10. Select NewWorld.exe
	11. Add
	12. Select NewWorld.exe
	13. Options
	14. High Performance
	15. Save
+ Power Plan
	1. Windows + R
	2. powercfg.cpl
	3. OK
	4. Select Ultimate Performance or High Performance
+ Disable HPET
	1. Start
	2. Search
	3. Device Manager
	4. System Devices
	5. High Precision Event Timer
	6. Right Click
	7. Disable device
+ Increase VRAM
	1. Start
	2. Search
	3. This PC
	4. Right Click inside the folder
	5. Properties
	6. Advanced System Settings
	7. Performance >> Settings
	8. Visual Effects
		1. Adjust for best performance
	9. Advanced
		1. Virtual Memory
		2. Change
		3. Select the drive where New World is installed
		4. Custom Size
		5. Initial: 20000
		6. Maximum: 20000
		7. Set
		8. OK (Virtual Memory)
	10. OK (Performance Options)
	11. OK (System Properties)
+ Task Manager, High Priority
	1. Run New World
	2. Open Task Manager
	3. Right Click New World
	4. Go to Details
	5. Right Click New World
	6. Set Priority
	7. High

## Update GPU Drivers

1. Start
2. Search
3. Task Manager
4. Performance Tab
5. GPU 0, GPU 1, and etc.
6. Top Right Corner
7. Make note of the names
8. Go update your drivers
	+ AMD -- https://www.amd.com/en/support
	+ INTEL -- https://www.intel.com/content/www/us/en/download-center/home.html
	+ NVIDIA -- https://www.nvidia.com/en-us/geforce/drivers/

## NVIDIA Control Panel

1. Desktop
2. Right Click
3. NVIDIA Control Panel
4. Adjust Image Settings with preview
	1. Use the advanced 3D image settings
	2. Apply
5. Manage 3D Settings
	1. Program Settings
	2. Add
	3. Sort by Recently Used
	4. New World (newworld.exe)
	5. Add Selected Program
	6. Select preferred graphics processor
	7. Almost everything OFF
	8. Image Sharpening -- ON; 0.50. 0.17
	9. Antialiasing - Gamma Correction -- ON
	10. CUDA GPUs -- ALL
	11. Low Latency Mode -- ULTRA
	12. OpenGL rendering GPU -- Select your preferred GPU
	13. Power Management Mode -- Prefer Maximum Performance
	14. Preferred Refresh Rate -- Highest Available
	15. Shader Cache Size -- ON
	16. Texture Filtering - Anisotropic Sample Optimization -- ON
	17. Texture Filtering - Negative LOD Bias -- ALLOW
	18. Texture Filtering Quality -- High Performance
	19. Texture Filtering - Trilinear Optimization -- ON
	20. Threaded Optimization -- ON
	21. Apply

## Steam Settings (Optional)

1. Open Steam
2. Top left corner -- Steam
3. Settings
4. Library
	1. Low Bandwidth Mode -- ON
	2. Low Performance Mod -- ON
	3. Disable Community Content -- ON
5. In-Game
	1. In-game FPS counter
		1. Top Left
		2. High Contrast Colour
	2. When a screenshot is taken
		1. Display a Notification
		2. Save an uncompressed copy

## Verify Integrity of Game Files

1. After downloading and installing a new patch / update, you should do this
2. Steam
3. Library
4. Right Click New World
5. Properties
6. Local Files
7. Verify integrity of game files
8. Steam File Service -- YES
9. Wait for Steam to verify

## New World Application Settings

1. Navigate to where New World is
2. Right click on NewWorldLauncher.exe
3. Properties
4. Compatibility tab
5. Disable full screen optimizations -- CHECK
6. Change High DPI Settings
7. Override high DPI Scaling behaviour -- CHECK -- SYSTEM
8. Apply the changes
9. Repeat for NewWorld.exe in the Bin64 folder

## General -- Miscellaneous

+ Close all applications that you will not be using
	+ Web Browsers
	+ Background programs
	+ System Tray programs
	+ Downloading other games, Windows updates, etc.
	+ Discord (especially the overlay)
+ Scan for malware
+ Check for signs of overheating
