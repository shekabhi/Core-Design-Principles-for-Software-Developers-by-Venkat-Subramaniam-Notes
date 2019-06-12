# Core-Design-Principles-for-Software-Developers-by-Venkat-Subramaniam-Notes

- ##  What is Good Design ?
          A Good Design is design which is easier to change .
          All most imposible to get a good design at first time .
          Software is never written , it is allways rewritten . 
          
- ##  How to create good design ?
          Take a time to review design and code.
          Simplicity (Simple keep you focussed) .

- ##  Software Complexity
          Inherent complexity and Accidental complexity .
          A good design is the one that hides inherent complexity and eliminates the accidental complexity .
          
- ## Cost of Implementing
          1 . if cost of implementing now  > cost of implementing later then POSTPONE it .
          2 . if cost of implementing now == cost of implementing later then POSTPONE it .
          3 . if cost of implementing now  < cost of implementing later then 
              How is it Protable ?
                  if High -> Do it now .
                  if low -> POSTPONE it .
                  
- ## Cohesive and Coupling
          A Good Design has high cohesition and low coupling.
          Cohesive : Like things are stay together and Unlike are far away .
                     If a code is cohesive , it has to change less frequently .
          Coupling : Degree of connecting amonge things .
                     Depending on a class is tight coupling.
                     Depending on a interface is loose coupling.
          
- ## DRY
          Don't Repeat Yourself
          Don't duplicate code and effort
- ## SLAP
          Single level Abstract Princple
          Focus on Single level of Abstraction

- ## Comments
          Don't Comment What , Instead Comment Why .
          
- ## OCP (Open Closed Princple)
          Software modules should be open for Extension but closed from Modification .
       
- ## LSP (Liskov's Substitution Principle)
          Inheritance should be used for substitutability .
          If an object of "B" should be used anywhere an object of "A" is used then use Inheritance .
          If an object of "B" should use an object of "A" , then use Composition or Delegation .
          Inheritance demands more from developer than Composition or Delegation .
         
- ## DIP (Dependency Inversion Princple)
          A class should not depend on another class , they both have to depend on an abstraction(interface).
          
