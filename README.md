# Wednesday Task

Each team has different topics to search and demos to present!

Each team must also do their demo on a VM that has been provisioned.

Learning outcomes:

- vagrant and vm
- provisioning files
- provision scrip
- more advanced bash topic

topics: cat, ls, ll, grep, echo, head, tail, | >>

- wildcards
- ls with wildcards
- grep and wildcards
- cat and grep to search files

## Wildcards

Wildcards are symbols or special characters that represent other characters. You can use them with any command such as ls command or rm command to list or remove files matching a given criteria, receptively.

## cat

`cat <file>` will read what is in the file.

If you input `cat <directory>` it will tell you `cat: <directory>: Is a directory`.

## ls

`ls` lists the content for the directory you are currently in.

## ll

`ll` lists all accessible content for the directory you are in. It is a more detailed version of the `ls`.

## grep

`grep` is used to search for specific text within a file. It will return the line of text you've searched for within the file. To use you input `grep 'text' <file>`

## echo

`echo` will print the text given into the terminal.

For instance `echo 'text'` will print `text` into the terminal.

You can do `echo 'text' >> <file>` to append 'text' into the file.

## head

`head` will print the top few lines within a text file.
For instance `head -2 <file>` will print the top 2 lines within the file.

## tail

`tail` will print the top few lines within a text file.

For instance `tail -2 <file>` will print the top 2 lines within the file.

## |

`|` will allow you to write multiple commands.

Doing `ls | grep 'text'` will print anything printed in the command `ls` with the word text in.

## >>

`>>` appends to a file or creates and appends to the file with the given text printed.

e.g `ls >> <file>` will append anything written by `ls` into the selected file.
