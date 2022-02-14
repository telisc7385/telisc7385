1.	Write a program to print “Teach One, Each One, Tree One” given number of times.
        =>
                 
Using System;

Namespace HelloWorld
{
  Class Program
  {
    Static void Main(string[] args)
    {
      Console.WriteLine(“Enter The Word “);    
      String name=Console.ReadLine();
      Console.WriteLine(“How Many Times”);
      Int n=Convert.ToInt32(Console.ReadLine());
      For(int i=1;i<=n;i++)
      {
         Console.WriteLine(“\n”+name);
      }     
    }
  }
}

