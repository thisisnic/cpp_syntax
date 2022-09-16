# Declaring a pointer

```
double pi = 3.14;
double* pi_pointer = &pi;

// print out the memory address that pi_pointer points to
cout << pi_pointer << endl;

// print out the value at the memory address that pi_pointer points to
cout << *pi_pointer << endl;

```


You must use the keyword `const` when creating a pointer that points to an element of an array
