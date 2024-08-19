## Other common formatting techniques

Code blocks should be used when specifying text that the user should enter or copy and paste. 

!!! Danger "Potential conflict with current Sales Enablement Center of Excellence (COE)"

    The COE alls for using the IBM Plex Mono Light font. While it may be possible to load fonts on the backend web server as part of the generated HTML code, that is not done today. The default font used by the material theme does use a monotype font for code blocks.

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

Did it work? Nope. However, it does work when it is in a numbered list so this helps us meet our style guidelines.

1. one
2. two
    ```
    trying again
    ```
3. three 

