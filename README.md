# first-repository
My first project 
import random
from random import randint
a = input("Ваше имя: ")
b = input("Ваш возрост: ")
c = input("Ваш цвет кожи (Белый, Черный(Негритос)): ")
rost = ['Увеличился', 'Уменьшился']
rostt = ['см', 'мм']
print(a,"Ваш рост",random.choice(rost), "на" ,randint(1, 18), random.choice(rostt)) 
 
