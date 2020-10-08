# polyglot

## The task

The nth program to be submitted must run in n different languages; specifically, all the languages added in previous programs to be submitted, plus one more. The program must output 1 when run in the first language used in answers to this question, 2 when run in the second language, and so on. For example, the first answer could print 1 when run in Python 3, and the second answer could output 1 when run in Python 3 and 2 when run in JavaScript; in this case, the third answer would have to output 1 when run in Python 3, 2 when run in JavaScript, and 3 when run in some other language.

## Additional rules

Your program must run without erroring out or crashing. Warnings (and other stderr output) are acceptable, but the program must exit normally.

The output must be only the integer, but trailing newlines are OK. Other unavoidable stdout output is also allowed.

Using different versions of the same language is allowed (although obviously they'll have to print different numbers, so you'll need to fit a version check into the polyglot). However, you may not use a language feature that returns the language's version number. Repeating the exact same language is, obviously, impossible (as the program would have to deterministically print one of two different numbers).

You don't have to use the previous answers as a guide to writing your own (you can rewrite the whole program if you like, as long as it complies with the spec); however, basing your answer mostly on a previous answer is allowed and probably the easiest way to make a solution.
#kartoshka
