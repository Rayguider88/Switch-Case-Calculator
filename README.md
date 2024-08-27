# Switch-Case-Calculator
A program that mimics a calculator, using the switch statement and a while loop to choose between various operators to perform calculations. 

#include <iostream>
using namespace std;

//Compiler version g++ 6.3.0

int main()
{
  //A calculator using the switch-case to calculate the results of three operands, seperated by spaces
  //It performs Addition, Subtraction, Multiplication, and Division
  char op{};
  double num1, num2, num3;
  int result;
  
    cout << "Choose your operator: +, -, /, or *" << endl;
    cin >> op;
    
    cout << "Enter your three operands, seperated by a space: " << endl;
    cin >> num1 >> num2 >> num3;
    
   {
      
    switch (op) {
      
      while(op) !'default';
      
     {
      
      case '+':
        result = num1 + num2 + num3;
        cout << num1 << "+" << num2 << "+" << num3 << "is:" << result;
        break;
       
      case '-': 
        result = num1 - num2 - num3;
        cout << num1 << "-" << num2 << "-" << num3 << "is: " << result;
        break;
        
      case '*':
        result = num1 * num2 * num3;
        cout << num1 << "*" << num2 << "*" << num3 << "is: " << result;
        break;
        
      case '/':
        result = num1 / num2 / num3;
        cout << num1 << "/" << num2 << "/" << num3 << "is: " << result;
        break;
        
        default:
       
        cout << "You've chosen an operator that isn't numerical" << endl;
        cout << "Please try again " << endl;
        break;
      }
      
    }
    
   }
}
