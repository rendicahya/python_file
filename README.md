# Python File Utilities

A Python library for file-related tasks.

## Installation

This library is designed to be used as a git submodule:
```bash
git submodule add https://github.com/rendicahya/python_file.git
```

## Dependencies
```bash
pip install tqdm
```

This project depends on another project that must also be installed as a submodule in the main project:
```bash
git submodule add https://github.com/rendicahya/assertpy.git
```

## Available Functions

### 1. `count_files()`

Returns the number of files in a directory. Parameters:
- `recursive` (boolean, default: `True`)
- `ext` (string, default: `None`)

Usage:
```python
from python_file import count_files

path = "/some/path"
n_files = count_files(path, recursive=True, ext=".txt")
```
