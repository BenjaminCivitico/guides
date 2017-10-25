#For Loop

##Syntax
```C#
for ((Initial variable); (condition); (step)) 
	{
	(code)
	}
```

The C# for loop consists of three expressions and some code.

##Description

- *Initial Variable*: your starting state, eg int i = 0;
- *Condition*: While this condition is true the code will continue to run, eg i<=5;
- *Step*: The increment, or decrement, of the initial variable, eg i++ or i-=2.

A for loop is used by developers to run code repeatedly untill the condition is false.

##Example

The following code can be used to run a for loop that will count all of the odd numbers up to, and including 13

```C#
for(int i = 1; i <= 13; i+=2)
	{
		Console.WriteLine("Value: {0}", i);
	}
```

##Output

```
Value: 1
Value: 3
Value: 5
Value: 7
Value: 9
Value: 11
Value: 13
```
