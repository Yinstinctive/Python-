[]{#609}

<div>

  -------------- ------------------------
  **Created:**   *8/16/2018 4:44 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

MAC/LINUX Commend Line:

</div>

-   <div>

    pwd \# print working directory\

    </div>

<!-- -->

-   <div>

    cd \#"change directory"

    </div>

<div>

            "." stands for current directory\

</div>

<div>

            ".." stands for parent directory. This allows for relative
navigation\

</div>

-   <div>

    ls \# list the contents of a directory. You can supply options such
    as "-a" to list all files (including hidden ones), or "-l" for a
    longer format

    </div>

-   <div>

    mkdir \#make directory

    </div>

-   <div>

    touch \# the command "touch" followed by the filename and file-type
    extension will create a new file of that type

    </div>

-   <div>

    mv \# files can be moved or renamed using the "mv" keyword, which
    takes two arguments: the source and the destination

    </div>

<div>

            mv favs.text GOAT.txt \#rename\

</div>

<div>

            mv GOAT.txt ../ \#move to parent directory\

</div>

-   <div>

    rm \#remove

    </div>

<div>

            Directories can also be deleted using "rm" keyword, with the
added option "-r"(recursive). You can also use "-f" (force) to prevent
warnings\

</div>

<div>

\

</div>

<div>

Formatting Strings

</div>

-   <div>

    F - Strings (new in Python 3.6):

    </div>

<div>

            x=10\

</div>

<div>

            formatted = f"I've told you {x} times already!"\

</div>

-   <div>

    .format method (Python 2-3.5)

    </div>

<div>

            x=10\

</div>

<div>

            formatted = "I've told you {} times already".format(x)\

</div>

<div>

\

</div>

<div>

Converting Data Types:

</div>

<div>

    decimal = 12.34234\

</div>

<div>

    integer = int (decimal) \#12\

</div>

<div>

\

</div>

<div>

Getting User Input:

</div>

<div>

    name = input ("Enter your name here:")\

</div>

<div>

\

</div>

<div>

Conditional Statements:

</div>

<div>

if \<condition\>:

</div>

<div>

    do something\

</div>

<div>

elif \<condition\>:

</div>

<div>

    do something\

</div>

<div>

else:

</div>

<div>

    do something\

</div>

<div>

\

</div>

<div>

Truthiness:

</div>

<div>

    x=1\

</div>

<div>

    x is 1 \# True\

</div>

<div>

    x is 0 \# False\

</div>

<div>

    \

</div>

<div>

    empty objects, empty strings, None and zero ---\> naturally falsy\

</div>

<div>

\

</div>

<div>

    animal = input(\"enter your favorite animal\")    

</div>

<div>

    if animal:

</div>

<div>

        print(animal + \" is my favorite too!\")

</div>

<div>

    else:

</div>

<div>

        print(\"YOU DIDNT SAY ANYTHING!\")

</div>

<div>

\

</div>

<div>

Difference between is and "=="

</div>

<div>

    a = 1\

</div>

<div>

    a == 1 \# True\

</div>

<div>

    a is 1 \# True\

</div>

<div>

\

</div>

<div>

    a = \[1,2,3\]\

</div>

<div>

    b = \[1,2,3\]\

</div>

<div>

    a == b \# True\

</div>

<div>

    a is b \# False\

</div>

<div>

\

</div>

<div>

for loops

</div>

<div>

for item in iterable\_object:

</div>

<div>

    \# do something with item\

</div>

<div>

\

</div>

<div>

range

</div>

<div>

range(7) \# 0-6

</div>

<div>

range(1,8) \# 1-7

</div>

<div>

range(1,10,2) \# 1,3,5,7,9

</div>

<div>

range(7,0,-1) \#integer from 7 to 1

</div>

<div>

\

</div>

<div>

while loops

</div>

<div>

while \<condition\>

</div>

<div>

    \# do something\

</div>

<div>

\
\

</div>

<div>

\

</div>

</div>

------------------------------------------------------------------------

[]{#503}

<div>

  -------------- ------------------------
  **Created:**   *8/16/2018 2:01 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

<div>

tasks = \["Install Python", "Learn Python", "Take a break"\]

</div>

<div>

tasks = list(range(1,4)) \#convert range to a list

</div>

<div>

[len(task)]{style="font-weight: bold;"} \#get list length

</div>

<div>

\

</div>

<div>

friends = \["Ashley", "Matt", "Michael"\]

</div>

<div>

\#You can use a negative number to index backwards

</div>

<div>

print(friends\[-1\]) \#"Michael"

</div>

<div>

\

</div>

<div>

[\#Check if a value is in a list]{style="font-weight: bold;"}

</div>

<div>

"Ashley" in friends \#True

</div>

<div>

\

</div>

<div>

[\#Accessing all values in a list]{style="font-weight: bold;"}

</div>

<div>

\

</div>

<div>

numbers = \[1,2,3,4\]

</div>

<div>

for number in numbers:

</div>

<div>

    print(number)

</div>

<div>

\

</div>

<div>

numbers = \[1,2,3,4\]

</div>

<div>

i=0

</div>

<div>

while i\<len(numbers):

</div>

<div>

    print(numbers\[i\])

</div>

<div>

    i += 1

</div>

<div>

\

</div>

<div>

\

</div>

<div>

[list.append()]{style="font-weight: bold;"} \# add an item to the end of
the list

</div>

<div>

[list.extend()]{style="font-weight: bold;"} \# add to the end of a list
all values passed to extend

</div>

<div>

[list.insert()]{style="font-weight: bold;"} \# insert an item at a given
position, e.g. list.insert(2, "Hi!") 注意：insert(-1,'the
end\')实际插入在新list的倒数第二个

</div>

<div>

[list.clear()]{style="font-weight: bold;"} \# remove all items from the
list

</div>

<div>

[list.pop()]{style="font-weight: bold;"} \# remove the item at the given
position in the list, and return it. If no index is specified, removes &
returns last item in the list

</div>

<div>

[list.remove()]{style="font-weight: bold;"} \# Remove the first item
from the list whose value is x. Throws a ValueError if the item is not
found

</div>

<div>

\

</div>

<div>

[list.index()]{style="font-weight: bold;"} \# returns the index of the
specified item in the list. Can specify start and end.

</div>

<div>

    e.g. 

</div>

<div>

    numbers = \[5,5,6,7,5,8,8,9,10\]

</div>

<div>

    numbers.index(5) \# 0

</div>

<div>

    numbers.index(5,1)  \# look up start from index 1, result = 1

</div>

<div>

    numbers.index(5,2) \# result = 4

</div>

<div>

    numbers.index(8,6,8) \#result = 6

</div>

<div>

    numbers.index(4) ---\> ValueError

</div>

<div>

[list.count()]{style="font-weight: bold;"} \# returns the number of
times x appears in the list

</div>

<div>

[list.reverse()]{style="font-weight: bold;"} \# reverse the elements of
the list (in-place)

</div>

<div>

[list.sort()]{style="font-weight: bold;"} \# sort the items of the list
(in-place), ascending by default. Uppercase come first over lowercase

</div>

<div>

[list.join()]{style="font-weight: bold;"} \#technically a String method
that takes an iterable argument. Concatenates (combines) a copy of the
base string between each item of the iterable

</div>

<div>

    e.g.

</div>

<div>

    words = \['Coding', 'Is', 'Fun!'\]

</div>

<div>

    ' '.join(words) \# 'Coding Is Fun!'

</div>

<div>

    name = \['Mr', 'Steele'\]

</div>

<div>

    '. '.join(name) \#'Mr. Steele'

</div>

<div>

\

</div>

<div>

[Slicing: Make new lists using slices of the old
list]{style="font-weight: bold;"}

</div>

<div>

    some\_list\[start:end:step\]

</div>

<div>

e.g.

</div>

<div>

    first\_list = \[1,2,3,4\]

</div>

<div>

    first\_list\[1:\] \# \[2,3,4\]

</div>

<div>

    first\_list\[-3:\] \# \[2,3,4\]

</div>

<div>

    first\_list\[:2\] \# \[1,2\]

</div>

<div>

    first\_list\[1:3\] \#\[2,3\]

</div>

<div>

    With negative numbers, how many items to exclude from the end (i.e.
indexing by counting backwards)

</div>

<div>

    first\_list\[:-1\] \# \[1,2,3\]

</div>

<div>

    first\_list\[1:-1\] \# \[2,3\]

</div>

<div>

    first\_list\[1::2\] \# \[2,4,6\]

</div>

<div>

    first\_list\[::2\] \# \[1,3,5\]

</div>

<div>

    With negative numbers, reverse the order

</div>

<div>

    first\_list\[1:-1\] \# \[2,1\]

</div>

<div>

    first\_list\[:1:-1\] \# \[6,5,4,3\]

</div>

<div>

    first\_list\[2::-1\] \# \[3,2,1\]

</div>

<div>

\

</div>

<div>

[Tricks with Slices]{style="font-weight: bold;"}

</div>

-   <div>

    Reversing lists / strings

    </div>

<div>

        string = "This is fun!"

</div>

<div>

        string\[::-1\]

</div>

-   <div>

    Modifying portions of lists

    </div>

<div>

        numbers = \[1,2,3,4,5\]

</div>

<div>

        numbers\[1:3\] = \['a','b','c'\]

</div>

<div>

        print(a) \#\[1,'a','b','c',4,5\]

</div>

<div>

***\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--***

</div>

<div>

***Important Note:***

</div>

::: {style="background-color:rgb(239, 240, 241);color:rgb(57, 51, 24);font-family:Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif;font-size:13px;font-variant-caps:normal;font-variant-ligatures:normal;letter-spacing:normal;orphans:2;widows:2;word-spacing:0px;"}
[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[=]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[\[]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[1]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
:::

::: {style="background-color:rgb(239, 240, 241);color:rgb(57, 51, 24);font-family:Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif;font-size:13px;font-variant-caps:normal;font-variant-ligatures:normal;letter-spacing:normal;orphans:2;widows:2;word-spacing:0px;"}
[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[\[]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[0]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[:]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[=]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[\[]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[4]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[5]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
:::

::: {style="background-color:rgb(239, 240, 241);color:rgb(57, 51, 24);font-family:Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif;font-size:13px;font-variant-caps:normal;font-variant-ligatures:normal;letter-spacing:normal;orphans:2;widows:2;word-spacing:0px;"}
[print]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(16, 16, 148);"}
[a
\#\[4,5,3\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
:::

::: {style="margin: 0px; padding: 0px 15px 0px 0px; border: 0px; font-variant-ligatures: normal; font-variant-caps: normal; font-family: Arial, "Helvetica Neue", Helvetica, sans-serif; font-size: 13px; vertical-align: top; flex-grow: 0; width: auto; grid-column: 1 / auto; color: rgb(36, 39, 41); letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255);"}
::: {style="margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-size: 13px; vertical-align: baseline; box-sizing: inherit; text-align: center; min-width: 46px;"}
::: {style="margin: 0px auto 10px; padding: 0px; border: 0px; font-size: 1px; color: rgb(0, 119, 204); cursor: pointer; background-image: url("../../Img/unified/sprites.svg?v=e5e58ae7df45"), none; background-repeat: no-repeat; overflow: hidden; text-indent: -9999em; width: 40px; height: 30px; background-position: 0px -220px;" title="This answer is not useful"}
[down
vote]{style="border: 0px; font-size: 1px; color: rgb(0, 119, 204); cursor: pointer; background-image: url("../../Img/unified/sprites.svg?v=e5e58ae7df45"), none; background-repeat: no-repeat; overflow: hidden; text-indent: -9999em; width: 40px; height: 30px; background-position: 0px -220px;"
title="This answer is not useful"}
:::
:::
:::

::: {style="margin: 0px; padding: 0px; border: 0px; font-variant-ligatures: normal; font-variant-caps: normal; font-family: Arial, "Helvetica Neue", Helvetica, sans-serif; font-size: 13px; flex-shrink: 1; width: auto; min-width: 0px; grid-column: 2 / auto; color: rgb(36, 39, 41); letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255);"}
::: {style="margin: 0px 0px 5px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: 1.3; font-family: Arial, "Helvetica Neue", Helvetica, sans-serif; font-size: 15px; vertical-align: baseline; box-sizing: inherit; width: 666px; overflow-wrap: break-word;"}
::: {style="margin: 0px 0px 1em; padding: 0px; border: 0px; font-size: 15px; clear: both;"}
[When you
specify]{style="border: 0px; font-size: 15px; clear: both;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; clear: both; background-color: rgb(239, 240, 241); white-space: pre-wrap;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[on
the left side of
the]{style="border: 0px; font-size: 15px; clear: both;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[=]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; clear: both; background-color: rgb(239, 240, 241); white-space: pre-wrap;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[operator,
you are using
Python\'s]{style="border: 0px; font-size: 15px; clear: both;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[normal
assignment]{style="border: 0px; font-size: 15px; clear: both; font-weight: bold;"}[,
which changes the
name]{style="border: 0px; font-size: 15px; clear: both;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; clear: both; background-color: rgb(239, 240, 241); white-space: pre-wrap;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[in
the current context to point to the new value. This does not change the
previous value to
which]{style="border: 0px; font-size: 15px; clear: both;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; clear: both; background-color: rgb(239, 240, 241); white-space: pre-wrap;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[was
pointing.]{style="border: 0px; font-size: 15px; clear: both;"}
:::

::: {style="margin: 0px 0px 1em; padding: 0px; border: 0px; font-size: 15px; clear: both;"}
[By
specifying]{style="border: 0px; font-size: 15px; clear: both;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[a\[0:2\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; clear: both; background-color: rgb(239, 240, 241); white-space: pre-wrap;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[on
the left side of
the]{style="border: 0px; font-size: 15px; clear: both;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[=]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; clear: both; background-color: rgb(239, 240, 241); white-space: pre-wrap;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[operator,
you are telling Python you want to
use]{style="border: 0px; font-size: 15px; clear: both;"}[ ]{style="border: 0px; font-size: 15px; clear: both;"}[Slice
Assignment]{style="border: 0px; font-size: 15px; clear: both; font-weight: bold;"}[.
Slice Assignment is a special syntax for lists, where you can insert,
delete, or replace contents from a
list:]{style="border: 0px; font-size: 15px; clear: both;"}
:::

::: {style="margin: 0px 0px 1em; padding: 0px; border: 0px; font-size: 15px; clear: both;"}
[Insertion]{style="border: 0px; font-size: 15px; clear: both; font-weight: bold;"}[:]{style="border: 0px; font-size: 15px; clear: both;"}
:::

::: {style="margin: 0px 0px 1em; padding: 5px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; vertical-align: baseline; box-sizing: inherit; width: auto; max-height: 600px; overflow: auto; background-color: rgb(239, 240, 241); color: rgb(57, 51, 24); overflow-wrap: normal;"}
<div>

[\>\>\>]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[=]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[\[]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[1]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[\>\>\>]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[\[]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[0]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[:]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[0]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[=]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[\[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[1]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[0]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[\>\>\>]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}

</div>

<div>

[\[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[1]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[0]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[1]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}

</div>
:::

::: {style="margin: 0px 0px 1em; padding: 0px; border: 0px; font-size: 15px; clear: both;"}
[Deletion]{style="border: 0px; font-size: 15px; clear: both; font-weight: bold;"}[:]{style="border: 0px; font-size: 15px; clear: both;"}
:::

::: {style="margin: 0px 0px 1em; padding: 5px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; vertical-align: baseline; box-sizing: inherit; width: auto; max-height: 600px; overflow: auto; background-color: rgb(239, 240, 241); color: rgb(57, 51, 24); overflow-wrap: normal;"}
<div>

[\>\>\>]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}

</div>

<div>

[\[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[1]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[0]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[1]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[\>\>\>]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[\[]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[:]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[4]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[=]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[\[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[\>\>\>]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}

</div>

<div>

[\[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[1]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}

</div>
:::

::: {style="margin: 0px 0px 1em; padding: 0px; border: 0px; font-size: 15px; clear: both;"}
[Replacement]{style="border: 0px; font-size: 15px; clear: both; font-weight: bold;"}[:]{style="border: 0px; font-size: 15px; clear: both;"}
:::

::: {style="margin: 0px 0px 1em; padding: 5px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; vertical-align: baseline; box-sizing: inherit; width: auto; max-height: 600px; overflow: auto; background-color: rgb(239, 240, 241); color: rgb(57, 51, 24); overflow-wrap: normal;"}
<div>

[\>\>\>]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}

</div>

<div>

[\[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[-]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[1]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[\>\>\>]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[\[:\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[=]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[\[]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[1]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[\>\>\>]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[a]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}

</div>

<div>

[\[]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}[1]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[2]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[,]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}
[3]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(125, 39, 39);"}[\]]{style="border: 0px; font-family: Consolas, Menlo, Monaco, "Lucida Console", "Liberation Mono", "DejaVu Sans Mono", "Bitstream Vera Sans Mono", "Courier New", monospace, sans-serif; font-size: 13px; background-color: rgb(239, 240, 241); color: rgb(48, 51, 54);"}

</div>
:::
:::
:::

<div>

[\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--]{style="font-weight: bold; font-style: italic;"}

</div>

<div>

[\
]{style="font-weight: bold;"}

</div>

<div>

[Swapping Values]{style="font-weight: bold;"}

</div>

<div>

    names = \["James", "Michelle"\]

</div>

<div>

    names\[0\], names\[1\] = names\[1\], names\[0\]

</div>

<div>

    print(names) \#\['Michelle','James\'\]

</div>

<div>

\

</div>

<div>

[List Comprehension]{style="font-weight: bold;"}

</div>

<div>

\[ \_ for \_ in \_ \]

</div>

<div>

e.g.

</div>

<div>

nums = \[1,2,3\]

</div>

<div>

\[ x\*10 for x in nums \#\[10,20,30\]

</div>

<div>

\

</div>

<div>

friends = \['ashley', 'matt', 'michael'\]

</div>

<div>

\[friend\[0\].upper() for friend in friends\] \#\['Ashely', 'Matt',
'Michael'\]

</div>

<div>

\

</div>

<div>

\[num\*10 for num in range(1,6)\] \#\[10,20,30,40,50\]

</div>

<div>

\

</div>

<div>

\[bool(val) for val in \[0,\[\],\''\]\] \#\[False, False, False\]

</div>

<div>

\

</div>

<div>

numbers = \[1,2,3,4,5\]

</div>

<div>

string\_list = \[str(num) for num in numbers\]

</div>

<div>

print(string\_list) \#\['1', '2', '3', '4','5'\]

</div>

<div>

\

</div>

<div>

[List Comprehension with Conditional Logic]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

numbers = \[1,2,3,4,5,6\]

</div>

<div>

evens = \[num for num in numbers if num%2 == 0\]

</div>

<div>

odds = \[num for num in numbers if num%2 != 0\]

</div>

<div>

\

</div>

<div>

\[num\*2 if num%2 ==0 else num/2 for num in numbers\] \#
\[0.5,4,1.5,8,2.5,12\]

</div>

<div>

\

</div>

<div>

with\_vowels = "This is so much fun!"

</div>

<div>

' '.join(char for char in with\_vowels if char not in "aeiou") \# "Ths s
s mch fn!"

</div>

<div>

\

</div>

<div>

[Nested List]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

nested\_list = \[\[1,2,3\],\[4,5,6\],\[7,8,9\]\]

</div>

<div>

nested\_list\[0\]\[1\] \#2

</div>

<div>

\

</div>

<div>

[Printing Values in Nested Lists]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

nested\_list = \[\[1,2,3\],\[4,5,6\],\[7,8,9\]\]

</div>

<div>

for l in nested\_list:

</div>

<div>

    for val in l:

</div>

<div>

        print(val)

</div>

<div>

\

</div>

<div>

[Nested List Comprehension]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

nested\_list = \[\[1,2,3\],\[4,5,6\],\[7,8,9\]\]

</div>

<div>

\[\[print(val) for val in l\] for l in nested\_list\]

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

</div>

</div>

------------------------------------------------------------------------

[]{#596}

<div>

  -------------- ------------------------
  **Created:**   *8/22/2018 11:56 AM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

[Limitations of Lists]{style="font-weight: bold;"}

</div>

<div>

Not enough information while want to describe data in more detail.

</div>

<div>

\

</div>

<div>

[Dictionary]{style="font-weight: bold;"}

</div>

<div>

A data structure that consists of key value pairs. We use the keys to
describe our data and the values to represent the data.

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

instructor = {

</div>

<div>

    "name": "Colt",

</div>

<div>

    "owns\_dog": True,

</div>

<div>

    "num\_courses": 4,

</div>

<div>

    "favorite\_languuage": "Python",

</div>

<div>

    "is\_hilarious": False,

</div>

<div>

    44: "my favorite number! \"

</div>

<div>

}

</div>

<div>

keys and values separated by a colon

</div>

<div>

our keys are almost always numbers or strings

</div>

<div>

\

</div>

<div>

[dict function]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

another\_dictionary = dict(key1 = 'value1', key2 = 'value2', .. )

</div>

<div>

\

</div>

<div>

[Accessing Individual Values]{style="font-weight: bold;"}

</div>

<div>

instructor\["name"\] \# "Colt"

</div>

<div>

\

</div>

<div>

for value in [instructor.values()]{style="font-weight: bold;"}:

</div>

<div>

    print(value)

</div>

<div>

\

</div>

<div>

for k in [instructor.keys()]{style="font-weight: bold;"}:

</div>

<div>

    print(k)

</div>

<div>

\

</div>

<div>

for key,value in [instructor.items()]{style="font-weight: bold;"}:

</div>

<div>

    print(f"key is {key} and value is {value}")

</div>

<div>

\

</div>

<div>

[Test if a key exists in a dictionary]{style="font-weight: bold;"}

</div>

<div>

e.g "name" in instructor \# True

</div>

<div>

\

</div>

<div>

[Test if a dictionary have a value]{style="font-weight: bold;"}

</div>

<div>

e.g. "Colt" in instructor.values() \# True

</div>

<div>

\

</div>

<div>

instructor.clear() \# clears all the keys and values in a dictionary

</div>

<div>

\

</div>

<div>

clone = instructor.copy()

</div>

<div>

clone is instructor \# False

</div>

<div>

\

</div>

<div>

[fromkeys: creates key-value pairs from comma separated
values]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

{}.fromkeys(\"a\",\"b\") \# {\'a\': \'b\'}

</div>

<div>

{}.fromkeys(\"a\",\[1,2,3,4,5\]) \# {\'a\':\[1,2,3,4,5\]}

</div>

<div>

\

</div>

<div>

new\_user = {}.fromkeys(\[\'name\', \'score\', \'email\'\], \'unknown\')

</div>

<div>

new\_user \#{\'name\':\'unknown\', \'score\':\'unknown\',
\'email\':\'unknown\'}

</div>

<div>

\

</div>

<div>

[get: retrieves a key in an object and return None instead of a KeyError
if the key does not exist]{style="font-weight: bold;"}

</div>

<div>

d = dict(a=1,b=2,c=3) ==

</div>

<div>

d.get(\'a\') \#1

</div>

<div>

d.get(\'no\_key\') \#None

</div>

<div>

\

</div>

<div>

[[dict.get(key, default =
None)]{style="background-color: rgb(241, 241, 241); color: rgb(49, 49, 49); font-family: Menlo, Monaco, Consolas, "Courier New", monospace; font-variant-caps: normal; font-variant-ligatures: normal; font-weight: bold; font-size: 12pt;"}]{style="box-sizing: border-box; border-radius: 0px; width: 604px; border: 1px solid rgb(214, 214, 214); background-color: rgb(241, 241, 241); overflow: auto; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

\

</div>

<div>

[pop: takes a single argument corresponding to a key and removes that
key-value pair from the dictionary. Returns the value corresponding to
the key that was removed.]{style="font-weight: bold;"}

</div>

<div>

d = dict(a=1,b=2,c=3)

</div>

<div>

d.pop(\'a\') \#1

</div>

<div>

d \# {\'c\':3, \'b\':2}

</div>

<div>

\

</div>

<div>

[popitem: removes a random key in a
dictionary]{style="font-weight: bold;"}

</div>

<div>

d.popitem()

</div>

<div>

\

</div>

<div>

[update: update keys and values in a dictionary with another set of key
value pairs]{style="font-weight: bold;"}

</div>

<div>

person = {\"city\": \"Antigua\"}

</div>

<div>

person.update(instructor)

</div>

<div>

person\[\"name\"\] = \"Evelia\"

</div>

<div>

person.update(instructor)

</div>

<div>

person.update({})

</div>

<div>

\

</div>

<div>

[Data Modeling:]{style="font-weight: bold;"}

</div>

<div>

playlist = {

</div>

<div>

    \'title\': \'patagonia bus\',

</div>

<div>

    \'author\': \'colt steele\',

</div>

<div>

    \'songs\': \[

</div>

<div>

        {\'title\': \'song1\', \'artist\': \[\'blue\'\],
\'duration\':2.5},

</div>

<div>

        {\'title\': \'song2\', \'artist\': \[\'kitty\',\'djcat\'\],
\'duration\':5.25},

</div>

<div>

        {\'title\': \'meomeow\', \'artist\': \[\'garfield\'\],
\'duration\':2.0}

</div>

<div>

    \]

</div>

<div>

}

</div>

<div>

\

</div>

<div>

total\_length = 0

</div>

<div>

for song in playlist\[\'songs\'\]:

</div>

<div>

    total\_length += song\[\'duration\'\]

</div>

<div>

print(total\_length)

</div>

<div>

\

</div>

<div>

\

</div>

<div>

[Dictionary Comprehension:]{style="font-weight: bold;"}

</div>

<div>

{ \_\_:\_\_ for \_\_ in \_\_}

</div>

<div>

iterates over keys by default

</div>

<div>

to iterate over keys and values using . items()

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

numbers = dict(first=1, second=2, third=3)

</div>

<div>

squared\_numbers = {key:value \*\* 2 for key, value in numbers.items()}

</div>

<div>

print(squared\_numbers) \#{\'first\':1, \'second\':4, \'third\':9}

</div>

<div>

\

</div>

<div>

num\_list = \[1,2,3,4\]

</div>

<div>

{num:(\"even\" if num%2==0 else \"odd\") for num in num\_list}
\#{1:\'odd\', 2: \'even\', 3:\'odd\', 4:\'even\'}

</div>

<div>

 

</div>

</div>

------------------------------------------------------------------------

[]{#608}

<div>

  -------------- ------------------------
  **Created:**   *9/7/2018 2:10 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

[Tuple: An ordered collection or grouping of
items]{style="font-weight: bold;"}

</div>

<div>

e.g. numbers = (1,2,3,4)

</div>

<div>

It is immutable. Can never be changed.

</div>

<div>

\

</div>

<div>

locations = {

</div>

<div>

    (35.6895, 39.6917): \"Tokyo Office\",

</div>

<div>

    (40.7128, 74.0060): \"New York Office\"

</div>

<div>

}

</div>

<div>

// cannot use list as dictionary key

</div>

<div>

\

</div>

<div>

[Why use a Tuple?]{style="font-weight: bold;"}

</div>

<div>

Tuples are faster than lists

</div>

<div>

It makes your code safer

</div>

<div>

Valid keys in a dictionary

</div>

<div>

Some methods return them to you - like .items() when working with
dictionaries

</div>

<div>

\

</div>

<div>

[Creating/Accessing Tuple]{style="font-weight: bold;"}

</div>

<div>

e.g.()

</div>

<div>

first\_tuple = (1,2,3,3,3)

</div>

<div>

first\_tuple\[1\] //2

</div>

<div>

first\_tuple\[-1\] //3

</div>

<div>

\

</div>

<div>

value = (1,) \#need comma , 

</div>

<div>

**\
**

</div>

<div>

**tuple() constructor**

</div>

<div>

thistuple = tuple((\"apple\",\"banana\",\"cherry\"))

</div>

<div>

\

</div>

<div>

We can use a for loop to iterate over a tuple just like a list

</div>

<div>

e.g.

</div>

<div>

numbers = (1,2,3,4)

</div>

<div>

for num in numbers:

</div>

<div>

    print(num)

</div>

<div>

\

</div>

<div>

[Tuple ]{style="font-weight: bold;"}[methods]{style="font-weight: bold;"}

</div>

<div>

count: returns the number of times a value appears in a tuple

</div>

<div>

e.g.

</div>

<div>

x = (1,2,3,3,3)

</div>

<div>

x.count(3) \#3

</div>

<div>

\

</div>

<div>

index: returns the index at which a value is found in a tuple

</div>

<div>

x.index(1) \#0

</div>

<div>

x.index(3) \#2 - only the first matching index is returned

</div>

<div>

\

</div>

<div>

**\
**

</div>

<div>

**Sets: **

</div>

<div>

sets are like formal mathematical sets

</div>

<div>

sets do not have duplicate values

</div>

<div>

elements in sets are not ordered

</div>

<div>

you cannot access items in a set by index

</div>

<div>

sets can be useful if you need to keep track of a collection of
elements, but don\'t care about ordering, keys or values and duplicates

</div>

<div>

\

</div>

<div>

**Creating/Accessing**

</div>

<div>

s = set({1,4,5})

</div>

<div>

s = {1,4,5}

</div>

<div>

4 in s \#True

</div>

<div>

\

</div>

<div>

\#remove duplicates

</div>

<div>

cities = \[\'a\', \'b\',\'b\',\'c\',\'\'d\]

</div>

<div>

list(set(cities))

</div>

<div>

**\
**

</div>

<div>

**add: adds an element to a set. if the element is already in the set,
the set doesn\'t change**

</div>

<div>

s = set(\[1,2,3\])

</div>

<div>

s.add(4) \#{1,2,3,4}

</div>

<div>

**\
**

</div>

<div>

**remove: removes a value from the set - returns a KeyError if the value
is not found**

</div>

<div>

s.remove(2)

</div>

<div>

**\
**

</div>

<div>

**could use .discard if do not want error**

</div>

<div>

s.discard(5)

</div>

<div>

\

</div>

<div>

**copy: creates a copy of the set**

</div>

<div>

another\_s = s.copy()

</div>

<div>

\

</div>

<div>

**clear: removes all the contents of the set**

</div>

<div>

s.clear()

</div>

<div>

\

</div>

<div>

**Set Math**

</div>

<div>

math\_students = {\"Matthew\", \"Helen\", \"Prashant\", \"James\",
\"Aparna\"}

</div>

<div>

biology\_students = {\"Jane\", \"Matthew\", \"Charlotte\", \"Mesut\",
\"Oliver\", \"James\"}

</div>

<div>

\

</div>

<div>

math\_students \| biology\_students \# union \|

</div>

<div>

math\_students & biology\_students \# intersection &

</div>

<div>

\

</div>

<div>

**Set Comprehension**

</div>

<div>

e.g.

</div>

<div>

{x\*\*2 for x in range(10)} \#{0,1,64,4,36,9,16,49,81,25}

</div>

<div>

{char.upper() for char in \'hello\'} \# {\'O\',\'L\', \'H\', \'E\'}

</div>

<div>

\

</div>

<div>

string = \"hello\"

</div>

<div>

{char for char in string if char in \'aeiou\'} \#{\'e\', \'o\'}

</div>

</div>

------------------------------------------------------------------------

[]{#607}

<div>

  -------------- ------------------------
  **Created:**   *9/10/2018 9:45 AM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

<div>

[Why Use Functions?]{style="font-weight: bold;"}

</div>

<div>

Stay DRY - Don\'t Repeat Yourself

</div>

<div>

Clean up and prevent code duplication

</div>

<div>

\"Abstract away\" code for other users

</div>

<div>

\

</div>

<div>

[Function Structure]{style="font-weight: bold;"}

</div>

<div>

def name\_of\_function ():

</div>

<div>

    \# block of runnable code

</div>

<div>

e.g.

</div>

<div>

def say\_hi():

</div>

<div>

    print(\'Hi!\')

</div>

<div>

\

</div>

<div>

[Returning Values from Functions]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

def square\_of\_7():

</div>

<div>

    return 7\*\*2

</div>

<div>

\

</div>

<div>

[return]{style="font-weight: bold;"}

</div>

<div>

exits the function

</div>

<div>

outputs whatever value is placed after the return keyword

</div>

<div>

pops the function off the call stack

</div>

<div>

\

</div>

<div>

[Parameters vs Arguments]{style="font-weight: bold;"}（形参vs实参）

</div>

<div>

A parameter is a variable in a method definition

</div>

<div>

When a method is called, the arguments are the data you pass into the
method\'s parameters

</div>

<div>

Parameter is variable in the declaration of function

</div>

<div>

Argument is the actual value of this variable that get passed to
function

</div>

<div>

\

</div>

<div>

[Default Parameters]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

def exponent(num, power=2):

</div>

<div>

    return num \*\* power

</div>

<div>

print(exponent(2,3)) \#8

</div>

<div>

print(exponent(3)) \#9

</div>

<div>

\

</div>

<div>

[Why have default params?]{style="font-weight: bold;"}

</div>

<div>

Allows you to be more defensive

</div>

<div>

Avoids errors with incorrect parameters

</div>

<div>

More readable examples

</div>

<div>

\

</div>

<div>

def add(a,b):

</div>

<div>

    return a+b

</div>

<div>

def math(a,b,[fn]{style="font-weight: bold;"}=add):

</div>

<div>

    return [fn]{style="font-weight: bold;"}(a,b)

</div>

<div>

def subtract(a,b):

</div>

<div>

    return a-b

</div>

<div>

\

</div>

<div>

math(2,2) \#4

</div>

<div>

math(2,2,subtract) \#0

</div>

<div>

\

</div>

<div>

[Keyword Arguments]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

def full\_name(first, last):

</div>

<div>

    return f\"Your name is {first} {last}\"

</div>

<div>

\

</div>

<div>

full\_name(last=\'Steele\', first=\'Colt\') \#order does not matter
anymore

</div>

<div>

\

</div>

<div>

[Scope: where variables can be accessed]{style="font-weight: bold;"}

</div>

<div>

variables created in functions are scoped in that function

</div>

<div>

\

</div>

<div>

[global]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

total=0

</div>

<div>

def increment():

</div>

<div>

    total+=1

</div>

<div>

    return total

</div>

<div>

increment() \#[error 如果在函数体中没有声明引用global变量，
该变量是不能被modify的]{style="font-weight: bold;"}

</div>

<div>

\

</div>

<div>

total=0

</div>

<div>

def increment():

</div>

<div>

    [global total]{style="font-weight: bold;"}

</div>

<div>

    total+=1

</div>

<div>

    return total

</div>

<div>

increment() \#1

</div>

<div>

\

</div>

<div>

name=\"Rusty\"

</div>

<div>

def greet():

</div>

<div>

    print(name)

</div>

<div>

greet() \# Rusty

</div>

<div>

\

</div>

<div>

[nonlocal: let us modify a parent\'s variables in a child(aka nested)
function]{style="font-weight: bold;"}

</div>

<div>

def outer():

</div>

<div>

    count=0

</div>

<div>

    def inner():

</div>

<div>

        [nonlocal count]{style="font-weight: bold;"}

</div>

<div>

        count+=1

</div>

<div>

        return count

</div>

<div>

    return inner()

</div>

<div>

\

</div>

<div>

[Documenting functions: Use \"\"\" \"\"\"]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

def say\_hello():

</div>

<div>

    \"\"\"A simple function that returns the string hello\"\"\"

</div>

<div>

    return \"Hello!\"

</div>

<div>

say\_hello[.\_ \_doc\_ \_]{style="font-weight: bold;"} \#\'A simple
function that returns the string hello\'

</div>

<div>

\

</div>

<div>

[\*args: a special operator we can pass to functions; gathers remaining
arguments as a tuple; does not need to be called args, could be \*nums,
etc.]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

def sum\_all\_nums(\*args):

</div>

<div>

    print(args)

</div>

<div>

sum\_all\_nums(4,6,9,4,10) \#inputs could be as many as user wants

</div>

<div>

\

</div>

<div>

[\*\*kwargs: a special operator we can pass to functions; gathers
remaining keyword arguments as a dictionary]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

def fav\_colors(\*\*kwargs):

</div>

<div>

    print(kwargs)

</div>

<div>

fav\_colors(colt=\"purple\",ruby=\"red\",ethel=\"teal\")

</div>

<div>

\

</div>

<div>

**Parameter Ordering**

</div>

1.  <div>

    parameters

    </div>

2.  <div>

    \*args

    </div>

3.  <div>

    default parameters

    </div>

4.  <div>

    \*\*kwargs

    </div>

<div>

\

</div>

<div>

**Using \* as an Argument: Tuple/List Unpacking**

</div>

<div>

e.g.

</div>

<div>

def sum\_all\_values(\*args):

</div>

<div>

    print(args)\

</div>

<div>

    total=0\

</div>

<div>

    for num in args:\

</div>

<div>

        total+=num\

</div>

<div>

    print(total)\

</div>

<div>

\

</div>

<div>

nums = \[1,2,3,4,5,6\]

</div>

<div>

sum\_all\_values(**\*nums**) \#\*nums\--\>unpack the list/tuple into
arguments and pass to the function

</div>

<div>

\

</div>

<div>

**Using \*\* as an Argument: Dictionary Unpacking**

</div>

<div>

e.g.

</div>

<div>

def display\_names(first,second):

</div>

<div>

    print(f\"{first} says hello to {second}\")\

</div>

<div>

\

</div>

<div>

names = {\"first\": \"Colt\", \"second\": \"Rusty\"}

</div>

<div>

display\_names(**\*\*names**) \#\*\*names\--\>unpack the dictionary into
arguments and pass to the function

</div>

</div>

</div>

------------------------------------------------------------------------

[]{#606}

<div>

  -------------- ------------------------
  **Created:**   *9/11/2018 1:02 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

[Lambda: similar to anonymous function, could be used as a parameter
which could be passed to function]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

square = lambda num: num\*num

</div>

<div>

print(square(7))

</div>

<div>

\

</div>

<div>

add = lambda a,b: a+b

</div>

<div>

print(add(3,10))

</div>

<div>

\

</div>

<div>

command = lambda: print(\"Hello\")

</div>

<div>

\

</div>

<div>

[map]{style="font-weight: bold;"}

</div>

<div>

A standard function that accepts at least two arguments, a function and
an \"iterable\"

</div>

<div>

iterable - something that can be iterated over (lists, strings,
dictionaries, sets, tuples)

</div>

<div>

runs the lambda for each value in the iterable and returns a map object
which can be converted into another data structure 

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

nums = \[2,4,6,8,10\]

</div>

<div>

doubles = map(lambda x: x\*2, nums)

</div>

<div>

\

</div>

<div>

people = \[\"Darcy\", \"Christina\", \"Dana\", \"Annabel\"\]

</div>

<div>

peeps = map(lambda name: name.upper(), people)

</div>

<div>

\

</div>

<div>

[filter]{style="font-weight: bold;"}

</div>

<div>

there is a lambda for each value in the iterable

</div>

<div>

returns filter object which can be converted into other iterables

</div>

<div>

the object contains only the values that return true to the lambda

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

l =\[1,2,3,4\]

</div>

<div>

evens = list(filter(lambda x:x%2 == 0, l))

</div>

<div>

evens \# \[2,4\]

</div>

<div>

\

</div>

<div>

Combining filter and map

</div>

<div>

e.g.

</div>

<div>

names = \[\"Lassie\", \"Colt\", \"Rusty\"\]

</div>

<div>

list(map(lambda name: f\"Your instructor is {name}\",

</div>

<div>

    filter(lambda value: len(value)\<5, names)))

</div>

<div>

\

</div>

<div>

[all: return True if all elements of the iterable are truthy(or if the
iterable is empty)]{style="font-weight: bold;"}

</div>

<div>

all(\[0,1,2,3\]) \# False

</div>

<div>

all(\[char for char in \'eio\' if char in \'aeiou\'\]) \# True

</div>

<div>

\

</div>

<div>

people = \[\"Charlie\", \"Casey\", \"Cody\"\]

</div>

<div>

all(\[name\[0\]==\'C\' for name in people\]) \#True

</div>

<div>

\

</div>

<div>

[any: return True if any element of the iterable is truthy. If the
iterable is empty, return False.]{style="font-weight: bold;"}

</div>

<div>

any(\[0,1,2,3\]) \#True

</div>

<div>

any(\[val for val in \[1,2,3\] if val\>5\]) \#False

</div>

<div>

\

</div>

<div>

[generator object: lightweight version of list, no list
functions]{style="font-weight: bold;"}

</div>

<div>

name\[0\]==\"C\" for name in people

</div>

<div>

\

</div>

<div>

Basically, use a generator expression if all you\'re doing is iterating
once. If you want to store and use the generated results. then you\'re
probably better off with a list comprehension.

</div>

<div>

\

</div>

<div>

use [sys.getsizeof]{style="font-weight: bold;"} to compare the memory
difference between generator object and list

</div>

<div>

\

</div>

<div>

[sorted: returns a new sorted list from the items in
iterable]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

more\_numbers = \[6,1,8,2\]

</div>

<div>

sorted(more\_numbers) \#\[1,2,6,8\]

</div>

<div>

sorted(more\_numbers, reverse=True) \#\[8,6,2,1\]

</div>

<div>

print(more\_numbers) \# \[6,1,8,2\],
和.sort()不同，sorted不会改变原有的iterable

</div>

<div>

\

</div>

<div>

users = \[

</div>

<div>

    {\"username\": \"samuel\", \"tweets\": \"blablabla\"},

</div>

<div>

    {\"username\": \"samuel\"},

</div>

<div>

    {\"username\": \"samuel\", \"tweets\": \"bbb\",\"color:\"Green\"}

</div>

<div>

    {\"username\": \"samuel\", \"tweets\": \"aaaa\", color:\"Grey\",
\"password\":\"admin\"}

</div>

<div>

\]

</div>

<div>

\

</div>

<div>

sorted(users, key=len) \#sorted by dictionary length

</div>

<div>

sorted(users, key=lambda user:user\[\'username\'\]) \#sorted by username

</div>

<div>

\

</div>

<div>

[max and min: return the largest/smallest item in an iterable or the
largest/smallest of two or more arguments]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

max(3,67,99)

</div>

<div>

max(\'c\',\'d\',\'a\')

</div>

<div>

max(\[3,4,1,2\])

</div>

<div>

max(\'awesome\')

</div>

<div>

max({1:\'a\', 3:\'c\', 2:\'b\'})

</div>

<div>

\

</div>

<div>

names = \[\'Arya\', \'Samson\', \'Dora\', \'Tim\', \'Ollivander\'\]

</div>

<div>

max(names, key=lambda n: len(n)) \#\'Ollivander\'

</div>

<div>

\

</div>

<div>

[reversed: return a reverse iterator]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

nuns=\[1,2,3,4\]

</div>

<div>

reversed(nuns)

</div>

<div>

\

</div>

<div>

for char in reversed(\"hello world\"):

</div>

<div>

    print(char)

</div>

<div>

\

</div>

<div>

\'\'.join(list(reversed(\"hello\")))
\#\'olleh\',可以用slices\--\>\"hello\"\[::-1\]

</div>

<div>

\

</div>

<div>

[len: return the length of  an object. the argument may be a
sequence(such as a string, tuple, list or range) or a collection(such as
a dictionary, set)]{style="font-weight: bold;"}

</div>

<div>

len(\'hi\') \# actually calling \'hi\'. \_\_len\_\_()

</div>

<div>

\

</div>

<div>

class SpecialList:

</div>

<div>

    

</div>

<div>

    def \_\_init\_\_(self, data)

</div>

<div>

        self.\_\_data = data

</div>

<div>

    def \_\_len\_\_(self):

</div>

<div>

        return 50

</div>

<div>

\

</div>

<div>

l1 = SpecialList(\[1,40,30,100\])

</div>

<div>

print(len(l1)) \#50

</div>

<div>

\

</div>

<div>

[abs: return the absolute value of a number. the argument may be an
integer or a floating point number]{style="font-weight: bold;"}

</div>

<div>

abs(-5) \#5

</div>

<div>

\

</div>

<div>

[sum: takes an iterable and an optional start. returns the sum of start
and the items of an iterable from left to right and returns the total.
start defaults to 0]{style="font-weight: bold;"}

</div>

<div>

sum(\[1,2,3\], 10) \#16, 10 is the start

</div>

<div>

\

</div>

<div>

\

</div>

<div>

[round: return number rounded to ndigits precision after decimal point.
if ndights is omitted or is None, it returns the nearest integer to its
input]{style="font-weight: bold;"}

</div>

<div>

round(10.2) \#10

</div>

<div>

round(1.2121212,2) \#1.21

</div>

<div>

\

</div>

<div>

[zip: make an iterator that aggregates elements from each of the
iterables. returns an iterator of tuples, where the i-th tuple contains
the i-th element from each of the argument sequence or
iterables.]{style="font-weight: bold;"} [the iterator stops when the
shortest input iterable is
exhausted.]{style="font-weight: bold; color: rgb(255, 122, 116);"}

</div>

<div>

e.g.

</div>

<div>

first\_zip = zip(\[1,2,3\],\[4,5,6\])

</div>

<div>

list(first\_zip) \#\[(1,4), (2,5), (3,6)\]

</div>

<div>

dict(first\_zip) \#{1: 4. 2: 5. 3: 6}

</div>

<div>

\

</div>

<div>

five\_by\_two = \[(0,1), (1,2), (2,3), (3,4), (4,5)\]

</div>

<div>

list(zip(\*five\_by\_two)) \#\[(0,1,2,3,4), (1,2,3,4,5)\]

</div>

<div>

\

</div>

<div>

midterms = \[80,91,78\]

</div>

<div>

finals = \[98,89,53\]

</div>

<div>

students = \[\'dan\', \'ang\', \'kate\'\]

</div>

<div>

\

</div>

<div>

\# returns dict with {student:highest score} USING DICT COMP

</div>

<div>

\# {\'dan\': 98, \'ang\': 91, \'kate\': 78}

</div>

<div>

final\_grades = {t\[0\]:max(t\[1\], t\[2\]) for t in zip(students,
midterms, finals)}

</div>

<div>

\

</div>

<div>

\# returns dict with {student:highest score} (same thing as above) USING
MAP+LAMBDA

</div>

<div>

\# {\'dan\': 98, \'ang\': 91, \'kate\': 78}

</div>

<div>

final\_grades = dict(

</div>

<div>

    zip(

</div>

<div>

        students,

</div>

<div>

        map(

</div>

<div>

            lambda pair: max(pair),

</div>

<div>

            zip(midterms, finals)

</div>

<div>

        )

</div>

<div>

    )

</div>

<div>

)

</div>

<div>

\

</div>

<div>

\# returns dict with student:average score

</div>

<div>

\# {\'dan\': 89.0, \'ang\': 90.0, \'kate\': 65.5}

</div>

<div>

avg\_grades = dict(

</div>

<div>

    zip(

</div>

<div>

        students,

</div>

<div>

        map(

</div>

<div>

            lambda pair: ((pair\[0\]+pair\[1\])/2),

</div>

<div>

            zip(midterms, finals)

</div>

<div>

        )

</div>

<div>

    )

</div>

<div>

)

</div>

</div>

------------------------------------------------------------------------

[]{#605}

<div>

  -------------- ------------------------
  **Created:**   *9/12/2018 1:55 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

[SyntaxError]{style="font-weight: bold;"}

</div>

<div>

Occurs when Python encounters incorrect syntax

</div>

<div>

Usually due to typos or not knowing Python well enough

</div>

<div>

\

</div>

<div>

[NameError]{style="font-weight: bold;"}

</div>

<div>

This occurs when a variable is not defined, i.e. it hasn\'t been
assigned

</div>

<div>

\

</div>

<div>

[TypeError]{style="font-weight: bold;"}

</div>

<div>

Occurs when:

</div>

<div>

An operation or function is applied to the wring type

</div>

<div>

Python cannot interpret an operation on two data types

</div>

<div>

\

</div>

<div>

[IndexError]{style="font-weight: bold;"}

</div>

<div>

Occurs when you try to access an element in a list using an invalid
index

</div>

<div>

\

</div>

<div>

[ValueError]{style="font-weight: bold;"}

</div>

<div>

This occurs when a built-in operation or function receives an argument
that has the right type but an inappropriate value

</div>

<div>

\

</div>

<div>

[KeyError]{style="font-weight: bold;"}

</div>

<div>

This occurs when a dictionary does not have a specific key.

</div>

<div>

\

</div>

<div>

[AttributeError]{style="font-weight: bold;"}

</div>

<div>

This occurs when a variable does not have an attribute

</div>

<div>

\

</div>

<div>

[Raise your own exception]{style="font-weight: bold;"}

</div>

<div>

in python we can also throw errors using the raise keyword. this is
helpful when creating your own kinds of exception and error message

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

raise ValueError(\'invalid value\') \#equivalent to throw in Java

</div>

<div>

\

</div>

<div>

def colorize(text, color):

</div>

<div>

    colors = (\"cyan\", \"yellow\", \"blue\")\

</div>

<div>

    if type(color) is not str:

</div>

<div>

        raise TypeError(\"color must be instance of str\")

</div>

<div>

    if type(text) is not str:\

</div>

<div>

        raise TypeError(\"text must be instance of str\")\

</div>

<div>

    if color not in colors:\

</div>

<div>

        raise ValueError(\"color is invalid color\")\

</div>

<div>

    print(f\"Printed {text } in {color}\")\

</div>

<div>

**\
**

</div>

<div>

**Handle Errors: try/except blocks**

</div>

<div>

e.g.

</div>

<div>

try: 

</div>

<div>

    foobar\

</div>

<div>

except NameError:

</div>

<div>

    print(\"PROBLEM!\")\

</div>

<div>

\

</div>

<div>

d = {\"name\": \"Ricky\"}

</div>

<div>

\

</div>

<div>

def get(d, key):

</div>

<div>

    try:

</div>

<div>

        return d\[key\]

</div>

<div>

    except KeyError:\

</div>

<div>

        return None\

</div>

<div>

\

</div>

<div>

try:

</div>

<div>

    num = int(input(\'please enter a number:\'))

</div>

<div>

except ValueError as err:

</div>

<div>

    print(\"That\'s not a number!\")\

</div>

<div>

    print(err)\

</div>

<div>

else:

</div>

<div>

    print(\"I\'m in the else\")\

</div>

<div>

finally:

</div>

<div>

    print(\"Runs no matter what\")\

</div>

<div>

\

</div>

<div>

def divide(a,b):

</div>

<div>

    try:\

</div>

<div>

        result = a/b\

</div>

<div>

**   ** except (ZeroDivisionError, TypeError) as err:\

</div>

<div>

        print(\"Something went wrong\")\

</div>

<div>

        print(err)\

</div>

<div>

    else:\

</div>

<div>

        print(f\"{a} divided by {b} is {result}\")\

</div>

<div>

**\
**

</div>

<div>

**Debugging with Pdb(Python Debugger)**

</div>

<div>

To set breakpoints in our code we can use pdb by inserting this line:

</div>

<div>

**import pdb; pdb.set\_trace() \#commonly on one line**

</div>

<div>

**\
**

</div>

<div>

import pdb

</div>

<div>

first = \"First\"

</div>

<div>

second = \"Second\"

</div>

<div>

pdb.set\_trace()

</div>

<div>

result = first +second

</div>

<div>

third = \"Third\"

</div>

<div>

result += third

</div>

<div>

print(result)

</div>

<div>

\

</div>

<div>

\#common PDB commands

</div>

<div>

\# l (list)

</div>

<div>

\# n (next\_line)

</div>

<div>

\# p (print), if PDB commands is conflict with the variable name, use p
plus variable name. e,g. p l

</div>

<div>

\# c (continue - finishes debugging)

</div>

</div>

------------------------------------------------------------------------

[]{#604}

<div>

  -------------- ------------------------
  **Created:**   *9/13/2018 12:48 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

<div>

[Why Use Modules?]{style="font-weight: bold;"}

</div>

<div>

keep Python files small

</div>

<div>

reuse code across multiple files by importing

</div>

<div>

a module is just a Python file

</div>

<div>

\

</div>

<div>

[Built-in Modules Example]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

import random

</div>

<div>

random.choice(\[\'apple\', \'banana\', \'cherry\'\])

</div>

<div>

random.shuffle(\[\'apple\', \'banana\', \'cherry\'\])

</div>

<div>

\

</div>

<div>

[Importing Parts of a Module]{style="font-weight: bold;"}

</div>

<div>

the [from]{style="font-weight: bold;"} keyword lets you import parts of
a module

</div>

<div>

handy rule of thumb: only import what you need

</div>

<div>

if you still want to import everything, you can also use the from MODULE
import \* pattern

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

from random import choice, randint

</div>

<div>

\

</div>

<div>

[Different Ways to Import]{style="font-weight: bold;"}

</div>

<div>

import random

</div>

<div>

import random as omg\_so\_random

</div>

<div>

from random import \*

</div>

<div>

from random import choice, shuffle

</div>

<div>

from random import choice as give\_me\_one, shuffle as mixed\_up\_fruits

</div>

<div>

\

</div>

<div>

[Custom Modules]{style="font-weight: bold;"}

</div>

<div>

file1.py

</div>

<div>

de fn():

</div>

<div>

    return \"do some stuff\"

</div>

<div>

def other\_fn:

</div>

<div>

    return \"do some other stuff\"

</div>

<div>

\

</div>

<div>

file2.py

</div>

<div>

import file1

</div>

<div>

file1.fn()

</div>

<div>

file1.other\_fn()

</div>

<div>

\

</div>

<div>

[External Modules]{style="font-weight: bold;"}

</div>

<div>

using package management system for Python, pip

</div>

<div>

python3 -m pip install NAME\_OF\_PACKAGE

</div>

<div>

\

</div>

<div>

dir \# return a list of valid attributes for that object

</div>

<div>

help \# generate a help page for the object

</div>

<div>

\

</div>

<div>

[Using the autopep8 package to clean up
code]{style="font-weight: bold;"}

</div>

<div>

**\
**

</div>

<div>

**\_\_name\_\_variable**

</div>

<div>

when run, every Python file has a \_\_name\_\_variable

</div>

<div>

if the file the main file being run, its value is \"\_\_main\_\_\"

</div>

<div>

otherwise, its value is the file name

</div>

<div>

\

</div>

<div>

note: when using import, Python\...

</div>

1.  <div>

    Tries to find the module (if it fails, it throws an error)

    </div>

2.  <div>

    runs the code inside of the module being imported

    </div>

<div>

**\
**

</div>

<div>

**Ignoring Code on Import**

</div>

<div>

if \_\_name\_\_==\"\_\_main\_\_\":

</div>

<div>

    \# this code will only run if the file is the main file\

</div>

<div>

\

</div>

</div>

</div>

------------------------------------------------------------------------

[]{#603}

<div>

  -------------- ------------------------
  **Created:**   *9/14/2018 3:52 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

<div>

<div>

<div>

google.com

</div>

1.  <div>

    DNS Lookup

    </div>

2.  <div>

    Computer makes a request to a server

    </div>

3.  <div>

    Server processes  the request

    </div>

4.  <div>

    Server issues a response

    </div>

5.  <div>

    Request/response cycle (2-4)

    </div>

<div>

\

</div>

<div>

[HTTP Headers]{style="font-weight: bold;"}

</div>

</div>

<div>

sent with both requests and responses

</div>

<div>

provide additional information about the request or response

</div>

<div>

\

</div>

<div>

\

</div>

<div>

[Header Examples]{style="font-weight: bold;"}

</div>

<div>

Request Headers

</div>

<div>

Accept - Acceptable content-types for response (e.g. htm, json, xml)

</div>

<div>

Cache-Control - Specify caching behavior

</div>

<div>

User-Agent - Information about the software used to make the request

</div>

<div>

\

</div>

<div>

Response Headers

</div>

<div>

Access-Control-Allow-Origin - specify domains that can make requests

</div>

<div>

Allowed - HTTP verbs that are allowed in requests

</div>

<div>

\

</div>

<div>

[Response Status Codes]{style="font-weight: bold;"}

</div>

<div>

2xx - Success

</div>

<div>

3xx - Redirect

</div>

<div>

4xx - Client Error

</div>

<div>

5xx - Server Error

</div>

<div>

\

</div>

<div>

[HTTP Verbs and APIs]{style="font-weight: bold;"}

</div>

<div>

GET

</div>

-   <div>

    useful for retrieving data

    </div>

-   <div>

    data passed in query string

    </div>

-   <div>

    should have no \"side-effect\"

    </div>

-   <div>

    can be cached

    </div>

-   <div>

    can be bookmarked

    </div>

<div>

POST

</div>

-   <div>

    useful for writing data

    </div>

-   <div>

    data passed in body

    </div>

-   <div>

    can have \"side-effects\"

    </div>

</div>

-   <div>

    not cached

    </div>

-   <div>

    can\'t be bookmarked

    </div>

<div>

**\
**

</div>

<div>

**APIs**

</div>

<div>

API - Application Programming Interface

</div>

<div>

Allows you to get data from another application without needing to
understand how the application works

</div>

<div>

Can often send data back in different formats

</div>

<div>

Examples of companies with APIs: GitHub, Spotify, Google

</div>

<div>

\

</div>

<div>

**Using the requests Module**

</div>

<div>

import requests

</div>

<div>

res = requests.get(\"\#URL\")

</div>

<div>

res.ok

</div>

<div>

res.headers

</div>

<div>

res.text

</div>

<div>

res.status\_code

</div>

<div>

\

</div>

<div>

**requests Module**

</div>

<div>

lets us make HTTP request from our Python code

</div>

<div>

installed using pip

</div>

<div>

useful for web scraping/crawling, grabbing data from other APIs, etc

</div>

<div>

**\
**

</div>

<div>

**Request Headers**

</div>

<div>

import requests

</div>

<div>

response = requests.get(

</div>

<div>

    \"http://www.example.com\",\
    headers = {

</div>

<div>

        \"header1\": \"value1\",\

</div>

<div>

        \"header2\": \"value2\"\

</div>

<div>

    }

</div>

<div>

)

</div>

<div>

\

</div>

<div>

headers = {\"Accept\": \"application/json\"}

</div>

<div>

headers = {\"Accept\": \"text/plain\"}

</div>

<div>

\

</div>

<div>

print(response.text) \#string

</div>

<div>

print(response.json()) \#dictionary

</div>

<div>

**\
**

</div>

<div>

**What\'s a Query String**

</div>

<div>

a way to pass data to the server as part of a GET request

</div>

<div>

http://www.example.com/?key1=value1&key2=value2

</div>

<div>

\

</div>

<div>

import requests

</div>

<div>

response = requests.get(

</div>

<div>

   \"http://www.example.com/?key1=value1&key2=value2\"\

</div>

<div>

)

</div>

<div>

\

</div>

<div>

import requests

</div>

<div>

response = requests.get(

</div>

<div>

    \"http://www.example.com\",\

</div>

<div>

    params = {

</div>

<div>

        \"key1\": \"value1\",\

</div>

<div>

        \"key2\": \"value2\"\

</div>

<div>

    }\

</div>

<div>

)

</div>

<div>

\

</div>

<div>

**API Project**

</div>

<div>

**\
**

</div>

<div>

import requests

</div>

<div>

import pyfiglet

</div>

<div>

import termcolor

</div>

<div>

from random import choice

</div>

<div>

\

</div>

<div>

header = pyfiglet.figlet\_format(\"Dad Joke 3000\")

</div>

<div>

header = termcolor.colored(header, color=\"magenta\")

</div>

<div>

print(header)

</div>

<div>

\

</div>

<div>

term = input(\"Let me tell you a joke! Give me a topic: \")

</div>

<div>

response\_json = requests.get(

</div>

<div>

    \"https://icanhazdadjoke.com/search\",

</div>

<div>

    headers={\"Accept\": \"application/json\"},

</div>

<div>

    params={\"term\": term}

</div>

<div>

).json()

</div>

<div>

results = response\_json\[\"results\"\]

</div>

<div>

total\_jokes = response\_json\[\"total\_jokes\"\]

</div>

<div>

if total\_jokes \> 1:

</div>

<div>

    print(

</div>

<div>

        f\"I\'ve got {total\_jokes} jokes about {term}. Here\'s
one:\\n\",

</div>

<div>

        choice(results)\[\'joke\'\]

</div>

<div>

    )

</div>

<div>

elif total\_jokes == 1:

</div>

<div>

    print(

</div>

<div>

        f\"I\'ve got one joke about {term}. Here it is:\\n\",

</div>

<div>

        results\[0\]\[\'joke\'\]

</div>

<div>

    )

</div>

<div>

else:

</div>

<div>

    print(f\"Sorry, I don\'t have any jokes about {term}! Please try
again.\")

</div>

<div>

\

</div>

</div>

</div>

------------------------------------------------------------------------

[]{#602}

<div>

  -------------- ------------------------
  **Created:**   *9/23/2018 5:23 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

<div>

[What is OOP?]{style="font-weight: bold;"}

</div>

<div>

Object oriented programming is a method of programming that attempts to
model some process or thing in the world as a class or object.

</div>

<div>

\

</div>

<div>

class - a blueprint for objects. Classes can contain methods(functions)
and attributes(similar to keys in a dict).

</div>

<div>

\

</div>

<div>

instance - objects that are constructed from a class blueprint that
contain their class\'s methods and properties.

</div>

<div>

\

</div>

<div>

[Why OOP?]{style="font-weight: bold;"}

</div>

<div>

With object oriented programming, the goal is to encapsulate your code
into logical, hierarchical groupings using classes so that you can
reason about your code at a higher level.

</div>

<div>

\

</div>

<div>

[Encapsulation]{style="font-weight: bold;"}

</div>

<div>

the grouping of public and private attributes and methods into a
programmatic class, making abstraction possible

</div>

<div>

\

</div>

<div>

[Abstraction]{style="font-weight: bold;"}

</div>

<div>

exposing only \"relevant\" data in a class interface, hiding private
attributes and methods from users

</div>

<div>

\

</div>

<div>

[Creating Classes and Instances]{style="font-weight: bold;"}

</div>

<div>

classes in Python can have a special \_\_init\_\_method, which gets
called every time you create an instance of the class(instantiate)

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

class User:

</div>

<div>

    pass

</div>

<div>

\

</div>

<div>

class User:

</div>

<div>

    def \_\_init\_\_(self, first, last, age):

</div>

<div>

        self.first = first

</div>

<div>

        self.last = last

</div>

<div>

        self.age = age

</div>

<div>

\#定义类方法的时候需要有self参数，没有的话会报错

</div>

<div>

\

</div>

<div>

\#\_name \#suppose to be a private varible

</div>

<div>

\#\_\_name \#save in \_ClassName\_\_AttributeName, name mangling,
继承的时候用来区别子类和父类的相同属性名称

</div>

<div>

\#\_\_name\_\_ \#used for Python specific methods like \_\_init\_\_,
\_\_len\_\_, etc

</div>

<div>

\

</div>

<div>

class User:

</div>

<div>

    def \_\_init\_\_(self, first, last, age):

</div>

<div>

        self.first = first

</div>

<div>

        self.last = last

</div>

<div>

        self.age = age

</div>

<div>

\

</div>

<div>

    def full\_name(self):

</div>

<div>

        return f\"{self.first} {self.last}\"

</div>

<div>

\

</div>

<div>

    def initials(self):

</div>

<div>

        return f\"{self.first\[0\]}.{self.last\[0\]}.\"

</div>

<div>

\

</div>

<div>

    def likes(self, thing):

</div>

<div>

        return f\"{self.first} likes {thing}\"

</div>

<div>

\

</div>

<div>

    def is\_senior(self):

</div>

<div>

        return self.age \>= 65

</div>

<div>

\

</div>

<div>

    def birthday(self):

</div>

<div>

        self.age += 1

</div>

<div>

        return f\"Happy {self.age}th, {self.first}\"

</div>

<div>

\

</div>

<div>

[Class Attributes]{style="font-weight: bold;"}

</div>

<div>

We can also define attributes directly on a class that are shared by all
instances of a class and the class itself

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

class User:

</div>

<div>

\

</div>

<div>

    active\_users = 0

</div>

<div>

\

</div>

<div>

    [def \_\_init\_\_(self, first, last,
age):]{style="box-sizing: border-box; font-size: medium; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; color: rgb(0, 0, 0); font-family: "Segoe UI"; font-variant-caps: normal; font-variant-ligatures: normal;"}

</div>

::: {style="box-sizing: border-box; margin: 0px; padding: 0px; font-size: medium; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}
[        self.first =
first]{style="box-sizing: border-box; font-size: medium; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; color: rgb(0, 0, 0); font-family: "Segoe UI"; font-variant-caps: normal; font-variant-ligatures: normal;"}
:::

::: {style="box-sizing: border-box; margin: 0px; padding: 0px; font-size: medium; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}
[        self.last =
last]{style="box-sizing: border-box; font-size: medium; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; color: rgb(0, 0, 0); font-family: "Segoe UI"; font-variant-caps: normal; font-variant-ligatures: normal;"}
:::

<div>

[        self.age =
age]{style="box-sizing: border-box; font-size: medium; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; color: rgb(0, 0, 0); font-family: "Segoe UI"; font-variant-caps: normal; font-variant-ligatures: normal;"}

</div>

<div>

        User.active\_users +=1    

</div>

<div>

\

</div>

<div>

class Pet:

</div>

<div>

    allowed = \[\'cat\', \'dog\', \'fish\', \'rat\'\]

</div>

<div>

\

</div>

<div>

    def \_\_init\_\_(self, name, species):

</div>

<div>

        if species not in Pet.allowed:

</div>

<div>

            raise ValueError(f\"You can\'t have a {species} pet!\")

</div>

<div>

        self.name = name

</div>

<div>

        self.species = species

</div>

<div>

\

</div>

<div>

    def set\_species(self,species):

</div>

<div>

        if species not in Pet.allowed:

</div>

<div>

            raise ValueError(f\"You can\'t have a {species} pet!\")

</div>

<div>

        self.species = species

</div>

<div>

\

</div>

<div>

[Class Methods]{style="font-weight: bold;"}

</div>

<div>

class methods are methods (with the \@classmethod decorator) that are
not concerned with instances, but class itself.

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

class User:

</div>

<div>

    active\_users = 0

</div>

<div>

\

</div>

<div>

    \@classmethod

</div>

<div>

    def display\_active\_users(cls):

</div>

<div>

        return f\"There are currently {cls.active\_users} active users\"

</div>

<div>

    

</div>

<div>

    \@classmethod

</div>

<div>

    def from\_string(cls, data\_str):

</div>

<div>

        first, last, age = data\_str.split(\",\")

</div>

<div>

        return cls(firs, last, int(age))

</div>

<div>

    

</div>

<div>

print(User.discplay\_active\_users())

</div>

<div>

\

</div>

<div>

[String Representation Example]{style="font-weight: bold;"}

</div>

<div>

the [\_\_repr\_\_]{style="font-weight: bold;"} method is one of several
ways to provide a nicer string representation

</div>

<div>

\

</div>

<div>

def \_\_repr\_\_(self):

</div>

<div>

    return f\"{self.first} is {self.age}\"

</div>

<div>

\

</div>

<div>

tom= User(\"Tom\", \"Cat\", 18)

</div>

<div>

print(tom) \#tom is 18 

</div>

<div>

**\
**

</div>

<div>

**Inheritance**

</div>

<div>

a key feature of OOP is the ability to define a class which inherits
from another class (a \"base\" or \"parent\" class)

</div>

<div>

in Python, inheritance works by passing the parent class as an argument
to the definition of a child class

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

class Animal:

</div>

<div>

    def make\_sound(self, sound):\

</div>

<div>

        print(sound)\

</div>

<div>

    cool = True\

</div>

<div>

\

</div>

<div>

class Cat(Animal):

</div>

<div>

    pass\

</div>

<div>

\

</div>

<div>

gandalf = Cat()

</div>

<div>

gandalf. make\_sound(\"meow\") \#meow

</div>

<div>

gandalf.cool \#True

</div>

<div>

**\
**

</div>

<div>

**Properties**

</div>

<div>

\@property

</div>

<div>

\@property\_name.setter

</div>

<div>

**\
**

</div>

<div>

**super()**

</div>

<div>

e.g.

</div>

<div>

class Animal:

</div>

<div>

    def \_\_init\_\_(self, name, species):

</div>

<div>

        self.name = name

</div>

<div>

        self.species = species

</div>

<div>

\

</div>

<div>

    def \_\_repr\_\_(self):

</div>

<div>

        return f\"{self.name} is a {self.species}\"

</div>

<div>

\

</div>

<div>

    def make\_sound(self, sound):

</div>

<div>

        print(f\"this animal says {sound}\")

</div>

<div>

\

</div>

<div>

\

</div>

<div>

class Cat(Animal):

</div>

<div>

    def \_\_init\_\_(self, name, breed, toy):

</div>

<div>

        super().\_\_init\_\_(name, species=\"Cat\") \# Call init on
parent class

</div>

<div>

        self.breed = breed

</div>

<div>

        self.toy = toy

</div>

<div>

\

</div>

<div>

    def play(self):

</div>

<div>

        print(f\"{self.name} plays with {self.toy}\")

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

<div>

blue = Cat(\"Blue\",\"Scottish Fold\", \"String\")

</div>

<div>

blue.play()

</div>

<div>

**\
**

</div>

<div>

**Multiple Inheritance**

</div>

<div>

Python also allows classes to inherit from more than one parent class

</div>

<div>

**\
**

</div>

<div>

**Multiple Resolution Order(MRO)**

</div>

<div>

whenever you create a class, Python sets a Method Resolution Order for
that class, which is the order in which Python will look for methods on
instances of that class.

</div>

<div>

\

</div>

<div>

you can programmactically reference the MRO in three ways:

</div>

-   <div>

    \_\_mro\_\_ attribute on the class

    </div>

-   <div>

    use the mro() method on the class

    </div>

-   <div>

    use the built-in help(cls) method

    </div>

<div>

\

</div>

<div>

**Polymorphism**

</div>

<div>

a key principle in OOP is the idea of polymorphism - an object can take
on many forms

</div>

<div>

two important practical applications:

</div>

1.  <div>

    the same class method works in a similar way of different classes

    </div>

<div>

            a common implementation of this is to have method in a base
class that is overridden by a sub class. This is called method
overriding.\

</div>

<div>

            e.g.\

</div>

<div>

            Cat.speak()\

</div>

<div>

            Dog.speak(0\

</div>

<div>

            Human.speak()\

</div>

2.  <div>

    the same operation works for different kinds of objects

    </div>

<div>

            e.g.\

</div>

<div>

            len(list/tuple/string)\

</div>

<div>

**\
**

</div>

<div>

**Special Methods Example**

</div>

<div>

8+2 \#10

</div>

<div>

\"8\"+\"2\" \#\"82\"

</div>

<div>

the + operator is shorthand for a special method called \_\_add\_\_()
that gets called on the first operand

</div>

<div>

if the first(left) operand is an istance of int, \_\_add\_\_() does
mathematical addition. If it\'s a string, it does string concatenation

</div>

<div>

\

</div>

<div>

\_\_len\_\_()

</div>

<div>

\_\_repr\_\_()

</div>

<div>

\

</div>

<div>

\

</div>

</div>

</div>

------------------------------------------------------------------------

[]{#600}

<div>

  -------------- ------------------------
  **Created:**   *9/27/2018 2:01 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

[Iterators and Iterables]{style="font-weight: bold;"}

</div>

<div>

Iterator - an object that can be iterated upon. An object which returns
data. one element at a time when next(0 is called on it

</div>

<div>

\

</div>

<div>

Iterable - an object which will return an Iterator when iter() is called
on it

</div>

<div>

\

</div>

<div>

iter(iterable) \--\> interator

</div>

<div>

next(iterator) \--\> data

</div>

<div>

\

</div>

<div>

[Next]{style="font-weight: bold;"}

</div>

<div>

when next() is called on an iterator, the iterator returns the next
item. It keeps doing so until it raises a StopIteration error

</div>

<div>

\

</div>

<div>

[Custom For Loop]{style="font-weight: bold;"}

</div>

<div>

def my\_for(iterable, func):

</div>

<div>

    iterator = iter(iterable)

</div>

<div>

    while True:

</div>

<div>

        try:

</div>

<div>

            thing = next(iterator)

</div>

<div>

        except StopIteration:

</div>

<div>

            break

</div>

<div>

        else:

</div>

<div>

            func(thing)

</div>

<div>

        

</div>

<div>

def square(x):

</div>

<div>

    print(x\*x)

</div>

<div>

\

</div>

<div>

my\_for(\"lol\", print)

</div>

<div>

my\_for(\[1,2,3,4,5\], square)

</div>

<div>

\

</div>

<div>

[Custom Iterator]{style="font-weight: bold;"}

</div>

<div>

class Counter:

</div>

<div>

    def \_\_init\_\_(self, low, high):

</div>

<div>

        self.current = low

</div>

<div>

        self.high = high

</div>

<div>

\

</div>

<div>

    def \_\_iter\_\_(self):

</div>

<div>

        return self

</div>

<div>

\

</div>

<div>

    def \_\_next\_\_(self):

</div>

<div>

        if self.current \< self.high:

</div>

<div>

            num = self.current

</div>

<div>

            self.current += 1

</div>

<div>

            return num

</div>

<div>

        raise StopIteration

</div>

<div>

\

</div>

<div>

for x in Counter(50,70):

</div>

<div>

    print(x)

</div>

<div>

\

</div>

<div>

\

</div>

<div>

[Generator]{style="font-weight: bold;"}

</div>

<div>

generators are iterators

</div>

<div>

generators can be created with generator functions

</div>

<div>

generator functions use the yield keyword

</div>

<div>

generators can be created with generator expressions

</div>

<div>

\

</div>

<div>

![](Evernote_files/Image.png){width="506"}

</div>

<div>

e.g.

</div>

<div>

def count\_up\_to(max):

</div>

<div>

    count = 1\

</div>

<div>

    while count \<= max:\

</div>

<div>

        yield count \# return the count(generator object) and pause
until next() is called\

</div>

<div>

        count +=1\

</div>

<div>

**\
**

</div>

<div>

**Generator Expression**

</div>

<div>

sum(n for n in range(1000))

</div>

<div>

**\
**

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

</div>

------------------------------------------------------------------------

[]{#599}

<div>

  -------------- ------------------------
  **Created:**   *10/9/2018 3:32 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

[Higher Order Functions]{style="font-weight: bold;"}

</div>

<div>

def sum(n, func):

</div>

<div>

    total = 0

</div>

<div>

    for num in range(n):

</div>

<div>

        total += func(num)

</div>

<div>

    return total

</div>

<div>

\

</div>

<div>

def square(x):

</div>

<div>

    return x\*x

</div>

<div>

\

</div>

<div>

sum(10, square)

</div>

<div>

\

</div>

<div>

[\#nested functions]{style="font-weight: bold;"}

</div>

<div>

 from random import choice

</div>

<div>

\

</div>

<div>

def greet(person):

</div>

<div>

    def get\_mood():

</div>

<div>

        msg = choice((\'Hello there\', \'Go away\', \'I love you\'))

</div>

<div>

        return msg

</div>

<div>

    

</div>

<div>

    result = get\_mood() + person

</div>

<div>

    return result

</div>

<div>

\

</div>

<div>

[\#return a function]{style="font-weight: bold;"}

</div>

<div>

from random import choice

</div>

<div>

\

</div>

<div>

def make\_laugh\_at\_func(person):

</div>

<div>

    def get\_laugh():

</div>

<div>

        laugh = choice((\'HAHAHA\', \'lol\', \'tehehe\'))

</div>

<div>

        return f\"{laugh} {person}\"

</div>

<div>

    return get\_laugh

</div>

<div>

\

</div>

<div>

laugh\_at = make\_laugh\_at\_func(\"Linda\")

</div>

<div>

print(laugh\_at())

</div>

<div>

\

</div>

<div>

[What\'s a Decorator]{style="font-weight: bold;"}

</div>

<div>

Decorators are functions

</div>

<div>

Decorators wrap other functions and enhance their behaivior

</div>

<div>

Decorators are examples of higher order functions

</div>

<div>

Decorators have their own syntax, using \"@\"

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

def be\_polite(fn):

</div>

<div>

    def wrapper():

</div>

<div>

        print(\"What a pleasure to meet you!\")

</div>

<div>

        fn()

</div>

<div>

        print(\"Have a great day!\")

</div>

<div>

def greet():

</div>

<div>

    print(\"My name is Colt\")

</div>

<div>

\

</div>

<div>

greet = be\_polite(greet)

</div>

<div>

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

</div>

<div>

def be\_polite(fn):

</div>

<div>

    def wrapper():

</div>

<div>

        print(\"What a pleasure to meet you!\")

</div>

<div>

        fn()

</div>

<div>

        print(\"Have a great day!\")

</div>

<div>

[\@be\_polite]{style="font-weight: bold;"}

</div>

<div>

def greet():

</div>

<div>

    print(\"My name is Colt\")

</div>

<div>

\

</div>

<div>

greet() 

</div>

<div>

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

</div>

<div>

def shout(fn):

</div>

<div>

    def wrapper(\*args, \*\*kwargs):

</div>

<div>

        return fn(\*args, \*\*kwargs).upper()

</div>

<div>

    return wrapper

</div>

<div>

\

</div>

<div>

\@shout

</div>

<div>

def greet(name):

</div>

<div>

    return f\"Hi, I\'m {name}.\"

</div>

<div>

\

</div>

<div>

\@shout

</div>

<div>

def order(main, side):

</div>

<div>

    return f\"Hi, I\'d like the {main}, with a side of {side}, please.\"

</div>

<div>

\

</div>

<div>

\@shout

</div>

<div>

def lol():

</div>

<div>

    return \"lol\"

</div>

<div>

\

</div>

<div>

print(greet(\"todd\"))

</div>

<div>

print(order(side=\"burger\", main=\"fries\"))

</div>

<div>

print(lol())

</div>

<div>

\

</div>

<div>

[Using Wraps To Preserve Metadata]{style="font-weight: bold;"}

</div>

<div>

\#decorator pattern

</div>

<div>

from functools import wraps

</div>

<div>

\# wraps preserves a function\'s metadata when it is decorated

</div>

<div>

\

</div>

<div>

def my\_decorator(fn):

</div>

<div>

    [\@wraps(fn)]{style="font-weight: bold;"}

</div>

<div>

    def wrapper(\*args, \*\*kwargs):

</div>

<div>

        \#do some stuff with fn(\*args, \*\*kwargs)

</div>

<div>

        pass

</div>

<div>

    return wrapper

</div>

<div>

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

</div>

<div>

from functools import wraps

</div>

<div>

def log\_function\_data(fn):

</div>

<div>

    \@wraps(fn)

</div>

<div>

    def wrapper(\*args, \*\*kwargs):

</div>

<div>

        \"\"\"I AM WRAPPER FUNCTION\"\"\"

</div>

<div>

        print(f\"you are about to call {fn.\_\_name\_\_}\")

</div>

<div>

        print(f\"Here\'s the documentation: {fn.\_\_doc\_\_}\")

</div>

<div>

        return fn(\*args, \*\*kwargs)

</div>

<div>

    return wrapper

</div>

<div>

\

</div>

<div>

\@log\_function\_data

</div>

<div>

def add(x,y):

</div>

<div>

    \"\"\"Adds two numbers together.\"\"\"

</div>

<div>

    return x + y

</div>

<div>

\

</div>

<div>

print(add.\_\_doc\_\_)

</div>

<div>

print(add.\_\_name\_\_)

</div>

<div>

help(add)

</div>

<div>

**\
**

</div>

<div>

**Writing an ensure\_first\_arg\_is Decorator**

</div>

<div>

from functools import wraps

</div>

<div>

\

</div>

<div>

def ensure\_first\_arg\_is(val):

</div>

<div>

    def inner(fn):

</div>

<div>

        \@wraps(fn)

</div>

<div>

        def wrapper(\*args, \*\*kwargs):

</div>

<div>

            if args and args\[0\] != val:

</div>

<div>

                return f\"First arg needs to be {val}\"

</div>

<div>

            return fn(\*args, \*\*kwargs)

</div>

<div>

        return wrapper

</div>

<div>

    return inner

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\@ensure\_first\_arg\_is(\"burrito\")

</div>

<div>

def fav\_foods(\*foods):

</div>

<div>

    print(foods)

</div>

<div>

\

</div>

<div>

print(fav\_foods(\"burrito\", \"ice cream\")) \# (\'burrito\', \'ice
cream\')

</div>

<div>

print(fav\_foods(\"ice cream\", \"burrito\")) \# \'Invalid! First
argument must be burrito\'

</div>

<div>

\

</div>

<div>

\@ensure\_first\_arg\_is(10)

</div>

<div>

def add\_to\_ten(num1, num2):

</div>

<div>

    return num1 + num2

</div>

<div>

\

</div>

<div>

print(add\_to\_ten(10, 12)) \# 12

</div>

<div>

print(add\_to\_ten(1, 2)) \# \'Invalid! First argument must be 10\'

</div>

<div>

**\
**

</div>

<div>

**Enforcing Argument Types With a Decorator**

</div>

<div>

def enforce(\*types):

</div>

<div>

    def decorator(f):

</div>

<div>

        def new\_func(\*args, \*\*kwargs):

</div>

<div>

            \#convert args into something mutable   

</div>

<div>

            newargs = \[\]        

</div>

<div>

            for (a, t) in zip(args, types):

</div>

<div>

               newargs.append( t(a)) \#feel free to have more elaborated
convertion

</div>

<div>

            return f(\*newargs, \*\*kwargs)

</div>

<div>

        return new\_func

</div>

<div>

    return decorator

</div>

<div>

\

</div>

<div>

\@enforce(str, int)

</div>

<div>

def repeat\_msg(msg, times):

</div>

<div>

    for time in range(times):

</div>

<div>

        print(msg)

</div>

<div>

\

</div>

<div>

\@enforce(float, float)

</div>

<div>

def divide(a,b):

</div>

<div>

    print(a/b)

</div>

<div>

\# repeat\_msg(\"hello\", \'5\')

</div>

<div>

divide(\'1\', \'4\')

</div>

<div>

\

</div>

</div>

------------------------------------------------------------------------

[]{#597}

<div>

  -------------- ------------------------
  **Created:**   *10/10/2018 11:59 AM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

<div>

[Why test?]{style="font-weight: bold;"}

</div>

<div>

reduce bugs in existing code

</div>

<div>

ensure bugs that fixed stay fixed

</div>

<div>

ensure new features don\'t break old ones

</div>

<div>

ensure cleaning up code doesn\'t introduce new bugs

</div>

<div>

\

</div>

<div>

[TDD(Test Driven Development)]{style="font-weight: bold;"}

</div>

<div>

development begins by writing tests

</div>

<div>

once tests are written, write code to make tests pass

</div>

<div>

once tests pass, a feature is considered complete

</div>

<div>

\

</div>

<div>

[Red, Green, Refactor]{style="font-weight: bold;"}

</div>

1.  <div>

    Red - Write a test that fails

    </div>

2.  <div>

    Green - Write the minimal amount of code necessary to make the test
    pass

    </div>

3.  <div>

    Refactor - Clean up the code, while ensuring that tests still pass

    </div>

<div>

\

</div>

<div>

[Assertions]{style="font-weight: bold;"}

</div>

<div>

we can make simple assertions with the
[assert]{style="font-weight: bold;"} keyword

</div>

<div>

[assert]{style="font-weight: bold;"} accepts an expression

</div>

<div>

returns None if the expression is truthy

</div>

<div>

raises an AssertionError if the expression is falsy

</div>

<div>

accepts an optional error message as a second argument

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

def add\_positive\_numbers(x,y):

</div>

<div>

    assert x\>0 and y\>0, \"Both numbers must be positive!\"

</div>

<div>

    return x+y

</div>

<div>

add\_positive\_numbers(1,1) \# 2

</div>

<div>

add\_positive\_numbers(1,-1) \# AssertionError: Both numbers must be
positive!

</div>

<div>

\

</div>

<div>

Note: If a Python file is run with the [-O
flag]{style="font-weight: bold;"}, assertions will not be evaluated

</div>

<div>

\

</div>

<div>

[doctests]{style="font-weight: bold;"}

</div>

<div>

we can write tests for functions inside of the docstring

</div>

<div>

write code that looks like it\'s inside of a REPL

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

def add(x, y):

</div>

<div>

    \"\"\"add together x and y

</div>

<div>

    \>\>\> add(1,2)

</div>

<div>

    3

</div>

<div>

    \>\>\>add(8,\"hi\")

</div>

<div>

    Traceback (most recent call last):

</div>

<div>

        \...

</div>

<div>

    TypeError: unsupported operand type(s) for +: \'int\' and \'str\'

</div>

<div>

    \"\"\"

</div>

<div>

\

</div>

<div>

how to run the doctest?

</div>

<div>

e.g.

</div>

<div>

python 3 -m doctest -v doctest\_demo.py

</div>

</div>

<div>

\

</div>

<div>

[Issues with doctests]{style="font-weight: bold;"}

</div>

<div>

syntax is a little strange

</div>

<div>

clutters up our function code

</div>

<div>

lacks many features of larger testing tools

</div>

<div>

tests can be brittle

</div>

<div>

\

</div>

<div>

**Unit testing**

</div>

<div>

test smallest parts of an application in isolation

</div>

<div>

good candidates for unit testing: individual classes, modules, or
functions

</div>

<div>

bad candidates for unit testing: an entire application , dependencies
across several classes or modules

</div>

<div>

\

</div>

<div>

**unittest**

</div>

<div>

Python comes with a built-in module called unittest

</div>

<div>

you can write unit tests encapsulated as classes that inherit from
unittest.TestCase

</div>

<div>

this inheritance gives you access to many assertion helpers that let you
test the behavior of your functions

</div>

<div>

you can run tests by calling unittest.main()

</div>

<div>

![](Evernote_files/Image%20%5B1%5D.png)

</div>

<div>

import unittest

</div>

<div>

from activities import eat, nap, is\_funny, laugh

</div>

<div>

\

</div>

<div>

class ActivityTests(unittest.TestCase):

</div>

<div>

    def test\_eat\_healthy(self):

</div>

<div>

        \"\"\"eat should have a positive message for healthy
eating\"\"\"

</div>

<div>

        self.assertEqual(

</div>

<div>

            eat(\"broccoli\", is\_healthy=True),

</div>

<div>

            \"I\'m eating broccoli, because my body is a temple\"

</div>

<div>

        )

</div>

<div>

    def test\_eat\_unhealthy(self):

</div>

<div>

        \"\"\"eat should indicate you\'ve given up for eating
unhealthy\"\"\"

</div>

<div>

        self.assertEqual(

</div>

<div>

            eat(\"pizza\", is\_healthy=False),

</div>

<div>

            \"I\'m eating pizza, because YOLO!\"

</div>

<div>

        )

</div>

<div>

    def test\_eat\_healthy\_boolean(self):

</div>

<div>

        \"\"\"is\_healthy must be a bool\"\"\"

</div>

<div>

        with self.assertRaises(ValueError):

</div>

<div>

            eat(\"pizza\", is\_healthy=\"who cares?\")

</div>

<div>

\

</div>

<div>

    def test\_short\_nap(self):

</div>

<div>

        \"\"\"short naps should be refreshing\"\"\"

</div>

<div>

        self.assertEqual(

</div>

<div>

            nap(1),

</div>

<div>

            \"I\'m feeling refreshed after my 1 hour nap\"

</div>

<div>

        )

</div>

<div>

    def test\_long\_nap(self):

</div>

<div>

        \"\"\"long naps should be discouraging\"\"\"

</div>

<div>

        self.assertEqual(

</div>

<div>

            nap(3), \"Ugh I overslept.  I didn\'t mean to nap for 3
hours!\"

</div>

<div>

        )

</div>

<div>

    def test\_is\_funny\_tim(self):

</div>

<div>

        self.assertEqual(is\_funny(\"tim\"), False)

</div>

<div>

        \# self.assertFalse(is\_funny(\"tim\"), \"tim should not be
funny\")

</div>

<div>

\

</div>

<div>

    def test\_is\_funny\_anyone\_else(self):

</div>

<div>

        \"\"\"anyone else but tim should be funny\"\"\"

</div>

<div>

        self.assertTrue(is\_funny(\"blue\"), \"blue should be funny\")

</div>

<div>

        self.assertTrue(is\_funny(\"tammy\"), \"tammy should be funny\")

</div>

<div>

        self.assertTrue(is\_funny(\"sven\"), \"sven should be funny\")

</div>

<div>

    

</div>

<div>

    def test\_laugh(self):

</div>

<div>

        \"\"\"laugh returns a laughing string\"\"\"

</div>

<div>

        self.assertIn(laugh(), (\'lol\', \'haha\', \'tehehe\'))

</div>

<div>

\

</div>

<div>

if \_\_name\_\_ == \"\_\_main\_\_\":

</div>

<div>

    unittest.main()

</div>

<div>

\

</div>

<div>

\

</div>

<div>

**Commenting Tests**

</div>

<div>

class SomeTests(unittest.TestCase):

</div>

<div>

    def first\_test(self):\

</div>

<div>

        \"\"\"testing a thing\"\"\"\

</div>

<div>

        self.assertEqual(thing(), \"something\")\

</div>

<div>

    def second\_test(self):\

</div>

<div>

        \"\"\"testing another thing\"\"\"\

</div>

<div>

        self.assertEqual(another\_thing(), \"something else\")\

</div>

<div>

\

</div>

<div>

to see comments, run python NAME\_OF\_TEST\_FILE.py -v

</div>

<div>

\

</div>

<div>

**Types of Assertions**

</div>

<div>

self.assertEqual(x,y)

</div>

<div>

self.assertNotEqual(x,y)

</div>

<div>

self.assertTrue(x)

</div>

<div>

self.assertFalse(x)

</div>

<div>

self.assertIsNone(x)

</div>

<div>

self.assertIsNotNone(x)

</div>

<div>

self.assertIn(x)

</div>

<div>

\

</div>

<div>

**Testing for Errors**

</div>

<div>

class SomeTests(unittest.TestCase):

</div>

<div>

    def testing\_for\_error(self):\

</div>

<div>

        \"\"\"testing for an error\"\"\"\

</div>

<div>

        with self.assertRaises(IndexError):\

</div>

<div>

            l = \[1,2,3\]\

</div>

<div>

            l\[100\]\

</div>

<div>

**\
**

</div>

<div>

**Before and After Hooks**

</div>

<div>

**\
**

</div>

<div>

**setUp and tearDown**

</div>

<div>

for larger applications, you may want similar application state before
running tests

</div>

<div>

setUp runs before each test method

</div>

<div>

tearDown runs after each test method

</div>

<div>

common use cases: adding/removing data from a test database, creating
instances of a class

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

import unittest

</div>

<div>

from robot import Robot

</div>

<div>

\

</div>

<div>

class RobotTests(unittest.TestCase):

</div>

<div>

    def setUp(self):

</div>

<div>

        self.mega\_man = Robot(\"Mega Man\", battery=50)

</div>

<div>

\

</div>

<div>

    def test\_charge(self):

</div>

<div>

        self.mega\_man.charge()

</div>

<div>

        self.assertEqual(self.mega\_man.battery, 100)

</div>

<div>

\

</div>

<div>

    def test\_say\_name(self):

</div>

<div>

        self.assertEqual(

</div>

<div>

            self.mega\_man.say\_name(),

</div>

<div>

            \"BEEP BOOP BEEP BOOP.  I AM MEGA MAN\")

</div>

<div>

        self.assertEqual(self.mega\_man.battery, 49)

</div>

<div>

\

</div>

<div>

if \_\_name\_\_ == \"\_\_main\_\_\":

</div>

<div>

    unittest.main()

</div>

<div>

\

</div>

</div>

------------------------------------------------------------------------

[]{#595}

<div>

  -------------- ------------------------
  **Created:**   *10/10/2018 2:29 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

[Reading Files]{style="font-weight: bold;"}

</div>

<div>

you can read a file with the [open]{style="font-weight: bold;"} function

</div>

<div>

[open]{style="font-weight: bold;"} returns a file object

</div>

<div>

you can read a file object with the [read]{style="font-weight: bold;"}
method

</div>

<div>

\

</div>

<div>

[Cursor Movement]{style="font-weight: bold;"}

</div>

<div>

Python reads files by using a cursor

</div>

<div>

This is like the cursor you see when you\'re typing

</div>

<div>

After a file is read, the cursor is at the end

</div>

<div>

To move the cursor, use the [seek]{style="font-weight: bold;"} method

</div>

<div>

\

</div>

<div>

e.g. file.seek(0)

</div>

<div>

    file.readline()

</div>

<div>

    file.readlines()

</div>

<div>

\

</div>

<div>

[Closing a File]{style="font-weight: bold;"}

</div>

<div>

you can close a file with the [close]{style="font-weight: bold;"} method

</div>

<div>

you can check if a file is closed with the
[closed]{style="font-weight: bold;"} attribute

</div>

<div>

once closed, a file can\'t be read again

</div>

<div>

\

</div>

<div>

[with Blocks]{style="font-weight: bold;"}

</div>

<div>

option 1 

</div>

<div>

file = open(\"story.txt\")

</div>

<div>

file.read()

</div>

<div>

file.close()

</div>

<div>

file.closed \#True

</div>

<div>

\

</div>

<div>

option 2

</div>

<div>

with open(\"story.txt\") as file:

</div>

<div>

    file.read()

</div>

<div>

file.closed \#True

</div>

<div>

\

</div>

<div>

with
statement实际上在开始和结束时调用了.\_\_enter\_\_()和.\_\_exit\_\_(),
因此只要有.\_\_enter\_\_()和.\_\_exit\_\_()就可以使用with statment

</div>

<div>

\

</div>

<div>

[Writing to Text Files]{style="font-weight: bold;"}

</div>

<div>

you can also use open to write to a file

</div>

<div>

need to specify the \"w\" flag as the second argument

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

with open(\"haiku.txt\", \"w\") as file:

</div>

<div>

    file.write(\"abcdefg\")

</div>

<div>

\#will override everything, not adding to the original one

</div>

<div>

\

</div>

<div>

[Modes for Opening Files]{style="font-weight: bold;"}

</div>

<div>

\'r\' - open for reading(default)

</div>

<div>

\'w\' - open for writing, truncating the file first

</div>

<div>

\'x\' - open for exclusive creation, failing if the file already exists

</div>

<div>

\'a\' - open for writing, appending to the end of the file if it exists

</div>

<div>

\'r+\' - read and write to a file (writing based on cursor), will
override based on the cursor position, only works with existing file

</div>

<div>

\'b\' - binary mode

</div>

<div>

\'t\' - text mode

</div>

<div>

\'+\' - open a disk file for updating (reading and writing)

</div>

<div>

\'wb\' - writing binary

</div>

<div>

\'rb\' - reading binary

</div>

<div>

\

</div>

<div>

[Reading CSV Files]{style="font-weight: bold;"}

</div>

<div>

CSV files are a common file format for tabular data

</div>

<div>

we can read CSV files just like other text files

</div>

<div>

Python has a bulit-in CSV module to read/write CSVs more easily

</div>

<div>

\

</div>

<div>

[CSV Module]{style="font-weight: bold;"}

</div>

<div>

reader - lets you iterate over rows of the CSV as lists

</div>

<div>

DictReader - lets you iterate over rows of the CSV as OrderedDicts

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

\# Using reader

</div>

<div>

from csv import reader

</div>

<div>

with open(\"fighters.csv\") as file:

</div>

<div>

    csv\_reader = reader(file)

</div>

<div>

    next(csv\_reader) \#To skip the headers

</div>

<div>

    for fighter in csv\_reader:

</div>

<div>

        \# Each row is a list

</div>

<div>

        \# Use index to access data

</div>

<div>

        print(f\"{fighter\[0\]} is from {fighter\[1\]}\")

</div>

<div>

\

</div>

<div>

\# Example where data is cast into a list

</div>

<div>

from csv import reader

</div>

<div>

with open(\"fighters.csv\") as file:

</div>

<div>

    csv\_reader = reader(file)

</div>

<div>

    data = list(csv\_reader)

</div>

<div>

    print(data)

</div>

<div>

\

</div>

<div>

\# Reading/Parsing CSV Using a DictReader:

</div>

<div>

from csv import DictReader

</div>

<div>

with open(\"fighters.csv\") as file:

</div>

<div>

    csv\_reader = DictReader(file)

</div>

<div>

    for row in csv\_reader:

</div>

<div>

        \# Each row is an OrderedDict!

</div>

<div>

        print(row\[\'Name\'\]) \#Use keys to access data

</div>

<div>

\

</div>

<div>

[Other Delimiters]{style="font-weight: bold;"}

</div>

<div>

Readers accept a delimiter kwarg in case your data isn\'t separated by
commas

</div>

<div>

e.g.

</div>

<div>

from csv import reader

</div>

<div>

with open(\"example.csv\") as file:

</div>

<div>

    csv\_reader = reader(file, delimiter=\"\|\")

</div>

<div>

    for row in csv\_reader

</div>

<div>

        print(row)

</div>

<div>

\

</div>

<div>

[Writing CSV Files - using lists]{style="font-weight: bold;"}

</div>

<div>

writer - creates a writer object for writing to CSV

</div>

<div>

writerow - method on a writer to wrtie a row to the CSV

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

from csv import writer

</div>

<div>

with open(\"fighters.csv\", \"w\") as file:

</div>

<div>

    csv\_writer = writer(file)

</div>

<div>

    csv\_writer.writerow(\[\"Character\", \"Move\"\])

</div>

<div>

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

</div>

<div>

from csv import writer, DictWriter

</div>

<div>

\# Version using writer

</div>

<div>

with open(\"cats.csv\", \"w\") as file:

</div>

<div>

    csv\_writer = writer(file)

</div>

<div>

    csv\_writer.writerow(\[\"Name\", \"Age\"\])

</div>

<div>

     csv\_writer.writerow(\[\"Blue\", 3\])

</div>

<div>

    csv\_writer.writerow(\[\"Kitty\", 1\])

</div>

<div>

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

</div>

<div>

from csv import reader, writer

</div>

<div>

\# using nested with statements 注意：读写同一个文件时不能用嵌套的open

</div>

<div>

with open(\'fighters.csv\') as file:

</div>

<div>

    csv\_reader = reader(file) \#data never converted to list

</div>

<div>

    with open(\'screaming\_fighters.csv\', \"w\") as file:

</div>

<div>

        csv\_writer = writer(file)

</div>

<div>

        for fighter in csv\_reader:

</div>

<div>

            csv\_writer.writerow(\[s.upper() for s in fighter\])

</div>

<div>

\

</div>

<div>

\# Other approach, with only 1 file open at a time

</div>

<div>

with open(\'fighters.csv\') as file:

</div>

<div>

    csv\_reader = reader(file)

</div>

<div>

    \# data converted to list and saved to variable

</div>

<div>

    fighters = \[\[s.upper() for s in row\] for row in csv\_reader\]

</div>

<div>

\

</div>

<div>

with open(\'screaming\_fighters.csv\', \"w\") as file:

</div>

<div>

    csv\_writer = writer(file)

</div>

<div>

    for fighter in fighters:

</div>

<div>

        csv\_writer.writerow(fighter)

</div>

<div>

\

</div>

<div>

[Writing CSV Files - using dictionaries]{style="font-weight: bold;"}

</div>

<div>

DictWriter - creates a writer object for writing using dictionaries

</div>

<div>

fieldnames - kwarg for the DictWriter specifying headers

</div>

<div>

writeheader - method on a writer to write header row

</div>

<div>

writerow - method on a writer to write a row based on a dictionary

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

\# Version using DictWriter

</div>

<div>

with open(\"cats.csv\", \"w\") as file:

</div>

<div>

    headers = \[\"Name\", \"Breed\", \"Age\"\]

</div>

<div>

    csv\_writer = DictWriter(file, fieldnames=headers)

</div>

<div>

    csv\_writer.writeheader()

</div>

<div>

    csv\_writer.writerow({

</div>

<div>

        \"Name\": \"Garfield\",

</div>

<div>

        \"Breed\": \"Orange Tabby\",

</div>

<div>

        \"Age\": 10

</div>

<div>

    })

</div>

<div>

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

</div>

<div>

from csv import DictReader, DictWriter

</div>

<div>

\

</div>

<div>

def cm\_to\_in(cm):

</div>

<div>

    return float(cm) \* 0.393701

</div>

<div>

\

</div>

<div>

with open(\"fighters.csv\") as file:

</div>

<div>

    csv\_reader = DictReader(file)

</div>

<div>

    fighters = list(csv\_reader)

</div>

<div>

\

</div>

<div>

with open(\"inches\_fighters.csv\", \"w\") as file:

</div>

<div>

    headers = (\"Name\",\"Country\",\"Height\")

</div>

<div>

    csv\_writer = DictWriter(file, fieldnames=headers)

</div>

<div>

    csv\_writer.writeheader()

</div>

<div>

    for f in fighters:

</div>

<div>

        csv\_writer.writerow({

</div>

<div>

            \"Name\": f\[\"Name\"\],

</div>

<div>

            \"Country\": f\[\"Country\"\],

</div>

<div>

            \"Height\": cm\_to\_in(f\[\"Height (in cm)\"\])

</div>

<div>

        })

</div>

<div>

\

</div>

<div>

enumerate()

</div>

<div>

list1 = \[\"这\", \"是\", \"一个\", \"测试\"\] 

</div>

<div>

for index, item in enumerate(list1): 

</div>

<div>

    print index, item 

</div>

<div>

\>\>\> 

</div>

<div>

0 这 

</div>

<div>

1 是 

</div>

<div>

2 一个 

</div>

<div>

3 测试

</div>

<div>

\

</div>

<div>

**Pickle/pickling: Python object serialization**

</div>

<div>

import pickle

</div>

<div>

class Animal:

</div>

<div>

    def \_\_init\_\_(self, name, species):

</div>

<div>

        self.name = name

</div>

<div>

        self.species = species

</div>

<div>

\

</div>

<div>

    def \_\_repr\_\_(self):

</div>

<div>

        return f\"{self.name} is a {self.species}\"

</div>

<div>

\

</div>

<div>

    def make\_sound(self, sound):

</div>

<div>

        print(f\"this animal says {sound}\")

</div>

<div>

\

</div>

<div>

\

</div>

<div>

class Cat(Animal):

</div>

<div>

    def \_\_init\_\_(self, name, breed, toy):

</div>

<div>

        super().\_\_init\_\_(name, species=\"Cat\") \# Call init on
parent class

</div>

<div>

        self.breed = breed

</div>

<div>

        self.toy = toy

</div>

<div>

\

</div>

<div>

    def play(self):

</div>

<div>

        print(f\"{self.name} plays with {self.toy}\")

</div>

<div>

\

</div>

<div>

\

</div>

<div>

blue = Cat(\"Blue\", \"Scottish Fold\", \"String\")

</div>

<div>

\

</div>

<div>

\# To pickle an object:

</div>

<div>

with open(\"pets.pickle\", \"wb\") as file:

</div>

<div>

    pickle.dump(blue, file)

</div>

<div>

\

</div>

<div>

\# To unpickle something:

</div>

<div>

\# with open(\"pets.pickle\", \"rb\") as file:

</div>

<div>

\#     zombie\_blue = pickle.load(file)

</div>

<div>

\#     print(zombie\_blue)

</div>

<div>

\#     print(zombie\_blue.play())

</div>

<div>

**\
**

</div>

<div>

**JSON Pickling**

</div>

<div>

**\
**

</div>

</div>

------------------------------------------------------------------------

[]{#593}

<div>

  -------------- ------------------------
  **Created:**   *10/12/2018 12:52 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

<div>

[Introduction]{style="font-weight: bold;"}

</div>

<div>

Web scraping involves programmatically grabbing data from a web page

</div>

<div>

Three steps: Download, extract data, do something with data

</div>

<div>

\

</div>

<div>

[Why Scrape?]{style="font-weight: bold;"}

</div>

<div>

There\'s data on a site that you want to store or analyze

</div>

<div>

You can\'t get by other means (e.g. an API)

</div>

<div>

You want to prgrammatically grab the data (instead of lots of manual
copying/pasting)

</div>

<div>

\

</div>

<div>

[Is it\...OK?]{style="font-weight: bold;"}

</div>

<div>

Some websites don\'t want people scraping them

</div>

<div>

Best practice: consult the robots.txt file

</div>

<div>

If making making many requests, time them out

</div>

<div>

If you\'re too aggressive, your IP can be blocked

</div>

<div>

\

</div>

<div>

[HTML/CSS]{style="font-weight: bold;"}

</div>

<div>

\

</div>

<div>

[Beautiful Soup]{style="font-weight: bold;"}

</div>

<div>

python3 -m pip install bs4

</div>

<div>

\

</div>

<div>

To extract data  from HTML, we\'ll use Beautiful Soup

</div>

<div>

Install it with pip

</div>

<div>

Beautiful Soup lets us navigate through HTML with Python

</div>

<div>

Beautiful Soup does not download HTML - for this, we need the requests
module

</div>

<div>

\

</div>

<div>

[Parsing and Navigating HTML]{style="font-weight: bold;"}

</div>

<div>

BeautifulSoup(html\_string, \"html.parser\") - parse HTML

</div>

<div>

Once parsed, there are serveral ways to navigate:

</div>

-   <div>

    By Tag Name

    </div>

-   <div>

    Using find - returns one matching tag

    </div>

-   <div>

    Using find\_all - returns a list of matching tags

    </div>

<div>

\

</div>

<div>

[Navigating with CSS Selectors]{style="font-weight: bold;"}

</div>

<div>

select - returns a list of elements matching a CSS selector

</div>

<div>

Selector Cheatsheet

</div>

-   <div>

    Select by id of foo: \#foo

    </div>

-   <div>

    Select by class of bar: .bar

    </div>

-   <div>

    Select children: div \> p

    </div>

-   <div>

    Select descendants: div p

    </div>

<div>

![](Evernote_files/Image%20%5B2%5D.png){width="541"}

</div>

<div>

\

</div>

<div>

[Accessing Data in Elements]{style="font-weight: bold;"}

</div>

<div>

get\_text - access the inner text in an element

</div>

<div>

name - tag name

</div>

<div>

attrs - dictionary of attributes

</div>

<div>

You can also access attribute values using brackets

</div>

<div>

\

</div>

<div>

[Navigating with Beautiful Soup]{style="font-weight: bold;"}

</div>

<div>

[Via Tags]{style="font-weight: bold;"}

</div>

<div>

parent / parents

</div>

<div>

contents

</div>

<div>

next\_sibling / next\_siblings

</div>

<div>

previous\_sibling / previous\_siblings

</div>

<div>

[Via Searching]{style="font-weight: bold;"}

</div>

<div>

find\_parent / find\_parents

</div>

<div>

find\_next\_sibling / find\_next\_siblings

</div>

<div>

find\_previous\_sibling / find\_previous\_siblings

</div>

<div>

**\
**

</div>

<div>

**Creating a Web Crawler with Scrapy**

</div>

<div>

python -m pip install scrapy

</div>

<div>

scrapy runspider -o books.csv book\_scraper.py

</div>

<div>

\

</div>

</div>

<div>

import scrapy

</div>

<div>

\

</div>

<div>

class BookSpider(scrapy.Spider):

</div>

<div>

    name = \'bookspider\'

</div>

<div>

    start\_urls = \[\'<http://books.toscrape.com/>\'\]

</div>

<div>

\

</div>

<div>

    def parse(self,response):

</div>

<div>

        for article in response.css(\'article.product\_pod\')

</div>

<div>

            yield {

</div>

<div>

                \'price\':
article.css(\".price\_color:text\").extract\_first(),

</div>

<div>

                \'title\': article.css(\"h3 \>
a::attr(title)\").extract\_first()

</div>

<div>

            }

</div>

<div>

            next = response.css(\'.next \> a
::attr(href)\').extract\_first()

</div>

<div>

            if next:

</div>

<div>

                yield reponse.follow(next, self.parse)

</div>

</div>

------------------------------------------------------------------------

[]{#592}

<div>

  -------------- ------------------------
  **Created:**   *10/15/2018 1:32 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

**What are regular expressions?**

</div>

<div>

A way of describing patterns wthin search strings

</div>

<div>

\

</div>

<div>

e.g. Validating emails

</div>

<div>

(\^\[a-zA-Z0-9\_.+-\]+@\[a-zA-Z0-9-\]+\\.\[a-zA-Z0-9.\]+\$)

</div>

<div>

\

</div>

<div>

<https://pythex.org/>

</div>

<div>

\

</div>

<div>

**Potential Use Cases**

</div>

<div>

Credit card number validating

</div>

<div>

Phone number validating

</div>

<div>

Advanced find/replace in text

</div>

<div>

Formatting text/output

</div>

<div>

Syntax highlighting

</div>

<div>

\

</div>

<div>

**Some Regular Expression Syntax**

</div>

<div>

\\d digit 0-9

</div>

<div>

\\w letter, digit, or underscore

</div>

<div>

\\s whitespace character

</div>

<div>

\\D not a digit

</div>

<div>

\\W not a word character

</div>

<div>

\\S not a whitespace character

</div>

<div>

. any character except line break

</div>

<div>

\

</div>

<div>

**Some Regular Expression Syntax - Quantifiers**

</div>

<div>

\+ One or more

</div>

<div>

{3} Exactly x times. {3} - 3 times

</div>

<div>

{3,5} Three to five times

</div>

<div>

{4,} Four or more times

</div>

<div>

\* Zero or more times\

</div>

<div>

? Once or none(optional)

</div>

<div>

\

</div>

<div>

\[aeiou\] \# any in a,e,i,o,u

</div>

<div>

\[aeiou\]{2}

</div>

<div>

\[a-z\]

</div>

<div>

\[a-z0-9\]

</div>

<div>

\[\^k\] \# not letter k

</div>

<div>

\[\^@\$\] \#neither @ or \$

</div>

<div>

\

</div>

<div>

\^ Start of string or line

</div>

<div>

\$ End of string or line

</div>

<div>

\\b Word boundary

</div>

<div>

\

</div>

<div>

\#\|

</div>

<div>

\\(\\d{3}\\)**\|**\\d{3} matches (415) and 415

</div>

<div>

\

</div>

<div>

\#()

</div>

<div>

https?://(\[A-Za-z\_-\]+\\.\[A-Za-z\]+)

</div>

<div>

\# https://google.com \--\>match captures: google.com

</div>

<div>

**\
**

</div>

<div>

**Using Regular Expression With Python**

</div>

<div>

re(regular expression) module

</div>

<div>

\

</div>

<div>

\#import regex module

</div>

<div>

import re

</div>

<div>

\

</div>

<div>

\#define our phone number regex

</div>

<div>

pattern = re.compile(r\'\\d{3} \\d{3}-\\d{4}\') \#use r for escape
character

</div>

<div>

\

</div>

<div>

\#search a string with our regex

</div>

<div>

res = pattern.search(\'Call me at 415 555-4242!\') \#returns a match
object

</div>

<div>

res.group() \# only returns the first match since it was created by
pattern.search

</div>

<div>

res2 = pattern.findall(\"Call me at 310 445-9876 or 310 234-9999\")
\#\[\'310 445-9876\', \'234-9999\'\]

</div>

<div>

\

</div>

<div>

other way:

</div>

<div>

re.search(r\'\\d{3} \\d{3}-\\d{4}\', \'call me at 310 445-9876\')

</div>

<div>

re.findall(pattern, text)

</div>

<div>

\# will compile every time the method is called

</div>

<div>

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

</div>

<div>

import re

</div>

<div>

\# Returns first instance of phone number pattern:

</div>

<div>

def extract\_phone(input):

</div>

<div>

    phone\_regex = re.compile(r\'\\b\\d{3} \\d{3}-\\d{4}\\b\')

</div>

<div>

    match = phone\_regex.search(input)

</div>

<div>

    if match:

</div>

<div>

        return match.group()

</div>

<div>

    return None

</div>

<div>

\

</div>

<div>

\# Returns all instances of phone number pattern in a list

</div>

<div>

def extract\_all\_phones(input):

</div>

<div>

    phone\_regex = re.compile(r\'\\b\\d{3} \\d{3}-\\d{4}\\b\')

</div>

<div>

    return phone\_regex.findall(input)

</div>

<div>

\

</div>

<div>

\# One way of checking if entire string is valid phone number:

</div>

<div>

\# def is\_valid\_phone(input):

</div>

<div>

\#     phone\_regex = re.compile(r\'\^\\d{3} \\d{3}-\\d{4}\$\')

</div>

<div>

\#     match = phone\_regex.search(input)

</div>

<div>

\#     if match:

</div>

<div>

\#         return True

</div>

<div>

\#     return False

</div>

<div>

\

</div>

<div>

\# Another way of doing the same thing, using the fullmatch method

</div>

<div>

def is\_valid\_phone(input):

</div>

<div>

    phone\_regex = re.compile(r\'\\d{3} \\d{3}-\\d{4}\')

</div>

<div>

    match = phone\_regex.fullmatch(input)

</div>

<div>

    if match:

</div>

<div>

        return True

</div>

<div>

    return False

</div>

<div>

\

</div>

<div>

\# Calling our functions a bunch of times\...

</div>

<div>

\

</div>

<div>

print(extract\_phone(\"my number is 432 567-8976\"))

</div>

<div>

print(extract\_phone(\"my number is 432 567-897622\"))

</div>

<div>

print(extract\_phone(\"432 567-8976 asdjhasd \"))

</div>

<div>

print(extract\_phone(\"432 567-8976\"))

</div>

<div>

\

</div>

<div>

print(extract\_all\_phones(\"my number is 432 567-8976 or call me at 345
666-7899\"))

</div>

<div>

print(extract\_all\_phones(\"my number is 432 56\"))

</div>

<div>

\

</div>

<div>

print(is\_valid\_phone(\"432 567-8976\"))

</div>

<div>

print(is\_valid\_phone(\"432 567-8976 ads\"))

</div>

<div>

print(is\_valid\_phone(\"asd 432 567-8976 d\"))

</div>

<div>

\

</div>

<div>

**Parsing URLs With Python**

</div>

<div>

e.g.

</div>

<div>

import re

</div>

<div>

\

</div>

<div>

url\_regex =
re.compile(r\'(https?)://(www\\.\[A-za-z-\]{2,256}\\.\[a-z\]{2,6})(\[-a-zA-Z0-9@:%\_\\+.\~\#?&//=\]\*)\')

</div>

<div>

match =
url\_regex.search(\"https://www.my-website.com/bio?data=blah&dog=yes\")

</div>

<div>

print(f\"Protocol: {match.group(1)}\")

</div>

<div>

print(f\"Domain: {match.group(2)}\")

</div>

<div>

print(f\"Everything Else: {match.group(3)}\")

</div>

<div>

print(match.groups())

</div>

<div>

print(match.group())

</div>

<div>

\

</div>

<div>

**Symbolic Group Names**

</div>

<div>

import re

</div>

<div>

def parse\_name(input):

</div>

<div>

    name\_regex = re.compile(r\'\^(Mr\\.\|Mrs\\.\|Ms\\.\|Mdme\\.)
(**?P\<first\>**\[A-Za-z\]+) (**?P\<last\>**\[A-Za-z\]+)\$\')

</div>

<div>

    matches = name\_regex.search(input)

</div>

<div>

    print(matches.group())

</div>

<div>

    print(matches.group(\'first\'))

</div>

<div>

    print(matches.group(\'last\'))

</div>

<div>

\

</div>

<div>

parse\_name(\"Mrs. Tilda Swinton\")

</div>

<div>

**\
**

</div>

<div>

**Regex Compilation Flags**

</div>

<div>

\# Without Verbose Flag\...

</div>

<div>

\# pat =
re.compile(r\'\^(\[a-z0-9\_\\.-\]+)@(\[0-9a-z\\.-\]+)\\.(\[a-z\\.\]{2,6})\$\')

</div>

<div>

import re

</div>

<div>

pattern = re.compile(r\"\"\"

</div>

<div>

    \^(\[a-z0-9\_\\.-\]+)    \#first part of email    

</div>

<div>

    @                    \#single @ sign

</div>

<div>

    (\[0-9a-z\\.-\]+)        \#email provider

</div>

<div>

    \\.                    \#single period

</div>

<div>

    (\[a-z\\.\]{2,6})\$        \#com, org, net, etc.

</div>

<div>

\"\"\", re.X \| re.I) \#re.**VERBOSE** \| re.**IGNORECASE**, apply both
flags \|

</div>

<div>

\

</div>

<div>

match = pattern.search(\"ThomaS123\@Yahoo.com\")

</div>

<div>

print(match.group())

</div>

<div>

print(match.groups())

</div>

<div>

**\
**

</div>

<div>

**Regex Substitution Basics**

</div>

<div>

import re

</div>

<div>

text = \"Last night Mrs. Daisy and Mr. white murdered Ms. Chow\"

</div>

<div>

\

</div>

<div>

pattern = re.compile(r\'(Mr.\|Mrs.\|Ms.) (\[a-z\])\[a-z\]+\', re.I)

</div>

<div>

result = pattern.sub(\"\\g\<1\> \\g\<2\>\", text)

</div>

<div>

print(result)

</div>

<div>

**\
**

</div>

<div>

**Swapping File Names**

</div>

<div>

import re

</div>

<div>

titles = \[

</div>

<div>

    \"Significant Others (1987)\",

</div>

<div>

    \"Tales of the City (1978)\",

</div>

<div>

    \"The Days of Anna Madrigal (2014)\",

</div>

<div>

    \"Mary Ann in Autumn (2010)\",

</div>

<div>

    \"Further Tales of the City (1982)\",

</div>

<div>

    \"Babycakes (1984)\",

</div>

<div>

    \"More Tales of the City (1980)\",

</div>

<div>

    \"Sure of You (1989)\",

</div>

<div>

    \"Michael Tolliver Lives (2007)\"

</div>

<div>

\]

</div>

<div>

titles.sort()

</div>

<div>

fixed\_titles = \[\]

</div>

<div>

pattern = [re.compile(r\'(?P](http://re.compile(r'(/?P)\<title\>\^\[\\w
\]+) \\((?P\<date\>\\d{4})\\)\')

</div>

<div>

for book in titles:

</div>

<div>

    \# result = pattern.sub(\"\\g\<2\> - \\g\<1\>\", book)

</div>

<div>

    result = pattern.sub(\"\\g\<date\> - \\g\<title\>\", book)

</div>

<div>

    fixed\_titles.append(result)

</div>

<div>

fixed\_titles.sort()

</div>

<div>

print(fixed\_titles)

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

</div>

------------------------------------------------------------------------

[]{#389}

<div>

  -------------- ------------------------
  **Created:**   *11/12/2018 2:02 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

[Connecting to a DB With Python]{style="font-weight: bold;"}

</div>

<div>

e.g.

</div>

<div>

import sqlite3

</div>

<div>

conn = sqlite3.connect(\"my\_friends.db\")

</div>

<div>

\#create cursor object

</div>

<div>

c = conn.cursor()

</div>

<div>

\#execute some sql

</div>

<div>

c.execute(\"CREATE TABLE firends (first\_name TEXT, last\_name TEXT,
closeness INTEGER)\")

</div>

<div>

insert\_query = \'\'\'INSERT INTO friends 

</div>

<div>

                            VALUES(\'Merriwether\', \'Lewis\', 7 )\'\'\'

</div>

<div>

c.execute(insert\_query)

</div>

<div>

\#commit changes

</div>

<div>

conn.commit()

</div>

<div>

conn.close()

</div>

<div>

\

</div>

<div>

e.g.

</div>

<div>

import sqlite3

</div>

<div>

conn = sqlite3.connect(\"my\_friends.db\")

</div>

<div>

\# create cursor object

</div>

<div>

c = conn.cursor()

</div>

<div>

\

</div>

<div>

people = \[

</div>

<div>

    (\"Roald\",\"Amundsen\", 5),

</div>

<div>

    (\"Rosa\", \"Parks\", 8),

</div>

<div>

    (\"Henry\", \"Hudson\", 7),

</div>

<div>

    (\"Neil\",\"Armstrong\", 7),

</div>

<div>

    (\"Daniel\", \"Boone\", 3)\]

</div>

<div>

\# for person in people:

</div>

<div>

\#     insert that one person

</div>

<div>

average = 0

</div>

<div>

for person in people:

</div>

<div>

    c.execute(\"INSERT INTO friends VALUES (?,?,?)\", person)

</div>

<div>

    average += person\[2\]

</div>

<div>

print(average/len(people))

</div>

<div>

\# Insert all at once

</div>

<div>

\# c.executemany(\"INSERT INTO friends VALUES (?,?,?)\", people)

</div>

<div>

\# commit changes

</div>

<div>

[conn.commit](http://conn.commit/)()

</div>

<div>

conn.close()

</div>

<div>

\

</div>

<div>

**Selecting With Python**

</div>

<div>

import sqlite3

</div>

<div>

conn = sqlite3.connect(\"my\_friends.db\")

</div>

<div>

\# create cursor object

</div>

<div>

c = conn.cursor()

</div>

<div>

\# c.execute(\"SELECT \* FROM friends WHERE first\_name IS \'Rosa\'\")

</div>

<div>

c.execute(\"SELECT \* FROM friends WHERE closeness \> 5 ORDER BY
closeness\")

</div>

<div>

\

</div>

<div>

\# Iterate over cursor

</div>

<div>

\# for result in c:

</div>

<div>

\#     print(result)

</div>

<div>

\

</div>

<div>

\# Fetch One Result

</div>

<div>

\# print(c.fetchone())

</div>

<div>

\

</div>

<div>

\# Fetch all results as list

</div>

<div>

print(c.fetchall())

</div>

<div>

\

</div>

<div>

\# commit changes

</div>

<div>

[conn.commit](http://conn.commit/)()

</div>

<div>

conn.close()

</div>

<div>

\

</div>

<div>

**\
**

</div>

<div>

**SQL Injection**

</div>

<div>

**\
**

</div>

<div>

import sqlite3

</div>

<div>

conn = sqlite3.connect(\"users.db\")

</div>

<div>

\

</div>

<div>

\# query = \"CREATE TABLE users (username TEXT, password TEXT)\"

</div>

<div>

u = input(\"please enter your username\...\")

</div>

<div>

p = input(\"please enter your password\...\")

</div>

<div>

c = conn.cursor()

</div>

<div>

\

</div>

<div>

\# THE BAD WAY!

</div>

<div>

\# query = f\"SELECT \* FROM users WHERE username=\'{u}\' AND password =
\'{p}\'\"

</div>

<div>

\

</div>

<div>

\# THE MUCH SAFER WAY

</div>

<div>

query = f\"SELECT \* FROM users WHERE username=? AND password =?\"

</div>

<div>

c.execute(query,(u,p))

</div>

<div>

\

</div>

<div>

result = c.fetchone()

</div>

<div>

if(result):

</div>

<div>

    print(\"WELCOME BACK\")

</div>

<div>

else:

</div>

<div>

    print(\"FAILED LOGIN\")

</div>

<div>

\

</div>

<div>

[conn.commit](http://conn.commit/)()

</div>

<div>

conn.close()

</div>

<div>

**\
**

</div>

<div>

**Scraping to a Database**

</div>

<div>

**\
**

</div>

<div>

import sqlite3

</div>

<div>

import requests

</div>

<div>

from bs4 import BeautifulSoup

</div>

<div>

\

</div>

<div>

\# Request URl

</div>

<div>

\

</div>

<div>

def scrape\_books(url):

</div>

<div>

    response = requests.get(url)

</div>

<div>

    soup = BeautifulSoup(response.text, \"html.parser\")

</div>

<div>

    books = soup.find\_all(\"article\")

</div>

<div>

    all\_books = \[\]

</div>

<div>

    for book in books:

</div>

<div>

        book\_data =
(get\_title(book),get\_price(book),get\_rating(book))

</div>

<div>

        all\_books.append(book\_data)

</div>

<div>

    save\_books(all\_books)

</div>

<div>

    

</div>

<div>

\

</div>

<div>

def save\_books(all\_books):

</div>

<div>

    connection = sqlite3.connect(\"books.db\")

</div>

<div>

    c = connection.cursor()

</div>

<div>

    c.execute(\'\'\'CREATE TABLE books

</div>

<div>

        (title TEXT,price REAL,rating INTEGER)\'\'\')

</div>

<div>

    c.executemany(\"INSERT INTO books VALUES (?,?,?)\", all\_books)

</div>

<div>

    connection.commit()

</div>

<div>

    connection.close()

</div>

<div>

\

</div>

<div>

def get\_title(book):

</div>

<div>

    return book.find(\"h3\").find(\"a\")\[\"title\"\]

</div>

<div>

\

</div>

<div>

def get\_price(book):

</div>

<div>

    price = book.select(\".price\_color\")\[0\].get\_text()

</div>

<div>

    return float(price.replace(\"£\",\"\").replace(\"Â\",\"\"))

</div>

<div>

\

</div>

<div>

def get\_rating(book):

</div>

<div>

    ratings = {\"Zero\": 0, \"One\": 1, \"Two\": 2, \"Three\": 3,
\"Four\": 4, \"Five\": 5}

</div>

<div>

    paragraph = book.select(\".star-rating\")\[0\]

</div>

<div>

    word = paragraph.get\_attribute\_list(\"class\")\[-1\]

</div>

<div>

    return ratings\[word\]

</div>

<div>

\

</div>

<div>

scrape\_books(\"<http://books.toscrape.com/catalogue/category/books/history_32/index.html>\")

</div>

<div>

\# Initialize BS

</div>

<div>

\# Extract Data we Want

</div>

<div>

\# Save data to database

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

<div>

\

</div>

</div>

------------------------------------------------------------------------

[]{#390}

<div>

  -------------- ------------------------
  **Created:**   *10/16/2018 4:18 PM*
  **Author:**    *yingkaier\@gmail.com*
  -------------- ------------------------

</div>

\

<div>

<div>

<div>

[深入浅出python闭包]{style="font-size: 24px; overflow-wrap: break-word; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-variant-caps: normal; font-variant-ligatures: normal; font-weight: bold; line-height: 1.22;"} {#深入浅出python闭包 style="margin: 24px 0px; font-size: 24px; overflow-wrap: break-word; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255);"}
==================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================

<div>

[周围有些同事初学python，往往对python的一些高级特性，比如生成器(Generator),
闭包(closure)，装饰器(Decorator)感到有点不太容易理解，虽然这些特性并非python独有，但真的掌握了一定会让你感觉原来生活如此美好。]{style="font-size: medium; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-variant-caps: normal; font-variant-ligatures: normal;"}

</div>

1.  <div>

    [**1.
    闭包介绍**]{style="font-variant-ligatures: normal; font-variant-caps: normal; line-height: 1.5; font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; color: rgb(26, 26, 26); letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

    </div>

::: {style="margin: 1em 0px; font-size: medium; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255);"}
[闭包概念：在一个内部函数中，对外部作用域的变量进行引用，(并且一般外部函数的返回值为内部函数)，那么内部函数就被认为是闭包。举个栗子先：]{style="font-size: medium; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-variant-caps: normal; font-variant-ligatures: normal;"}
:::

::: {style="margin: 1em 0px; font-size: medium; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255);"}
[![](Evernote_files/Image.jpg)]{style="color: rgb(26, 26, 26);"}
:::

::: {style="margin: 1em 0px; font-size: medium; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255);"}
[在函数startAt中定义了一个incrementBy函数，incrementBy访问了外部函数startAt的变量，并且函数返回值为incrementBy函数（注意python是可以返回一个函数的，这也是python的特性之一）]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}[\
]{style="color: rgb(26, 26, 26);"}
:::

::: {style="margin: 1em 0px; color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255);"}
:::

</div>

<div>

![](Evernote_files/Image%20%5B1%5D.jpg)

</div>

<div>

[上面代码中a其实就是一个函数，上面代码执行的结果：]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

![](Evernote_files/Image%20%5B2%5D.jpg)

</div>

<div>

[从结果我们不难看出，a是函数incrementBy而不是startAt这个有点绕，但是并不难理解，因为return回来的是incrementBy函数。]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

[![](Evernote_files/Image%20%5B3%5D.jpg)]{style="color: rgb(26, 26, 26);"}

</div>

<div>

[输出是：]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

[![](Evernote_files/Image%20%5B4%5D.jpg)]{style="color: rgb(26, 26, 26);"}

</div>

<div>

[如果调用函数a的话，得到的结果是传入参数的整数值加。]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

[2. 常见错误]{style="font-variant-ligatures: normal; font-variant-caps: normal; font-weight: bold; font-size: 1.2em; line-height: 1.5; font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; color: rgb(26, 26, 26); letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"} {#常见错误 style="margin: 1.66667em 0px 0.83333em; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: bold; font-size: 1.2em; line-height: 1.5; font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; color: rgb(26, 26, 26); letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255);"}
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<div>

[闭包无法修改外部函数的局部变量]{style="font-weight: bold; color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255);"}[。这个是什么意思呢？]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

[![](Evernote_files/Image%20%5B5%5D.jpg)]{style="color: rgb(26, 26, 26);"}

</div>

<div>

[如果innerFunc可以修改x的值的话，x的值前后会发生变化，但结果是：]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

[![](Evernote_files/Image%20%5B6%5D.jpg)]{style="color: rgb(26, 26, 26);"}

</div>

<div>

[在innerFunc中x的值发生了改变，但是在outerFunc中x的值并未发生变化。]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

[python循环中不包含域的概念。]{style="font-weight: bold; color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

[**![](Evernote_files/Image%20%5B7%5D.jpg)**]{style="color: rgb(26, 26, 26);"}

</div>

<div>

[按照大家正常的理解，应该输出的是0, 2, 4对吧？但实际输出的结果是:4, 4,
4.
原因是什么呢？loop在python中是没有域的概念的，flist在像列表中添加func的时候，并没有保存i的值，而是当执行f(2)的时候才去取，这时候循环已经结束，i的值是2，所以结果都是4。]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

[其实修改方案也挺简单的：]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

[![](Evernote_files/Image%20%5B8%5D.jpg)]{style="color: rgb(26, 26, 26);"}

</div>

<div>

[在func外面再定义一个makefunc函数，func形成闭包，结果就正确了。]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

[3. 闭包的作用]{style="font-variant-ligatures: normal; font-variant-caps: normal; font-weight: bold; font-size: 1.2em; line-height: 1.5; font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; color: rgb(26, 26, 26); letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"} {#闭包的作用 style="margin: 1.66667em 0px 0.83333em; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: bold; font-size: 1.2em; line-height: 1.5; font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; color: rgb(26, 26, 26); letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255);"}
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<div>

[闭包可以保存当前的运行环境，以一个类似棋盘游戏的例子来说明。假设棋盘大小为50\*50，左上角为坐标系原点(0,0)，我需要一个函数，接收2个参数，分别为方向(direction)，步长(step)，该函数控制棋子的运动。
这里需要说明的是，每次运动的起点都是上次运动结束的终点。]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

[参考代码：]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

[![](Evernote_files/Image%20%5B9%5D.jpg)]{style="color: rgb(26, 26, 26);"}

</div>

<div>

[结果是]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}

</div>

<div>

[![](Evernote_files/Image%20%5B10%5D.jpg)]{style="color: rgb(26, 26, 26);"}

</div>

<div>

[也就是我们先沿X轴前进了10，然后沿Y轴前进了20，然后反方向沿X轴退了10，坐标分别问\[10,0\],
\[10, 20\], \[0,
20\]。]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255);"}

</div>

::: {style="margin: 1em 0px; color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgb(255, 255, 255);"}
[当然，闭包在爬虫以及web应用中都有很广泛的应用，并且闭包也是装饰器的基础，这些内容笔者会在后续的文章中分别介绍，这里就不多谈了。理解了本文中的概念，你应该知道的关于闭包的知识也差不多了，请在自己的编程中尽情使用吧。]{style="color: rgb(26, 26, 26); font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", "Source Han Sans SC", "Noto Sans CJK SC", "WenQuanYi Micro Hei", sans-serif; font-size: medium; font-variant-ligatures: normal; font-variant-caps: normal; letter-spacing: normal; orphans: 2; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px;"}
:::

</div>

</div>

 
