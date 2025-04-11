# FrogLang Keywords Documentation

Just the keywords and stuff if you dont know

## Keywords and Functions

### Variable Manipulation

- **jump**: 
  - Syntax: `jump varName = value`
  - Description: Assigns a numerical value to a variable.
  - Example: `jump pond1 = 10`

- **add**: 
  - Syntax: `add resultVar var1 var2`
  - Description: Adds two variables (or values) and stores the result in a new variable.
  - Example: `add result pond1 pond2`

- **subtract**: 
  - Syntax: `subtract resultVar var1 var2`
  - Description: Subtracts the second variable from the first and stores the result.
  - Example: `subtract result pond1 5`

- **multiply**: 
  - Syntax: `multiply resultVar var1 var2`
  - Description: Multiplies two variables and stores the result.
  - Example: `multiply result pond1 pond2`

- **divide**: 
  - Syntax: `divide resultVar var1 var2`
  - Description: Divides the first variable by the second (checks for division by zero).
  - Example: `divide result pond2 pond1`

- **print**: 
  - Syntax: `print varName`
  - Description: Outputs the value of the specified variable to the console.
  - Example: `print result`

### Froggy Fun Functions

- **ribbit**: 
  - Syntax: `ribbit count`
  - Description: Outputs "ribbit" a specified number of times.
  - Example: `ribbit 3` results in "ribbit ribbit ribbit"

- **frogLuck**: 
  - Syntax: `frogLuck`
  - Description: Generates and outputs a random lucky number between 1 and 6.
  - Example: `frogLuck`

- **frogScream**: 
  - Syntax: `frogScream message`
  - Description: Outputs a message in uppercase, simulating a frog's scream.
  - Example: `frogScream Jump higher, frogs!`

### Advanced Features

- **frogDoubleJump**: 
  - Syntax: `frogDoubleJump varName = value`
  - Description: Stores double the provided value in the given variable.
  - Example: `frogDoubleJump newVar = pond1`

- **max**: 
  - Syntax: `max resultVar var1 var2`
  - Description: Finds the maximum of two variables.
  - Example: `max maxResult pond1 pond2`

- **min**: 
  - Syntax: `min resultVar var1 var2`
  - Description: Finds the minimum of two variables.
  - Example: `min minResult pond1 pond2`

## Additional Notes

- Variable names must start with a letter and can include letters, digits, and underscores (_).
- Comments can be added using the `#` symbol. Everything written after `#` on the same line.
