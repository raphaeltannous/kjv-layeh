> __Disclaimer:__ I am not familiar with the C programming language. I am not actually maintaining this fork, and I can't fix __BIG BUGS__. You are free to fork, or contact me to continue this project if you are familiar with C. Thank You!
>
> Jesus Christ is Lord!

# kjv

Read the Word of God from your terminal

## Usage

    usage: kjv [flags] [reference...]

    Flags:
      -A num  show num verses of context after matching verses
      -B num  show num verses of context before matching verses
      -W num  enable line wrap to a specific width
      -C      show matching verses in context of the chapter
      -e      highlighting of chapters and verse numbers
              (default when output is a TTY)
      -p      output to less with chapter grouping, spacing, indentation,
              and line wrapping
              (default when output is a TTY)
      -b      have a blank line after each verse
      -i      remove all highlighting
      -l      list books
      -h      show help

    Reference:
        <Book>
            Individual book
        <Book>:<Chapter>
            Individual chapter of a book
        <Book>:<Chapter>:<Verse>[,<Verse>]...
            Individual verse(s) of a specific chapter of a book
        <Book>:<Chapter>-<Chapter>
            Range of chapters in a book
        <Book>:<Chapter>:<Verse>-<Verse>
            Range of verses in a book chapter
        <Book>:<Chapter>:<Verse>-<Chapter>:<Verse>
            Range of chapters and verses in a book

        /<Search>
            All verses that match a pattern
        <Book>/<Search>
            All verses in a book that match a pattern
        <Book>:<Chapter>/<Search>
            All verses in a chapter of a book that match a pattern

## Build

kjv can be built by cloning the repository and then running make:

    git clone https://github.com/raphaeltannous/kjv-layeh.git kjv
    cd kjv
    make

## License

Public domain
