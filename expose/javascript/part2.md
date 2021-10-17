1. Line 12 will print out ``3`` because ``i`` is a ``var`` and ``var`` cannot be loop-local.
2. Line 13 will print out ``150`` because ``discountedPrice`` is a ``var`` which means it can be accessed outside of the ``for`` loop.
3. Line 14 will print out ``150`` because ``finalPrice`` is a ``var`` within a function. This makes it a function-level variable, which means it can only be used inside the function.
4. The function will return an array of the discounted prices. This is because the function takes each element in the ``prices`` array, applies the ``discount``, and appends the result to the array ``discounted``.
5. The code causes an error because ``i`` is defined using ``let`` which means it cannot be accessed outside of the loop-block.
6. The code causes an error because ``discountPrice`` is defined inside of the ``for`` loop and it is defined with ``let``, which means that it cannot be accessed outside of the loop-block.
7. Line 14 will print our ``150`` because ``finalPrice`` is being used in the function code-block where it was defined.
8. The function will return an array of the discounted prices. No errors will be thrown because there is no variable that is used outside of its scope.
9. The code causes an error because ``i`` is defined using ``let`` which means it cannot be accessed outside of the loop-block.
10. Line 12 will print ``3`` because ``length`` is not modified in the function and it is being used in the same scope that it was defined in.
11. The function will return an array of the discounted prices. This is because none of the variables are used outside of their scope and none of the ``const`` variables are changed in a way that is not allowed. ``const`` arrays can have elements pushed into it but it cannot be reassigned.
12.
- ``student.name``
- ``student['Grad Year']``
- ``student.greeting()``
- ``student['Favorite Teacher'].name``
- ``student.corseLoad[0]``
