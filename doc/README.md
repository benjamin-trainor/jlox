## Lox - Java
Crafting Interpreters
- Lox.java
- Scanner.java
- Token.java
- TokenType.java

### Lox - Lexical Grammar

expression → literal | unary | binary | grouping ;

literal -> NUMBER | STRING | "true" | "false" | "nil" ;

grouping -> "(" expression ")" ;

unary -> ( "-" | "!" ) expression ;

binary → expression operator expression ;

operator -> "==" | "!=" | "<" | "<=" | ">" | ">=" | "+" | "-" | "*" | "/" ;

