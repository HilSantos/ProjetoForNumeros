# ProjetoForNumeros
Exercicios dia 25/10/24

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ProjetoForNumeros
{
    public class Program
    {
        static void Main(string[] args)
        {
            /*Solicite e receba um numero inteiro e exiba os proximos 20 numeros
             * a partir do valor que o usuario escolher.
            */

Console.WriteLine("Informe o numero: ");
            int numero = Convert.ToInt32(Console.ReadLine());

for (int i = 1; i <= 20; i++)
                
{
                numero += 1; 
                Console.WriteLine("Numero: " + numero);
            }

Console.ReadKey();
        }
    }
}
