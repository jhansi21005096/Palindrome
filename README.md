# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
Step 1: Start

Step 2: Create a class and declare two variable with string datatype

Step 3: Loop over the entire string and reverse it

Step 4: Use if condition to check whether the string and the reversed string is equal or not

Step 5: print palindrome if it's equal else print not a palindrome.

Step 6: stop the program.


## Program:
Developed by:k.Jhansi
refno:212221230045

using System;

namespace palindrome

{

    class pali
    
    {
    
        static void Main(string[] args)
        
        {
        
            string str, rev = "";
            
            int n;
            
            Console.WriteLine("Enter a string");
            
            str = Console.ReadLine();
            
            n = str.Length - 1;
            
            for (int i = n; i >= 0; i--)
            
            {
            
                rev += str[i];
                
            }
            
            if (rev == str)
            
                Console.WriteLine("{0} is Palindrome", str);
                
            else
            
                Console.WriteLine("{0} is not Palindrome", str);

        }
        
    }
    
}

## Output:
![output](https://github.com/jhansi21005096/Palindrome/blob/main/c%23output1.png)
![output](https://github.com/jhansi21005096/Palindrome/blob/main/c%23output2.png)
## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
