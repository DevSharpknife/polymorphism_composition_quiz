# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Polymorphism is derived from Greek and means "many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

A class can be of several different types, and pass on it's traits to multiple subclasses, which have these traits in common, or a common method can be used by separate classes in completely different ways.

3. What can we use to implement polymorphism in Java?

We can use Abstract Super Classes, Inhertitance and Interfaces to implement polymorphism.

4. How many 'forms' can an object take when using polymorphism?

As many as you deem appropriate. There are no limitations.

5. Give an example of when you could use polymorphism.

If you have many classes with a common method, you could create an interface to store that method, then implement it individually and possibly differently, across all your classes.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

When we use reuasable classes within others or abstract classes to instantiate others that have a HAS A or IS A relationship with it.

7. When would you use composition? Provide a simple example in Java.

A Course class would be a property of a Student class as the Student HAS A Course. A Car class would be an instance of the abstract Vehicle super class as it IS A Vehicle.

8. What is/are the advantage(s) of using composition?

This allows us to create code that is more flexible and much more dry.

9. When an object is destroyed, what happens to all the objects it is composed of?

They are maintained. Whereas, if these objects were data types to describe the objec, they would be lost.