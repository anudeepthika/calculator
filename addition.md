# Addition

Scenario: Add two numbers
  
  Given I have two numbers

  When I enter "number1"
  And press "+" button
  And enter "number2"
  And then press "=" button
  
  Then I see added sum as the result
