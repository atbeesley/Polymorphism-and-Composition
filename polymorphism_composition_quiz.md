# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

When an object has several types simultaneously.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

Use interfaces to give specific types of behaviour to different objects e.g. an interface called IFly can give 'flying behaviours' to various flying objects, e.g. broomsticks, magic carpets, etc.

3. What can we use to implement polymorphism in Java?

Interfaces.

4. How many 'forms' can an object take when using polymorphism?

Multiple.

5. Give an example of when you could use polymorphism.

Aside from the IFly example, an interface "ISwim" could be used to give swimming behaviour to different water-borne objects, such as fish, ducks, squid...



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

Composition describes a class that references one or more objects of other classes in instance variables, allowing a modelling of a has-a association between objects.

7. When would you use composition? Provide a simple example in Java.

When Type A only needs SOME of the behaviours from Type B, rather than ALL of them (in which case you would use inheritance).

8. What is/are the advantage(s) of using composition?

It allows code to be easily re-used in other modules.

9. When an object is destroyed, what happens to all the objects it is composed of?

All the objects it is composed of are destroyed too.
