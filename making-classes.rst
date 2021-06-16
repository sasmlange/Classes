Making Your First Class
==========================================

To make a class you use **class** followed by the class name. Then comes a
colon(**:**).

.. code-block:: python

    class My_Class:

Now you can make a variable in the class. You define the variable inside the
class indented.

.. code-block:: python

    class My_Class:
        my_var = "Hello World!"


That's it! You have made a basic class. You can now use it. Set it into a
variable outside the class. To do this, you write your variable name and an
equal sign(**=**). Now you can write the class name followed by the
parentheses (**()**). This variable is now an object.

.. code-block:: python

    My_Object = My_Class()

We made our class and set it into a object. We now want to get the
**my_var** variable that we made inside the class. We do this by typing the
object name and then add a dot(**.**). After the dot comes the variable name, in
our case **my_var**.

.. code-block:: python

    print(My_Object.my_var)

Your code should look like this:

.. code-block:: python

    class My_Class:
        my_var = "Hello World!"


    My_Object = My_Class()
    print(My_Object.my_var)

This code should give a result that looks like this:

.. code-block:: bash

    Hello World!
