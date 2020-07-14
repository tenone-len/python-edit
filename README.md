# python-edit

#Creat list
fruits=['apple','orange','banana','strawberry','durian','pear','cherry']
print(fruits)

#Acessing elements in a list
print(fruits[0])
print(fruits[0].title())

#Use the value in the list
mail=('My favorite fruit is '+fruits[2]+'!')
print(mail)

#Modify,add and delete the elements in the list
fruits[0]='watermelon'
fruits.append('watermelon')
fruits.insert(0,'watermelon')
del fruits[1]
fruits.remove('watermelon')
#There changes are permanent
#Here's how to take elements out and use them
anything_fruit=fruits.pop(0)
print(anything_fruit)
print('my favorite fruit is '+anything_fruit+'!')

#Permanently sort the list alphabetically
fruits.sort()
fruits.sort(reverse=True)
#Temporarily sort the list alphabetically
sorted(fruits)
