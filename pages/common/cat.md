# [cat](http://man7.org/linux/man-pages/man1/cat.1.html)
> Print and concatenate files.

- Print the contents of a file to the standard output:

`cat {{file}}`

- Concatenate several files into the target file:

`cat {{file1}} {{file2}} > {{target_file}}`

- Append several files into the target file:

`cat {{file1}} {{file2}} >> {{target_file}}`

- Number all output lines:

`cat -n {{file}}`
