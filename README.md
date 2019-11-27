# Unreal-Tournament
Custom Blue Prints and Levels for Unreal Tournament Pre-Alpha

IF YOU CANT GET THIS WORKING, DO NOT CONTACT ME!

These blue prints are based off the v1.7 of ProMode. You are free to use the contents of this mutator however you wish with the exception that you do not utilize the ProMode name or branding. The root filename is se to "CHANGEME1"  and it is required that you create a new and unique name otherwise you will cause conflicts with other morons who dont change it. If you fail to change it, you run the risk of breaking not only your mutator on the server but other peoples versions who didnt change it as well. All of the ProMode branding has been removed from the files, so please make sure you manually go through and change weapon names, mutator names and so on.  All of these elements have been changed to "CHANGEME".

To add the mutator to your installing of Unreal Tournament Editor:
1. Unzip the contents of the file directly into the "Contents" folder of the UnrealTournamentEditor folder. For EXAMPLE D:\Epic\UnrealTournamentEditor\UnrealTournament\Content\ChangeMe1
2. Launch UT Editor
3. Verify the files have shown up correctly
4. Modify as you please
5. To test the mutator in the editor add the following command to play in editor (PIE):
?mutator=/game/CHANGEME1/mutator_CHANGEMEMode.mutator_CHANGEMEMode_C
6. You may need to fix a few dependencies on weapons or other assets
7. Places to modify the "CHANGEME" value: Mutator file names, Mutator descriptions, Mutator author, All weapon and asset file names, All weapon descriptions, Match start splash logo/name
8. Once you have renamed all the objects/variables and modified the mutator as you like, from within the editor Select Share -> Share Mutator and select the "Mutator_CHANGEMEMode".
9. First time cooking can take upwards of an hour to complete, afterwards it should take just a few minutes.  You can find your cooked pak file in C:\Users\YOURNAME\Documents\UnrealTournament\Saved\Paks\MyContent
Play offline right now to test in the game or upload to your favorite HUB.


Mutator File Name Desciptions
1. BP_ChangeMovementInventory - This file contains the movement variables applied with Mutator_ChangeMovement.
2. Mutator_ChangeMode - This is the master file, cooking/sharing this file will add all the content to a ProMode like mutator.
3. Mutator_ChangeMovement - This is the mutator file that applies the BP_ChangeMovementInventory to the pawns movement.
4. Mutator_ChanceSwitch - This mutator applies fast weapon switch to stock weapons, changes made to this file only affect stock weapons.
5. Mutator_ChangeWeapons - This mutator is responsible for replacing all the stock weapons/items with your modified weapons.

Happy Fraggings! - PayBack
