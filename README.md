using System;
namespace CSharp_Shell
{
    public class stud
 {
 public string Class="sybca";
  public string name="harshu";
  }
 public class exam:stud
 {
  public string s1="c#";
   public string s2="audit";
   public string s3="Rdbms";
    }
   public class result:exam
   {
   public int sc=20;
  public int sa=30;
  public int sr=40;
 public static void Main(string [] args)
{
	result r= new result();
        Console.WriteLine(r.Class);
	Console.WriteLine(r.name);
	Console.WriteLine(r.s1);		
Console.WriteLine(r.s2);
	Console.WriteLine(r.s3);
         Console.WriteLine(r.sc);
	Console.WriteLine(r.sa);
          Console.WriteLine(r.sr);
	Console.ReadLine();
    }
    }
}
