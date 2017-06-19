using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Edno
{
    class Program
    {
        static void Main(string[] args)
        {
            double x1 = int.Parse(Console.ReadLine());
            double y1 = int.Parse(Console.ReadLine());
            double x2 = int.Parse(Console.ReadLine());
            double y2 = int.Parse(Console.ReadLine());
            double x3 = int.Parse(Console.ReadLine());
            double y3 = int.Parse(Console.ReadLine());

            double sideA = Math.Abs(x3 - x2);
            double h = Math.Abs(y1 - y2);
            
            double s = (sideA * h) / 2;

            Console.WriteLine(s);
        }
    }
}
