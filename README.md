# HomeworkStringsAndTextProcessing
Homework from course Advanced C#
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace StringsAndTextProcessing
{
    class ReverseString
    {
        static void Main()
        //Write a program that reads a string from the console, reverses it and prints the result back at the console.
        {
            string input = Console.ReadLine();
            char[] ch = input.ToCharArray();
            Array.Reverse(ch);
            for (int i = 0; i < ch.Length; i++)
            {
                Console.Write("{0}", ch[i]);
            }
            Console.WriteLine();
        }
    }
}
