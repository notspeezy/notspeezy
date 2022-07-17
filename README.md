<p align="left"> <img src="https://komarev.com/ghpvc/?username=speezyw&label=Profile%20views&color=0e75b6&style=flat" alt="speezyw" /> </p>

```python
from GitHub import ReadMe
import random, sys, os

os.system("clear") if sys.platform == "linux" else os.system("cls")

ReadMe.init()

def README():
    username = "speezy"
    age = "16"
    location = "France"
    programming_language = "Python"
    infos = {
        "Discord Server": "https://discord.gg/55yy7skbQ4",
        "YouTube Channel": "https://youtube.com/c/speezyw"
    }
    contacts = [
        "sp#5084",
        "@notspeezy",
        "@hzmicid"
    ]
    print("Hi my name is " + username + " and I am " + age + " years old")
    print("I live in " + location)
    print("Self learner of " + programming_language)
    print("You can contact me here: " + random.choice(contacts))
    input("Press enter when you're done reading")
    
if __name__ == "__main__":
    os.system("title About me & mode con: cols=90 lines=30")
    README()
```
```python
Output: 
Hi my name is speezy and I am 16 years old
I live in France
Self learner of Python
You can contact me here: sp#5084
Press enter when you're done reading
```
