# Code challenge

This challenge aims to show how you resolve problems, write code, and like to
work. This repository is private, and just for you, the repository will be
deleted after the recruitment process is finished. During the challenge, you
will have write permissions to the fork we have created for you.

Think of the solution as a complete software product, not just a one-liner to
solve the particular problem at hand. Consider additional aspects such as
maintainability, onboarding of new engineers, testing, error scenarios and
various edge cases. Use this repository to manage the product and any related
assets.

You are free to use any tools and resources, including AI assistants. However,
we expect you to know and understand every single line of code as if it was
written by ourself.

## Challenge

A small school library has many borrowers, and students are not very keen on
keeping books in the correct order. This makes teachers' jobs more difficult.
Hence, they want to keep the library in good order with printed lists. One main
problem is adding new books to this list since the school participates in a
national reading digest program and gets a couple of new books weekly.
Eventually the popular books also wear out beyond repair, and have to be removed
from the list.

## Task

The task is to create a program that helps teachers to keep the books in order.
The program takes a file name as the first command line argument, and the file
contains information on the book's name, the writer's name, and ISBN. You can
choose any appropriate textual format for the file.

After reading the file, the program shows the user interface, where they have
options to:

```
 - Add a new book
 - Remove a book
 - Print current database content in ascending order by writer's name
 - Exit the program
```

With the first option, the program should ask the user for the book's name,
writer's name, and book ISBN. Then, show the results to the user and ask if the
user wants to update the database. If the user selects to update the database,
the program should add the new book's information into the file given as a
command line input argument. Otherwise, return to the main menu.

The input file should always be kept in alphabetical order based on the writer's
name. Also, if the user chooses to print current database content, the program
should print out to screen all information from database, old and new
information.

The visual content of the file, user interface, or printing out the database can
be freely chosen. Still, it should be in human-readable format.

## Practicalities

You have three (3) hours to complete the challenge. Please complete the task in
the programming language of the role you are applying to. Remember to commit and
push your work!

We recommend starting the challenge by removing this paragraph and committing &
pushing the result. This ensures the Git access technicalities are OK and you
have write access to the repository. In case of you any trouble, please don't
hesitate to be in touch via phone/email to your contact person.
