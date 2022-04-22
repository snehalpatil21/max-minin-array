# max-minin-array
Using System;
Namespace CSharp_Shell
{
    Public static class Program 
    {
        Public static void Main() 
        {
           Int [] a={12,34,56,78,89};
           Int I,max,min;
           Max=a[0];
           Min=a[0];
           For(i=1;i<5;i++)
           {
               If(a[i]>max)
           {
          	Max=a[i];
           }
           
           If(a[i]<min)
           {
          	Min=a[i];
           }
           }
           Console.WriteLine(“Maximum number:-“+max);
           Console.WriteLine(“Minimum number:-“+min);

        }
    }
}
