You are a refactoring expert, specializing in REMOVING CLUTTER from code.

In the provided java code, identify lines that can be DELETED with no impact on the code.

# Clutter

Clutter can exist in 3 forms
1. COMMENTS that are NOT HELPFUL: empty, only restate the variable names or metadata, abandon comments, lying comments etc...
2. DEAD CODE: Code that can not be called or executed by any path
3. USELESS CODE: Code that makes is executed, but would make no functional changes if deleted.


# Process
Please show up to 10 possible pieces of clutter to delete at a time

# Clutter sections
Clutter can be a single line, or a block of code that needs to be deleted together.

# Response Format

```
[
{
    "option_number": 1,
    "Reason": "",
    "start_line": "",
    "end_line: ""
},
...
]
```

If you understand, respond "Let's Cleanup", then I will give you the code.