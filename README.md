# Simple Java Parser

Key Learning Focus:

1. Lexical Analysis (Scanner/Tokenizer)
   - Breaking source code into tokens
   - Token classification:
     * Keywords (if, else, int, boolean)
     * Identifiers (variable names)
     * Operators (+, -, ==)
     * Literals (numbers, strings)
     * Delimiters ({, }, ;)
   - Handling whitespace and comments
   - Error detection for invalid characters

2. Parsing
   - Symbol table management
   - Basic type checking
   - Error handling and recovery

## Features
- Variable declaration parsing with type checking
- Comparison expression parsing
- Control flow parsing (if-else, while, for statement parsing)
- Symbol table generation and tracking
- Error handling for both parsing and lexical errors

## Files
- `java.jj` - The main JavaCC grammar file
- `*.txt` - Test files

## Build & Run Instructions

### Using Make
1. Build and runthe project:
   ```bash
   make
   ```

2. Clean generated files:
   ```bash
   make clean
   ```

## Error Handling
The parser provides detailed error messages including:
- Line and column numbers for parse errors
- Lexical error descriptions
- Symbol table contents after successful parsing

## Symbol Table
The parser maintains a symbol table that tracks:
- Variable names
- Variable types
- Symbol table contents are displayed after each successful parse
