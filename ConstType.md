# Demo-25.04.2017
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace DemoCSharp1
{
    class ConstTypeTest
    {
        public static int ConstTypeTotal()
        {
            const int a = 3, b = 5;
            const int v = a + b;
            return v;
        } 
        public static void ConstTypeEkstact()
        {
            const int num1 = 20;
            int num2 = num1 - 15;
            int num =num1 - num2;
            // num1 = 15; // error
            Console.WriteLine(num);
        }
    }
}
