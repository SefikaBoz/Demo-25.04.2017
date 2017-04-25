# Demo-25.04.2017


namespace DemoCSharp1
{
    class ObjectDataType
    {
       public static void ObjectType()
        {
            object a;
            a = 5;
            Console.WriteLine(a.GetType());
            a = "ss";
            Console.WriteLine(a.GetType());
            a = 'l';
            Console.WriteLine(a.GetType());
            a = true;
            Console.WriteLine(a.GetType());
        }


    }
}
