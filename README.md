# edu_python_mini_lib
Minimal Example of a Python-Lib that is installable via pip

## Installation
Always use `venv` and a `requirements.txt` when you are working on a project.
Add the Repo to your `requirements.txt` by using `-e git+ssh://git@github.com/bjoekeldude/edu_python_mini_lib.git#egg=mylibrary`

## Usage
In order to use the library-functions, make sure to `import` the Library to your project by adding `import mylibrary` in the first few lines of your project.
You may also use `import mylibrary as libalias`.
After that, try to use the function `library_test()` in you code. 
Or `libalias.library_test()` if you declareted an alias ;)
