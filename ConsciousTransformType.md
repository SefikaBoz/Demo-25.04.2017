# Demo-25.04.2017

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace DemoCSharp1
{
    class ConsciousTransformType
    {
        public static void ConsciousTransform()
        {
            int num = 12;
            string value = num.ToString();
            int i = 256;
            byte b;
            byte c;
            checked
            {
                b = (byte)i;
                unchecked
                {
                    c = (byte)i; // Burayı kontrol etmez
                }
            }
            Console.WriteLine(b);
        }
  
    }
}
