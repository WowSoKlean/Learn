
# Virtual environment for python projects

In this article i'll show you how to set up a 
virtual environment for developing python projects.
A video version series of this article can be found below: 
[Watch part 1](https://youtu.be/glmVJBAf5qA)
[Watch part 2](https://youtu.be/Ellaf5PoR9g)
[Watch part 3](https://youtu.be/HpFVx6QqQRA)

## Why?

Creating a virtual environment is recomended for isolating and separating dependency concerns. Also, if something breaks, it does not compromise anything outside that environment. 

## Deploy

To create this virtual environment, do:

```bash
  python3 -m venv <name_of_your_env>
```
After, do:
```bash
  python3 -m venv <name_of_your_env>
```

This has created your virtual environment.
To activate it, do:

```bash
  source <name_of_your_env>/bin/activate
```

Install and create a django project. Be sure to have your environment initiated:

```bash
  pip install django
  django-admin startproject <project_name>
```


