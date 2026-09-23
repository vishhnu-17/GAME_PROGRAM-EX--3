# GAME_PROGRAM-EX--3.

## Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

## Procedure
Import New Character Mesh and Animations:

In the Content Browser, import a new Skeletal Mesh along with its Animations (FBX files).
Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).
Replace Character Mesh:

Open the ThirdPersonCharacter Blueprint (usually found in ThirdPersonBP/Blueprints).
Select the Mesh component.
In the Details Panel, change the Skeletal Mesh to the newly imported mesh.
Set Animation Blueprint:

If available, assign a matching Animation Blueprint in the Details Panel under the Animation section.
If not available, create one:
Right-click in the Content Browser → Animation → Animation Blueprint.
Choose the correct skeleton.
In the AnimGraph, set up state machines or direct animation nodes.
Compile and save.
Preview and Test:

Place the character in the level.
Press Play to test idle, walk, and run animations based on character movement.

## Output
<img width="939" height="573" alt="image" src="https://github.com/user-attachments/assets/eb6d0f10-4cb2-4388-a9f6-67f5b24cd0d9" />
<img width="1035" height="597" alt="image" src="https://github.com/user-attachments/assets/8efe9f72-16fc-4bf0-a205-8e205cb5bc59" />
<img width="577" height="499" alt="image" src="https://github.com/user-attachments/assets/d6367d78-2a9f-4d4e-aee0-e72f7b5b1a4c" />

## Result
Thus the replacement of the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint was executed sucessfully.
