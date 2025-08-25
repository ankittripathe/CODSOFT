# Documentation
- Select the Elements by using getElementById or querySelectorAll.
- Create a variable to Display Output:- CurrentDisplay.
- Apply forEach loop in the buttons.
- Apply addEventListener in Each of the button:- (eachBtn) you can give any name inside it like 
value, elements for Better underStanding I give (eachBtn).
- Now we can print in console browser to see the target Element:- console.log(evt.target.innerHTML)
- storing (evt.target.innerHTML) to new variable for better understanding.
- Now using if(){}, else{} we can check the target Elements or output.
- If (buttonText === "AC") this condition occur then we have to change the currentDisplay = '' empty string. And finally to show the output we have to select storeInput.value = currentDisplay;
- If (buttonText === "DEL") then currentDisplay = currentDisplay.slice(0, -1); delete one Element
- If (buttonText === "=") this => then we have to use js eval() function for showing output means 
Evaluate krega. There will be the possibility of error so we can put this in try (), catch() block
- Append the button's text to the expression for others

