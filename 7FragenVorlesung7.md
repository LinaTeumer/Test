**1. Die Konsole als Ausgabegerät kann in C# nicht angepasst werden?**

  [()] wahr  
  [(X)] falsch

**2. Welche Methoden kann man z.B. auf der Konsole schreiben?**

  [(X)] System.Console.Write  
  [()] Console.Write (ohne das vorher im Programm etwas ergänzt werden muss)  
  [()] Console.PrintOut  
  [(X)] System.Console.WriteLine  
  [()] System.Console.PrintOut  
  [[?]] Gerne auch mal ausprobieren und dann erst lösen  
*************************************************************************   
{{1}}
Console.WriteLine beendet die Zeile mit einem Zeilenumbruch  
Console.Write nicht
**************************************************************************

**3. Für was braucht man try und catch?**
  [(x)] Um Exceptions abzufangen  
  [()] Um ein Programm mehrmals mit hintereinander mit verschiedenen Werten durchlaufen zu lassen  
  [()] Um Anzahl an Durchläufen in einer Schleife zu zählen  

**4. Was für eine Ausgabe erzeugt dieses Programm? (In der "Deutschen" Variante)**  
```C#
using System;
namespace HelloWorld
{
    class Program
    {
        static void Main()
        {
            var n = 0.36789;
            Console.WriteLine($"{ n, 3 :p}");
        }
    }
}
```
[[36,79%]]  
[[?]] Komma statt Punkt  
[[?]] Hinten %  

**5. Was ändert ein $ im Ausdruck Console.Write($"blabla {var1} blabla \n")?** 
  [()] ergänzt einen Zeilenumbruch am Anfang  
  [()] entfernt den Zeilenumbruch am Ende  
  [(X)] ohne diese könnte var1 nicht direkt in den {} stehen  
  [()] $ ändert den Cultural Ausdruck auf English  

**6. Nur bei der Eingabe kümmert sich das Programm alleine um Exceptions.**  
  [()] wahr  
  [(x)] falsch  
 ***************************************************  
 {{1}}    
 Das Programm kümmert sich nie alleine um die Exceptions  
 ****************************************************

**7. Da ein Int? den Wert NULL annehmen kann, führt eine Division durch 0 nie zu einer Exception.**    
  [(X)] falsch  
  [()] wahr
