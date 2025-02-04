# Task-1-C-

Console.InputEncoding = System.Text.Encoding.GetEncoding("UTF-16"); // Это взял с хабра когда пытался понять почему кирилицу не принимает https://qna.habr.com/q/1160590
Console.WriteLine("Как вас зовут?");
string a = Console.ReadLine();
Console.WriteLine("Какая ваша фамилия?");
string b = Console.ReadLine();
Console.WriteLine("Введите День Вашего Рождения");
string c = Console.ReadLine();
int d = Convert.ToInt32(c);
Console.WriteLine("Введите номер месяца вашего Рождения");
string x = Console.ReadLine();
int m = Convert.ToInt32(x);
Console.WriteLine($"Вас зовут: {a}");
Console.WriteLine($"Ваша Фамилия: {b}");
if ((m == 1 && d <= 20 && d > 0) || (m == 12 && d > 21 && d < 32))
{
    Console.WriteLine("Вы Козерог");
}
else if ((m == 1 && d > 20 && d < 32) || (m == 2 && d <= 20 && d > 0))
{
    Console.WriteLine("Вы Водолей");
}
else if ((m == 2 && d > 20 && d < 30) || (m == 3 && d <= 20 && d > 0))
{
    Console.WriteLine("Вы Рыбы");
}
else if ((m == 3 && d > 20 && d < 32) || (m == 4 && d <= 20 && d > 0))
{
    Console.WriteLine("Вы Овен");
}
else if ((m == 4 && d > 20 && d < 31) || (m == 5 && d <= 20 && d > 0))
{
    Console.WriteLine("Вы Телец");
}
else if ((m == 5 && d > 20 && d < 32) || (m == 6 && d <= 21 && d > 0))
{
    Console.WriteLine("Вы Близнецы");
}
else if ((m == 6 && d > 21 && d < 31) || (m == 7 && d <= 22 && d > 0))
{
    Console.WriteLine("Вы Рак");
}
else if ((m == 7 && d > 22 && d < 32) || (m == 8 && d <= 23 && d > 0))
{
    Console.WriteLine("Вы Лев");
}
else if ((m == 8 && d > 23 && d < 32) || (m == 9 && d <= 23 && d > 0))
{
    Console.WriteLine("Вы Дева");
}
else if ((m == 9 && d > 23 && d < 31) || (m == 10 && d <= 23 && d > 0))
{
    Console.WriteLine("Вы Весы");
}
else if ((m == 10 && d > 23 && d < 32) || (m == 11 && d <= 22 && d > 0))
{
    Console.WriteLine("Вы Скорпион");
}
else if ((m == 11 && d > 22 && d < 31) || (m == 12 && d <= 21 && d > 0))
{
    Console.WriteLine("Вы Стрелец");
}
else
{
    Console.WriteLine("Данные о вашем дне рождения введены неправильно повторите попытку");
}
