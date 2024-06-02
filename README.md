# Executable PDF
Use [Actually Portable Executable](https://justine.lol/ape.html) and inspiration from
"A guide to ICO/PDF polyglot files" in [Paged Out](https://pagedout.institute/download/PagedOut_001_beta1.pdf)
to create a PDF file that you can both view in a PDF viewer and execute from the command line.

When executed from the command line, the PDF runs an executable program that is embedded in it.

Try out the example `hello.pdf`:
```bash
evince hello.pdf
./hello.pdf
```

If you want to recreate it for yourself, try [Create Executable PDF.ipynb].

