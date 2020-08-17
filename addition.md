# Addition

Scenario: Add two numbers
  
  Given I have two numbers

  When I enter number1, press + button, enter number2 and then press = button
  
  Then I see <added-sum> as the result
