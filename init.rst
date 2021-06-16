\__init__
==========================================
**__int__** is a special method that is executed when you define an object.

.. code-block:: python

    class My_Class:
        my_var = "Hello Earth"

        def __init__(self):
            self.my_var = "Hello Moon"

    My_Object = My_Class()
    print(My_Object.my_var)

This code should give an output that looks like this:

.. code-block:: bash

    Hello Moon

What did we just do? We made a class called **My_Class**. **My_Class**
defines a variable inside the class called **my_var** that is set to
**"Hello Earth"**. **My_Class** also defines **__init__** to change **my_var**
to **"Hello Moon"**. Outside the class we made an object. When this object
was made, the content of **my_var** was changed from **"Hello Earth"** to
**"Hello Moon"**. We then print out **my_var**.

You also can use **__init__** for parameters for a class. Make a class that
has the **__init__** function. Give the **__init__** function parameters just
like you would give a method a parameter.

.. code-block:: python

    class My_Class():
        my_var = "I hope this works"
        def __init__(self, new_value):
            self.my_var = new_value

    My_Object = My_Class("Yay! It worked!")
    print(My_Object.my_var)


The output should be:

.. code-block:: bash

    Yay! It worked!

What did we just do? We made a class with a variable called **my_var**. With the
**__init__** function we overwrote **my_var** with the parameter of class,
**new_value**
