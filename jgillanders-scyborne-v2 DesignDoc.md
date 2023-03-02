# Second version of my platformer game inspired by Bloodborne!
# This is a boss-rush gauntlet of sorts, while not finalized, it
# is the next version of the original platformer made in Construct 3!

# Controls: 
# Arrow Keys: Left/Right to move, Up to jump
# Space bar: Attack with your weapon! The hitbox can be a bit
# wonky, however it should work if you land it right. 

# Citations for assets that were NOT my own are listed here. In addition, the title screen
# background was made with DALLE 3. 

# I used these assets from user “ansimuz” on https://opengameart.org/content/industrial-parallax-
# background and https://opengameart.org/content/mountain-at-dusk-background


#GDD


I. Updates and Iterations
	For this second iteration of my game, I wanted to focus on the aspect that was the most fun to me, which in this case was not designing tricky platforms, but rather making cool, unique boss encounters in which I think I succeeded. Since my game is a kind of homage to the game Bloodborne, which has some notorious boss fights, I wanted to emulate that here in my game as well. 
	We have abandoned all the platforming sections and instead worked to create a game solely around boss fights, with some updated mechanics and fancy enemy AI to work with. 
Major Changes
-	Health bar for player and bosses, each hit received is damage taken, and that is true for both. I utilized instance variables to calculate the width, then subtract a from that width each time a hit is exchanged. It varies between fights and enemies, but the damage is fitting of the encounter. 
-	Health pickups, hearts are found across the battlefields to help the player in a pinch. While I was playtesting, I found the fights far too difficult without any way to restore your health. In this case I did the inverse with instance variables, rather than subtracting I would add to the width whenever a player would pick up heart. Also making sure that when the player is at full health, they do not go over the limit, and when an enemy goes over a hear,t they will not be affected by it. A single heart restores about 1/5 of a health bar for the player, and with a few around the battlefields that can make for a big difference.
-	Improved enemy AI. in my first iteration I was unsure of how to program enemy AI so I just made it where they would be bullets, or they would move around when the player moves etc. This time I wanted to implement true boss AI and I succeeded in that. There are three encounters each with their own differing movements. 
o	Boss one is a reiteration of the boss from my first version, which was more of a concept than anything. However, I liked the design and effort I put into that stage so much I wanted to redo it and I think it paid off. boss one doesn't really move around very much, rather it will stay in a general location and fire projectiles at the player. Using the bullet property on the projectiles and making sure that they were mapped to the players direction, and it can be difficult to get in on the boss as it is firing projectiles constantly and shuffling about.
 
o	Boss two is a dual fight, as there are two enemies to contend with. They are essentially carbon copies of each other and present a kind of symmetry in the level and fight. Each of them teleports around to different platforms and will shoot projectiles at the player while doing so. To accommodate for this difficulty, they have less health than other bosses, however you do need to defeat both of them at the same time for the level to progress. It is a fun and engaging fight from my testing.
 
o	Boss 3 is a mirror version of yourself, I have always been a fan of the shadow trope and one is to try and implement it here as it was a fitting end. While not all the animations are the same the opposite version of the player will chase them around the stage and attack when they get close, in addition the shadow version is very fast so making sure the player has ample time to attack is a key part of the fight. 
 
-	To me each boss offers something unique, and no two fights feel the same which is something I was going for. I wanted to emphasize quality over quantity and in my next iteration I will continue to not only improve past fights but add new and better ones. 
-	Title Screen. What game is complete without a title screen? I made a custom logo and put in a few of the enemies and characters you see in the game and rather than just throwing the player blind to what I made I figured a title would be nice.
 

-	Lore. While these are simple 2D games, the lore is something I think about while making them and I have been putting together a story. Though for now I would say some simple themes are conquering your own self, your inner doubt, and your demons. Additionally, a player receives a special heart at the end of each level, and I always thought the term “heart in the darkness” was thought provoking, so having some simple themes like that in mind helps to fuel the narrative and world. 

Future Additions
-	More fights. This is the obvious one, however I will continue to expand until I think I have a set of solid boss fights that encapsulate the lore and mechanics that I'm trying to go for. I think 3 is a solid starting point for now but I hope to get at least 6 and truly test my limits of designing intriguing fights in 2D.
-	Upgrade System. I implemented an upgrade system in the platformer to give the player say double jump or increase speed but I would like to do it here as I think it could be an interesting flow to combat, such as giving the player a projectile. or possibly letting players choose upgrades and approach the bosses in a nonlinear manner such as the Mega Man games. just food for thought but something I would like to implement. 
-	Music. I have a plethora of tracks and songs I made that I have never put or released anywhere, and what better place to use them besides a game. some would not fit but I think others could be solid as boss music or level music, more on this when I figure out audio. 
