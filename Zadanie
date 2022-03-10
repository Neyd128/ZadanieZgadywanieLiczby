using System;

namespace zadanie
{
    class Program
    {
        static void Main(string[] args)
        {
            bool correctAnswer = false;
            int correctNumber = new Random().Next(1, 11);


            Console.WriteLine("Zgadnij wylosowaną liczbę z przedziału od 1 do 10.");

            do
            {
                bool isNumber = int.TryParse(Console.ReadLine(), out int userInput);

                if (!isNumber)
                {
                     Console.WriteLine("Wprowadź liczbę");

                    continue;
                }

                if (userInput < 1 || userInput > 10)
                {
                    Console.WriteLine("Wprowadź liczbę od 1 do 10");

                    continue;
                }

                if (userInput < correctNumber)
                {
                    Console.WriteLine("Liczba jest za mała");

                }
                else if (userInput > correctNumber)
                {
                    Console.WriteLine("Liczba jest za duża");

                }
                else
                {
                    Console.WriteLine("Gratulacje użytkowniku");

                    correctAnswer = true;
                }

            } while (!correctAnswer);
        }

        
    }
}
