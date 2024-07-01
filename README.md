# python_oops and DSA
this is the repo containing basic tutorials and code of OOPS and DSA


### What is object 
>a object have a type like (int,str) of it's class
>all the object store in a heap memory
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

print(id(x))

print(id(y))

```
* you could think *x* will have values [5,10,15,20,50] and *y* will have values [5,10,15,20] but in python because of memeory optimization, so when you assign *x* values  to *y* (`y=x`) all the change made in *x* will reflect in *y* so both will have same output because their memeory  address assign to them is same. you can check it using `id()` method.

* to handle this we have different methods like we can copy one list into another instead assigning values

```
x=[5,10,15,20]
y=x.copy()

x.append(854)


print(x)
print(y)


```

## Instence vs Object 
>in some of the cases instance and class considers as same but there is little difference between them here is explaination of instance and object.
>>*object* :- a object reprsent blueprint or class

>>instance :- it is unique copy of an object with it's own distinct of values

```
class Car:  # Object (blueprint)
    def __init__(self, color, model):
        self.color = color
        self.model = model

my_car = Car("red", "Toyota")  # Instance of the Car object
your_car = Car("blue", "Honda")  # Another instance
```


### what is an class

it is blueprint of object 
* a class is blueprint of object means it contain all the things that need to make your idle object,    
  object is created by following rules of a class. first class is created then object, there could be class without existing it's object
