# empty <stmt>

- `!` Assert
- `x` Break (if in loop)
- `c` Class
- `C` Continue (if in loop)
- `D` Delete
- `f` For (Async)
- **`d` Function (Async)**
- `g` Global
- `i` If
- `I` Import (From)
- `n` Nonlocal (if in function)
- `p` Pass
- `R` Raise
- **`r` Return (if in function)**
- `t` Try
- `w` While
- `W` With (Async)

# empty <expr>

- `A` Await (if in async?)
- `b` Bytes
- `{` Dict (DictComp)
- `.` Ellipsis
- `?` IfExp
- `l` Lambda
- **`[` List (ListComp)**
- **`s` Name**
- `TFN` NameConstant (True, False, None)
- **`n` Num**
- `s` Set (SetComp)
- `S` Starred ?
- `"` Str (JoinedStr, FormattedValue)
- `(` Tuple (GeneratorExp)
- `` UnaryOp ?
- `y` Yield (From)

# selected <expr>

- **`a` Assign (AugAssign, AnnAssign)**
- `` Attribute
- `` BoolOp
- **`+` BinOp**
- `` Call
- `` Compare
- `` Subscript
