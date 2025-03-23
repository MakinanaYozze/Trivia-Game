# Trivia-Game
This Python trivia game project demonstrates the real world application. Here, I explain my thought process and how I came up with ideas so you can understand my thought process. I am walking youthrough the theory I have learned which helped me apply the skills I gained in my learning journey. This project is great for me because I applied the basics of Python such as If statements, For loop, and variables. Firstly, I planned this project on how I  am going to execute the steps:
- I need a list of questions
- Store the answers to these questions
- The questions are associated with the Python coding language
- Ask the questions
- See if they are correct
- Keep track of the score
- Tell the user the score
Firstly, broken the smaller steps into sub-problems that are quite easier for me to tackle. I am using a Dictionary in my code.  A Dictionary in Python, is a key value store. It allows you to have some kind of key and a value. In this case, my key is the question and value is the answer that is associated with question. The reason that I am doing this is because I can quickly look up what the answer to a particular question. I am using the Dictionary as a teaching opportunity and that I am avoiding having a messy list.
- I have my questions and answers pairing each other.
- To randomly pick the questions I need.
- I imported the "random" module at the top of my code.
- Then, define a function where most of the code for project is going to live. So, that I can run the function agaim if I want to continually run the game multiple times. And if you have not seen a function before, essentially this is a "reusable block of code".
- You define a function using the "def" keyword, you write the name of the function and then put a set of parentheses() and a colon: anything that is indented belongs to that function. And can be used multiple times.

The "def python_trivia_game(): is what the project game is actually about.
The questions_list = list(questions.keys())
    total_questions = 5
is the number of questions I want to randomly selected from questions. Otherwise I could have chosen to select them all 10 questions. Hence, I used the random.sample(questions_list, total_questions) line 21.
And notice, all of my variables here that I am trying to give them a meaningful  name and something that make sense, and that even if you someone did not know how to code, they would be able to read this program. So, whenever you are writing your code, you must make sure everything reads like English. 

The purpose of this python_trivia_game is to show you my thought process of how I created a little bit of my plan. I went through the plan step by step. Obviously, I did not explain some of the steps here, but generally you will kind of follow this so you that you get where I started and it was a ;ot easier for me to create this code because I knew the steps that I needed to follow and I did not have to stop constantly and keep thinking about what to do next. I am sure some of this code might be a little bit confusing, but I wanted to not really focus on the theory but to get directly into the project. So, you can see exactly how to write this code project and analyze the whole code yourself.

So generally, what to take away from this is when you are building out some kind of a coding project always start by asking yourself, what do I actually need to do? How can I break this down into smaller steps that are easier for me to tackle. And my advice is to get in the habit of doing that early. It is going to help you a lot later on in your coding journey. 
