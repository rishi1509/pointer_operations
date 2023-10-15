# pointer_operations


## **THEORY**
In the case of **Call by Value**, when we pass the value of the parameter during the calling of the function, it copies them to the function’s actual local argument.
In the case of **Call by Reference**, when we pass the parameter’s location reference/address, it copies and assigns them to the function’s local argument. Thus, both the actual argument and passed parameters refer to one similar location.

### **FLOWCHART**
![call by value and call by reference](https://github.com/Purvansha022609/Pointer-Operations/assets/139473344/dbae44b3-eb56-47cf-9fc7-66024e27648a)

### **ALGORITHM**

**Call by Value**

1.Define a function that takes a pointer as a parameter.

2.Inside the function, you can access and modify the data pointed to by ptr. Changes made to *ptr will affect the original data in the calling code.

3.In the main program, declare a variable and initialize it.

**Call by Reference**

1.Define a function that takes a pointer as a parameter.

2.Inside the function, you can access and modify the value at the memory location pointed to by x. Changes made to *x will affect the original variable from the calling code.

3.Call the function from your main program and pass the address (pointer) of the variable you want to modify.

These algorithms demonstrate how to implement call by value and call by reference using pointers in C++. Remember that in the call by value method, a copy of the argument is passed to the function, while in the call by reference method using pointers, the function receives the address of the original variable, allowing it to modify the original variable.

### **OUTPUT**

![exp10](https://github.com/Purvansha022609/Pointer-Operations/assets/139473344/1fc4ef84-14d5-410a-b778-8c36c5f54155)
