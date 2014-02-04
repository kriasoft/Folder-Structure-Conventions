Folder Structure Conventions
============================

> Folder structure options and naming conventions for software projects

### A typical top-level directory layout

    .
    ├── build                   # Compiled files (or `dist`)
    ├── docs                    # Documentation files
    ├── scripts                 # Scripts used for developent (test runner etc.)
    ├── src                     # Source files (or `lib`, `app`)
    ├── test                    # Unit, integration and other tests
    ├── tools                   # Utilities
    ├── LICENSE
    └── README.md

> - Use short lowercase names at least for the top-level files and folders except `LICENSE`, `README.md` and similar files

### Source files

The actual source files of a software project are usually stored inside the `src` folder. Alternatively, you can put them into the `lib` (if you're developing a library), or into the `app` folder (if your application's source files are not supposed to be compiled). In case, your application contains just one or two source files, you can put them into the root folder.

### Automated tests

...

### Documentation files

...

### Scripts

...

### Tools and utilities

...

### Compiled files

...

### 3rd party libraries

...

### License information

...
