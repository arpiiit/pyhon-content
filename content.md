
# def-definition
# it uses interpreter. compile to bytecode(low level & plateform independent)
# byte code runs faster
#  .pyc ---> compiled python(frozen binaries)
# __pycache__ ---> it is like a system code. it uses of internal use for python
# sourece change & pyhon version --> contains files with name (chai.cpython-312.pyc)
# -->works only for imported files
#  -->not for top level file


# PVM (python cirtual machine)-->
# also said as run time engine
# code loop to iterate byte code
# also known as python interpreter

# byte code is not machine code 
# --> python specific interpretation
# --> cpython, jython, ironpython, PyPy, stackless

#os.getcwd()---->current working directory

<!-- # for c in 'chai':
# ...     print(c) 
# ...
# c
# h
# a
#i -->

<!-- # from importlib import reload 
# import sys
# sys.platform -->



# data types
-Number 323,213.42, 0b11, Decimal(), fraction()
-String: 'span', "nfks", b'a\x12x
-List: [1,2,[242,231],31], list(range(10))------>start 0 index
-tuple: (1,'spam',3,'U')
-dictonary: starting not 0 index->{'dda':'dad','dad':'dad'}
-set
-file: open('adn.txt')
-boolean: true, false
-none: none
-function, modules, classes

-Advance: decorator, denerator, iterator, metaprogramming