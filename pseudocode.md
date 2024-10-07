LET unsortedBookList be our list of unsorted books
LET sortedBookList be our list of sorted books
LET bookToSort be our book we are currrently sorting
LET the value of bookToSort be the first book present in unsortedBookList
IF sortedBookList is empty, LET the first book of sortedBookList be bookToSort
IF sortedBookList is not empty, add bookToSort to sortedBookList
IF the book of bookToSort is the same as the last book of unsortedBookList, you're complete.
IF bookToSort comes before the book at the index before it in sortedBookList, swap the two books in the sortedBookList
IF bookToSort does not come before the book at the index before it or there is not another book before it in sortedBookList, LET bookToSort's new value be the next book in bookList & GOTO step 6.
