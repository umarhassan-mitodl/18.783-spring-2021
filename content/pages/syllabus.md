---
content_type: page
description: This section includes information about the course topics, readings,
  software, assignments, and grading.
learning_resource_types: []
ocw_type: CourseSection
title: Syllabus
uid: e5c30f22-49fa-8667-27d5-11007088a7a8
---

Course Meeting Times
--------------------

Lectures: 2 sessions / week, 1.5 hours / session

Prerequisite
------------

[_18.702 Algebra II_](/courses/18-702-algebra-ii-spring-2011) 

Description
-----------

This course is a computationally focused introduction to elliptic curves, with applications to number theory and cryptography. While this is an introductory course, we will (gently) work our way up to some fairly advanced material, including an overview of the proof of Fermat's Last Theorem.

Each of the topics listed below corresponds to roughly one week of lectures (a total of three hours).

1.  **Introduction**  
    Course overview, the group law, and Weierstrass and Edwards curves.
2.  **Efficient computation**  
    Integer arithmetic, finite field arithmetic, polynomial arithmetic, and root-finding.
3.  **Isogenies and endomorphisms**  
    The Frobenius endomorphism, division polynomials, and Hasse’s theorem.
4.  **Elliptic curves over finite fields**  
    Point counting, baby-steps giant-steps, and Schoof’s algorithm.
5.  **The discrete logarithm problem**  
    ECEDH, Pollard rho, Pohlig-Hellman, generic lower bounds, and index calculus.
6.  **Integer factorization and primality proving**  
    Lenstra ECM, Goldwasser-Kilian ECPP, and Montgomery curves.
7.  **Endomorphism rings**  
    The dual isogeny, quadratic orders, quaternion algebras, and supersingular curves.
8.  **Elliptic curves over the complex numbers**  
    Elliptic functions, Eisenstein series, the Weierstrass ℘-function, complex tori, the _j_\-function, the uniformization theorem, and isogenies.
9.  **Modular curves**  
    Congruence subgroups, Riemann surfaces, and modular functions.
10.  **The theory of complex multiplication**  
    Ring class fields, Hilbert class polynomials, and the CM method.
11.  **Isogeny graphs**  
    Isogeny volcanoes, supersingular isogeny graphs, and isogeny-based cryptography.
12.  **Divisors and pairings**  
    Divisor class groups, pairings, Miller’s algorithm, and pairing-based cryptography.
13.  **Elliptic curves over Q, modular forms, and Fermat’s Last Theorem**  
    _L_\-series, BSD, Galois representations, modularity, and outline of Wiles’s proof.

Textbook and Notes
------------------

There is no required text; {{% resource_link 34ce673e-528e-a9cc-e1fc-539d275a3d85 "lecture notes" %}} will be provided. We will make reference to material in the following books.

Washington, Lawrence C. _Elliptic Curves: Number Theory and Cryptography_. Second edition. Chapman & Hall / CRC, 2008. ISBN: 9781420071467. ({{% resource_link "4cb5bbf6-07bd-430e-a91d-eb2b24ce00f3" "Errata (PDF)" %}}) \[Preview with {{% resource_link "10e28a5a-dd88-4a71-b932-5c579f4bf62f" "Google Books" %}}\]. {{% resource_link "e1fffb6f-9e54-4f0a-86c1-acc1f33ec472" "Online version" %}}.

Milne, James S. _Elliptic Curves_. BookSurge Publishing, 2006. ISBN: 9781419652578. ({{% resource_link "49aa6355-19be-444a-9217-f4769c8b3ece" "Addendum / erratum (PDF)" %}}). {{% resource_link "19eb9ef6-0d3d-4974-933d-b166a9ff8513" "Online version (PDF - 1.5MB)" %}}.

Silverman, Joseph H. _The Arithmetic of Elliptic Curves_. Springer-Verlag, 2009. ISBN: 9780387094939. ({{% resource_link "a47ea7c0-ee3b-4e1b-9d90-76024dd83e50" "Errata (PDF)" %}}) \[Preview with {{% resource_link "9d09916c-e3e0-4e3e-88f6-5ad707eb1e7f" "Google Books" %}}\]. {{% resource_link "d711db41-da82-42eb-b451-0711359ab36f" "Online version" %}}.

———. _Advanced Topics in the Arithmetic of Elliptic Curves_. Springer-Verlag, 1994. ISBN: 9780387943251. ({{% resource_link "2128c092-3b89-4ef7-8bae-6fffcc67f133" "Errata (PDF)" %}}). {{% resource_link "f1516913-6fce-433d-89e8-f295450d1770" "Online version" %}}.

Cox, David A. _Primes of the Form_ \\(x^2 + ny^2\\)_:_ _Fermat, Class Field Theory, and Complex Multiplication_. Wiley-Interscience, 1989. ISBN: 9780471506546. ({{% resource_link "a2641dc5-84dc-47ad-a20c-1918b5308d70" "Errata (PDF)" %}}). {{% resource_link "2fb11ae2-3053-451f-8fb3-56d533fac9e9" "Online version" %}}.

The following two books give quite accessible introductions to elliptic curves from different perspectives. You may find them useful as supplemental reading, but we will not use of them in the course.

Blake, Ian F., Gadiel Seroussi, and Nigel P. Smart. _Elliptic Curves in Cryptography_. Cambridge University Press, 1999. ISBN: 9780521653749. \[Preview with {{% resource_link "8952a76f-339a-4d18-8dee-73328843cb50" "Google Books" %}}\]

Silverman, Joseph H., and John T. Tate. _Rational Points on Elliptic Curves_. Springer-Verlag, 1994. ISBN: 9780387978253. {{% resource_link "ced4d524-3ddc-4b32-84f5-a22931983bfc" "Online version" %}}.

The following references provide introductions to algebraic number theory and complex analysis; neither of these topics is an official prerequisite for this course, but we will occasionally need to make use of their results.

{{% resource_link "d6456f65-1dee-4a71-b589-11394633e458" "Algebraic Number Theory Course Notes" %}} by James S. Milne.

Lang, Serge. _Complex Analysis_. Springer-Verlag, 2003. ISBN: 9780387985923. {{% resource_link "70d20245-2b7f-47c7-8721-71d8de9541eb" "Online version" %}}.

Software
--------

Some of the theorems and algorithms presented in lecture will be demonstrated using {{% resource_link "a06a008b-4bc2-413d-9bdc-7a6eb25d8acb" "Sage" %}}, a python-based computer algebra system, hosted on {{% resource_link "ddf6eba4-743a-4743-b4ef-3ceaa23ae542" "CoCalc" %}}. Most of the problem sets will contain at least one computationally-focused problem, which you will likely want to use Sage to solve, but you are free to use other packages, or roll your own code from scratch. You will be graded on your results and your mathematical explanation and analysis of your algorithm, not your code.

Problem Sets
------------

There will be weekly problem sets, each of which typically contains three to five multi-part problems. You are not expected to solve all of the problems; you be given the option to choose a subset to turn in. Some problems are purely theoretical in nature, while others are more computationally focused; those who prefer proofs to programming (or vice versa) can choose problems that appeal to their interests.

Problem sets are to be prepared in typeset form (typically via LaTeX) and submitted electronically as PDF files. Collaboration is permitted, but you must write up your own solutions and identify any collaborators, as well as any resources you used that are not listed above. There will be computational problems for which the correct answer will be different for every student, based on a unique identifier derived from your MIT ID.

Grading
-------

Your grade will be primarily determined by your average problem set score, after dropping your lowest score, plus bonus points you can earn by participating in polls held in class—you will get one point of extra credit for each question you answer (correctly or incorrectly). That might not sound like much, but over the course of the term it could be enough to make up for an entire problem set you missed.