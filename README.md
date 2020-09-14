# Game-of-Rock-Paper-ans-Scissors
Children often play the game of rock, paper and scissors. This game has two players, each of whom chooses one of three ojects:rock,paper, or scissors. If player 1 chooses rock and player 2 chooses paper, player 2 wins the game becouse paper covers the rock.

I will use the following enumeration type to describe the objects.

This program is divided into the following functions, which the ensuing sections
describe in detail.

displayRules: This function displays some brief information about
the game and its rules.

validSelection: This function checks whether a player’s selection
is valid. The only valid selections are R, r, P, p, S, and s.

retrievePlay: Because enumeration types cannot be read directly,
this function converts the entered choice (R, r, P, p, S, or s) and
returns the appropriate object type.

gameResult: This function outputs the players’ choices and the
winner of the game.

convertEnum: This function is called by the function gameResult
to output the enumeration type values.

winningObject: This function determines and returns the winning object.

displayResults: After the game is over, this function displays the
final results
