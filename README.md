# Code_Compiler

**INTELLIJ PROJECT** 

Written in Java along with the use of ANTLR as part of a University assignment.

A Lexer and Parser for a simple programming language. 

Checks for syntax errors, and can output answers to code that follows the correct coding convention.

**Example 1:**

**INPUT:**

```
bool main(int n, int d) {
  collatzA(n, d)
}

int collatzA(int qoz29, int depth) {
  if (qoz29 == 4)
  then { print qoz29; print space; depth }
  else {
    if ((2*(qoz29 / 2)) == qoz29)
    then { print qoz29; print space; collatzA((qoz29 / 2), (depth + 1)) }
    else { print qoz29; print space; collatzA(((qoz29 * 3) + 1), (depth + 1)) }
  }
}
```

**OUTPUT:**
```
Wrong return type declared for main function
```
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Example 2:**

  **INPUT:**
```  
int main(int n)
{
    int a := 0;
    int i := 1;
    while (i <= n) do {

      a := (a + i);
      i := (i + 1)
    };
    a
}
```

**OUTPUT:**

```
NORMAL_TERMINATION
0

NORMAL_TERMINATION
1

NORMAL_TERMINATION
5050
```
