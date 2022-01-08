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