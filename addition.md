# Addition

Scenario: Add two numbers
  
  Given I have a calculator that is turned on

  When I enter "first number"
  And press "+" button
  And enter "second number"
  And then press "=" button
  
  Then I see added sum as the result
