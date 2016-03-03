#Implementing Solvers Module(and Sets Module en route) in SymEngine

##Personal Details

**Name**: Akash Trehan<br/>
**University**: [Indian Institute of Technology, Bombay](http://www.iitb.ac.in)<br/>
**Email**: akash.trehan123@gmail.com<br/>
**Github**: [CodeMaxx](https://github.com/CodeMaxx)<br/>
**Other Contact Methods**: Google Hangouts, Gitter Chat<br>
**Blog**: [codemaxx.github.io](codemaxx.github.io) (TODO)<br/>
**Time-zone**: UTC+5:30

##Personal background

I am a first year B.Tech. undergraduate at [Indian Institute of Technology, Bombay](http://www.iitb.ac.in). I am pursuing **Computer Science and Engineering** as my Major. I love coding. I'm just addicted to it. I have a keen interest in Mathematics and Theoretical Physics. I like reading books on theoretical physics, such as Feynman Lectures.

Other than this I like tinkering with electronic circuits and making small robotic vehicles. I also like dancing, listening to music and performing Card magic tricks. I'll like learning and trying out new things.

#Programming Details

##Platform and Text Editor Used
I use both **Mac OS X** and **Ubuntu 14.04 LTS** as my work machines.
I use **Sublime Text 3** as my primary text editor because of its functionality, user-friendly nature and the useful packages which can be installed on it.
Sometimes I also use vim.

##Programming Experience
I have been using C and C++ since the past one year and python since past 4 months.

Apart from these I also do web programming so I have used Javascript,PHP with SQL for databases.I contribute to mozilla's open source project 'wptview' which is a web app for displaying results of web-platform-tests.

While working with SymEngine I also learn about 'cmake' and 'CMake files' - how to create them and how they function to create 'Makefiles'.

I use git and Github everyday and I am well acquainted with how to use them for version control.

Among all the programming languages I'm most comfortable with C++ and use it in most of my projects. I developed a game of Checkers, with Artificial Intelligence for one player game, using C++ for my class project.

#Contributions to SymEngine

I was introduced to SymEngine in mid-December 2015 and I have been contributing ever since. It has been an enriching experience and I look forward to continue contributing to it. A list of my contributions is as follows:

1.[PR #678](https://github.com/symengine/symengine/pull/678)(**Merged**) - Wrote a python script to check for the presence of Trailing Whitespace in the code during continuous integration in Travis.

2.[PR #715](https://github.com/symengine/symengine/pull/715)(**Merged**) - Moved dependencies(Catch and Teuchos) to utilities directory so that all the dependencies are together in a single subfolder.

3.[PR #727](https://github.com/symengine/symengine/pull/727)(**Merged**) - Added an additional compiling test for Travis with the latest gcc and g++ compiler(version 5.2 for both when I did this) so that new warnings coming up from these can be fixed.

4.[PR #736](https://github.com/symengine/symengine/pull/736)(**Pending**) - Adds two new functions, one for finding quadratic residues and second for checking if a number is a quadratic residue of another .Added tests for both. Also fixed variable names in another function which were causing ambiguity. This led to an issue for checking Integer overflows.

4.[PR #758](https://github.com/symengine/symengine/pull/758)(**Merged**) - Removed some redundant code left by another Developer's PR.

5.[PR #761](https://github.com/symengine/symengine/pull/761)(**Merged**) - Fixed a bug in `eval_mpfr.cpp` and `eval_mpc.cpp` where Euler's constant was being instead of Euler's Number.Added Tests for the same.

6.[PR #767](https://github.com/symengine/symengine/pull/767)(**Merged**) - Code for Whitespace Check shifted to the end of Travis file so that other more important errors can be handled first, before the program exits due to trailing  whitespaces.

7.[PR #792](https://github.com/symengine/symengine/pull/792)(**Merged**) - Added complete functionality for functions `sech`, `csch` and `acsch` and their Derivatives,printing and tests.

8.[PR #795](https://github.com/symengine/symengine/pull/795)(**Closed**) - This meant to prevent the use of 'Arb' when the user disables 'Flint'. It was closed since the discussion proved the corresponding [Issue #788](https://github.com/symengine/symengine/issues/788) to be Invalid.

9.[PR #807](https://github.com/symengine/symengine/pull/736)(**Merged**) - Improved and fixed functions of `Polygamma` class and added tests for the same.

10.[PR #815](https://github.com/symengine/symengine/pull/815)(**Pending**) - Add a cmake switch to prevent `Catch` from catching exceptions so that stacktraces can be obtained from `Teuchos`.

11.[PR #835](https://github.com/symengine/symengine/pull/835)(**Pending**) - Improves the `abs` functions so that it can handle `Complex` and  also `abs(x-y)` is treated as equal to `abs(y-x)`


- I also try to review some less complicated PRs and follow the discussions on others. This has helped me learn a lot of new stuff.

#The Project

##What I want to Achieve

Currently SymEngine lacks any support for Solvers and Sets. My aim through this project is to get a fully functional Sets module and use it for the implementations of the Solvers Module. Also I would improve the Polynomial module by adding Polynomial factorisation and other algorithms to provide support to the Solvers module. Solvers are a necessary part of any Computer Algebra System and since the final aim is to use SymEngine as a core for SymPy, we definitely need this functionality.

##What excites me

I've been working with SymEngine community from quite some time and want to remain associated with it for long. Making a significant contribution to it by taking up this project would be the best method to achieve this and to develop better understanding with the mentors. Maybe I can be a mentor myself some day.

I have always liked Maths and a projects such as this would help me improve my skills. Solvers would expose me to diverse areas of mathematics and help me learn new things in each.

Also being a programming and open source enthusiast, I've always wanted to take part in Google Summer of Code.

Also I want to meet other people working in this area and learn from them. Open Source indeed has a lot of talented people.

##Qualification

In this project I will be working with Sets and Solvers of Algebraic Equations and Ordinary Differential Equations.

The related courses I've taken are -  Calculus, Linear Algebra, Differential equations. As regard the programming skills I've done courses on - Computer Programming and Utilisation,Introduction to Computer Science, Abstractions and Paradigms for Programming. I have also knowledge about Algorithms and Data Structures. I think I am well suited to work on this project.

Also since I've worked with SymEngine, I've got comfortable with its code.

##Previous Implementations

This project has not been tried before in SymEngine, so I will be starting these modules. SymPy on the other hand has a very robust and flexible Sets module and a partially developed Solvers module. These would act as a good reference since these are very well documented.[[1](http://docs.sympy.org/latest/modules/solvers/solvers.html)][[2](http://docs.sympy.org/latest/modules/sets.html)]

For polynomial factorisation there are well written wiki pages on [Polynomial Factorisation](https://en.wikipedia.org/wiki/Polynomial_factorization), [Berlekamp's algorithm](https://en.wikipedia.org/wiki/Berlekamp%27s_algorithm) and [Cantor-Zassenhaus algorithm](https://en.wikipedia.org/wiki/Cantor-Zassenhaus_algorithm).

##Time during and after Summers

I have no other commitments this summer. So I'll be able to give a full 50 hours or more per week.

My summer break starts from 30th April so I can start working full time from that day on. I'll not be taking any vacations.

My classes start around mid-July. That might reduce the time given during weekdays but I'll try to compensate on weekends.

I'll continue to contribute to the project after Summer of Code although I'll not be able to work full time.

##Timeline

TODO