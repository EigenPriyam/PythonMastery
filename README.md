# Python Mastery

A hands-on Python learning repository: session-by-session Jupyter notebooks, practice tasks with solutions, interview question banks, and concise PDF revision notes. Built as part of my AI preparation journey, going from Python fundamentals to OOP, file handling, decorators, and generators.

## Contents

### Session notebooks

| Session | Topic |
|---|---|
| 1 | Python fundamentals |
| 2 | Operators, if/else, loops |
| 3 | Strings and lists |
| 4 | Lists in depth |
| 5 | Tuples, sets, dictionaries |
| 6 | Functions |
| 7 | OOP basics |
| 8 | OOP part 2 |
| 9 | OOP part 3 |
| 10 | File handling |
| 11 | Exception handling |
| 12 | Namespaces and decorators |
| - | Time complexity, iterators, generators |

### Practice tasks and solutions
Task notebooks (`session_*_task*.ipynb`, `session10_tasks.ipynb`, `session11_task.ipynb`, `session12_task_generator_decorator_iterator.ipynb`) and solution notebooks (`session_4/5/6_task_solutions.ipynb`), plus `oop_project.ipynb`, a small OOP project.

### Interview preparation
- Weekly question banks: `Week1_Interview_Questions_Ans.ipynb`, `week_2_interview_questions.ipynb`, `Week_3_Interview_Questions.ipynb`, `week3_interview_theory_questions.ipynb`
- `array_interview_questions.ipynb`

### Revision notes (`InterviewNotes/`)
Short PDF cheat sheets covering: Python fundamentals, operators, if/else/modules/loops, strings, lists, tuples, sets, dictionaries, functions, map/filter/reduce, namespaces and scope, OOP, shallow vs deep copy, iterators, generators, decorators, file handling, serialization/deserialization, exception handling, memory/recursion/time complexity, and a `uv` project guide.

### Sample data files
`abc.txt`, `abc_reversed.txt`, `freq.json`, `numbers.txt`, `output.txt`, `sample.txt`, `text_file.txt`, used by the file handling exercises.

## Getting started

Requires Python 3.13+ and [uv](https://docs.astral.sh/uv/).

```bash
git clone <your-repo-url>
cd PythonMastery
uv sync
```

Open any notebook in VS Code or Jupyter, and select the `.venv` interpreter as the kernel.

```bash
uv run jupyter lab   # if you add jupyterlab: uv add jupyterlab
```

## Tech

- Python 3.13
- Jupyter notebooks (`ipykernel`)
- `python-dotenv`, `nlpcloud` (listed dependencies)
- Dependency management with `uv`

## Suggested study order

1. Fundamentals, operators, control flow (sessions 1-2)
2. Strings, lists, tuples, sets, dictionaries (sessions 3-5)
3. Functions and OOP (sessions 6-9)
4. File and exception handling (sessions 10-11)
5. Namespaces, decorators, iterators, generators (session 12 and extras)
6. Interview question banks and PDF notes for revision

## License

Personal learning material, shared for reference.
