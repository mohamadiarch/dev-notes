
# python notes
[2:4] its up to but not 

## Milse
>>>  ===> chevron prompt

## strings
. strings are objects
. uppercase letter < lowercase letter ===> Z < z | Z < a 
. \n is one charachter
. print() adds a newline at the end
.

## loops
. continue means skip





## files
```py
    fhand = open('mbox-short.txt')  # a file handle is a sequence of lines(lines as a string)
    print(fhand)                    # print the file handle object( not lines of file)
    #if you want to see lines of file you should use for
    for line in fhand:  # read each of line
        print(line)     # WARN print add a \n and each line have \n too
        line.rstrip()  # alternative to print for read each line with just one \n

``
```py
    fhand = open('mbox-short.txt')
    line = fhand.readline()             # read the first line
    all_lines = fhand.readlines()       # read all the lines
    all_lines = fhand.read()            # read all the lines
    print(all_lines)
```




