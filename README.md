#Knight survivor pre alpha features:
  
Movement W,A,S,D and arrow keys
touching ennemies and their projectiles makes you lose health
escape key to access the pause menu:
it allows to go back to the game or the main menu
main menu to start, view the highscore or quit the game
move the camera by holding the left mouse button, 
on release the camera resets back to follow the player

During gameplay there's an UI to show: 
hp/max_hp
xp/max_xp
kills
elapsed_time

melee weapon:
(rocks that orbit around the character)

ranged weapon:
(rock projectile)
It follows the mouse position for the aim

4 ennemies:
Thief:
Anomaly:
Dead:
	moves fast
Flying Demon:
	is very tanky
	fires a ranged attack: fireball 
	drops a chest that makes you level up

All the enemies play a hit animation and stop moving while being hit
All the enemies spawn outside the screen and always move toward the player
All the enemies spawn more frequently as time goes on
Stronger enemies spawn less often than the weaker ones
All the enemies drop xp when they die.

Magnet Mechanic:
The xp will start to follow the player when he is in range until it hits the player to be collected

level up: 
When current xp reaches max_xp a level up occurs where you can choose 3 random upgrades
All the upgrades:

For weapons:
faster rotation (only the rotating rocks)
bigger rocks
bigger radius of the circle that the rocks rotate on
additional rock (only the rotating rocks)
faster attack speed (only the projectile)
more damage

For the character:
increased health_regen
increased max_hp
increased movement speed
increased pickup range

passive bonus on each level up: 
max_hp+20
damage+=5

Items that drop in random spots:
health potion-> heart +50hp
magnet-> increases pickup range and movement velocity of xp during 10 seconds

Features to do:
Add limits to upgrades
Add Maximum amount of each enemy and drop
add a rarity system to each upgrade
Add hp_bar
Add xp_bar
Add level design
add obstacles for player and grounded ennemies
limit the size of the map with invisible walls
stop the walk animation when the player doesn't move
Add ranged weapon 2
add melee weapon 2
add options in the main menu
add credits button in the main menu
find more free assets
...


