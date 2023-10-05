# pythonfrp

pythonfrp is an attempt to bring reactive programming into python.

## What is Reactive Programming?

Simply put, reactive programming uses continuous time and data flow instead of explicit time.

The [wikipedia](http://en.wikipedia.org/wiki/Reactive_programming) article has a good explanation.

## Usage

A simple hello world:

    from pythonfrp.Engine import *
    from pythonfrp.Printer import printer

    printer(x = integral(1, 0))
    start(tSteps = 10)

## Documentation and website

All documentation and other information used to be found at our website, [reactive-engine.org](http://www.reactive-engine.org), but that's gone now; now see the archived (2017-07-25) [Reactive Panda](https://web.archive.org/web/20170725062950/http://wiki.western.edu/mcis/index.php?title=Reactive_Panda_Web_Site) web site. There are also papers:

- Cleary, A., Vandenbergh, L. & Peterson, J. (2015). Reactive Game Engine Programming for STEM Outreach. In A. Decker, K. Eiselt, C. Alphonce & J. Tims (eds.), Proceedings of the 46th ACM Technical Symposium on Computer Science Education, February, : ACM
  - [doi: 10.1145/2676723.2677312](https://doi.org/10.1145/2676723.2677312)
- Peterson, J., Cleary, A. & Roe, K. (2015). PyFRP: Function Reactive Programming in Python
  [PDF](http://www.cs.jhu.edu/~roe/pyfrp-function-reactive.pdf)

## Installation

(Added 2023 by @gdmcbain.)

```PowerShell
python -m venv .venv
Add-Content .git/info/exclude ".venv/", ".vscode/"
.venv/Scripts/Activate.ps1
python -m pip install -U pip
python -m pip install -e .
python
```

Then try the example from the _Usage_ above. It doesn't work.
