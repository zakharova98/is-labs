# Tasks

## Lab 1: Prolog introduction

What do you need to do:
- find and configure any Prolog [implementation](https://en.wikipedia.org/wiki/Comparison_of_Prolog_implementations)
- develop a knowledge base:
  - populate it with some facts
  - add as many rules as possible for extracting additional knowleges out of raw facts
  
Example:

```
male(tom).
female(angela).
female(lisa).
parent(tom, angela).
parent(lisa, angela).

% define mother(X, Y), mother(X)
% define father(X, Y), father(X)
% define son, brother, sister, daughter and other relationship
```

Example 2:

```
hobby(drawing).
hobby(sketching).
related_hobbies(drawing,sketching).
person(john).
likes(john, drawing).

% define common_interest(Person1, Person2)
% define suggested_hobbies(Person)
% define unpopular_hobbies(Hobby)
% define the_most_popular_hobby(Hobby)
```

Example 3:

```
book("Title", 120). % 120 - number of pages
written_by(john, "Title").

% define small_book(Book), huge_book(Book)
% define the_biggest_book(Book)
% define author_of_small_books(Author)
```