```javascript
from dataclasses import dataclass, field

@dataclass()
class Profile:
    name: str = field(default="Antidote")
    bio: str = field(default="Hello friends, I have been dealing with cybersecurity and software since 2012.")
    skills: str = field(default="Javascript, Python, Golang, C#, PHP, C/C++, Micro C/BSC/PAS, Pascal")
    interests: str = field(default="Cybersecurity, Malware, Reverse Eng.,Software Dev.")
    
    def socialmedia():
        twitter = "@coderantidote"
        keybase = "@coderantidote"
        return True
```
<img src="https://tryhackme-badges.s3.amazonaws.com/antidote1337.png" alt="TryHackMe">
