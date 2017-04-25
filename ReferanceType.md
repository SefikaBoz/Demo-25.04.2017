# Demo-25.04.2017

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace DemoCSharp1
{
    // object and string !!
    class ReferanceType
    {
        public int num1 { get; set; }
        public string str { get; set; }


        private int result = 0;
        public void Square(int num)
        {
            result = num * num;
        }
        public void WriteResult()
        {
            Console.WriteLine(result);
        }

        public static void ShowReferanceTypeObject()
        {
            object a = 5;
            object b = a;
            a = 20;
            Console.WriteLine(a);          
            Console.WriteLine(b);

            object m = new object();
            m = 5;
            object n = new object();
            n = m;
            m = 20;
            Console.WriteLine(m);
            Console.WriteLine(n);

        }
        public static void UseWayStringShow()
        {
            //Include special characters in string with escape(\) and @
            string way = "C:\\docs\\xxx\\";
            string way2 = "@C:\\docs\\xxx\\";
            Console.WriteLine(way);
            Console.WriteLine(way2);

            //string str2 = "Some sring characters : ' , / , # , \ "; escape error
            // Console.WriteLine("str2" + str2);

            string str = "Some sring characters : \' , \\ ";
            Console.WriteLine(str);
        }

        public void GetResultReferansType()
        {
           
        }
    }
}
