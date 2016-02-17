# Zacate-one-player-game
Intelligent one player version of popular game Zacate
# Automatic Zacate game player
# Name: Shwethambari Surendran
'''
 *The Zacate dice game follows the rule of probability where we try to play the game by rolling and rerolling 5 dices and choose subsets to complete 13 turns of the game.
 *The main idea here would be to try to assign the result of the dice roll to categories that would provide the highest score.
 *The categories that provide the maximum scores are categories like Quintupulo,Pupusa de Queso,Pupusa de Frijol and in cases when the number of higher scored dice like 4,5 and 6
 are more in number so that categories like Cuatros,Cincos and Seises may be filled with a higher score.
 *The logic is to maintain a seperate list at every roll of the categories that are satisfied by the current dice combination and another list maintaining information about required
 data to satify the other categories.We use these two lists to make decisions and also try to fill in the first six categories so as to get the bonus points.
 *The checkcombi() function does the work of preparing the list of categories satisfied and not satisfied with the current dice combination.
 *The evaluateNextMove() function does the work of evaluating what is the subset of dice to be chosen  to reroll again so as to achieve a higher score.
'''
