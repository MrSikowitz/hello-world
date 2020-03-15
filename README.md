using System;

namespace MyFirstApp
{
    class Program
    {
        static void Main(string[] args)
        {
            int x; // здесь обявляется переменная
            int y; // здесь обявляется еще одна переменная
            int z; // очередная переменная
            int a; // снова...
            int f; // ...

            x = 100; // здесь переменной x присваивается значение 100

            Console.WriteLine("x содержит" + x);
            y = x / 2;
            Console.Write("y содержит x / 2: ");
            Console.WriteLine(y);
            z = x * y;
            Console.Write("z содержит x * y: ");
            Console.WriteLine(z);
            a = ((z - x) * y) / x;
            Console.Write("a содержит ((z - x) * y) / x: ");
            Console.WriteLine(a);
            f = ((z - a) * x / y + x) / z;
            Console.Write("a содержит ((z - x) * y) / x: ");
            Console.WriteLine(f);
            Console.ReadKey();
        }
    }
}
