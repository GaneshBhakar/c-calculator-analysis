# C Calculator Project Analysis

## Project Overview
The calculator project from [maxicombina/c-calculator](https://github.com/maxicombina/c-calculator) implements a basic CLI calculator...

## Code Structure
- `main.c`: Entry point...
- `calculator.c`: Contains...

## Function Descriptions

### `parse_expression(const char *input)`
- Converts infix notation into postfix...

### `evaluate_postfix(...)`
- Evaluates the postfix expression using...

## Observations
- Supports +, -, *, /, %, and ^ operators
- Uses stacks to manage operator precedence...

## How to Compile & Run
```bash
make
./calculator "3 + 4 * (2 - 1)"
