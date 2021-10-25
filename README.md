# askerusing System;
namespace zamt
{
    class AskMain
    {
        static void Main(string[] args)
        {
            ask1 m = new ask1();
            ask1.Animals();
            ask2 n = new ask2();
            ask2.insects();
            ask3 e = new ask3();
            ask3.fish();
        }
    }
    class Parents
    {
        public static void Animals()
        {
            Console.Write("общее у животных:");
            string s = Console.ReadLine();
            Console.WriteLine($" :{s}");
            Console.ReadKey();
           
        }
        public static void insects()
        {
            Console.WriteLine("особенность: хитиновый скелет");
            Console.WriteLine("особенность: крылья");
            Console.WriteLine("особенность: трахейное дыхание");
            
        }
        public static void fish()
        {
            Console.WriteLine("\nособенность: Кожа рыб покрыта чешуёй");
            Console.WriteLine("особенность: наличие жабр");
            Console.WriteLine("особенность: имеют хрящевой скелет");
           
        }
    }
    class ask1 : Parents
    {         

    }
    class ask2 : Parents
    {
           
    }
    class ask3 : Parents
    {

    }
}
