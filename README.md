Basic Library in python 

import math as mt
mt.sqrt(), mt.floor(), mt.ceil() # basic functions in math modules 
if we want to see all function in modules  dir(math)

Basic Operations :- 
True division 10/4 it will retun 2.5 
Floor division 10//4 it will return 2

Data Types :- 
type(2) int
type(2.0) float 
type('siva') str
type(True) bool
type(None) NoneType 

Check data type in given format or not 
isinstance(2.0,[int,float]) return True 
isinstance(2.0,[int]) return False 

Convert object to given type
float(2)
int (2.5)
str(3) 

zero None and empty containers are converted to False non empty container are converted to True 
bool(0),bool(none), bool([]),bool(''),bool({}) - False 
bool(2) - True 

if we want to know the id of any object id(list) it will return id of objects 

TUPLES:- 
Create Tuples two ways 
digits =(1,2,'Four')
digits=tuple([1,2,'Four']) # Create tupple from list 
len(digits) # It will return 3 
digits[0] # It will retrun 1 
concatenate tuples digits + (5,6,7)

String Operations 



