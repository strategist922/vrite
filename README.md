# vrite
An experimental AST-based semantic code editor for python 

## Motivation

- Code is mostly written in text editors.

### Text editors

- Allow writing anything (are a general tool)
- Not needed for programming where only a small subset is a syntactically valid program
- "With great power comes great responsibility"
- Bad Examples:
  - f-String and print statement
  - Deleting one element from two element tuple and also removing the comma (resulting in int instead of tuple)
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


# Features

- Automatic formatting
  - always conforming to style guide
  - Automatic parenthesis
  - Reformat on resize
  - easy syntax highlighting
  - user preferences (e.g. amount of indentation, display mode of individual numbers)
- No syntax errors
- Semantic actions (e.g. "create function")
- Context-aware options (e.g. "return" only valid in function)
- deactivate nodes 
