##Scripting

#One line scripting

#For loops

Single line Syntax: for x in {start..end}; do <commands>; done

Command used: for number in {3..34}; do echo "## Level progressions
#Example header lvl_1 -> lvl_2

#lvl_1 -> lvl_2

Objective:

Commands used:

Important Flags:" > ./bandit_$number/notes.md

Concepts: x: Like in many programming languages, is a variable name for iterations in a loop; {start..end}: the start and end of whatever youre iterating(numbers, names, libraries, etc); do: start of actual commands and code that is run; done: ends one iteration of the loop

Why was it used: I didnt want to go through each notes.md file in every dir to paste the lines.


Multi-line Syntax:

for x in {start..end}

do
	
	<commands>

done


#Variables

Variables are declared without spacing: x=5

Evaluation of a variable has a specific syntax: $x; $ means to evaluate

Arithmetic Expansion: $((x+1))
