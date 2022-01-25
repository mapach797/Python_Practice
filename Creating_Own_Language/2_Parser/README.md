Will create a parser, which takes the tokens created by the lexer and builds up an abstract tree, basically the tree from the code.

EX: 2 + (3 * 6.5)

    (INT:2, PLUS, (INT:3, MUL, FLOAT:6.5))

EX: 8 + 24 * 3
    (INT: 8, PLUS, (INT:24, MUL, INT:3))