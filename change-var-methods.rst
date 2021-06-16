Change Object Variables
==========================================

Way 1: Do it outside the class
-------------------------------
This way is very easy to do. Create a class with a variable.

.. code-block:: python

    class My_Class:
        my_var = "Hello Bob!"

We can now can change it. Outside the class make an object that is set to
**My_Class**. After that we can write the name of the class and add a dot(**.**),
then we write the name of the variable, in our case **my_var**. We now add
an equal sign (**=**) and then the value we want the variable to be.

.. code-block:: python

    My_Object = My_Class()
    My_Object.my_var = "Hello Joe!"

We have changed the value of the **my_var** variable. How do we check this? We
can print the value of **my_var** to the console, like what we did in the first
chapter.

.. code-block:: python

    print(My_Object.my_var)

Your code should look like this:

.. code-block:: python

    class My_Class:
        my_var = "Hello Bob!"


    My_Object = My_Class()
    My_Object.my_var = "Hello Joe!"
    print(My_Object.my_var)

Your output should like this:

.. code-block:: bash

    Hello Joe!


Way 2: Do it with a method
-------------------------------

If you do it this way, you do it inside the class. This is very similar to
the other way. Make the same class as the first way.

.. code-block:: python

    class My_Class:
        my_var = "Hello Bob!"

Now you can add a method. Inside the method you almost do the same code as
before but inside of setting an object you use the self parameter. Note: This
way can also be used to read variables.

.. code-block:: python

    def my_method(self):
        self.my_var = "Hello Joe!"
        print(self.my_var)


Now we can use the method.

.. code-block::

    My_Object = My_Class()
    My_Object.my_method()


Your code should now look like this:

.. code-block:: python

    class My_Class:
        my_var = "Hello Bob!"

        def my_method(self):
            self.my_var = "Hello Joe!"
            print(self.my_var)


    My_Object = My_Class()
    My_Object.my_method()


The result should be:

.. code-block:: bash

    Hello Joe!


Note: You can do this for a variable that does not exist (works on ways 1 and
2)
