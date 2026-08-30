# Steve's Jujutsu tutorial (with my updates Aug 2026!)

[Read the updated version here](https://lookbusy1344.github.io/jujutsu-tutorial/), or
[download it as a PDF](https://lookbusy1344.github.io/jujutsu-tutorial/jujutsu-tutorial.pdf).

This is an expanded version of Steve Klabnik's original tutorial, with extra
chapters and fixes. Thanks to Steve for his work — you can find it at
[steveklabnik/jujutsu-tutorial](https://github.com/steveklabnik/jujutsu-tutorial)

## Requirements

Building the book requires [mdBook]. To get it:

[mdBook]: https://github.com/rust-lang/mdBook

```bash
$ cargo install mdbook
```

Or you can also install via Homebrew:

```bash
$ brew install mdbook
```

## Building

To build the book, type:

```bash
$ mdbook build
```

The output will be in the `book` subdirectory. To check it out, open it in
your web browser.

_Firefox:_
```bash
$ firefox book/index.html                       # Linux
$ open -a "Firefox" book/index.html             # OS X
$ Start-Process "firefox.exe" .\book\index.html # Windows (PowerShell)
$ start firefox.exe .\book\index.html           # Windows (Cmd)
```

_Chrome:_
```bash
$ google-chrome book/index.html                 # Linux
$ open -a "Google Chrome" book/index.html       # OS X
$ Start-Process "chrome.exe" .\book\index.html  # Windows (PowerShell)
$ start chrome.exe .\book\index.html            # Windows (Cmd)
```