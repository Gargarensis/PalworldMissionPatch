# PalworldMissionPatch

## What is it
This patch is intended as a workaround to restore the main mission of the Palworld game if it disappears due to a common bug. This patch was tested on Palworld version 0.6.0.

## First of all
1. Go to your Palworld saved games directory. It should be `C:\Users\<your username>\AppData\Local\Pal\Saved`
2. Make a backup of your saved games if something goes wrong

## How to install it
1. Download the file `QuestFixMod_P.pak`
2. Go to your Palworld directory. Mine was `C:\Program Files (x86)\Steam\steamapps\common\Palworld`
3. Create a directory called `Mods` inside `...\Palworld\Pal\Content\Paks`
4. Move the `QuestFixMod_P.pak` in the `Mods` directory.

## Multiplayer server?
Ensure both the host and the player have installed the mod. Do not join the game if the host has installed the patch and you haven't or vice-versa.

## How to use it
1. Open the Palworld game
2. Go to the Small Settlement
3. Talk to this guy:
![The Samurai in the Small Settlement](the_guy.png "The Samurai in the Small Settlement")
4. He will give you the quest to fight Lily
5. Done, if you had already completed the Lily quest, you will receive the next one

## What to do next
1. Exit Palworld
2. Go back to the `Mods` folder
3. Delete `QuestFixMod_P.pak`
4. You can now play normally!


<br>

## For Dedicated Servers (thanks to Deregis)
For dedicated server, create the directory and upload the mod to "...\common\PalServer\Pal\Content\Paks" instead of "...\common\PalWorld...".
Only has to be done from the PalServer side, other players will have access to the Mod through that.

<br>

## FAQ

### What will happen if I was at a previous step in the main mission?
I did not test it, I guess you will receive the Lily quest anyway and skip the others.

### Can't I keep the mod installed in the case it will happen again?
It should not have any side effects until the next patch, but you won't be able to complete the samurai missions. If it happens again, just do this once more.

### Why the samurai?
It was the first NPC I remembered that gives quests and was easy to find.

### Wasn't there a better solution?
Probably yes. This was the fastest one to implement.
