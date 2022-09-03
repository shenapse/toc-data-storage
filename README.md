# Table of Contents of Books

A storage for table of contents of books.

In order to avoid copyright infringement, I try to ensure that the scope of quotations comply with the law and social conventions (In Japanese copyright law practice, the table of contents of almost all books is interpreted as not subject to copyright). Please let me know if there are any problems.

Pull requests and any suggestions for improvement are also welcome.

## Directory structure

Typical structure is

```txt
category
└── sub-category
    └── language
        └── 'title, author, publication year'.txt
```

For instance,

```txt
data
├── math
│   ├── algebra
│   │   ├── eng
│   │   └── ja
│   ├── calculus
│   │   ├── eng
│   │   └── ja
..............
├── statistics
│   ├── bayesian
│   │   ├── eng
│   │   └── ja
│   ├── causal_inference
│   │   ├── eng
│   │   └── ja
..............
```

## File format

### Name

The file name should be detailed enough to easily identify the book.

- File name should include
  - (Required): title, author, publication year
  - (Optional): edition, publisher, etc.

- Example of file name
  - (OK): Abstract Algebra, Dummit and Foote, 2003
  - (NG): Abstract Algebra, 3rd edition, 2003 (<- probably identifies the book but not so obvious.)

### Contents

- **Only the table of contents should be listed.**
- One line represents one headline
- page numbers are not required, but would be nice to have

```txt
# sample

Preface to the First Edition ix
CHAPTER I
Hilbert Spaces
§1. Elementary Properties 1
.........
References
Index
```
