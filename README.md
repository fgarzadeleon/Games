# RollCompare

This game is about human intuition and learning from the collective experience of other players. The players are playing against the house.

There are 60 cubes arranged in a table the following 


``` 
House's        Players'
  cubes         cubes
			|
			|                Won without
   20		|    20	      looking at dice
			|
-------------------------
			|
			|
   20		|    20       Won with
			|				looking at dice
			
```		
There is an overall tie at the beginning of the game.

## Gameplay

The player will roll their dice and the house will roll their dice.

The player's dice is multiplied by two that is the roll can be (2,4,6,8,10,12). The house will sum their dices together (2,3,4,5,6,7,8,9,10,11,12).

The player has to call if their dice sumed by the number of cubes they wish to bet is smaller than the House's sum of dice. 

```
playerDice + cubeBet < houseDice1 + houseDice2
```

The number of cubes they can bet is at a maximum of 6 cubes.

If the player wins he moves **the number of cubes the player bet** from the House into their area. If the player loses he moves **the number of cubes the player bet** from their area into the House's. In the case of a tie nothing happens.

The player may chose the option of paying **one cube** to take a look at one of the House's dices. After looking at it the player once again call if their roll is higher than the House's.

The player will be allowed 10 rolls after which his involvement will be finished. They will be invited to come back later on and see the state of the game and play again.

Whenever any of the pots has 0 cubes the game is over and is restarted.

## Comments

The game is not only about wagering the bet but having a finite number of cubes that move around depending on the previous results. The new players who arrive receive a snapshot from these results and can learn what the best strategy is from these results.

## Variants
Payoffs can be changed to nudge players towards one option or another, for example instead of having to pay one cube to see a dice, it's free. Or instead of getting charged one cube to look at the dice, they get paid one cube more if they don't look at the dice.



