Script/Code is used for creating Weapon, Attachment and Magazine CSV files

"BattleBitRemasteredDataMiningScript PUBLIC" is a script created by Ox1gen1.

In order to use the script you need to use Unity AssetRipper

To use the Script/Code
You need:
C# IDE (Recommended: Microsoft Visual Studio)
AssetRipper (https://github.com/AssetRipper/AssetRipper), also tutorial for using it (https://www.youtube.com/watch?v=jiWSxHzj434)

What you need to do:
Use Asset Ripper and get ALL BattleBit Remastered files (See BattleBit Asset Ripper GUIDE.pdf)

Copy/Paste code into a code project/IDE so you can run the code
Insert your own file paths.
Monobehaviour_Location  ...\BattleBit\ExportedProject\Assets\MonoBehaviour\
PrefabInstance_Location  ...\BattleBit\ExportedProject\Assets\PrefabInstance\
AnimationClip_Location  ...\BattleBit\ExportedProject\Assets\AnimationClip\
CSV_Location ...\"Where you want your .csv files written in"

Execute Script and CSV_Location should have 5 .csv files, which are filled with values.
NOTE: IF the created .csv files look like AK74;X;X;X;X;X, you need replace HEADER strings with the version which uses , as a separator instead.
