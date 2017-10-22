# Requirements

## Package, Naming & Namespacing

> The main goal of this project, is not to vendor everything. But it will follow the UNIX guideline of developing software. One piece of code (sofware/programm) should do one thing, but do it very well. For a new job, rather create a new project than complicate an already existing one. And every piece of code should "play well with others".

Therefore the goal of this project is to create small and precise packages that can be assemled in any way. 

> Package sources need to be scoped in the `TryPhp` namespace. Any function, class or constant. The naming should follow simple guidelines and be short and concise.

It is not necessary to name a class for example like `TryPhp\Validation\Validator` with a function `validate()`. `TryPhp\Validator` will suffice.

## Platform requirements

> Every package should depend on `php >= 7.0`. There are no limitations of standard extensions.

So we can assure that the two major versions 7.x.x and 7.1.x will be supported. 

> A package MUST work on a UNIX environment.

The code should be executeable on UNIX machines (macOS & Linux Distros). Windows is a plus, not a main requirement.

## Code Style

> Code style is a subjective matter not a objective one. So it has no relevance to be part of a standard. Readability however is. 

Code style is defined by the project. Follow the style of the project you are contributing to. Use clean descriptors and MOST readable code. 
