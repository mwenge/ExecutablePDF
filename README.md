# Executable PDF
Use [Actually Portable Executable](https://justine.lol/ape.html) and inspiration from
"A guide to ICO/PDF polyglot files" in [Paged Out](https://pagedout.institute/download/PagedOut_001_beta1.pdf)
to create a PDF file that you can both view in a PDF viewer and execute from the command line.

When viewed in a PDF viewer, it's a PDF document that can contain whatever PDF content you wish to publish.

When executed from the command line, the PDF runs an executable program that is embedded in it. This can be any
program you wish to compile in [ape](https://justine.lol/ape.html) format.

Try out the example `hello.pdf` in Linux:
```bash
evince hello.pdf
```
This shows:


Now try running the same file from the command line, as though it was a program:
```bash
./hello.pdf
```
Which it is:
```bash
[mwenge@mwenge ExecutablePDF (master)]$ ./hello.pdf
I'm also a little Computer Program!
```

If you want to recreate it for yourself, try [the Jupyter notebook](Create%20Executable%20PDF.ipynb).

