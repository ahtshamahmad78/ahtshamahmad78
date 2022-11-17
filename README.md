- 👋 Hi, I’m @ahtshamahmad78
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp11
{
    class Program
    {
        static void Main(string[] args)
        {
         
            double  num1, num2;
            double result;
            Console.WriteLine("Enter operations \n" + "\n Enter " + "\n for subtraction  1 " + " \n for addition 2 " + "\n for division 3 "+ "\n for multiplication 4"+ "\n for square 5 "+ "\n for square root 6" +" \n for models 7");
            int opr = Convert.ToInt32(Console.ReadLine());
            if ((opr == 1 || (opr == 2) || (opr == 3) || (opr == 4)))
            {

                Console.WriteLine("Enter 1st number ");
                num1 = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine("Enter 2nd number ");
                num2 = Convert.ToInt32(Console.ReadLine());
                if (opr == 1)
                {
                    result = num1 - num2;
                    Console.WriteLine("Subtraction is " + result);
                }
                else if (opr == 2)
                {
                    result = num1 + num2;
                    Console.WriteLine("Adittion is " + result);
                }
                else if (opr == 3)
                {
                    result = num1 / num2;
                    Console.WriteLine(" Division is " + result);
                }
                else if (opr == 4)
                {
                    result = num1 * num2;
                    Console.WriteLine("Multiply is " + result);
                }
            }

            else if (opr == 5)
            {
                Console.WriteLine("Enter number");
                num1 = Convert.ToInt32(Console.ReadLine());
                result = num1 * num1;
                Console.WriteLine("Square is " + result);
            }
            else if (opr == 6)
            {
                Console.WriteLine("Enter number");
                num1 = Convert.ToInt32(Console.ReadLine());
                result = Math.Sqrt(num1);
                Console.WriteLine("Sqaure root is " + result);
            }
            else if (opr == 7)
            {
                Console.WriteLine("enter number");
                num1 = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine("enter power");
                num2 = Convert.ToInt32(Console.ReadLine());
                result = Math.Pow(num1, num2);
            }
            else
            {
                Console.WriteLine("Invalid Selection");
            }
            Console.ReadLine();
        }
       

        }
    }



<!---
ahtshamahmad78/ahtshamahmad78 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
