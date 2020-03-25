## Documentation

**version** x 

​	indicating release information, x --*string*

**@Group**(x,y) 

​	parameter groups for rule settings, x --*string* group name, y --*int* group order ascending

**@order**(x)

​	individual parameter order, x --*int* ascending

**@range**(x,y)

​	parameter range, x --*int* lower bounds, y --*int* upper bounds

@handle

​	

**attr**

​	type indicating variable parameter







## Samples

Parameter Initialization

```cga
@Group("Lorem Ipsum", 1)
@order(1) @range(0,20)
attr Dolor = 5

```

