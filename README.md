using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace project   
{
   /// <summary>
   /// c#语法学习笔记
   /// </summary>
    class Program
    {
        static void Main(string[] args)
        {
            var person = new Person(5);
            Console.WriteLine(person.getGetAge());
            Console.WriteLine(Person.getFive());
            Console.ReadKey();                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  
        }
    }
    class Person
    {
        int age;
        public Person(int myage)
        {
            age = myage;
        }
        public int getGetAge()
        {
            return age;
        }
        public static int getFive()
        {
            return 100;
        }

    }


}

