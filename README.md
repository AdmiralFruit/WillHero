# Will-Hero

Gaming Rules
1. The default world as the background and the first level of the game is supported. (See Video at 0:28 to 0:35)
2. The Hero always keeps jumping at its current position. Each of these jumps is of fixed height. The player has to use a single input to move the Hero once in the forward direction. The Hero can only move in the forward direction of a fixed length with each input. The game should always display the Hero's location at the top. Location at any point is simply the total number of forward movements of the Hero. Our game could have a total of 122 locations, where the Boss fights between locations 107 to 112. (See https://www.youtube.com/watch?v=VuyBQOXcX00&ab_channel=MobileGamesDaily at 7:01 to 7:12, and the location is displayed at the top, e.g., the number 107 at the duration 7:01). 
3. Apart from the Boss, our implementation has two different Orcs (red and green orcs). The Hero can defeat each Orc either by pushing it into the abyss or by killing it using some weapon. Refer to the video for how Hero can eliminate different Orcs.
4. An obstacle TNT is included in the game which can detonate and stun the Hero.
5. The Hero can hop between floating islands only. Failing to land on an island will make the Hero fall into the abyss (See Video at 1:37), ending the game. The Hero can also be eliminated by an obstacle or by an Orc. In all such cases, webprovide an option to resurrect the Hero in exchange for some fixed number of coins. Only one resurrection is allowed per game, and you can choose the number of coins required for resurrection.
6. The Hero is equipped with a fixed helmet at the start of the game. each helmet comes with a set of two weapons namely the sword and the lance. Whenever the Hero kills an Orc, he gets rewarded with some number of coins. 
7. The Hero will find Chests placed throughout the game level. We support coin chests and weapon chests. The Coin Chests rewards the Hero with some number of coins that the Hero collects. The Hero doesn't have any weapons available with him initially. He will be able to get these weapons only if he can find Weapon Chests. Each Weapon Chest can equip the Hero with only one type of Weapon (See Video at 0:42). If the Hero already has that same Weapon, the weapon is upgraded (See Video at 6:40).
8. The Hero wins the game if he defeats the Boss at the end of the level (See Video at 7:08 to 7:15). 
9. Our implementation allows the player to start a new game, save the current game or load a previously saved game from any point during the gameplay. For this, we save the Hero's current position, Helmet with weapons unlocked, and the coins collected so far.