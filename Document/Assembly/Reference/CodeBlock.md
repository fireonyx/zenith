A code block can be used to store a group of code, when used, a memory chunk will be allocated to contain the code for the code block. Your code will go between the `{` and `}`.

**Basic Example**
```firestone:ast
{}
``` 

**Multiple Code Blocks**
Muliple code blocks can exist side by side.
```firestone:ast
{} {} {}
```

**Nested Code Blocks**
Code blocks can also exist inside another code block.
```firestone:ast
{
    {
        {

        }
    }

    {

    }
}

{
    {

    }

    {
        {
            {

            }
        }
    }
}
```