

# input.py
# moving past 'hello world.'

# ask for name and age, then tell them when they will be one hundred years old.
# need to input something first but don't know when to say something so have the computer ask you something
print('Hello, whom are you?')
name = input()
# got the name now ask for age
print('Good to meet you ' + name + '\! Also how old are you?')
age = int(input())
# use the name and the age to find years till hundred
print('Well, ' + name + ' in ' + str(100 - age) + ' years you will be one hundred years old.')

