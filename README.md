# PATrilhasAtiv01
a) using System;

namespace CLASS
{
	class Program
	{
		public static void Main()
		{
			Console.WriteLine("digite um numero inteiro:  ");
			
			int numero = int.Parse(Console.ReadLine());
			
			Console.WriteLine("Você digitou: " + numero);
			
			Console.ReadKey(true);
		
			
		}
	}
}

b)

using System;

namespace CLASS
{
	class Program
	{
		public static void Main()
		{
			Console.Write("digite um numero real:  ");
			
			 double numero = Convert.ToDouble(Console.ReadLine());
			
			Console.WriteLine("o valor digitado foi digitou: " + numero);
			
			Console.ReadKey(true);



  c) 


  using System;

namespace CLASS
{
	class Program
	{
		public static void Main()
		{
			Console.Write("Digite um número de ponto flutuante:  ");
			
			 float numero = float.Parse(Console.ReadLine());
			
			 Console.WriteLine("O valor digitado foi: " + numero);
			
			Console.ReadKey(true);
		
			
		}
	}
}
