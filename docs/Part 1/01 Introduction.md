# Test Repository

## heading

### smaller heading with no line

Here is how to reference one of the **extra** variables from the **mkdocs.yml** files. The offering.name variable is: {{offering.name}}.

Links to other documents are done like below. You use the html href syntax to do this. Use the *target="_blank"* attribute to make sure all links open in new browser tabs or windows so users don't loose their place in the L3 demonstration guide!

- **IBM:** <a href="https://yourlearning.ibm.com/activity/PLAN-4E64FE2FDBF0" target="_blank">IBM Power Virtual Server Sales Foundation</a>
- **Business Partners:** <a href="https://learn.ibm.com/course/view.php?id=11419" target="_blank">IBM Power Systems Virtual Server Sales Foundation</a>

Images can be included:

![](_attachments/ITZ-1.png)

You should use a border around images to make sure the are visually separated from other content. I use SnagIt!, how about you?

You can also have videos:

![type:video](_videos/GitHubInstallExtension-final.mp4)

You can make things **bold** and you can make things *italic* and guess what, ***bold and italic***.


Bullets are done like this

- bullet 1
- bullet 2
  - and sub-bullets 1
  - and 2



Numbered lists are good for step by step stuff.

1. 
2. 

!!! bug "Bug or as intended, not sure"

    Note, if you don't put a space after the period in you numbered lists, mkdocs treats it differently and
the numbers appear on the same line like this:
    1.
    2.
    

Recall from Center of Excellence style guides, images associated with a numbered item should be indented like the one below.

1. Look at this image.

    Notice how my images lines up with this line of text and the numbered item above. You need to use **4** spaces before the image definition to make things line up properly.

    ![](_attachments/part1_step1.png)
