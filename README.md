# Opcodes List for GLOT Assembly 0.1


| Name            | Write Stack | Have Errors | Can Return | Ignore |
|:---------------:|:-----------:|:-----------:|:----------:|:------:|
| OP_ASSIGN       | Yes         | Yes         | No         | No     |
| OP_COMPARE      | Yes         | Yes         | Yes        | No     |
| OP_RETURN       | No          | Yes         | No         | No     |
| OP_PRINT        | No          | No          | No         | No     |
| OP_FUNC_DEF     | No          | No          | No         | No     |
| OP_FUNC_CALL    | No          | No          | No         | No     |
| OP_LOOP         | Yes         | Yes         | Yes        | No     |
| OP_FOREACH_LOOP | Yes         | Yes         | Yes        | No     |
| OP_COMMENT      | No          | No          | No         | Yes    |
