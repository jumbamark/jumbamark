<h3 align="center">
  Hi there
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28">
</h3>

## 🌐 Socials:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jumbamark/) [![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/17032431/jumba-mark) [![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/_jumbamark_)

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=63CF15&lines=Trust+but+verify+with+unit+testing+.)](https://git.io/typing-svg)

### About Me
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
    languages: Sequence[str] = 'python', 'shell', 'JavaScript', 'C'
    operation_systems: Sequence[str] = 'Linux'
    test_frameworks: Sequence[str] = 'pytest, unittest' 
    web_frameworks: Sequence[str] = 'django','django rest-framework', 'react.js'
    code_quality: Sequence[str] = 'betty', 'pycodestyle'
    version_control: Sequence[str] = 'git'
    ongoing: Sequence[str] = 'Flutter'


@dataclass(frozen=True)
class Social:
    github: str = 'https://www.github.com/jumbamark'
    codewars: str = 'https://www.codewars.com/users/jumbamark'
    twitter: str = 'https://twitter.com/_jumbamark_'
    email: str = 'jumbamark@yahoo.com' 
```