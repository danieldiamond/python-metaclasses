## Deep Dive into Python MetaClasses
Highlights from a great talk by James Powell found [here.](https://www.youtube.com/watch?v=cKPlPJyQrt4)

In this repo you will find notebooks highlighting when and why to use
various metaclasses.
1. [Data Model Methods](./DataModel.ipynb)
    - intro to data models
2. [Generators](./Generators.ipynb)
    - What are generators and when to use them.
    - Eager vs Lazy Loading
3. [Decorators](./Decorators.ipynb)
    - investigate runtime objects
4. [Context Managers](./ContextManagers.ipynb)
    - Putting it all together: combining generators, decorators and context managers

#### NOTE: In python you will always find this pattern:
top-level function or syntax and a corresponding `__method__` function
