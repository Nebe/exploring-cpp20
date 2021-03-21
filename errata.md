# Errata for *Exploring C++20*

On **page 80** [technical accuracy]:
 
The book falsely states that "the *or* operator evaluates its right-hand operand only if the left-hand operand is *true*." The short-circuting of the *or* logical operator happens, when the left-hand operator is *false*.

***

On **page 109** [technical accuracy]:
 
The book states "C++ guarantees that any character set your compiler and library support represents digit characters with contiguous values", which is true.

It goes on to say "The same sequence is true for letters in the alphabet, that is, 'A' + 25 == 'Z'", which is not.  In EBCDIC (mentioned earlier in the chapter) the letters are not contiguous.

***

On **page 112** [technical accuracy]:
 
The book states that "MacOS uses a carriage return ('\x0d')" as a newline character.  This is not true of more modern versions of MacOS, which use a line feed like UNIX.

***
On **page xx** [Summary of error]:
 
Details of error here. Highlight key pieces in **bold**.

***
