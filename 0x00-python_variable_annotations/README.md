# 0x00. Python - Variable Annotations

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Learning Objectives](#learning-objectives)
- [Project Structure](#project-structure)
- [Project Requirements](#project-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Author](#author)

## Introduction
The **0x00. Python - Variable Annotations** project focuses on type annotations in Python, which is an optional feature introduced in Python 3.5. Variable annotations help clarify the type of variables, function parameters, and return values, making code more readable and easier to debug. Although type annotations don’t affect runtime behavior, they are useful for code quality checks and ensuring consistency.

## Project Overview
In this project, you will work on several Python scripts that utilize variable annotations. You will annotate function parameters, return types, and variable declarations to specify their expected data types. This is crucial for developing clear, maintainable code and can be combined with type checkers like `mypy`.

### Key topics covered in this project:
- Function annotations
- Type hints for lists, tuples, and dictionaries
- Type checking with `mypy`
- Advanced type annotations using `Union`, `Optional`, `Callable`, etc.

## Learning Objectives
By the end of this project, you should be able to:
1. Understand the purpose of type annotations in Python.
2. Apply type annotations to function parameters and return types.
3. Use built-in types like `List`, `Tuple`, `Dict`, and more in your annotations.
4. Implement type checking in Python using tools like `mypy`.

## Project Structure

Here’s a list of files in this project and their purposes:

1. **0-add.py**
   - Defines a function `add(a: float, b: float) -> float` that adds two floating-point numbers with type annotations.

2. **1-concat.py**
   - Implements a function `concat(str1: str, str2: str) -> str` that concatenates two strings with type hints.

3. **2-floor.py**
   - Defines a function `floor(n: float) -> int` that returns the floor of a floating-point number.

4. **3-to_str.py**
   - Contains a function `to_str(n: float) -> str` that converts a float to a string.

5. **4-define_variables.py**
   - Demonstrates variable annotation by defining variables with specific types, such as integers and strings.

6. **5-sum_list.py**
   - Implements a function `sum_list(input_list: List[float]) -> float` that sums a list of floats.

7. **6-sum_mixed_list.py**
   - Contains a function `sum_mixed_list(mxd_lst: List[Union[int, float]]) -> float` that sums a list with mixed integer and float types.

8. **7-to_kv.py**
   - Implements a function `to_kv(k: str, v: Union[int, float]) -> Tuple[str, float]` that returns a tuple from a string and a number.

9. **8-make_multiplier.py**
   - Defines a function `make_multiplier(multiplier: float) -> Callable[[float], float]` that returns a function to multiply a float by the given multiplier.

10. **9-element_length.py**
    - Contains a function `element_length(lst: Iterable[Sequence]) -> List[Tuple[Sequence, int]]` that returns a list of tuples containing the length of each element in the iterable.

11. **100-safe_first_element.py**
    - Implements `safe_first_element(lst: Sequence[Any]) -> Optional[Any]`, a function that returns the first element of a sequence if it exists, otherwise returns `None`.

12. **101-safely_get_value.py**
    - Defines `safely_get_value(dct: Mapping, key: Any, default: Union[None, T] = None) -> Union[Any, T]`, which safely retrieves a value from a dictionary.

13. **102-type_checking.py**
    - Demonstrates advanced type checking using `mypy` in the script, and focuses on more complex data types and checks.

## Project Requirements
- **Python 3.8+** is required to run the scripts.
- Your code should follow **PEP 484** for type hints and annotations.
- You should install **mypy** for type checking.
  
### Install mypy:
```bash
pip install mypy
