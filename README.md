# Python Data Science Audio Example

Download data from:

`https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio/`

Copy to `../RAVDESS/<project-folder>`

## Install

`poetry install`

Select local pyenv in VSCode/editor

## Requirements

### Pyenv

`brew install pyenv`

### Python 3.11.6

`xz` may be required

`brew install xz`

`pyenv install 3.11`

### Poetry

`pip install poetry`

Ensure pyenv is local to project:

`poetry config virtualenvs.in-project true`

### llvm@14

`brew install llvm@14`

Make sure paths specify `@14`

```
export PATH="/usr/local/opt/llvm@14/bin:$PATH"
export LDFLAGS="-L/usr/local/opt/llvm@14/lib"
export CPPFLAGS="-I/usr/local/opt/llvm@14/include"
```

### cmake

`pip install cmake`