# Binary Search

- [Challenge information](#challenge-information)
- [Solution](#solution)
- [References](#references)
- [Flag](#flag)

## Challenge information
```
Tags: Easy, General Skills, picoCTF2024, shell, browser_webshell_solvable, ls
Author: JEFFERY JOHN

Description:
Want to play a game? As you use more of the shell, you might be interested in how they work! Binary search is a classic algorithm used to quickly find an item in a sorted list. Can you find the flag? You'll have 1000 possibilities and only 10 guesses.
Cyber security often has a huge amount of data to look through - from logs, vulnerability reports, and forensics. Practicing the fundamentals manually might help you in the future when you have to write your own tools!
You can download the challenge files here:.. [challenges.zip](https://play.picoctf.org/practice/challenge/442?category=5&difficulty=1&page=1)

Hints:
1. Have you ever played hot or cold? Binary search is a bit like that.
2. You have a very limited number of guesses. Try larger jumps between numbers!
3. The program will randomly choose a new number each time you connect. You can always try again, but you should start your binary search over from the beginning - try around 500. Can you think of why?
```

Challenge link: [https://play.picoctf.org/practice/challenge/442?category=5&difficulty=1&page=1](https://play.picoctf.org/practice/challenge/442?category=5&difficulty=1&page=1)

## Solution

First, I downloaded the challenges zip file and tried to edit the bash script to print the target number directly, but it didn't work. Instead, I had to guess the number. So, I guessed numbers from 1 to 1000 with the help of feedback to determine if my guess was higher or lower, and I found the flag.

<img src="solution.jpg" width="300" />

## References

- [Edit file in Linux](https://stackoverflow.com/questions/35695160/how-to-edit-a-text-file-in-my-terminal)
- [Execute .sh Files](https://medium.com/@dassandrew3/how-to-execute-sh-files-71d8885d8ef3#:~:text=A%20file%20with%20the%20%E2%80%9C.,files%20in%20Unix%20or%20Linux.)

## Flag

picoCTF{g00d_gu355_ee8225d0}