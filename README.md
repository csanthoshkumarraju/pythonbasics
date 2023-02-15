# pythonbasics
# This is a sample Python script.

# Press ⌃R to execute it or replace it with your code.
# Press Double ⇧ to search everywhere for classes, files, tool windows, actions, and settings.


def print_hi(name):
    # Use a breakpoint in the code line below to debug your script.
    print(f'Hi, {name}')  # Press ⌘F8 to toggle the breakpoint.


# Press the green button in the gutter to run the script.
if __name__ == '__main__':
    print_hi('PyCharm')


# See PyCharm help at https://www.jetbrains.com/help/pycharm/
# print statement
# print('hi hello santhosh welcome to python //-->')
# python multiple comments / doc strings
#  print('''
# hi,
# santhosh''')
# create variable
# x = 1
# print('value of x is ', x)
# y = 2
# print("sum of ", x, "and", y, "is", x+y)
# x = 9
# print(type(x))
# y = int(9)
# print(y)
# f = float(9)
# j = 8.9
# print(type(j))
# s = 12E4
# print(type(s))
# c = 9 + 7j
# print(c)
# print(type(c))
# python casting
# x = 7
# y = int(x)
# print(x, y, type(y))
# f = float(x)
# print(f)
# st = '4567'
# n = int(st)
# print(n, type(n))
# s = str(x)
# print(type(s))
# strings operations
# st = 'santhosh'
# print(st[0])
# print(st[1:5])
# st1 = '  santhosh   '
# print(st1.strip())
# print(len(st))
# us = 'SANTHOSH'
# print(us.lower())
# ls = 'santhosh'
# print(ls.upper())
# print(ls.replace('santhosh', 'macbook'))
# print(ls.split())
# sl = 'hi, santhosh, welcome'
# print(sl.splitlines())
# python operators
# fv = int(input("enter the first value:-->"))
# sv = int(input("enter the second value:-->"))
# print("the first value is :==", fv)
# print("the second value is :==", sv)
# print('operations are :--> +,-,*,/,%')
# op = input()
# if op == '+':
#     print('sum of ', fv, 'and', sv, 'is :--', fv + sv)
# elif op == '-':
#     print('subtraction of ', fv, 'and', sv, 'is :--', fv - sv)
# elif op == '*':
#     print('product  of ', fv, 'and', sv, 'is :--', fv * sv)
# elif op == '/':
#     print('div of ', fv, 'and', sv, 'is :--', fv / sv)
# elif op == '%':
#     print('modulus of ', fv, 'and', sv, 'is :--', fv % sv)
# else:
#     print('give the correct operation')
# python lists
# l = ["hi", 'welcome', 'santhosh']
# print(l[1])
# l.append('python')
# print(l)
# for x in l:
#     print(x)
# if "hi" in l:
#     print("hi is present in l")
# print(len(l))
# l[1] = 'hello'
# print(l)
# l.remove('hi')
# print(l)
# l.remove(l[-1])
# print(l)
# l.clear()
# print(l)
# t = ('hi', 'santhosh')
# l1 = list(t)
# print(l1)
#
# python tuples
# t = ('hi', 'santhosh', 'welcome')
# print(t[0])
# l = list(t)
# l.append('hello')
# l[1] = 'python'
# print(l)
# for c in t:
#     print(c)
# if 'hi' in t:
#     print("yes ")
# print('length of the tuple is : ', len(t))
# del t
# print('the list is deleted',)
# nt = tuple('hi')
# print(nt)
# st = tuple('santhosh')
# print(st)
# python sets
# s = {'hi', 'welcome', 'santhosh'}
# for a in s:
#     print(a)
# if 'hi' in s:
#     print('hi is in set')
# s.add('python')
# print(s)
# s.update('abc', 'def', 'fgh')a
# print(s)
# print(len(s))
# s.remove('santhosh')
# print(s)
# s.discard('def')
# p = s.pop()
# print(p)
# s.clear()
# print(s)
# s1 = set('hi')
# print(s1)
# d = {1: "hi", 2: "santhosh", 3: "welcome"}
# print(d)
# print(d[1])
# d[10] = "python"
# print(d)
# print(d.keys())
# print(d.values())
# print(d.items())
# if 'hi' in d:
#     print("hi in dictionary")
# print(len(d))
# print(d.pop(1))
# e = d.clear()
# print(e)
# c = dict(hi="hi")
# print(c)
# multiple dictionaries
# d = {
#     's1': {
#     'name': "san", "rel ": "me"
#     },
#     's2 ': {
#     'name': "santhosh", "rel ": "mine"
#
#     }
# }
# print(d)
# for loop
# i = 1
# for i in range(10):
#     print(i)
# stri = 'santhosh'
# for x in stri:
#     print(x)
#  while loop
# i = 1
# while i <= 10:
#     print(i)
#     i = i +1
#
# print("ho")
# python functions
# def fu(name = 'chiluru'):
#     print('hi', name)
#
# fu("santhosh")
# fu("kumar")
# fu("raju")
# fu()
# def ca(x):
#     print(7 + x)
# ca(2)
# ca(6)
# python lamda

# x = lambda x:x+10
# print(x(3))
# y= lambda y:y*10
# print(y(3))
# z = lambda a,b,c:a+b+c
# print(z(2,4,8))
# python arrayys
# list is considered as arrays
# class pra:
#     def __init__(self, name, age):
#         self.name = name
#         self.age = age
# v = pra('santhosh',23)
# print(v.name, v.age)
# v.name = 'cskraju'
# print(v.name)
# del v
# print("no values")
# python dates
# import datetime
# ct = datetime.datetime.now()
# print(ct)
# ctu = datetime.datetime(2023, 1, 20)
# print(ctu)
# print(ct.day)
# print(ctu.strftime('%B'))
# python math
# import math
# x = 4
# y= -3
# v = (1, 2, 3, 4)
# z = 3.6
# print(min(v))
# print(max(v))
# print(pow(2, 3))
# print(z.__ceil__())
# print(z.__floor__())
# print('pi is', math.pi)
# print(math.sqrt(x))
# python try except
# try:
#     print(x)
# except NameError:
#     print('variable x is not defined')
# except:
#     print("an exception occuerd")
# try:
#     print("santhosh")
# except NameError:
#     print('variable x is not defined')
# else:
#     print("program executed successfully")
# try:
#     print(c+10)
# except NameError:
#     print("enter a value")






