---
# Node.js CLI Calculator  

A simple command-line interface (CLI) calculator built with Node.js. This tool performs basic arithmetic operations like addition, subtraction, multiplication, and division directly from your terminal.  

## Features  
- Perform basic arithmetic operations:  
  - Addition  
  - Subtraction  
  - Multiplication  
  - Division  
- Easy-to-use CLI interface.  

## Prerequisites  
- [Node.js](https://nodejs.org/) installed on your system.  

## Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/aniquatasnim/node_cli_calculator.git
   cd node-cli-calculator  
   ```  
2. Install dependencies (if any):  
   ```bash  
   npm install  
   ```  

## Usage  
Run the calculator in your terminal using the following command:  
```bash  
node calculator.js <operation> <number1> <number2>  
```  

### Examples  
1. **Addition**:  
   ```bash  
   node calculator.js add 5 3  
   ```  
   Output: `8`  

2. **Subtraction**:  
   ```bash  
   node calculator.js subtract 10 4  
   ```  
   Output: `6`  

3. **Multiplication**:  
   ```bash  
   node calculator.js multiply 6 7  
   ```  
   Output: `42`  

4. **Division**:  
   ```bash  
   node calculator.js divide 20 4  
   ```  
   Output: `5`  

## Supported Operations  
- `add` or `+`: Adds two numbers.  
- `subtract` or `-`: Subtracts the second number from the first.  
- `multiply` or `*`: Multiplies two numbers.  
- `divide` or `/`: Divides the first number by the second.  

## Error Handling  
- Ensures valid input is provided.  
- Displays an error message if invalid operations or arguments are passed.  
