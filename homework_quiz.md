Polymorphism
1. What does the word 'polymorphism' mean?

It means to be able to have or take many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

It relates to when we have many classes that are related to each other, any type can behave as a super-class or one of it’s own and can use the methods it inherits to perform different tasks. It allows us to treat an object as different types of objects. e.g. a superclass called Bird that has a method called birdSound(). Subclasses could be seagulls, pigeons, parrots which all have their own implementation of a method to make the sound they make.

3. What can we use to implement polymorphism in Java?

Using Abstract classes and Interfaces. 

4. How many 'forms' can an object take when using polymorphism?

Any amount applicable

5. Give an example of when you could use polymorphism.

If you have 2 classes which are children of a different super-class but you want them to share a behaviour that the super classes do not have.

Composition
6. What do we mean by 'composition' in reference to object-oriented programming?

It’s when an object has an attribute as opposed to being something i.e. an object being composed of other objects.

7. When would you use composition? Provide a simple example in Java. 

When an object is made up of other objects with a “has-a” relationship.  e.g. a Human Body HAS a heart, HAS a brain, HAS lungs so we can think of the object being composed of other objects.

8. What is/are the advantage(s) of using composition?

Objects can use different attributes and methods from different sources as opposed to the ones inherited from the super-class.You can reuse code keeping it DRY.

9. When an object is destroyed, what happens to all the objects it is composed of?

They are also destroyed
