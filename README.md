# personal-liberaray-c-
“Personal library in your pocket” this sentence can describe our app very well. With the help of this app, you can use the three main lists which you will find once you sign in [books to read list, finished books list, my quotes list] to organize your reads. The app is implemented using (c++) language and it’s a linked list based.       
/////	Features and Functionality explanation:
 
2.1 Sign in and sign up:
First thing you need to do once you run the app.
When you sign up the app makes you a three text files named by the lists we mentioned before [books to read list, finished books list, my quotes list] + the username and saved in the app data base. When you sign in the app asks you to enter your name and searches for your file in the data base. If the app found the files, it creates three linked lists named by the names of our three lists and move the contents of each file to its linked list. If it didn’t find them, it will ask you if you want to sign up.


2.2 Books to read list:
This choice contains five options:

2.2.1 Show:
It displays the content of the” books to read” linked list.

2.2.2	Add a new book:
It asks you to enter a book name then it inserts it in” books to read” linked list using the function (insert new ()).

2.2.3	I finished a book:
It displays books to read list then asks you to enter a book ID then it deletes the book you choose and move it to “finished books” linked list.

2.2.4	Choose a random book to read:
It displays books to read list then it suggests you a book using the built in function (rand) then ask you if you want to try it again.

2.2.5	Back: 
It saves the changes in the (books to read) text file then it goes back to previous page.

2.3	your finished books list:
it contains three options:

2.3.1	show:
 It displays the content of the” finished books” linked list by using the function (show).

2.3.2	Clear:
it clears finished books” linked list by using the function (delete last) in a loop till it’s cleared.

2.3.3	Back:
It saves the changes in the (my finished books) text file then it goes back to previous page.

2.4	My quotes list:
It contains four options:

2.4.1	Show: 
It displays the content of the” my quotes” linked list by using the function (show).

2.4.2	Add a quote:
It asks you to enter the quote you want to save then it inserts it in” my quotes” linked list using the function (insert new ()).

2.4.3	Clear:
it clears “my quotes” linked list by using the function (delete last) in a loop till it’s cleared.

2.4.4	Back:
It saves the changes in the (my quotes) text file then it goes back to previous page.
