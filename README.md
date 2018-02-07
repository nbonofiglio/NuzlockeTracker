### README ###

This is a Nuzlocke Tracker Application for Pokemon Red and Blue written in Java.

Author: Nick Bonofiglio
GitHub: github.com/nbonofiglio/NuzlockeTracker

----- What is Pokemon? -----

Pokemon is a Japanese role-playing game, or JRPG, created by Satoshi Tajiri in 1996. The original games were released by Tajiri's studio, Game Freak, for the Nintendo GameBoy. The game contained two main goals for the player to achieve. 

-Goal #1: Gym Leader Challenege and Elite Four

The first main goal is to take the Gym Leader Challenge, comprised of 8 gyms, in which the player must travel throughout the region in order to defeat each leader and earn their respective "gym badges." Once all 8 badges are collected, the player travels to Indigo Plateau to take on the Elite Four and the current Champion. After defeating all 5 in succession, you become the new Champion!

-Goal #2: Gotta Catch 'Em All

The second main goal is to catch all 150 Pokemon in the game. A Pokemon is caught when a player successfully captures a Pokemon inside of a "Pokeball." If a player obtains every single Pokemon in the game, they can receive an in-game certificate to prove that they completed the goal. 

There is a "catch" to this though. Not all 150 Pokemon are available in the game. Two versions of the game were created, titled Pokemon Red Version and Pokemon Green Version (followed by a special edition Blue Version), and each version had a handful of Pokemon that were version-exclusive. This meant that they could only be caught in one version of the game, and not the other. This was done by Tajiri in order to emphasize socialization and cooperation between players. While the story was the same across both games, a player had to either know someone that owned the other version of the game, or buy both versions and use two GameBoys in order to trade with themselves. A revised version of Pokemon Green was released in Japan soon after as Pokemon Blue Verison, which contained some bug fixes.  

Over the following year after Pokemon's release, the United States saw a sudden burst in popularity of Japanese manga and anime. Because of this, Tajiri decided to wanted to bring his creation to the rest of the world, translating the updated version of the Japanese Pokemon Blue Version into other languages and releasing them as Pokemon Red Version and Blue Version. The games have become so popular worldwide, that they have spawned numerous sequels (each adding more new Pokemon for the player the capture), several different manga series, an anime, feature films, a trading card game, and competitive battle tournaments. The card game and competitive battling both have national championships and world championships held annually, giving out tens of thousands of dollars in prize money to the winners.

----- What is a Nuzlocke? -----

When Pokemon was released in the U.S. 20 years ago, it was marketed towards children. While it is still marketed towards children, a lot of the original fans that grew up with it have remained loyal to the series. Because a good portion of their fanbase is now in their 20s, and the difficulty level of the games being fairly consistent throughout the entire series, players have begun created their own self-imposed rules in order to make the game harder. Things like healing restrictions, capturing restrictions, and even perma-death have become very popular.

A Nuzlocke is a specific set of self-imposed rules created by a user named "Nuzlocke" on the forum site, 4chan. The user's avatar was the body a Pokemon called a Nuzleaf and the head of Terry O'Quinn's character John Locke from ABC's "Lost," hence "Nuzlocke." Nuzlocke's ruleset the he proposed was as follows:

1. Only the first Pokemon encountered in each area (Route, Town, City, Cave, etc.) is eligable to be captured. 
			
	Exception: Catching a Pokemon to avoid a "soft-lock" (the inability to continue progressing through the game due to a specific set of circumstances) is allowed, but only for the purpose of avoiding the soft-lock. It cannot be used in battle.
			
2. Perma-death: Normally when a Pokemon loses all of its health, it "faints" (reaches 0 hit points, or HP) and can be revived 	by some healing items or it can be restored to full health at a local Pokemon Center (basically a Pokemon hospital). Perma-		death means that any Pokemon that faints is declared dead, and can no longer be used. The "dead" Pokemon must be take to a 		Pokemon Center and placed into a storage box on the computer for the remainder of the game or released back into the wild.

3. If all of the Pokemon that a player has obtained die, they game is over and the player loses. The only way to win is to 			defeat the Elite Four and the Champion while still having at least 1 Pokemon alive at the finish. 
	
	Optional Rule (more difficult): If all Pokemon in a player's party die (a player can only carry up to 6 Pokemon in their party at any point in time), the game is over and the player loses.

These 3 rules have grown exponentially in popularity because of their simplicity, the challenge they bring, and the replay value they bring to the games. There are other rules that are optional, the most popular being that all Pokemon must be nicknamed so that the player has a greater emotional attachment to each Pokemon they catch. 

----- What does this Nuzlocke Tracker do? -----

This Nuzlocke Tracker is meant to keep track of encounters for Pokemon Red and Blue. 

1. The user is prompted for an area name.

		If the area name is invalid or is already associated with an encounter, an appropriate error message will be displayed, and the player will be prompted again to enter an area name.

2. The user is prompted for the name of the Pokemon encountered.

		If the Pokemon name is invalid, an error message will be displayed, and the player will be promtped again to enter a Pokemon name.

3. The user is asked if the Pokemon was captured.

		If the Pokemon was caught, the tracker will save the Pokemon name and associate it to the area name. If it was no caught, then a string containing "missed capture" will be displayed.
		

		

		
		