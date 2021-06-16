Method Parameters
==========================================

To make a method parameter, define it after the self parameter.

.. code-block:: python

    class My_Class:
        my_var = "Hello Everybody"

        def my_method(self, new_value):
            self.my_var = new_value

    my_object = My_Class()
    my_object.my_method("Bye Everyone")
    print(my_object.my_var)

The output of this code should be:

.. code-block:: bash

    Bye Everyone

In the code above we just made a class called **My_Class** and made a
variable called **my_var**. We then made a method called **my_method**.
**my_method** has a parameter called **new_value**. In **my_method**
**my_var** is changed to whatever **new_value** is set to. Outside the
class we make an object and