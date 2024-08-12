A few other things I do often...

### Code blocks
Code blocks are nice since the draw attention to text that the user may need to type somewhere in some user interface you are talking about. Notice the copy icon at far left. This is really nice, especially when what the user needs to copy and paste is complex. 

```
ls -l
```

It also supports language specific highlighting:

```python
def fn():
    pass
```

The documentation says "Note that fenced code blocks can not be indented. Therefore, they cannot be nested inside list items, blockquotes, etc.", but we can try

   ```
   this code is indented
   ```

Did it work? Nope. thats too bad as this doesn't help us fit into our style guide for being indented under numbered items.

1. one
2. two
   ```
   trying again
   ```
3. three 
