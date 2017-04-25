# Demo-25.04.2017
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace DemoCSharp1
{
    class TransformationType
    {
        //implicitly Convert type
        public static void Transform()
        {
            int num = 20;
            float num2 = num;
            Console.WriteLine(num2);

            int number  = 25;
            long number2 = number;
            Console.WriteLine("Num j " + number2);

            //int no = 25;  error!
            //short no2 = no;
            //Console.WriteLine("Num j " + no2);
        }

        public static void Test()
        {
            string str = "12.56";
            int num = 7;
            float num2 = num;
            int i = Convert.ToInt32(str);
            double d = Convert.ToDouble(str);


        }

        public static void Transformation()
        {
            char m = 'c';
            decimal d = m;
            Console.WriteLine(d);
        }

        public static void ExpTransformation()
        {
            int i = 20;
            byte b = 30;
            short s = 10;
            double total = i + b + s;
            Console.WriteLine(total);
        }

        public static void ByteTransformation()
        {
            byte num1 = 45;
            byte num2 = 10;
            //  byte num3 = num1 + num2; error:  can not implicitly convert type int to byte
            int num3 = num1 + num2;
            Console.WriteLine(num3);
        }

        public static void ComplexTransform()
        {
            int c = 'f';
            // Console.WriteLine("C icin implicitly Convert type : " +  c);


            // Nullable<int> h = null;
            int h = 89;
            byte a = (byte)h;
            Console.WriteLine(" a : " + a);
            
            byte g = 12;
            g = (byte)h;

            int value1 = 14;
            byte value2 = 5;
            value1 = Convert.ToInt32(value2);
            Console.WriteLine(value1);

            short val1  = 8;
            byte val2 = 7;
            val1 = (short)val2;
            
        }

    }
}
