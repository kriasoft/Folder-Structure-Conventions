Folder Structure Conventions
============================

> Folder structure options and naming conventions for software projects

### A typical top-level directory layout

    .
    ├── build                   # Compiled files (alternatively `dist`)
    ├── docs                    # Documentation files
    ├── scripts                 # Scripts used for developent (test runner etc.)
    ├── src                     # Source files (alternatively `lib` or `app`)
    ├── test                    # Unit, integration and other tests (alternatively `tests`)
    ├── tools                   # Utilities
    ├── LICENSE
    └── README.md

> Use short lowercase names at least for the top-level files and folders except
> `LICENSE`, `README.md`

### Source files

The actual source files of a software project are usually stored inside the
`src` folder. Alternatively, you can put them into the `lib` (if you're
developing a library), or into the `app` folder (if your application's source
files are not supposed to be compiled).

> **Samples**: [jQuery](https://github.com/jquery/jquery) `src`, [Node.js](https://github.com/joyent/node) `lib` and `src`, [D3.js](https://github.com/mbostock/d3) `src`, [AngularJS](https://github.com/angular/angular.js) `src`, [Adobe Brackets](https://github.com/adobe/brackets) `src`, [Express](https://github.com/visionmedia/express) `lib`, [Socket.IO](https://github.com/LearnBoost/socket.io) `lib`, [Less.js](https://github.com/less/less.js) `lib`, [Redis](https://github.com/antirez/redis) `src`, [Ace](https://github.com/ajaxorg/ace) `lib`, [Semantic UI](https://github.com/Semantic-Org/Semantic-UI) `src`, [Zepto.js](https://github.com/madrobby/zepto) `src`, [Emscripten](https://github.com/kripken/emscripten) `src`, [RethinkDB](https://github.com/rethinkdb/rethinkdb) `src`, [Bitcoin](https://github.com/bitcoin/bitcoin) `src`, [MongoDB](https://github.com/mongodb/mongo) `src`, [Facebook React](https://github.com/facebook/react) `src`, [Rust](https://github.com/mozilla/rust) `src`, [ASP.NET](https://aspnetwebstack.codeplex.com/SourceControl/latest) `src`, [SignalR](https://github.com/SignalR/SignalR) `src`, [libgit2](https://github.com/libgit2/libgit2) `src`.

### Automated tests

Automated tests are usually placed into the `test` or, less commonly, into the `tests` folder.

> **Q: Why tests are placed into a seporate folder, as opposed to having them closer to the code under test?**
>
> **A:** Because you don't want to test the code, you want to test the *program*.

    .
    ├── ...
    ├── test
    │   ├── load                # Load and stress tests
    │   ├── e2e                 # End-to-end, integration tests
    │   └── unit                # Unit tests
    └── ...

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

If you want to share your work with others, please consider choosing an open
source license and include the text of the license into your project.
The text of a license is usually stored in the `LICENSE` (or `LICENSE.txt`,
`LICENSE.md`) file in the root of the project.

> You’re under no obligation to choose a license and it’s your right not to
> include one with your code or project. But please note that opting out of
> open source licenses doesn’t mean you’re opting out of copyright law.
> 
> You’ll have to check with your own legal counsel regarding your particular
> project, but generally speaking, the absence of a license means that default
> copyright laws apply. This means that you retain all rights to your source
> code and that nobody else may reproduce, distribute, or create derivative
> works from your work. This might not be what you intend.
>
> Even in the absence of a license file, you may grant some rights in cases
> where you publish your source code to a site that requires accepting terms
> of service. For example, if you publish your source code in a public
> repository on GitHub, you have accepted the [Terms of Service](https://help.github.com/articles/github-terms-of-service)
> which do allow other GitHub users some rights. Specifically, you allow others
> to view and fork your repository.

For more info on how to choose a license for an open source project, please
refer to http://choosealicense.com
