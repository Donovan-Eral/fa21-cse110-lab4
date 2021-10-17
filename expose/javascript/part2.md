1. Line 12 will print out ``3`` because ``i`` is a ``var`` and ``var`` cannot be loop-local.
2. Line 13 will print out ``150`` because ``discountedPrice`` is a ``var`` which means it can be accessed outside of the ``for`` loop.
3. Line 14 will print out ``150`` because ``finalPrice`` is a ``var`` within a function. This makes it a function-level variable, which means it can only be used inside the function.
4. The function will return an array of the discounted prices. This is because the function takes each element in the ``prices`` array, applies the ``discount``, and appends the result to the array ``discounted``.
5. 
