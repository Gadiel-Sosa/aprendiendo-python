# Virtual environments

A simple guide to using a virtual environment.

---

## What is a virtual environment?

It is an isolated space where you can install libraries for your project.

Every project contains its own dependencies without affecting others.

**Advantages:**

- It doesn't mix libreries between projects.
- It avoid version conflicts.
- You can use different Python versions.


## Windows 

1. Make sure you are in your project folder (e.g., `C:\Users\Your Name>` — you can use `cd`).
2. Run this command: `python -m venv myfirstproject`
3. Finally, you should see this estructure inside your folder:

```myfirstproject
  Include
  Lib
  Scripts
  .gitignore
  pyvenv.cfg 
```
4. Now you can activate the venv with this command: `myfirstproject\Scripts\activate`


## Mac and Linux

1. Make sure you are in your project folder (e.g., `C:\Users\Your Name>` — you can use `cd`).
2. Run this command: `python -m venv myfirstproject`
3. Finally, you should see this estructure inside your folder:

```myfirstproject
  Include
  Lib
  Scripts
  .gitignore
  pyvenv.cfg 
```
4. Now you can activate the venv with this command: `source myfirstproject/bin/activate`