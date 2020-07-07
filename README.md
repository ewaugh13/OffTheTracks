# OffTheTracks

​Was originally designed to be played with an alternative controller. A cooperative gameplay experience controlling a handcar through pumping and leaning.

Developed in Unreal Engine 4 as a semester long project with a team of 11. Team consisted of 3 producers, 5 engineers, 2 artists and 1 tech artist.
Took all files from Perforce depo and copied over to a git repo.

# Some of the things that I worked on

- Converted many Train, Rail & Roller Coaster System blueprints to C++. Can be found on the Unreal Marketplace here https://www.unrealengine.com/marketplace/en-US/product/train-and-rail-system
  - Converted TrainTrack, TrainAndRailFunctionLibrary, TrainCarriage and the DebugTool blueprints to C++ amoung others. Contained 70+ functions that where conveted to ~4,000 lines of code
  - Added custom functionality to the track and carriages(handcars) and added optimizations for better performance in the editor when using these
- Created two unique enemies that would attack the player to slow them down
  - Both enemies using Behvavior Trees with Blackboards
  - Created custom BT Nodes (Tasks, Services and Decorators) that were used by both enemies and unique ones for each enemy
  - All code for the enemies and BT elements I wrote can be found [here](https://github.com/ewaugh13/OffTheTracks/tree/master/Source/HaphazardHandcart/Gamecode/Enemies)

# Can be downloaded here 
https://ewaugh13.itch.io/off-the-tracks