# search_engine

Salient features of the projects
1. It is basically a search engine which search 
 a word , string or a quotations in all text files
 which are present in a given directory.


2. For pdf files first it convert the pdf files into text files then search given input string in them.

3. Algorithm used is inverted indexing, ranking and then searching
the word in O(1) time.
Preprocessing time complexity is O(n).

4. Command needed to execute for search your query are as follows.
  command 1:   $python search.py .
  
It give following options :
1) to create index and search in folder.
2) to search in folder.
3) to convert pdf to text.
4) search in file by kmp.
5) recently modified or created files.
6) exit program.

Enter your option like 1, 2 ,3 ,4 ,5 or 6

Initially execute the option 1 for creating index and ranking the files accordingly.
It take a little time to make indexing and giving ranking to all the files present in Texts directory.

KMP algorithm is used to search in files created or edited after previous indexing of files.

Now you can chose option on your choice.

For query:

For searching word simply give word as your input.

For quotations give input as <"your quotation"> .

Output:-
It gives file name and line number containing your query.

     



 
