int[] par = new int[10];
int[] impar = new int[10];
int numero;
for (int i = 0; i < 10; i++)
{
    Console.WriteLine("Informe o {0}° número, i + 1");
    numero = Convert.ToInt16(Console.ReadLine());
    if (numero % 2 == 0)
    {
        par[i] = numero;
    }
    else
    {
        impar[i] = numero;
    }

}
Console.WriteLine("Os números pares são :");
for(int i = 0; i < 10; i++)
{
    Console.WriteLine(par[i])
        ;
}
