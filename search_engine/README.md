# search_engine
This project search the word ,sentence /string or Quotations 

Salient features of the projects
1. It is basically a search engine which search the 
 a word , string/Sentence or a quotations in all text files and pdf files
 which are present in a given directory


2. for pdf files first it convert the pdf files into text then search in them.

3. algorithm is using is inverted indexing, making raking and then searching
the word in O(1) time.
preprocessing time is O(n)

4. In texts folder contain all txt files and in PDFs folder contain pdf files

5. command need to execute for search your query
  command 1:   $python search.py
     it give following options to you
1)to create index and search in folder
2)to search in folder
3)to convert pdf to text
4)search in file by kmp
5)recently modified or created files
6)exit program

enter your option like 1, 2 ,3 ,4,5,6


enter one for execute the option 1
first execute the option 1

it make the index and rank the files accordingly
it take a liitle time to make indexing and giving ranking to all the files present in Texts sirectory

now you can chose option on your choice

for Quoray:
for search word simple give input your word example <algorithm>
for Search the Sentence input <your Sentence>
for quotations input <"your quotation">

Output:-
It gives
1 File name and line number containg your query ;

I am using Kmp to those files which you add next few files so that not waste time to
make indexing all files after adding few files
If you adding a number of files then you can make indexing executing the command 1

     



 
