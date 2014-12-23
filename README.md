# subprime

This repository will host sample code for manipulating subprime Fibonacci sequences, as described in *Conway's subprime Fibonacci sequences*, Mathematics Magazine, Dec. 2014.

Right now, the code is only available in Python. Running

```python cyclegen.py N```

will enumerate the cycles reached by starting terms ```1 <= a, b <= N```, and

```python cyclegen.py a b```

will print the sequence generated by ```a, b``` *starting from the first node*, and ```trivial``` otherwise.