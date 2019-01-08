# COWBOY1
             static void Main(string[] args)
        {
            Console.WriteLine("Введите число");
            string number = Console.ReadLine();
            int a;
            bool parsed = Int32.TryParse(number, out a);


           
            if (a <= 10)
            {
                int b = ++a;
                Console.WriteLine(b);
                Console.WriteLine("Была произведена операция инкремента");


            }
            else
                Console.WriteLine("Число должно быть меньше,или равняться 10");


            Console.ReadLine();

        }
    }
