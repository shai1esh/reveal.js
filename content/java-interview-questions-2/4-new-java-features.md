## Question
# What is Spring?

--

# What is the interviewer looking for?
- Which version of Java have you worked on ?
    you can explain whatever java version you have used like java 8,9,10,11, out of these java 8 and java 11 are the long term support versions and most of the questions will be on these 2 versions.
    
- Can you explain new features of java 8 ?
    Default and static methods in interface
    lambda and functional interfaces
    Stream API
    Collections improved
    Date time API is improved
    Java IO operations improved

- What is functional interface ?
    functional interfaces are those which has only one abstract method but can have multiple implemented methods. it's also called as SAM(single abstract method). 
    functional interfaces enable the use of lambda expressions. we can use @FunctionalInterface annotation for these interfaces.

- Why the static or default methods in interface are introduced in Java 8 ?
    In the java old version there is a lot of use of interfaces, and to provide the backword compatibility for collections interfaces, defualt methods are introduced. Static methods are also same only thing you can not override that method so it kind of provide new feature 
    
- Can you explain few stream operations ?
    Stream operations are typically divided into 2 parts,  
    1) Intermediate     - filter(), map(), flatmap()
    2) Terminal         - anyMatch(), allMatch(), collect()
    Intermediate operations returns Stream only while terminal operations returns some definite type of object.

- Can you differentiate between sequential stream and parallel stream ?
    Main difference between these streams is that sequential stream processes the data in sequencial order while parallel stream processes data in random order. Parallel stream makes use of processor cores for processing the data, so parallel stream will work effectively when your machine has multiple cores.
    Also you should use parallel stream when have very large data to process and tasks are independant.

- What is Optional and why do we need it ?

- What is the change in Date time APIs ?

- What is Lambda expression and why it's introduced ?
    Lambda expression is nothing but a piece of code or you can a small logic which can be provided as parameter to a method. Syntax of lambda is as below,
    () -> { statement;} 
    Lambda expression is very powerfull feature, it allows use to execute code/logic without creating the object of the class. Also to enable the use of functional interfaces we need lambda expression. This is way of functional programming and java is heading towards functional programming.

- how do you break the forEach of stream ?


--

# Answer
- One
- Two
- Three

---

## Question
# What is Spring?

--

# What is the interviewer looking for?
- One
- Two
- Three

--

# Answer
- One
- Two
- Three

---