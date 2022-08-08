<p align="left"> <img src="https://komarev.com/ghpvc/?username=speezyw&label=Profile%20views&color=321CBA&style=for-the-badge" alt="speezyw" /> </p>

```python
import random, os

os.system("cls") if os.name == "nt" else os.system("clear")

class ReadMe:
    def __init__(self, username: str, age: str, location: str, language: str):
        self.username = username
        self.age = age
        self.location = location
        self.language = language

    
    def About(self):
        contacts = {
            "discord_server": "https://discord.gg/hcaptcha",
            "youTube_channel": "https://youtube.com/c/speezyw",
            "contacts": [
                "sp#5084 on discord",
                "@notspeezy on telegram",
                "@hzmicid on instagram"
            ]
        }
        print(f"Hi, my name is {self.username} and I am {self.age} years old.")
        print(f"I live in {self.location}")
        print(f"Self learner of {self.language}")
        print("Where could you contact me?")
        print(f"Discord Server: {contacts['discord_server']}")
        print(f"YouTube Channel: {contacts['youTube_channel']}")
        print(f"Social: {random.choice(contacts['contacts'])}")
        input("Press enter when you're done reading.")

    
if __name__ == "__main__":
    os.system("title About me & mode con: cols=90 lines=30")
    ReadMe(
        "speezy",
        "16",
        "France",
        "Python"
    ).About()
```
```python
Output: 
Hi, my name is speezy and I am 16 years old.
I live in France
Self learner of Python
Where could you contact me?
Discord Server: https://discord.gg/hcaptcha
YouTube Channel: https://youtube.com/c/speezyw
Social: @notspeezy on telegram
Press enter when you're done reading.
```
