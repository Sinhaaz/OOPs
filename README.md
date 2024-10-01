# Programming Structures

In programming languages there are basically two approaches : 
  -  POPs (Procedural Oriented Programming Structure)
  -  OOPs (Object Oriented Programming Structure)

## OOPs (Object Oriented Programming Structure)

OOPs stands on 4 pillars :
>- Polymorphism
>- Inheritance
>- Encapsulation
>- Data Abstraction

### 1. Polymorphism
**Poly means many and morphism means form**<br>
Same object having different behaivours.

**There are 2 types of Polymorphism:-**<br>
i. Compile time polymorphism<br>
ii. Runtime polymorphism

#### i. Compile Time Polymorphism
A polymorphism which exists at the time of compilation is called Compile Time Polymorphism

**Ex: Method Overloading**
- When a class contains more than one method with same name and different types and different number of parameters.
  -     int pol(int a)
  -     int pol(int a,int b)

#### ii. Runtime Polymorphism
A polymorphism which exists at the time of execution of program is called Runtime Polymorphism

**Ex: Method Overriding**
- Whenever we are writing method in the **super(base) and sub(derived)** class in such a way that the method name and parameter must be same called method overriding.
- It uses **extends** keyword in **derived** class.
- We can't perform method overriding without using **Inheritance.**
  -     class A{
            void show()
            {
              -----
              -----
            }
        }
        class B extends A{
            void show()
            {
              -----
              -----
            }
        }
<img src = "">

### 2. Inheritance
When we create a new class from existing class in such a way that the new class access all the features and properties of existing class called Inheritance.
- In java **extends** keyword is used to perform inheritance.
- It provides code reusability
- We can't access private members of class through inheritance.
- A subclass contains ll the features of super class. Therefore we should create the object of sub class(new class)
- **Method Overriding** only possible through inheritance.
  -     class A{                               // Base/Super class
            void show()
            {
              -----
              -----
            }
        }
        class B extends A{                     // Derived/Sub class
            void show()
            {
              -----
              -----
            }
        }
- **Object hamesha sub class ke banane chahiye, kyuki subclass mein saare properties hote h super class ke.**
<img src = "Types of Inheritance">

### 3. Encapsulation 
Encapsulation is a mechanism through which we can wrap the data members and member methods of class in a single unit is called Encapsulation.
- 
