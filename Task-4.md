# Practical One, Task Four

## Getting to grips with variables

Now its time to test your knowledge.

**_Step One_**

+ Create a new project as shown in [Task One](https://github.com/fslcoding/Practical-1/blob/main/Task-1.md)
+ Create three ```int``` variables, and call them ```width```, ```height``` and ```area```
+ Use ```Console.ReadLine();``` to _initialise_ the height and width variables

You may notice this gives an error, 

![image](https://github.com/fslcoding/Practical-1/assets/62078259/10f5b996-8335-44f2-90cb-d377f478e203)

+ You need to convert the ```Console.ReadLine();``` to an integer.
+ To do this, use the ```Convert.ToInt32();``` method:

```
int width = Convert.ToInt32( Console.ReadLine() );
```

+ Do the same for height
+ Find the area of the shape by multiplying the two variables
+ Finally, print out the area using:

```
Console.WriteLine(area);
```


