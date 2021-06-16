Basic Methods
==========================================

What is a method? A method is a function that is in a class. It is most often
used to configure an object. Making a method is very similar to making a
function. You just define the function indented inside the class. You must
also add a **self** parameter. You have now made a method.

.. code-block:: python

    class My_Class:
        def my_method(self):
            print("Hello World!")

What did we just do? We made a class called **My_Class** and a method called
**my_method**. To test our method we can make an object (outside the class),
then we can call the method by writing the name of our object and add a dot
(**.**). After we did that we can write the method name which is **my_method**
followed by parentheses (**()**). Notices that we did not add anything in the
parentheses, even though in the class we have a required parameter called
**self**. This is because by having the object first and then the method,
we set the **self** parameter to the object.

.. code-block:: python

    My_Object = My_Class()
    My_Object.my_method()

Your code should now look like:

.. code-block:: python

    class My_Class:
        def my_method(self):
            print("Hello World!")


    My_Object = My_Class()
    My_Object.my_method()

Your output should look like:

.. code-block:: bash

    Hello World!