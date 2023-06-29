# Markdown Cheatsheet

## basic syntax


### headings : <!-- headings -->
    # heading1
    ## heading2
    ### heading3
    #### heading4
    ##### heading5
    ###### heading6

  # heading1
  ## heading2
  ### heading3
  #### heading4
  ##### heading5
  ###### heading6

---


### horizontal rule <!-- horizontal rule -->
<!-- can use *** or ___ -->
    --- 
    or
    ***
    or
    ___
  ---


### Text Formatting <!-- text formatting -->


  #### italic : <!--italic text-->
    *italic text1* or _italic text2_

  *italic text1* or _italic text2_


  #### bold : <!-- bold text -->
    **bold text1** or __bold text2__

  **bold text1** or __bold text2__


  #### bold and italic : <!-- bold and italic -->

  ***bold and italic text***

  #### strikethrough : <!-- strikethrough text -->
    ~~strikethrough text~~
  ~~strikethrough text~~

---


### List


  #### ordered list : <!-- ordered list -->

  <!-- notice the only number md cares about
       is the first one and it automatically 
       takes care of next numbers-->
    1. one
    2. two
    3. three 
 
  1. one
  2. two
  3. three

 #### unordered list : <!-- unordered list -->
<!-- can use - or + or * -->

    - first         +first         *first
    - second   or   +second   or   *second
    - third         +third         *third
   
  - first 
  - second
  - third


---


### code formatting <!-- code formatting -->


#### Inline code :

    use Javascript `map()` on arrays.
    
  use Javascript `map()` on arrays.

#### fence code block :

  three back ticks will make it a code block
  and by using js or python it will colorize your cod
  <small>(you can use js or py instead of javascript and python)</small>

    ```javascript
    const PI = 3.14
    ```

    ```python
      numbers = [1, 2, 3, 4]
      plus_numbers = [ i+1 for i in numbers]
    ```
  ```javascript
  const PI = 3.14
  ```

  ```python
    numbers = [1, 2, 3, 4]
    plus_numbers = [ i+1 for i in numbers]
  ```

---


### blockquote : <!-- blockquote -->

    > this is a blockquote

    > another blockquote
    >  
    > > blockquote inside blockquote

> this is a blockquote

> another blockquote
>  
> > blockquote inside blockquote


---


### link : <!-- link -->

    [google.com](https://google.com)
    [index file](./index.html)

[google.com](https://google.com)
[index file](./index.html)

 you can add a title , when user hovers over link it will show the title:

    [github](https://github.com "title of link")

  [github](https://github.com "title of link")

link to parts of your markdown file notice we have to use - instead of space:

    [go to code formatting](###code-formatting)

[go to code formatting](###code-formatting)

you can make reference and use that:

    [go to google website][google]

    [google]: https://google.com
    
[go to google website][google]

[google]: https://google.com

---


### images : <!-- images -->

    ![alter_text](./Googel.svg)

![alter_text](./Googel.svg)

<!-- make images link -->
    [![google](./Googel.svg)](https://google.com)

[![google](./Googel.svg)](https://google.com)


---

## extended syntax


from now we are using extended markdowns and it may not work everywhere don't worry it will work on github


### tables: <!-- tables -->

:--- means align text left
:---: means align column text center
---: means align text right 
pipe character doesn't have to be aligned perfectly



    | framework | Description | skill percent |
    | :-------- | :---------: | ------------: |
    | React     |  front-end  |           60% |
    | Django    |  back-end   |           80% |

| framework | Description | skill percent |
| :-------- | :---------: | ------------: |
| React     |  front-end  |           60% |
| Django    |  back-end   |           80% |


---


### task list : <!-- task list -->

which is a modified list that can be used for todo like style

  >- [x]  Html
  >- [x]  Css
  >- [ ]   Javascript

- [x]  Html
- [x]  Css
- [ ]   Javascript


---


### emojis : <!-- emojis -->
    emojis are fun! :joy: :tada:
emojis are fun! :joy: :tada:


---


### comment : <!-- wired syntax for comment -->
    [your comment in here]: #
[comment]: #
[another comment]: #


---


### callout :
  nothing special but a useful pattern to show tips

    > :bulb: **Tip:** here is an important tip to remember
> :bulb: **Tip:** here is an important tip to remember


---


> :bulb: **Tip** : 
    you can use html tags inside your markdown 
    file but markdown syntax won't work
    inside html tags

<!-- toggle -->

make a toggle with html:

### toggle
<details>
  <summary> toggle summary </summary>
        content 1 <br>
        content 2 <br>
        _markdown_ #syntax won't work in ***here***<br>
</details>


---
### make a table of contents
you can make a table of contents with
all in one extension press `Ctrl+Shif+P`
and look for  `table of content` to find all in one extension option.

(#markdown-cheatsheet)
- [Markdown Cheatsheet](#markdown-cheatsheet)
  - [basic syntax](#basic-syntax)
    - [headings : ](#headings--)
- [heading1](#heading1)
  - [heading2](#heading2)
    - [heading3](#heading3)
      - [heading4](#heading4)
        - [heading5](#heading5)
          - [heading6](#heading6)
    - [horizontal rule ](#horizontal-rule-)
    - [Text Formatting ](#text-formatting-)
      - [italic : ](#italic--)
      - [bold : ](#bold--)
      - [bold and italic : ](#bold-and-italic--)
      - [strikethrough : ](#strikethrough--)
    - [List](#list)
      - [ordered list : ](#ordered-list--)
      - [unordered list : ](#unordered-list--)
    - [code formatting ](#code-formatting-)
      - [Inline code :](#inline-code-)
      - [fence code block :](#fence-code-block-)
    - [blockquote : ](#blockquote--)
    - [link : ](#link--)
    - [images : ](#images--)
  - [extended syntax](#extended-syntax)
    - [tables: ](#tables-)
    - [task list : ](#task-list--)
    - [emojis : ](#emojis--)
    - [comment : ](#comment--)
    - [callout :](#callout-)
    - [toggle](#toggle)
    - [make a table of contents](#make-a-table-of-contents)





