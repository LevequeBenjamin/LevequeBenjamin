```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class Developer:

    def __init__(self):
        self.name = "Lévêque Benjamin"
        self.role = "Developer"
        self.language_spoken = ["fr_FR", "en_US"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")


me = Developer()
me.say_hi()
```
