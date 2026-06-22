# LaserDetect Test Release

LaserDetect is an experimental Android app for detecting and scoring laser hits on a target using the phone camera, using a "Dry Lasers Trainer Cartridge" for your specific firearm.

This repository contains prebuilt test releases only.

## Downloads

Download the latest version from the Releases section.

Files:

- `LaserDetect.apk` — Android app
- `detect.exe` — Windows UDP receiver/viewer
- 'dfs_15m.pdf' - the target used

## Usage

Before using LaserDetect with firearms, training weapons, or laser cartridges, always verify that the firearm is unloaded and that no live ammunition is present in the firearm, magazine, chamber, shooting area, or test setup.

LaserDetect is intended primarily for indoor use under dim or controlled lighting conditions. Strong ambient light, direct sunlight, reflections, glare, bright red objects, or unstable lighting may reduce detection accuracy or cause false detections.

See [SETTINGS.md](SETTINGS.md) for details.

### Quick Start

1. Install the APK on an Android phone.
2. Start `detect.exe` on a Windows PC.
3. In the LaserDetect app, open UDP settings and enter the PC IP address. Use port `5005`.
4. Make sure the phone and PC are connected to the same network.
5. Start with simulated target mode (`Sim target`) and verify that hits are received by `detect.exe`.
6. Switch to ArUco target detection (`ArUco target`) when the simulated target test works.
7. Place the phone in a stable position with a clear view of the ArUco target. The phone may be placed at an angle, but a distance of about 20–30 cm is recommended for testing.
8. Test hits at the center, 12 o’clock, 3 o’clock, 6 o’clock, and 9 o’clock.
9. Verify that the score, hit position, and UDP output match the actual hit location.

## License

LaserDetect is distributed as a prebuilt binary test release only.  
The source code is not published.

Personal, educational, and non-commercial testing is permitted.  
Commercial use, redistribution, modification, reverse engineering, or integration into commercial products or services is not permitted without prior written permission.

See [LICENSE.md](LICENSE.md) for details.
