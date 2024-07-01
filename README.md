# python_oops and DSA
this is the repo containing basic tutorials and code of OOPS and DSA


### What is object 
>a object have a type like (int,str) of it's class
>>any number , list, all are object in python 
>>>you can check it by using `type()` 
>>> if you type `dir()` with any of the object it will provide all the function you can use with that object

>>> you can use `id()` to find id of any object 
```
x=15.5

print(dir(x))

```

> Memory optimization in python
```
x=[5,10,15,20]
y=x

x.append(50)

print("x=",x)
print("y=",y)

```
* you could think *x* will have values [5,10,15,20,50] and *y* will have values [5,10,15,20] but in python because of memeory optimization, so when you assign *x* values  to *y* (`y=x`) all the change made in *x* will reflect in *y* so both will have same output because their memeory  address assign to them is same. you can check it using `id()` method.