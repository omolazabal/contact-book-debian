# Contact Book  

A little Debian contact book program accessible through the terminal. Created to learn how to make packages for Debian and as a little exercise for python (still learning the language).

Build with package with the command `sudo dpkg --build contact-book/`.  
Install the package with the command `sudo dpkg -i contact-book.deb`.

`$ contact-book -h` will display the arguments and their use.  
`$ contact-book -a` will let you add a new contact.  
`$ contact-book -d` will let you delete a contact(s).  
`$ contact-book -l` will list all of the contacts in alphabetical order.  
The `-n`, `-p`, and `-e` arguements will let you print a specific contact's information given their name, phone, or email respectively
