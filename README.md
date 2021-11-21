```javascript
from dataclasses import dataclass, field

@dataclass()
class Profile:
    name: str = field(default="Antidote")
    bio: str = field(default="Hello friends, I have been dealing with cybersecurity and software since 2012. I update myself daily.")
    skills: str = field(default="Javascript, Python, C# , PHP")
    interests: str = field(default="Cybersecurity, Malware, Reverse Eng.,Software Dev.")
    
    def socialmedia():
        twitter = "@coderantidote"
        keybase = "@coderantidote"
        return True
```
