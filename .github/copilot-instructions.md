# Copilot Instructions for hello-world

## Project Overview

This is a beginner Python learning project containing simple command-line utility scripts. The codebase demonstrates basic Python concepts: input handling, string manipulation, and numeric operations.

## Project Structure

- **`print('hello world').py`**: Interactive greeting program that takes user name input, normalizes whitespace, and displays a personalized greeting.
- **`Calculator`** (no extension): Simple division calculator that accepts two float inputs and returns the result rounded to 3 decimal places.

## Key Patterns & Conventions

### Input Handling
All scripts use `input()` for interactive user prompts. Always validate and convert input types appropriately (e.g., `float()` in Calculator for numeric inputs).

### String Processing
The greeting script demonstrates the common pattern for string normalization:
```python
clean = " ".join(name.split())  # Remove extra whitespace
```
Use `.title()` for capitalizing names/titles consistently.

### Numeric Operations
Use `round()` with explicit precision (e.g., `round(x / y, 3)`) when displaying calculated results.

## Development Workflow

1. **Running scripts**: Execute directly with `python3 <filename>` from the project root
2. **Testing approach**: Manual interactive testing via terminal (no automated tests currently)
3. **Python version**: Python 3.x (confirmed by shebang and type conversion patterns)

## Guidance for AI Agents

- Keep scripts simple and focused on single operations
- Maintain interactive prompts that are clear and concise
- Use descriptive variable names (`x`, `y`, `z` for math; `name`, `clean` for strings)
- Include brief comments explaining the "why" behind operations
- Follow the existing minimal structure (no classes/functions for these simple utilities)

