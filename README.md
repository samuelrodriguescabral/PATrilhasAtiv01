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

D)
using System;

namespace class
{
    class Program
    {
        public static void Main(string[] args)
        {
            Console.Write("Digite 'sim' ou 'não': ");
            
            string resposta = Console.ReadLine();
            
            bool respostaBool = resposta.ToLower() == "sim";
            
            Console.WriteLine("O valor da variável booleana é: " + respostaBool);
            
            Console.Write("Press any key to continue . . . ");
            Console.ReadKey(true);
        }
    }
}   


e)
using System;
namespace CLASS
{
	class Program
	{
		public static void Main(string[] args)
		{
			char palavra;
			Console.WriteLine("Escreva uma letra:");
			palavra = Convert.ToChar(Console.ReadLine());
			Console.WriteLine("A letra escolida foi: " + palavra);
			
			Console.WriteLine("Presione algo para sair . . . ");
			Console.ReadKey(true);
		}
	}
}
















f)
using System;
namespace class
{
	class Program
	{
		public static void Main(string[] args)
		{
			decimal numero;
			Console.WriteLine("Escreva um número decimal: ");
			numero = Convert.ToDecimal(Console.ReadLine());
			Console.WriteLine("O número decimal é: " + numero);
			
			Console.WriteLine("Presione algo para sair . . . ");
			Console.ReadKey(true);
		}
	}
}








g)

using System;
namespace CLASS
{
	class Program
	{
		public static void Main(string[] args)
		{
			string nome;
			int idade;
			Console.WriteLine("Informe seu nome:");
			nome = Console.ReadLine();
			Console.WriteLine("Informe sua idade:");
			idade = Convert.ToInt32(Console.ReadLine());
			Console.WriteLine("Seu nome é:" + nome );
			Console.WriteLine("Sua idade é: " + idade);
			
			Console.WriteLine("Presione algo para sair . . . ");
			Console.ReadKey(true);
		}
	}
}









h)



using System;
namespace CLASS
{
	class Program
	{
		public static void Main(string[] args)
		{
			float preco;
			float resutado;
			float desc;
			Console.WriteLine("Informe o valor do produto:");
			preco = float.Parse(Console.ReadLine());
			Console.WriteLine ("Informe o desconto:");
			desc = Convert.ToInt32(Console.ReadLine());
			resutado = preco - (preco*(desc /100));
			Console.WriteLine("O preço da sua compra deu: " + resutado);
			
			
			Console.WriteLine("Presione algo para sair . . . ");
			Console.ReadKey(true);
		}
	}
}

i)

using System;
namespace CLASS
{
	class Program
	{
		public static void Main(string[] args)
		{
			string palavra;
			Console.WriteLine("Escreva uma palavra:");
			palavra  = Console.ReadLine();
			Console.WriteLine("A palavra tem: " + palavra.Length + " caracteres");
			
			
			Console.WriteLine("Presione algo para sair . . . ");
			Console.ReadKey(true);
		}
	}
}





j)

Console.WriteLine("Informe sua rua:");
			string rua = Console.ReadLine();
			Console.WriteLine("Digite o número da residencia:");
			int num = Convert.ToInt32(Console.ReadLine());
			string num = Convert.ToString(Console.ReadLine());
			Console.WriteLine("Digite seu bairro:");
			string bairro = Console.ReadLine();
			Console.WriteLine("Digite sua cidade:");
