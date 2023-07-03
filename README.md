Python. HW_1. 
Part_1
1) Создать переменную типа String
2) Создать переменную типа Integer
3) Создать переменную типа Float
4) Создать переменную типа Bytes
5) Создать переменную типа List
6) Создать переменную типа Tuple
7) Создать переменную типа Set
8. Создать переменную типа Frozen set
9) Создать переменную типа Dict

10) Вывести в консоль все выше перечисленные переменные с добавлением типа данных.

11) Создать 2 переменные String, создать переменную в которой сканкатенируете эти переменные. Вывести в консоль.
12) Вывести в одну строку переменные типа String и Integer используя “,” (Запятую)
13) Вывести в одну строку переменные типа String и Integer используя “+” (Плюс)


























stroka='Helga';
print("task 1- ", stroka, type(stroka))

num= 18;
print("task 2 -",num, type( num))

num2=4.5;
print("task 3 -", num2, type(num2))

byt=b'cringe'
byt2=b"cring"
byt3=b"""3 double quotes"""
print("task 4 - ", byt,byt2,byt3)
print(type(byt),type(byt2),type(byt3))

print(" Task 5.There are 4 methods of creation lists in Python")
l1=[];
print("1) Empty list", l1,type(l1))
l2=[1.3,5,'hi'];
print("2) By using [] and separeting elements , ",l2,type(l2))
l3=[i for i in range (1,10)];
print("3)Lists generator l3=[i for i in range (1,10)] ", l3, type(l3))
l4=list();
print("4) List functions ",l4,type( l4), list('ksendzov'), type( list('ksendzov')))

t=(1,2,'r');
t1=tuple('hello vadim');
print("task 6 There are 2 ways of creation tuples: "
      "1) - ", t,type(t),
      "2)using function - ",t1, type(t1))

s=set('daddy');
s1={'w','w','r', 't'};
s2=a = {i for i in range(10)};
print("task 7",s,type(s),s1, type(s1),s2,type(s2))

f=frozenset('cool');
print("task 8",f,type(f))

d1={'name':'julia', 'age':18, 'city':'belarus'};
print("task 9", type(d1), d1)

u='mom ';u1='dad';
result=u+u1;
print("task 11", result)

new=11
print("task 12 - ", 11, 'i', 'love', new)

ne=32; g=' group padawans';
r=str(ne)+g;
print("task 13 ", r)

# Python
