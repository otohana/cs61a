1. from lab02:
    ```python
    >>> print_lambda = lambda z: print(z)  # When is the return expression of a lambda expression executed?
    >>> print_lambda
    ______

    >>> one_thousand = print_lambda(1000) 
    ______ # why 1000 is printed here but not printed in the following statement?

    >>> one_thousand 
    ______
    ```
    
2. from lab02:
    ```python
    >>> def cake():
    ...    print('beets')
    ...    def pie():
    ...        print('sweets')
    ...        return 'cake'
    ...    return pie
    >>> chocolate = cake()
    ______

    ```

    <del>What if more than one functions are defined in the body of function `cake()`? Would these functions be executed in order if I call `cake()()`?</del>
