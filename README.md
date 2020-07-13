# Optimization Modeling for Python (DOcplex)

With this library, you can quickly and easily add the power of optimization to
your application. You can model your problems by using the Python API and solve
them on the cloud with the IBM® Decision Optimization on Cloud service or on
your computer with IBM® ILOG CPLEX Optimization Studio.

This library is composed of 2 modules:

* IBM® Decision Optimization CPLEX Optimizer Modeling for Python - with namespace docplex.mp
* IBM® Decision Optimization CP Optimizer Modeling for Python - with namespace docplex.cp

Solving with CPLEX locally requires that IBM® ILOG CPLEX Optimization Studio V12.8.0
is installed on your machine.

Solving with the IBM Decision Optimization on Cloud service requires that you
register for an account and get the API key.

This library is numpy friendly.

## Install the library

```
   pip install docplex
```

## Get the documentation and examples

* [Documentation](https://github.com/ArmanBehnam/Optimization)
* [Examples](https://github.com/ArmanBehnam/Optimization/tree/master/cp/jupyter)

## Get Cloud API key
    
- Get your API key
    With your free trial, you can generate a key to access the DOcplexcloud API. 
    Visit the [Get API key & base URL](http://developer.ibm.com/docloud/docs/api-key) page to generate the key once you've registered. 
    This page also contains the base URL you must use for DOcplexcloud.
    
- Copy/paste your API key and service URL where appropriate in the examples to be able to run them, or have a look at *Setting up an optimization engine* section of the documentation

## Dependencies

These third-party dependencies are automatically installed with ``pip``

- [docloud](https://pypi.python.org/pypi/docloud)
- [enum34](https://pypi.python.org/pypi/enum34)
- [futures](https://pypi.python.org/pypi/futures)
- [requests](https://pypi.python.org/pypi/requests)
- [six](https://pypi.python.org/pypi/six)

