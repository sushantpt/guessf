# guess-and-enter-the-program
Basic program written in shell.
---------------------------------------------------------------------------------------------------------------------
<<< [ Steps ] >>>
* 1st ----> Store $name and $id in a variable.
* 2nd ----> [ "$#" -ne 2 ] returns the input and check if something is missing. [ $name and $id ] 
* 3rd ----> check if the data stored in $name is string or doesnot contain any integers. If not, then re-do the process.
* 4th ----> do same for $id.
* 5th ----> store key in a variable.
* 6th ----> put total attempts to give user to guess.
* 7th ----> create a function to count attempts. If guessed accordingly, continue to the program. Else, return to 1st step.
* 8th ----> create another function which will unlock after correct key.
* 9th ----> create country with country code. 
* 10th ----> if any country-code is choosen, output result. Exit case statement.
* 11th ----> create another function to choose players.
* 12th ----> create player with player code.
* 13th ----> if correct player choosen, output result which is exported from text file using CAT $player command.
* 14th ----> ask user to continue. If yes, return to main_page (6th step). Else, exit with wholesome message.
