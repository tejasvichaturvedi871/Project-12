# Project-12
# program 12:Consider a tuple t1=(1,2,5,7,9,2,4,6,8,10).WAP to perform following operations:
# (a)Print half the values of the tuple in one line and other half in the other next line.
#  (b)Print another tuple whose values are even numbers in the given tuple.
# (C)Concatenate a tuple t2=(11,13,15) with t1.
# (d)Return maximum and minimum value from this given tuple.

  (a)
t1=(1,2,5,7,9,2,4,6,8,10)
half_value=len(t1)//2
first_half = t1[ :half_value]
print("first_half",first_half)
second_half = t1[half_value: ]
print("second_half",second_half)


(b)
t1=(1,2,5,7,9,2,4,6,8,10)
even_number=tuple(filter(lambda x: x%2==0,t1))
print("tuple with even number",even_number)

(C) t1=(1,2,5,7,9,2,4,6,8,10)
t2=(11,13,15)
concatenation=(t1+t2)
print("tuple with concatenation", concatenation)

(D) t1=(1,2,5,7,9,2,4,6,8,10,11,13,15)
print("maximum value in t1 is",max(t1))
print("minimum value in t1 is", min(t1)) 
![Screenshot_20241227-013800_Chrome](https://github.com/user-attachments/assets/f7f32019-9a6c-4ba0-9e13-d20804891de2)
