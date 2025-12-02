# Домаћи задатак из Техничке документације
## Задатак 
Напиши програм који на основу унете висине једнакостраничног троугла а израчунава површину П

$P = \frac{a^2 \cdot \sqrt{3}}{3}$

### Алгоритамска шема

![Алгоритамско решење](Main.png)

## Решење 

''' 
using System;

namespace PovrsinaTrougla
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Unesi visinu jednakostranicnog trougla a:");
            double.TryParse(Console.ReadLine(), out double a);
            double P = (a * a * Math.Sqrt(3)) / 3;
            Console.WriteLine("Povrsina trougla je " + P);
        }
    }
}
'''
