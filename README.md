# Stacker-lang
####A stack based domain-specific language implemented in Racket 

The language takes in arguments in the form of a stack and each operator applies itself to the 2 numbers above it.

For example, the expressions:
-  push 5
-  push 6
-  +
-  push 3
-  *
  
translate to (5 + 6) * 3 in 'normal' math notation. 

## Usage:
- Download the file "stacker-lang.rkt" and place it inside the same directory as the file with Stacker source code.
- Begin your source file with "#lang reader "stacker-lang.rkt""
- Code away!

###todo:
- Add support for arbitrary number of arguments to primary operators
