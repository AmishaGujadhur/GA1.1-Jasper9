# GA1.1-Jasper9

Group assignment 1.1: basic arithmetic functions implemented in the notebooks in `notebooks/`.

## Functions

### `add(a, b)`

- **Notebook:** `notebooks/add_function.ipynb`
- **Input:** Two values, `a` and `b`, that support Python's `+` operator. Integers and floats are the intended inputs.
- **Output:** The sum `a + b`.
- **Example:** `add(2, 6)` returns `8`.
- **Errors:** Raises a Python `TypeError` when the inputs cannot be added.

### `sum_list(values)`

- **Notebook:** `notebooks/add_function.ipynb`
- **Input:** An iterable of values. The intended input is a list of integers.
- **Output:** The sum of all values in `values`. An empty iterable returns `0`.
- **Example:** `sum_list([1, 2, 3])` returns `6`.
- **Errors:** Raises an error when `values` is not iterable or when one of its values cannot be added to the running total.

### `multiply(a, b)`

- **Notebook:** `notebooks/multiply.ipynb`
- **Input:** Two values, `a` and `b`, that support Python's `*` operator. Integers and floats are the intended inputs.
- **Output:** The product `a * b`.
- **Example:** `multiply(3, 4)` returns `12`.
- **Errors:** Raises a Python `TypeError` when the inputs cannot be multiplied.

### `square(x)`

- **Notebook:** `notebooks/multiply.ipynb`
- **Input:** One value, `x`, that can be multiplied by itself. Integers and floats are the intended inputs.
- **Output:** The square `x * x`.
- **Example:** `square(7)` returns `49`.
- **Errors:** Raises an error when `x` cannot be multiplied by itself.

### `subtract(a, b)`

- **Notebook:** `notebooks/subtract.ipynb`
- **Input:** Two values, `a` and `b`, that support Python's `-` operator. Integers and floats are the intended inputs.
- **Output:** The difference `a - b`.
- **Example:** `subtract(5, 3)` returns `2`.
- **Errors:** Raises a Python `TypeError` when the inputs cannot be subtracted.

### `distance_from_zero(x)`

- **Notebook:** `notebooks/subtract.ipynb`
- **Input:** One numeric value, `x`.
- **Output:** The value of `x - 0`. For numeric inputs, this is the signed distance from zero as implemented by the function.
- **Example:** `distance_from_zero(5)` returns `5`.
- **Errors:** Raises an error when `x` cannot be subtracted from zero.

## Notes

The functions do not perform explicit type validation. Their behavior depends on the corresponding Python arithmetic operator, so unsupported input types may raise `TypeError` or another operator-specific exception.


