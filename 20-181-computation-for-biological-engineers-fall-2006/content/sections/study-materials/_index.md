---
course_id: 20-181-computation-for-biological-engineers-fall-2006
layout: course_section
menu:
  leftnav:
    identifier: cdaac6d9fa8d0985f397e3cc20d29c21
    name: Study Materials
    weight: 50
title: Study Materials
type: course
uid: cdaac6d9fa8d0985f397e3cc20d29c21

---

Python® Tutorial
----------------

Given the programming content of 20.180's [assignments](/courses/20-180-biological-engineering-programming-spring-2006/sections/assignments) and the [superb tutorials](/courses/20-180-biological-engineering-programming-spring-2006/sections/study-materials) composed by its TAs, the class is assumed to have some experience with Python®. So, rather than offer a purely introductory tutorial to programming + Python®, the 20.181 TAs offered a short refresher course during office hours after the first lecture session.

Python®+Emacs+Shell cheat sheet ([PDF]({{< baseurl >}}/sections/study-materials/python_sheet))

If you still crave more Python® tutorials here is a [list of 300 Python® Tutorials](http://www.tutorialized.com/tutorials/Python/1). You may also find [the official Python® documentation](http://docs.python.org/lib/) to be handy.

Refresher Course on Python®/Emacs/Shell: Five Different Ways to do The Fibonacci Sequence
-----------------------------------------------------------------------------------------

Code for 20.181 Refresher Course ([ZIP](/coursemedia/20-181-computation-for-biological-engineers-fall-2006/2e4e198a63c5e65d10968b7319fd7203_fibonacci_example.zip)) (The ZIP file contains: fib.txt, fib\_module.py, and fibonacci\_tutorial.py.)

Start with file fib\_module.py. This file defines a function called calc\_fib that we will use in method 1.

(In this class we will often start with a big code base that someone else has developed, and we will write some small part which utilizes this pre-existing code. When you are supposed to hijack others' code, you will be told to do so explicitly and the code will be provided to you. In all other cases, using code you found on the internets is not acceptable. So please don't.)

For this tutorial we'll be working on emacs. Emacs is like pico (which you used last term in 20.180), the text editor on MIT server, except with more functionality. But you can use whichever you're comfortable with. A few additional emacs tips:

*   cntl-Z to step out of emacs without killing it, then type "fg" (stands for foreground) to step back in.  
    your changes won't be lost when you do this, but if you want to run the new version of your file, cntl-x cntl-s to save the chances before stepping out.
*   emacs find and replace function
    *   M-% (alt-shift-5)
    *   you have to have your cursor at the top of the file
    *   space bar to accept change and keep finding
    *   more info on [find and replace](http://kb.iu.edu/data/abdp.html)

Python® code written during the refresher course, with some associated comments: OH1\_commentedcode.txt ([TXT](/courses/biological-engineering/20-181-computation-for-biological-engineers-fall-2006/study-materials/OH1_commentedcode.txt))