# europython2025-recap

My recap of the EuroPython 2025.

From 2025-07-14 to 2025-07-20 in Prague (Czech Republic).

* Monday and Tuesday : tutorials (workshops)
* Wednesday, Thursday and Friday : conferences (talks)
* Saturday and Sunday : sprints (contribution to Open Source)

Additional events :

* Tuesday evening : speakers' dinner
* Wednesday evening : "pyvo" (beer)
* Thursday morning : data leaders breakfast
* Thursday evening : social event

## Tutorials

### Monday morning : Rambo Python

@Julien : clarify that the repo is the end-goal, that participants should start a new one
@Julien : prepare formatting/typechecking/typing exercices
@Julien : rename the repo to not have a dash (`-`) in its name, for the `package = true` trick

### Monday afternoon : PyScript

May be useful in some cases, still not convinced of its potential for global adoption (too many edge cases to not being a first-party Python target, nor a first-party for browsers)

### Tuesday morning : CI/CD with Python, K8s, TestContainers, AWS, Jenkins, ...

A total waste of time. I left as soon as possible.

### Tuesday morning : Cleaner Code, Better Queries: SQLAlchemy, ORMs and asyncio

Very well prepared, clear, and insightful.

Repo : https://github.com/rhythm-patel/sqlalchemy-workshop

Course : https://aelsayed95.github.io/sqlalchemy-wkshop/

### Tuesday afternoon : Packaging Summit

Super interesting ! Too many things going too fast to take notes myself.

Shared notes : https://hackmd.io/-RZmb68eSsyCTk-aTZ8Q4g

PyCon US notes : https://hackmd.io/3AUJd0GkRFKHclfzULowTw

## Conferences

Planning :

* Wednesday
  * 09h30 - You don’t have to be a compiler engineer to work on Python
    * interesting, but the talk's message was quite simple : "there are many ways to contribute, and they may be simpler than you expect"
  * 10h45 - Design Pressure: The Invisible Hand That Shapes Your Code
    * @Julien : replay at Kaizen
  * 10h45 - ~~Teamwork makes the dream work~~
  * 10h45 - Myths and fairy tales around Python performance
    * very interesting, made clear what are the problems caused by Python's extreme dynamicity
    * at the end, Antonio Cuni presented what he thinks is the way towards a more efficient Python, and this bold direction he started to follow by implementing a proof-of-concept language `SPy`
  * 11h40 - Inside the Black Box: The Anatomy of Virtual Environments
    * interesting, mostly the comparison between CPython's and uv's venvs
    * just a description of what they contain, no real insight on their role in the current ecosystem
  * 12h20 - Building my own (accurate!) Spotify Wrapped
    * great talk ! actually delivers what its title promised : an actually good and insightful Spotify Wrapped, without much work (for European citizens only, through RGPD)
    * @Julien : replay at Kaizen for the Data team ?
  * 12h50 - [poster] Exploring LLM latency
    * intéressant, mais je ne sais pas quoi en tirer
  * 13h50 - Godot & Python: open source in game development
    * déçevant, juste une démo technique de communication (via socket) avec un serveur qui fait du OpenCV
  * 13h50 - ~~How to contribute to Python docs in your own language~~
  * 14h30 - ~~Typing at scale: statically type-checking a large codebase~~
    * @JULIEN : replay (personnel ?)
  * 14h30 - Bridging the gap: Viewing your project through a downstream packager's lens
    * une collection de bonnes pratiques pour faciliter la vie des packagers, mais souvent en contradiction avec les bonnes pratiques de dev, donc y'a pas de bonne solution
    * surtout pertinent pour les OSS maintainers qui ont leurs projets packagés downstream
  * 14h30 - ~~The Evolution of Advanced Python Monitoring~~
  * 15h25 - Type Hints in Real-World Projects: Maintenance & Improvement
    * la salle était pleine, j'ai été obligé de regarde rle livestream
    * nouvelle features en 3.13 : `TypeGuard` et `TypeIs`, backportées dans `typing_extensions`
    * nouvelle syntaxe pour `list`, `dict`, `Optional`, ... (upgrade par `Ruff` ou `pyupgrade`)
    * éviter raw `# type: ignore` et rajouter `[attr-defined]`, et `typing.Any`
    * cf son talk à l'EuroPython 2024, pour les décorateurs penser à `ParamSpec` et `Concatenate`
  * 16h05 - The FastAPI-Postgres stack you've been waiting for
  * 16h45 - Building a large SaaS AI product with Python: The tale of three ecosystems
  * 17h30 - Python quiz
  * 17h45 - Lightning talks

* Thursday
  * 09h20 - Why it took 4 years to get a lock files specification
  * 10h30 - A new safe external debugger interface for CPython
  * 10h30 - Intuition vs. Reality: Surprising Truths in Python Performance
  * 11h25 - Choosing Between Free Threading and Async
  * 11h25 - Testing the Tests - Assess and Improve Your Python Testing Code
  * 12h05 - Fixtures meets parameters: Writing efficient, elegant and reusable tests
  * 12h45 - Turbocharge your Python test suite today!
  * 13h15 - [poster] Preserving Culture with Python: AI plays Ayo, a Traditional Nigerian Game
  * 14h15 - Pydantic, Everywhere, All at Once
  * 14h15 - Snapshot Testing: A New Era of Reliability
  * 14h55 - Good Practices for Testing Web User Interfaces
  * 14h55 - Continuous Documentation: basics and advanced techniques
  * 15h50 - End to End with Testcontainers and Playwright
  * 16h30 - Behind the scenes of FastAPI and friends for developers and builders
  * 17h15 - Lightning talks

Friday:
  * 09h00 - The Boom of Generative AI: realities, promises and awkward situations
  * 10h10 - ...

## Sprints

TODO
