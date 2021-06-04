# Susumu Sakamoto
Hey Susumu! You have finished the Prework, which is the first step of this bootcamp. In general you did a good work, but you could have tried the bonus questions, you are definitely able to do it!. If you try to do some of them and have any question, tell me your doubts! 

Remember also, to show the output of all the cells of your code. 
 
Let's check these assignments!

## 1. Snail and the well

In this exercise, you had to work mainly with `while` loops and it seems that you understood the logic behind them, good work!

During your code cells, you don't need to store the values in variables in every cell. It's enough to store them just one time. 

Inside the while loop, which is the key part of the assignment, the correct answer is adding an if condition for the distance lost during the night. It will be something like this:
```python
while snail_position <= well_height:
    days += 1
    snail_position += daily_distance
    if snail_position <= well_height:
        snail_position += nightly_distance
```
## 2. Duel of sorcerers 

Great work here using the `zip` function, it will useful for you to understand how this function works. 
If you want to optimize your code here, you don't need to create the variable `tie` in any cell. Doing that, you avoid to write an `elif` condition in exercises 3-4. 

As I said, you understood perfectly how while loops and if conditions work. If you have some time, you should try the bonus questions. The structure of the solutions is similar to the one that you performed in the main questions. 

## 3. Bus 

Good work again! You know how to deal with tuples and iterate them, which is really cool! As I said before, remember that you don't have to name variables in each cell, it will save you a lot of time.

Finally, it's interesting that you have used the `statistics` library to calculate the standard deviation!

## 4. Robin Hood

Excellent work here using lists comprehension!! Also you created a function at the beginning of the task, well done!

It seems that you have understood how to work with empty lists and dictionaries, which is really good!

The assignment is perfect, but take in count that in the last exercise, the question was about the arrows that didn't hit the target. 

## 5. Temperature

You had to deal here with some operators and conditionals to answer the questions properly. Remember again that you have to show the output of every cell. 

The logic behind your code is pretty good in general. In question #3 you can optimize your code removing a `for` loop and get the same output. It will be something like this:

```python
hot_list = []
hot_times =0
for t in temperatures_C:
    if t >= 70:
        hot_list.append(t)
        hot_times += 1
```
Good job using slicing to get your estimator, you could either choose among calculating the mean or this option. It seemed that you understood how to do this task, great!

## 6. Rock, paper, scissors

Here, from question #6 to #9 you had to create functions and you already know how, it would be perfect if you spend some time creating them!

In #6 instead of create a variable storing the `random.randint` function from `random` you can directly use `random.choice(gestures)`

If you wanna learn more about the random library, here you will find useful documentation:
https://docs.python.org/3/library/random.html

Be careful with the identation of your code lines, specially with any loop. In this particular case, in exercise 7, you have to move one level to the left your lines of code. It would be something like this: 
```python
player = input("Enter your gesture (rock, paper, scissors): ")
while player != "rock" and player != "paper" and player != "scissors":
    print("! Please enter the valid gesture !")
    player = input("Enter your gesture (rock, paper, scissors): ")
    if player == "rock" and player == "paper" and player == "scissors":
        break
```
Check identations also in exercise 9. Take in mind what the questions ask you everytime, but at the end, the final question is perfect, so congrats, because it was hard to solve!!

If you have some time I encourage you to try the bonus questions again. They are pretty similar to what you did. Keep going!
