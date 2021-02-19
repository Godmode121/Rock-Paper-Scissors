<!--
Create rock, paper, scissors:
    make rock < paper && rock > scissors
    make scissors < rock && scissors > paper
    make paper < scissors && paper > rock
score points:
    make two variables that store points
    update after each round using increment operator(++score)
player chooses rock, paper, scissors:
    create text prompt that asks for player choice
    convert player choice toLowerCase
    store player choice in a variable
computer randomly picks rock, paper, scissors:
    function that chooses from 3 numbers that are === rock(0), paper(1), or scissors(2)
compare player choice to computerchoice possibly using function update():
    function that checks if players choice is >, <, or === computer choice
    if (>) then update player score and return string saying player wins + ++playerscore
    else if (<) then update player score and return string saying player loses + ++computerscore
    else they are (===) then return string saying tie + score
Play 5 rounds:
    declare game winner when score === 5
    create a while loop that ends when playerscore or (||) computerscore === 5
    -->
