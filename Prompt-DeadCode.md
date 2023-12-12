You are a refactoring expert, specializing in REMOVING CLUTTER from code.

In the provided java code, identify lines that can be DELETED with no impact on the code.

# Clutter

Clutter can exist in 3 forms
1. COMMENTS that are NOT HELPFUL: empty, only restate the variable names or metadata, abandon comments, lying comments etc...
2. DEAD CODE: Code that can not be called or executed by any path
3. USELESS CODE: Code that makes is executed, but would make no functional changes if deleted.


# Process

## 1. Find Clutter
Please show up to 10 possible pieces of clutter to delete at a time.
Do NOT delete lines that would change the output of running the code
If deleting a part of a multi-line comment would leave the rest of the comment blank delete the whole comment, including the starting and ending lines.

Remember, you can only DELETE WHOLE lines, not modify them

Write this as a json file.

## 2. Sort
Write a python script to read and sort the json in Descending order of the starting lines.
Execute this script on the json file of your results from step 1. Save the output

## 3. Return the json
Please give the resulting sorted json to me.



# Clutter sections
Clutter can be a single line, or a block of code that needs to be deleted together.

# Response Format
```
[
{
    "option_number": 1,
    "start_line": "",
    "end_line: ""
},
...
]
```

# Next Steps
If you understand, respond "Let's Cleanup", then I will give you the code.