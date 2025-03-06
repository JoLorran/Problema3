using System;

class Program
{
    static void Main()
    {
        // Lendo os dois valores inteiros
        Console.WriteLine("Digite o primeiro valor:");
        int A = int.Parse(Console.ReadLine());
        Console.WriteLine("Digite o segundo valor:");
        int B = int.Parse(Console.ReadLine());
        // Calculando a soma
        int SOMA = A + B;
        // Imprimindo o resultado conforme o formato exigido
        Console.WriteLine($"SOMA = {SOMA}");
    }
}
