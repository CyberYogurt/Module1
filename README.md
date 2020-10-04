# Module1
public class Mathematic
    {
        public static void Sum(double a, double b)
        {
            double sum = (a + b);
            Console.WriteLine("Сумма равняется: " + sum);
            Console.ReadLine();
        }
        public static void Min(double a, double b)
        {
            double min = (a - b);
            Console.WriteLine("Отнимание равняется: " + min);
            Console.ReadLine();
        }
        public static void Mult(double a, double b)
        {
            double mult = (a * b);
            Console.WriteLine("Умножение равняется: " + mult);
            Console.ReadLine();
        }
        public static void Del(double a, double b)
        {
            double del = (a / b);
            Console.WriteLine("Деление равняется: " + del);
            Console.ReadLine();
        }
        public static void CircR(double R)
        {
            double circR = (Math.PI * Math.Pow(R, 2));
            Console.WriteLine("Площадь круга равняется: " + circR);
            Console.ReadLine();
        }
        public static void CircD(double D)
        {
            double circD = (D / 2);
            Console.WriteLine("Площадь круга равняется: " + circD);
            Console.ReadLine();
        }
        public static void Paral(double a, double h)
        {
            double paral = (a * h);
            Console.WriteLine("Площадь параллелограма равняется: " + paral);
            Console.ReadLine();
        }
    }
    Это то, что внутри библиотеки.
