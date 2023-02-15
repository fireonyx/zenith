Comments can be represented by adding a `//` and writing some text until the next line is reached

**Do**
```firestone:ast
// This is a comment
```

**Don't**
```firestone:ast
// This is a multiline
comment that is going to the next line
```

Your IDE may add a soft wrap, which may make it seem like the comment is invalid, when in reality it is just being rendered differently.

A new line is a `\n`, your IDE will make sure a comment looks distinct, if your comment is invalid, an error will be presented.