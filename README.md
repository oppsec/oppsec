```py
from secrets import about_me

class myInfo():
  def __init__(self, name: str, age: int, working: bool, langs: list) -> None:
     self.name = name
     self.age = age
     self.working = working
     self.langs = langs

myInfo("Daniel", 17, True, ["Brazilian Portuguese", "English"])
```
