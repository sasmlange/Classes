Extending
==========================================


What does it mean to extend a class? This means copying all the methods and variables
from one class to another. In python this is very easy. First make the class that
you want to copy.

.. code-block:: python

    class Basic_Class:
        my_var = "Some very cool content"

        def my_method():
            print(self.my_var)

What did we just do? We first made a class called **Basic_Class** and made a
method called **my_method**. We also a variable called **my_var**. Now we need
to make the class that receives all the other class functionality.

.. code-block:: python

    class My_Class(Basic_Class):
        pass

We made a new class, **My_Class**. In the parentheses is our class we made earlier,
**Basic_Class**. Inside **My_Class** we have a command, **pass**. **pass** is
just a place holder. We use it because we need something indented. We could have
put any code there like :py:`a = 1`. It could be anything.