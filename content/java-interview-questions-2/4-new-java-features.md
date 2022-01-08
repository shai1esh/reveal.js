## Question
# Which version of Java have you worked on ?
--
# Answer
- you can explain whatever java version you have used like java 8,9,10 or 11.
- out of these java 8 and java 11 are the long term support versions and most of the questions will be on these 2 versions.
---
    
# Can you explain new features of java 8 ?
--
# Answer
- Default and static methods in interface
- lambda and functional interfaces
- Stream API
- Collections improved
- Date time API is improved
- Java IO operations improved
---

# What is functional interface ?
--
# Answer
 - Functional interfaces are those which has only one abstract method but can have multiple implemented methods. 
 - It's also called as SAM(single abstract method). 
 - Functional interfaces enable the use of lambda expressions. 
 - We can use @FunctionalInterface annotation for these interfaces.
---

# Why were default methods added to the interface in Java 8?
--
# Answer
 -  Allows addition of new methods to old interfaces 
 - This prevents old implementations from breaking because of compiler errors due to unimplemented methods
 - Static methods are also same only thing you can not override that method so it kind of provide new feature 
---

# What are the two types of stream operators?
--
# Answer
 - Stream operations are typically divided into 2 parts
 - Intermediate operations returns only Stream object, while terminal operations returns some definite type of object.
   1) Intermediate operations     - filter(), map(), flatmap()
   2) Terminal operations         - anyMatch(), allMatch(), collect()
 
---

# Can you differentiate between sequential stream and parallel stream ?
--
# Answer
  - primary difference between these streams is that sequential stream processes the data in sequencial order while parallel stream processes data in random order. 
  - Parallel stream makes use of processor cores for processing the data, so parallel stream will work effectively when your machine has multiple cores.
  - Also you should use parallel stream when have very large data to process and tasks are independant.
---

# What is Optional and why do we need it ?
--
# Answer
  - Optional is new class introduced in Java8, it provides way to handle the nulls in program. 
  - As we are working on objects there is a chance that we could have null objects in our program, which causes NullPointerException as effect it will terminate the program. 
    This is big issue if it's production environment, to prevent these kind of incident Optional is introduced.
---

# What is the change in Date time APIs ?
--
# Answer
  - Old API was not a thread safe and has less operations. 
  - In Java 8 date time API we have multiple operations and flexibility, it also introduced the zoned date time.
---

# What is Lambda expression and why it's introduced ?
--
# Answer
- Lambda expression is a Java syntax that allows you to treat functionality as values, method arguments or data
- Enables us to pass code as values to methods and dynamically use them in the code
- Syntax shortcut for anonymous classes or inline class implementations
- Enables functional programming coding style in Java
---

# how do you break the forEach loop of stream ?
--
# Answer

---
# What is Predicate ?
--
# Answer

---

# What is Consumer function ?
--
# Answer

---