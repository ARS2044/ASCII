# ASCII
Code


using System;
using System.Text;

namespace codigo_ascii
{
    class Program
    {
        static void Main(string[] args)
        {
            
            Console.WriteLine("Dame letra o número");
            var str0 = Console.ReadLine();            
            Console.WriteLine(Encoding.ASCII.GetBytes(str0.ToString())[0]);

            Console.WriteLine("Dame código ASCII");
            int int0 = int.Parse(Console.ReadLine());
            Console.WriteLine((char)(int0));

            Console.WriteLine("Presiona tecla para terminar...");
            Console.ReadLine();

        }
    }
}

