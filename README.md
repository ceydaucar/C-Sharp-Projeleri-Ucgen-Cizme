# C-Sharp-Projeleri-Ucgen-Cizme

Kullanıcıdan alınan boyut bilgisine göre console'a Üçgen çizen uygulamayı yazınız.

    using System;

    class Program {
    
      static void Main(string[] args)  {
      
        Console.WriteLine("üçgenin taban uzunluğunu girin:");
        int baseSide = int.Parse(Console.ReadLine());
        
        üçgen(baseSide);
        Console.ReadLine();
      
      }

      static void üçgen(int n)  {
        
        for (int i = 1; i <= n; i++)  {
          for (int j = 1; j <= i; j++)  {
            Console.Write("* ");
          }
          
          Console.WriteLine();
        
        }
      }
    }
