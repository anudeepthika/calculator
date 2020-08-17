# Addition

Scenario: Add two numbers
  
  Given I have two numbers

  When I enter <number1> and press <+> button and then enter <number2> and press <=> button
  
  Then I see <added-sum> as the result
