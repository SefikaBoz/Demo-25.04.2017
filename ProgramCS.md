# Demo-25.04.2017

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace DemoCSharp1

{
    class Program
    {

        static void Main(string[] args)
        {

            //ConstTypeTest.ConstTypeTotal();
            //ConstTypeTest.ConstTypeEkstact();
            //ValueTypesWork.GetValueTypeResult();
            //ConstType.ConstTypeChangeShow();
            //ValueTypesWork.FirstValueAssigment();
            //ValueTypesWork.WriteBoolType();
            //ValueTypesWork.WriteCharType();
            //ReferanceType.ShowReferanceTypeObject();

            //GetResultReferansType();

            //TransformationType.Transform();

            //TransformationType.Transformation();
            //TransformationType.ExpTransformation();

            TransformationType.ComplexTransform();
         
            // ConsciousTransformType.ConsciousTransform();

            //Boxing.ToBoxing();

            Console.WriteLine();

            ReferanceType obj = new ReferanceType();
            obj.Square(5);
            obj.WriteResult();

            ReferanceType newObj = obj; ;
            newObj.WriteResult();
            obj.Square(6);
            obj.WriteResult();
            newObj.WriteResult();

            /////////////////////////////

            ReferanceType rTypeObject = new ReferanceType();
            rTypeObject.num1 = 10;
            
            ReferanceType rNewObject = rTypeObject;
            rTypeObject.num1 = 8;
            
            Console.WriteLine("rTypeObject : " + rTypeObject.num1);
            Console.WriteLine("rTypeObject : " + rNewObject.num1);

            ReferanceType str1 = new ReferanceType();
            str1.str = "neriman";


            ReferanceType str2 = str1;
            str2.str = "ayse";
            str1.str = "fevzi";


            Console.WriteLine("rTypeObject : " + str1.str);
            Console.WriteLine("rTypeObject : " + str2.str);

            Console.ReadKey();
        }

    }
}
