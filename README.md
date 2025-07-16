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
    * disappointing, just a technical demo of the communication (through `socket`) with a Python server doing OpenCV
  * 13h50 - ~~How to contribute to Python docs in your own language~~
  * 14h30 - ~~Typing at scale: statically type-checking a large codebase~~
    * @JULIEN : replay (for myself only ?)
  * 14h30 - Bridging the gap: Viewing your project through a downstream packager's lens
    * a collection of good practices to ease the job of packagers, but they are often contradicting the development good practices, so there is no globally satisfying solution
    * mostly relevant for OSS maintainers who have their projects packaged downstream
  * 14h30 - ~~The Evolution of Advanced Python Monitoring~~
  * 15h25 - Type Hints in Real-World Projects: Maintenance & Improvement
    * I was late so the room was full, I had to watch the livestream
    * new features in 3.13 : `TypeGuard` and `TypeIs`, backported into `typing_extensions`
    * new syntax for `list`, `dict`, `Optional`, ... (upgrade by `Ruff` or `pyupgrade`)
    * avoid raw `# type: ignore` but add `[attr-defined]` (or other), and avoid `typing.Any`
    * see also its talk at EuroPython 2024, for the decorators better use `ParamSpec` and `Concatenate`
  * 16h05 - The FastAPI-Postgres stack you've been waiting for
    * https://github.com/geldata/gel-python client for the Gel DB (ex: EdgeDB), actually Postgres
    * no, I was not waiting for it
    * a bit too commercial and trying to hype for it
    * said it is not an ORM, it is actually partly an ORM, and sketchily tried to evade the question about it
  * 16h45 - Building a large SaaS AI product with Python: The tale of three ecosystems
    * slow to start
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
