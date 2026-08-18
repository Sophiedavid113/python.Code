module) KO install krta hia 
..........................................................
#  single line comment dena

"""
comment dene Ka tareeka multi line comment dene Ka tareeka 
"""
..........................................................
Data type 
1 integer ,  2.0 float  , 
"Harry"  string  ,   false   Boolean ,
..........................................................variable 
a = 1 b = 2  print("a+b")    3
name = "Ali"  
age = 30
is_ student = true
.........................................................

name = "Ali"
print(type(name))       string
..........................................................
Arithmetic Operators
a = 10
b = 3          print("a+b")  13
..........................................................
Comparison Operators
x = 10
y = 20
print(x == y)  # False
print(x < y)   # True
..........................................................
Assignment Operators
x = 5
x += 3
print(x)  # 8
..........................................................
Logical Operators
and
True if both conditions are true
or
True if at least one condition is true 
a = 10    b = 20
print(a < b and b > 15)  # True
print(not(a > b))        # True
........................................I8                         String
age = "25"
print(type(age))       string 
..........................................................
name = "Pakistan"
print(len(name))    8
..........................................................
String index   0 SE start hota hia
name = "Pakistan"
print(name[0])          p        
Negative   -1
..........................................................
String slicing half part nakalne ke liye use hota hia. 
name = "Pakistan"
print(name[0:4])    answer   paki
..........................................................
name = "ali khan"
print(name.title()) answer Ali khan
.......................................................
replace ik text ko dosre text SE replace krna
text = "I like JavaScript"
print(text.replace("JavaScript", "Python"))
Answer I like python 
...........................................................List 
fruits = ["Apple"]
print(fruits)        answer apple
..........................................................
data = ["Ali", 25]
print(data) answer string number
..........................................................
List mein har item ka ek( index) number hota hai.
Index 0 se start hota hai.
fruits = ["Apple", "Banana", "Mango", "Orange"]
print(fruits[0])
print(fruits[1])
print(fruits[2])
Answer apple banana mango
(Negative index ) -1 SE start hoti h
..........................................................
append() list ke end mein item add karta hai.
fruits = ["Apple", "Banana"]
fruits.append("Mango")
print(fruits)   answer apple banana mango

remove krna    fruits.remove("  ")
..........................................................
fruits = ["Apple", "Banana", "Mango"]
print(len(fruits))      answer   3
..........................................................tuples
Lekin Tuple ko round brackets ( ) mein likhte hain
fruits = ("Apple", "Banana", XX "Mango")
print(fruits) answer apple banana mango
..........................................................
Tuple index
colors = ("Red", "Green", "Blue")
print(colors[0])
print(colors[1])
print(colors[2])
Answer red green blue
Negative tuple index -1 SE start hota ha
........................................................Dictionary 
Dictionary ایسا data structure ہے جس میں data Key اور Value کی شکل میں محفوظ ہوتا ہے۔
Key    "name"       value       "Bilal"
..........................................................
student = {
    "name": "Ali",
    "age": 20,
    "city": "Lahore"
}
Print(student)  answer "name to Lahore" dictionary ayse likhte han
..........................................................
Dictionary کے لیے {} استعمال ہوتے ہیں۔
.........................................................
Dictionary SE value hasil krna 
 Student ={
         "name":       "Ali",
         "Age":          20,
          "City":         lahore    }
 Print(student ["name"])        Ali
..........................................................
student = {          pop ( ) return
    "name": "Ali",
    "age": 20
}
student.pop("age")
print(student)        pop remove krta hia      answer name Ali
.........................................................print(numbers)  answer {1,2} 
..........................................................
numbers = {1, 2, 2, 3, 3, 4}
print(numbers)  duplicate value khatam krta h       answer {1,2,3,4}
..........................................................
numbers = {1, 2, 3}
numbers.add(4)
number.remove(3)
print(numbers)   number add kra
{1,2,3,4}            {1,2,}
..........................................................
numbers = {10, 20, 30, 40}
print(len(numbers))       lenght
Answer 4
........................................................Conditional if and else
if condition:
    # condition درست ہو تو یہ code چلے گا
else:
    # condition غلط ہو تو یہ code چلے گا              basic syntax
..........................................................
age = 20

if age >= 18:
    print("Aap adult hain")
else:
    print("Aap adult nahi hain")
.......................................................for and while loop
 for i in range(5): 
print(i)    for    answer 1 2 3 4 
..........................................................
a = 10
while >= 5:
print(a)  
a += 10                 while 
..........................................................
fruits = ["Apple", "Mango", "Banana"]
for fruit in fruits:
    print(fruit)
..........................................................
for i in range(1, 10):         Break
    if i == 5:
        break
    print(i)       1 2 3 4 answer
break loop کو فوراً روک دیتا ہے
..........................................................
for i in range(1, 6):         Continue 
    if i == 3:
        continue
    print(i)   3 skip ہو گیا۔ ..
........................................................Function 
def function_name():
    # code
def → function بنانے کے لیے keyword
function_name → function کا نام
() → parameters کے لیے
: → function شروع ہونے کی نشانی
..........................................................
def hello():
    print("Hello Python")
hello( )           simple function 
..........................................................
def hello(name):
    print("Hello", name)
hello("Ali")
hello("Ahmed")           parameter 
..........................................................
                           Multiple parameter

def add(a, b):
    print(a + b)
add(10, 20)
..........................................................
                                  return 
def add(a, b):
    return a + b
result = add(10, 20)
print(result)
......................................................object oriented programming 
class Student:
    def study(self):
        print("Student is studying")
student1 = Student()
student1.study()      
..........................................................
                             Class and object
class Student:
    name = "Ali"
student1 = Student()
print(student1.name)
1student ایک object ہے۔    car class
.........................................................
class Student:             self Kia hia
    def __init__(self, name):
        self.name = name
student1 = Student("Ali")
student2 = Student("Ahmed")
print(student1.name)
print(student2.name)
..........................................................
Method کیا ہوتا ہے؟
Class کے اندر بنائے گئے function کو عام طور پر Method کہتے ہیں۔
class Student:
    def __init__(self, name):
        self.name = name
    def study(self):
        print(self.name, "study kar raha hai")
student1 = Student("Ali")
student1.study()
.......................................................object oriented programming 2
Python OOP میں Inheritance کا مطلب ہے کہ ایک Child Class، دوسری Parent Class کے attributes اور methods کو استعمال کر سکتی ہے۔
..........................................................
class Animal:
    def eat(self):
       print("Animal kha raha hai")
class Dog(Animal):
    def bark(self):
        print("Dog bhonk raha hai")
dog = Dog()
dog.eat()
dog.bark()
.......................................example............
class Parent:
    def hello(self):
        print("Hello")
class Child(Parent):
    pass
obj = Child()
obj.hello()
......................parent and child.................Advanced python 01
def total(*numbers):
    print(numbers)
                                         *Argument 
total(10, 20, 30, 40) 
Answer 10 20 30 40
Jab function mein unknown number of arguments dene hon:
..........................................................
def student(**data):
    print(data)
student(name="Ali", age=20, city="Lahore")
 Answer {'name': 'Ali', 'age': 20, 'city': 'Lahore'}.                         *Kwargs
**kwargs multiple keyword arguments ko dictionary mein store karta hai.
..........................................................
Lambda ek small anonymous function hota hai. 
                                Lambda function 

def square(x):
    return x * x   answer x
..........................................................
numbers = [1, 2, 3, 4]
result = list(map(lambda x: x * 2, numbers))                               map
print(result)
Answer [2, 4, 6, 8]
..............................................................numbers = [1, 2, 3, 4, 5, 6]

def is_even(number):
    return number % 2 == 0

result = filter(is_even, numbers)

print(list(result))
Answer   [2, 4, 6]      filter
..........................................................
from functools import reduce
numbers = [1, 2, 3, 4, 5]
result = reduce(lambda x, y: x * y, numbers)                    reduce
print(result)
1 × 2 = 2
2 × 3 = 6
6 × 4 = 24
24 × 5 = 120
..
...



