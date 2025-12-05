# guess-the-number-game
A simple python game to guess a number between 1and100
import random
secretـnumber = random.randrange(1,100)
print('welcome to guess the number')
print('i have selected a number between 1 and 100')
yourـname=input('enter your name: ')
s=0
while True:
  guess = int(input('enter your guess: '))
  s=s+1
  if guess > secretـnumber:
    print('too big try again')
  elif guess < secretـnumber:
    print('too smail try again')
  else:
    print("correct")
    print("score",s)
    break

