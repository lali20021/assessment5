#### 1. What is a method in Ruby? How is it different or similar to functions in JavaScript?
Method is a set of expressions that returns a value.
Method in Ruby is the same as function in JS. There is no functions in Ruby.

#### 2. What does it mean that a class inherits from another class? Try to explain Ruby inheritance.
This means that the class lower down in hierarchy gets features of the higher up class. But also can add its own specific features.
Inheritance is a relation between two classes.

#### 3. What is rspec and what is the general process for writing tests in RSpec?
RSpec is a testing tool for Ruby. Also it is the most frequently used.
The general purpose is to make sure the app behaves in a certain and expected way.

#### 4. Name three possible non-inheritance relationships between ruby objects?
One to One
Many to Many
One to Many


#### 5. What do we call the #{} convention used below? What is it accomplishing?
It is called string interpolation.It lets you substitute the result of Ruby code into the middle of the string.

In the code below the result will be:
I am printing a random number 1022

```ruby
x = 1022
puts "I am printing a random number #{x}"
```

#### 6. How do you feel about testing right now? What potential pros/cons/barriers/advantages do you see to implementing BDD in your own code?
BDD keeps focus on the end user and their needs. This is great. This gives you a look at the application from the user's perspective.
BDD provides the description of what an application does in simple terms and everyone can understand.

#### 7. What is an instance variable in Ruby? How is it different from a normal, local variable?
Local variable can be only accessed in a specific, local environment. For example if its defined inside one method, it cannot be accessed by another method. In order to get access to it, that variable has to be an instance variable.
Instance variable begins with @ and lives within a class instance and can be referenced in any method of the class.

#### 8. Ruby has a great community and tons of free resources to help you learn. Here is the long list of great resources: https://www.ruby-lang.org/en/documentation/. Below are a few popular ones:
- Interactive Ruby tutorial (http://tryruby.org/levels/1/challenges/0)
- Why's (poigniant) Guide to Ruby: comics, anecdotes, and microscopic canaries (http://poignant.guide/book/chapter-1.html)
- Ruby in 20 min (https://www.ruby-lang.org/en/documentation/quickstart/)


Choose one of these resources and go through the material (not for hours, only looking for around 10min of your time) then come back here and list a few new things you learned about Ruby.
