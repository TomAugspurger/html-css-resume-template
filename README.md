View the sample PDF at
<https://dl.dropbox.com/u/35602272/resume_example.pdf>.

Design inspired by http://practicaltypography.com/resumes.html

## Formats

HTML is the canonical format.
I generate a pdf using Safari's built-in pdf generator.
⌘-P > Save as PDF

This adds some extra markup, like the page numbers and URL.
I remove these (manually) with [PDFPen](http://www.smilesoftware.com/PDFpen/index.html)

A markdown version can be created with [pandoc](http://johnmacfarlane.net/pandoc/):

```
pandoc --css=resume.css resume.html -o resume_pandoc.md
```

