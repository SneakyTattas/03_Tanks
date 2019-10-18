# 03_Tanks
[Η πουτσα που μου τρωει τη ζωη](https://www.ceid.upatras.gr/el) 

[tips and useful tutorials taken from here](https://www.udemy.com)

[BT35 COMMIT: Workarourd of compiler bug to force ue to run on 4.22 version.](https://developercommunity.visualstudio.com/content/problem/734585/msvc-142328019-compilation-bug.html)

## List
* BT01 Intro
* BT02 Game Design Document (GDD)
* BT03 Setting Up Github Repo
* BT04 Create and Delete Landscapes
* BT05 Landscape Setup and Scaling
* BT06 Sculpting tools - a Landscaping Process
* BT07 Using Landscape Layers ( Multi-layered colours )
* BT08 Importing and Exporting Landscapes
* BT09 Final 1st Commit for Landscape
* BT10 Building Tank, Importing Static Meshes, Actors from Multiple Meshes
* BT11 Improved Static Mesh for Tank
* BT12 Configuring Tank, GameMode to start as a Tank
* BT13 3rd person camera control, input binding
* BT14 Quick Fix, Camera Roll when spawning on slope, Untick Inherit Roll
* BT15 Setting up User Interface, AimPoint for the gun (WIP), Setting up extra level for Main Menu, 5/7 BEST IMAGE
* BT16 DANK UI SCALE BOX AND START BUTTON
* BT17 Escape Button + Controller button to exit game
* BT18 Quick Fix, escape button wasnt working and first package of the game ( version 0.1 )
* BT19 Quick Update of readme
* BT20 Making C++ Classes for Tank and TankPlayerController BPs, delegating to components, changing parents classes.  ( 2 hours to fix broken binaries, coding is FUN )
* BT21 Virtual and override functionality ( if a method is virtual, any descendant of the method will be able to be overriden )
* BT22 Possessing pawns (other tanks) with AI controllers ( AIs )
* BT23 Get the AIs to find the player controller
* BT24 Added Tick() to player controller
* BT25 Introducing Ray Trace to aim, using an out parameter method ( FVector OutHitLocation )
* BT26 Finding AimDot Screen pixel coordinates
* BT27 DeProjectScreenToWorld() method, ( actually getting the coordinates where the dot points )
* BT28 LineTraceSingleByChannel() method, using it to line trace from the dot to a straight line the coords
* BT29 Unify Player and AI Aiming, both using the same interface for aiming
* BT30 Update of readme
* BT31 Introducing AimingComponent to move turret/barrel (moved output log to AimingComponent Class
* BT32 Using BlueprintCallable() ue4 function to set the barrel component and get its position
* BT33 SuggestProjectileVelocity Implementation ( // weird out values must check if true )
* BT34 And Another update of readme
* BT35 Starting the day with a compiler bug, normalisation of vectors in version 4.23 is bugged, workarourd at: MSVC (link in readme) REMEMBER TO CHANGE WHEN ITS FIXED
* BT36 Forgot to commit updated readme woops
* BT37 Introducing Rotators in unreal in order to move barrel
* BT38 New TankBarrel class inherited from StaticMeshComponent, Using BlueprintSpawnableComponent to introduce defaulth properties
* BT39 Forward Declarations of classes where needed, Fixed SuggestProjectileVelocity which produced a bug with default values
* BT40 And Another One
* BT41 Finally moving the barrel and using clamp() to limit max/min values 
* BT42 Copypasta Barrel elevation code to make the turret rotate, Completed Functioning Turret+Barrel
* BT43 Adding Projectile C++ class and BP, start of setup
* BT44 Readme update, fixed bug that resetted turret static mesh to none