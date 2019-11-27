# Unreal-Tournament
Custom Blue Prints and Levels for Unreal Tournament Pre-Alpha

IF YOU CANT GET THIS WORKING, DO NOT CONTACT ME!

These blue prints are based off the v1.7 of ProMode. You are free to use the contents of this mutator however you wish with the exception that you do not utilize the ProMode name or branding. The root filename is set to "GamePlay"  and it is required that you create a new and unique name otherwise you will cause conflicts with other morons who dont change it. If you fail to change it, you run the risk of breaking not only your mutator on the server but other peoples versions who didnt change it as well. All of the ProMode branding has been removed from the files, so please make sure you manually go through and change weapon names, mutator names and so on.  All of these elements have been changed to "GamePlay". CHANGE THEM!!

To add the mutator to your installing of Unreal Tournament Editor:
1. Unzip the contents of the file directly into the "Contents" folder of the UnrealTournamentEditor folder. For EXAMPLE D:\Epic\UnrealTournamentEditor\UnrealTournament\Content\GamePlay
2. Launch UT Editor
3. Verify the files have shown up correctly
4. ***RENAME THE ROOT FOLDER IN THE EDITOR FROM "GamePlay" TO ANYTHING ELSE!
     You must change the name from within the Editor otherwise all the references will not carry over.
5.  ***RENAME ALL THE MUTATORS FROM "MUTATOR_GameplayXXX" to "Mutator_MyNewNameXXX"
6. Modify as you please
7. To test the mutator in the editor add the following command to play in editor (PIE):
?mutator=/game/MyNewName/mutator_MyNewNameMode.mutator_MyNewNameMode_C
8. You may need to fix a few dependencies on weapons or other assets
9. Places to modify the "GamePlay" value: Mutator file names, Mutator descriptions, Mutator author, All weapon and asset file names, All weapon descriptions, Match start splash logo/name
10. Once you have renamed all the objects/variables and modified the mutator as you like, from within the editor Select Share -> Share Mutator and select the "Mutator_MyNewNameMode".
11. First time cooking can take upwards of an hour to complete, afterwards it should take just a few minutes.  You can find your cooked pak file in C:\Users\YOURNAME\Documents\UnrealTournament\Saved\Paks\MyContent
Play offline right now to test in the game or upload to your favorite HUB.


Mutator File Name Desciptions
1. BP_GamePlayMovementInventory - This file contains the movement variables applied with Mutator_GamePlayMovement.
2. Mutator_GamePlayMode - This is the master file, cooking/sharing this file will add all the content to a ProMode like mutator.
3. Mutator_GamePlayMovement - This is the mutator file that applies the BP_GamePlayInventory to the pawns movement.
4. Mutator_GamePlaySwitch - This mutator applies fast weapon switch to stock weapons, changes made to this file only affect stock weapons.
5. Mutator_GamePlayWeapons - This mutator is responsible for replacing all the stock weapons/items with your modified weapons.

Happy Fraggings! - PayBack
