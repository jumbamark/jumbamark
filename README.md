<h3 align="center">
  Welcome to Mark's profile!
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28">
</h3>

<p align="center"> 
  Visitor count<br>
  <img src="https://profile-counter.glitch.me/jumbamark/count.svg" />
</p>

<p align="center">            
<a href="https://github.com/jumbamark/github-readme-stats">
  <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=jumbamark&theme=highcontrast" />
</a>
</p>

```python
from dataclasses import dataclass
from typing import Sequence


@dataclass(frozen=True)
class Portfolio:
    name: str = 'Jumba Mark'
    location: str = 'Nairobi Kenya'
    profile: str = 'Python-Django Developer, Linux User'


@dataclass(frozen=True)
class Skills:
    languages: Sequence[str] = 'python', 'shell', 'JavaScript',
    operation_systems: Sequence[str] = 'Linux'
    test_frameworks: Sequence[str] = 'pytest' 
    web_frameworks: Sequence[str] = 'django','django rest-framework', 'react.js'
    ongoing: Sequence[str] = 'React.js'


@dataclass(frozen=True)
class Social:
    github: str = 'https://www.github.com/jumbamark'
    codewars: str = 'https://www.codewars.com/users/jumbamark'
    twitter: str = 'https://twitter.com/_jumbamark_'
    email: str = 'jumbamark@yahoo.com' 
```



