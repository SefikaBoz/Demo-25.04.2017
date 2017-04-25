# Demo-25.04.2017
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace DemoCSharp1
{
    public class ValueTypesWork
    {
        public static void GetValueTypeResult()
        {
            int a = 3;
            int b;
            b = a;
            a = 10;
            b = a;
            Console.WriteLine("a' s new value :" + b);
        }
        public static void ShowValue()
        {
            int numA = new int();        
            Console.WriteLine("num1' s  value :" + numA);
            int numB = new int();
            numB = 21;
            Console.WriteLine("B nin degeri :" + numB);
        }
      public static void FirstValueAssigment()
        {
            int numA = new int();
            Console.WriteLine("İnt tipinde default ilk değer : " + numA);
           
            bool constructureValue = new bool ();
            Console.WriteLine("Bool tipinde ilk değer ataması: " + constructureValue);
            // bool nonConstructureValue;
            // Console.WriteLine("..........." + nonConstructureValue); // unassigned !
            float testFloatNum = new float();
            Console.WriteLine(testFloatNum);
        }
        public static void ByteType()
        {
            // byte byteNum = 256; // error
            //byteNum2 = -65; // error
            byte byteNum2 = 255;
            
        }
        public static void SByteType()
        {
            sbyte sByteNum = -128;
            sbyte SbyteNum = 127;
           // sbyte sByteNum = -129; error
           // sbyte sbyteNum =128;error
        }
        public static void ShortType()
        {
            short shortValue = 32767;
            short shorValue = -32768;
          // short shortValue = 32768; error
          // short shorValue = -32769; error
        }
        public static void FloatAndLongType()
        {
            float floatValue = 3.45F; //32 bit signed (if we do not F -get compiler error 
            long longValue = -32768; // 64 bit signed
            double doubleValue = 5.45; // 64 bit signed
            // short shortValue = 32768; error
            // short shorValue = -32769; error
        }
        public static void WriteBoolType()
        {
            int a = 20;
            bool b3 = a < 60;
            Console.WriteLine(b3);
            if (b3)
            {
                Console.WriteLine("B3  : true " );
               
            }else
                Console.WriteLine("B3  false" );
        }

        public static void WriteCharType()
        {
            char c1 = new char();
            Console.WriteLine(c1);
            char c2 = (char)90;
            char c3 = (char)112;
            char c4 = 'f';
            char c5 = '\u0057';
            char c6 = '\u0052';

            Console.WriteLine(c1);
            Console.WriteLine(c2);
            Console.WriteLine(c3);
            Console.WriteLine(c1 +c2 + c3 +c4  +"");
            Console.WriteLine("" + c1 + c2 + c3 + c4);
            Console.WriteLine(c2 + c3);
            Console.WriteLine(c5);
            Console.WriteLine(c6);
        }


    }
}
