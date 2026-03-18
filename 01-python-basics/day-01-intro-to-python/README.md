# Day 1 — Introduction to Programming & Python

## Topics covered
- What is Python and why it's used in data science
- Python syntax and indentation rules
- PEP 8 style guide basics
- IDEs — Jupyter Notebook vs VS Code

## Key concepts
- High-level, interpreted, dynamically typed language
- 4-space indentation (no tabs)
- snake_case for variables, PascalCase for classes
- f-strings for string formatting

## Assignment — "Hello Analyst" script
Print a personalised message using variables and string formatting.
```python
student = "Your Name"
course  = "Data Science"
batch   = "2026"
print(f"Hello, {student}!")
print(f"Welcome to {course} — Batch {batch}.")
print("Let's build something amazing!")
```

## Resources
- W3Schools Python Intro — https://www.w3schools.com/python
- Programming with Mosh – Python Crash Course (1 hr) — YouTube
- PEP 8 Style Guide — https://peps.python.org/pep-0008

## Files in this folder
| File | Description |
|------|-------------|
| `README.md` | This file — day overview |
| `day01_notes.ipynb` | Full lecture notebook |
| `python_2026_day1_notes.pdf` | Tutor handout PDF |
| `hello_analyst.py` | Assignment solution |
```

---

**One thing to fix in your current structure** — looking at the screenshot, you have a folder called `Notes` inside `01-python-basics` instead of `day-01-intro-to-python`. The correct structure should be:
```
01-python-basics/
├── day-01-intro-to-python/
│   ├── README.md          ← you're creating this now ✓
│   ├── day01_notes.ipynb
│   └── hello_analyst.py
├── day-02-variables/
└── ...
