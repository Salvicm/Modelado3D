- Everything from 3dsMaxAssets should go to sceneassets -> Images in a project on 3dsMax in case they don't show correctly

- The scene has been assembled on Unreal Engine 4.23.1. 
- All imported assets, blueprints and the scene are on the /unreal folder

- To make the UE4 work it might be possible you need to create new project with first person example, close unreal engine,  go to MyProject\Content\FirstPersonBP and move the folders Assets, Blueprints and Maps from my exercice to the other, replace everything. Now open UE4 again and open the FirstPersonExampleMap and everything should work.

- On play mode you can only move the cámera rotation but not the position, since the models are optimized(Or at least I tried to) and if you advance you'll see missing unnecessary faces, although you can move freely on the editor.

- If the scene cannot be loaded by some reason I included two builds from the game, you won't be able to move freely but it's just in case, they are on Unreal/Builds folder for windows 32 bit and windows 64 bit.

- I also included all the .psd on which i made the textures and added the .fbx