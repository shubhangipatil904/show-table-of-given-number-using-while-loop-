# show-table-of-given-number-using-while-loop-
using System;
namespace loop
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Enter a number: ");
            int a = (int)Convert.ToInt32(Console.ReadLine());
            int i = 1; //initialization
            while (i <= 10) //condition
            {
                Console.WriteLine(a + " * " + i + " = " + i*a);
                i++; //increment
            }
            Console.ReadLine();
        }
    }
}
