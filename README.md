# vrite
An experimental AST-based semantic code editor for python 

## Motivation

- Code is mostly written in text editors.

### Text editors

- Allow writing anything (are a general tool)
- Not needed for programming where only a small subset is a syntactically valid program
- "With great power comes great responsibility"
- Bad Examples:
  - simple syntax error
  - f-String and print statement (py2/3 incompatibility)
  - Deleting one element from two element tuple and also removing the comma (resulting in int instead of tuple)
  - Swapping operands: `a%3 * b/5` vs. `b/5 * a%3`
  - Style guide violation
  - Tabs vs. spaces
- "Do we really need all that power?"
  
- Idea: what if programmer was only given manipulation choices that lead to (syntactically) correct code?

### ASTs

- Internal representation of a program used by the interpreter.
- Contains all information necessary to execute the program, but nothing more.
- Formatting, ... are not part of the AST
- Example: some simple program

### Structure editors

---TODO

- Related Projects

# Features

## Viewing

- Display AST so that it's easy to understand for humans:
  - non-monospace fonts are easier to read
  - Doesn't need to have unambiguous syntax
  - always conforming to style guide
  - Automatic parenthesis
  - Reformat on resize
  - easy syntax highlighting
  - user preferences (e.g. amount of indentation, display mode of individual numbers)

## Editing

- No syntax errors
- Semantic navigation
- Semantic actions (e.g. "create function" instead of typing character by character)
- choice of actions limited to those that yield a valid program.
- Context-aware options (e.g. "return" only valid in function)
- deactivate nodes 

# Demo 

- This is an experiment
- Do not use for real code
- only covers a small subset of the python syntax

## Features to show

- assignment
- binop
- functiondef (simplified)
- list
- import?
- return

# Discussion

- 
