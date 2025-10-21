# Pig-Game-Using-JavaScript-

This is more of a real game now because we actually have two players. You can play this with a friend or just against yourself. The idea is that we roll a dice. Now I'm playing as player one, so this one is the active player. I roll the dice and see that I rolled a two. This number gets added to my current score down here. This is my current score for the current round, and this here is my total score.

I can roll the dice again if I want to, and now I rolled a four. That four got added to the two that I had previously, so now that's six. I can choose to hold this score. If I click this button, the score of the current round will get added to my total score, which right now is zero. When I hold, my current score will reset to zero, and the turn switches to player two.

Now it's player two's turn. I can click roll dice again. We rolled a two, and I can hold again. Now player two has two points. The key rule here is that whenever we roll a one, we lose all our current score and it's the next player's turn. That's why sometimes we need to hold our points.

For example, I rolled a one right away, so now it's player two again. Let's keep rolling the dice. I will wait for a one so you can see that all my current score will be lost. After accumulating a lot of points, I rolled a one and lost all the points. I could have held the points to add them to my total score. Let's do that here, and again a one. Now I hold and add the points to my total score.

By now, you should understand how the game works. The first player to reach 100 points wins the game. We have two buttons here, a way to reset the game. When I click reset, the dice disappears and all scores are set back to zero.

Whenever the user rolls the dice by clicking the roll dice button, we generate a random dice roll, display it, and check whether it is a one. If it is not one, we add the dice roll to the current score. This is exactly the behavior we saw when testing the game earlier. If the dice roll is a one, we simply switch the player without adding to the current score.

Another option is that the user wants to hold their score. Then we add the current score to the total score. After that, we check if the score is at least 100 points because the player wins when reaching 100 points. If not, we switch the player and the game continues running. Finally, when the user chooses to reset the game, we set all scores to zero and set player one as the starting player.
