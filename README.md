// Напишите цикл, который принимает на вход два числа (A и B) и возводит число A в натуральную степень B.
//3, 5 -> 243 (3⁵)
//2, 4 -> 16

void Vozvedenie(double a, double b)

{

    double c = Math.Pow(a,b);
    
    Console.WriteLine(c);
    
}

Console.WriteLine("Введите число: ");

double a = Convert.ToDouble(Console.ReadLine());

Console.WriteLine("Введите степень, в которую нужно возвести число: ");

double b = Convert.ToDouble(Console.ReadLine());

Vozvedenie(a, b);
