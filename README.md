# README.md

## I. Description

### Book:
- **ID:** Auto-incremented
- **Title:** String
- **Author:** Object (with properties such as name, active years, etc.)
- **Published Year:** Integer
- **Status:** String (e.g., "Available", "Borrowed")

## II. Requirements

### 1. Setup Library

```
========= SET UP LIBRARY =========
=> Enter Library's Name : SOUR SDEY LIBRARY
=> Enter Library's Address : Phnom Penh
"SOUR SDEY LIBRARY" Library is already created in "Phnom Penh" address successfully on Mon Mar 07 19:16:33 ICT 2022
```

### 2. Display Library Menu

```
========= SOUR SDEY LIBRARY , PHNOM PENH =========
1- Add Book
2- Show All Books
3- Show Available Books
4- Borrow Book
5- Return Book
6- Exit
-----------------------------------------
=> Choose option(1-6) : 2
========= ALL BOOKS INFO =========
No Book Available
```

### 3. Add Book

```
========= SOUR SDEY LIBRARY , PHNOM PENH =========
1- Add Book
2- Show All Books
3- Show Available Books
4- Borrow Book
5- Return Book
6- Exit
-----------------------------------------
=> Choose option(1-6) : 1
========= ADD BOOK INFO =========
=> Book ID : 3
=> Enter Book's Name : The Art of War
=> Enter Book Author Name: Sun Tzu
=> Enter Author Year Active: 560-640
=> Enter Published Year : 604
Book is added successfully
```

### 4. Show All Books

```
========= SOUR SDEY LIBRARY , PHNOM PENH =========
1- Add Book
2- Show All Books
3- Show Available Books
4- Borrow Book
5- Return Book
6- Exit
-----------------------------------------
=> Choose option(1-6) : 2
========= ALL BOOKS INFO =========

Press "ENTER" to continue...
```

### 5. Borrow Book

#### Case 1: Book ID doesn’t exist in the library

```
========= SOUR SDEY LIBRARY , PHNOM PENH =========
1- Add Book
2- Show All Books
3- Show Available Books
4- Borrow Book
5- Return Book
6- Exit
-----------------------------------------
=> Choose option(1-6) : 4
========= BORROW BOOK INFO =========
=> Enter Book ID to Borrow : 4
Book ID : 4 not Exist...
```

#### Case 2: Book ID exists in the library

```
========= SOUR SDEY LIBRARY , PHNOM PENH =========
1- Add Book
2- Show All Books
3- Show Available Books
4- Borrow Book
5- Return Book
6- Exit
-----------------------------------------
=> Choose option(1-6) : 4

========= BORROW BOOK INFO =========
=> Enter Book ID to Borrow : 1
Book ID : 1
Book Title : Titanic
Book Author : James Cameron (1950-2010)
Published Year : 1997 is borrowed successfully...
```

### 6. Show Available Books

```
========= SOUR SDEY LIBRARY , PHNOM PENH =========
1- Add Book
2- Show All Books
3- Show Available Books
4- Borrow Book
5- Return Book
6- Exit
-----------------------------------------
=> Choose option(1-6) : 3
========= AVAILABLE BOOKS INFO =========

Press "ENTER" to continue...
```

### 7. Return Book

#### Case 1: Book ID is not in borrowed book list

```
========= SOUR SDEY LIBRARY , PHNOM PENH =========
1- Add Book
2- Show All Books
3- Show Available Books
4- Borrow Book
5- Return Book
6- Exit
-----------------------------------------
=> Choose option(1-6) : 5
========= RETURN BOOK INFO =========
=> Enter Book ID to Return : 1
Book ID : 1 is failed to return...
```

#### Case 2: Book ID is in borrowed books list

```
========= SOUR SDEY LIBRARY , PHNOM PENH =========
1- Add Book
2- Show All Books
3- Show Available Books
4- Borrow Book
5- Return Book
6- Exit
-----------------------------------------
=> Choose option(1-6) : 5
========= RETURN BOOK INFO =========
=> Enter Book ID to Return : 1
Book ID : 1
Book Title : Titanic
Book Author : James Cameron (1950-2010)
Published Year : 1997 is returned successfully...
```

### 8. Exit Program

```
========= SOUR SDEY LIBRARY , PHNOM PENH =========
1- Add Book
2- Show All Books
3- Show Available Books
4- Borrow Book
5- Return Book
6- Exit
-----------------------------------------
=> Choose option(1-6) : 6
(^-^) Good Bye! (^-^)
```

## Hint:
- Use an array of objects.
- Have a class `Book` with the following attributes:
  - `id` (private, auto-generated)
  - `title` (private)
  - `author` (private, as an object)
  - `publishedYear` (private)
  - `status` (private, e.g., "Available", "Borrowed")
- Provide setters and getters for all attributes to modify and retrieve values.

## Bonus Features:
- Pagination for book lists
- Set row size for book lists
- Remove books
- Additional custom features

