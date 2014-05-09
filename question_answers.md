1-Which function is responsible for getting the name from the user?
A-GetPlayerName()
2-How will you ensure that the user is asked for the name repeatedly?
A-Using a while loop to ensure that if the answer is invalid, it will ask again with a message saying that last answer was invalid.
3-What additional variable will you need and what will its datatype be?

4-Which function is responsible for adding scores to the table?
A-UpdateRecentScores(RecentScores,Score)
5-What additional module will you need to import into the program?
A-date      from datetime import date
6-Identify the four functions that will require changes.
A-def __init__(self)  def GetChoiceFromUser    def DisplayRecentScores
7-How do you convert a string in the format DD/MM/YY (e.g. 14/08/93) to a date type in Python?
A-('%d/%m/%Y')
8- Describe each variable role in your own words with examples.
A-fixed value-- holds a value that doesn't change, eg: NoOfSwaps = 1000
stepper-- goes through a number of predicted values/implements by 1 every time, eg: Count, NoOfCardTurnedOver, NoOfSwapsMadeSoFar
most recent holder-- stores the latest value in a process, eg: Choice, LineFromFile, LastCard
most wanted holder-- stores the most appropriate value for the program/ holds the value the program wants, eg: NextCard
gatherer-- gathers the total of values so far, no examples
transformation-- gets its value from other variables, eg: Higher, FoundSpace
follower-- the value of this is one of another one's old one, eg: LastCard
temporary-- holds value for a short time/ used as an intermediate, eg: SwapSpace
9-difference between passing by value and passing by reference.
A-the variable uses a reference to the same memory location and is passed as a parameter 
the value is copied to the parameter
pass by value: creates a copy of original value
RankNo,SuitNo
pass by reference:
ThisCard, 
10-Where would be a good place in the program to keep track of whether the ace is high or not?Remember that the
  aces' value will be set before a game is started and it will not change for the duration of the game.
A-global AceRank   
11-Name the function that will need to be altered so that 5. Options is part of the main menu.
DisplayMenu
12-Name the function that will need to be modified so that card value comparisons will work correctly now that aces can be either high or low.
GetRank(RankNo)
13- pseudo code for the options code.
FUNCTION DisplayOptions
	OUTPUT "OPTION MENU"
	OUTPUT " "
	OUTPUT "1.Set Ace to be high or low"
	OUTPUT " "
	
FUNCTION GetOptionChoice
	OptionChoice <- OUTPUT "Select an option from the menu (or enter q to quit): "
	RETURN OptionChoice
	
FUNCTION SetOptions(OptionChoice)
	Valid = FALSE
	IF OptionChoice="1" THEN
		SetAceHighOrLow
		Valid= TRUE
	ELSE IF OptionChoice= "q" Then
		Valid=True
	ELSE
		Valid=False




