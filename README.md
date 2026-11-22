# My CV

## Local contact details

Contact details are loaded from `personal.tex`, which is ignored by Git. To
include them in a local PDF, create `personal.tex` in the repository root with:

```tex
\renewcommand{\CVaddress}{Your address}
\renewcommand{\CVemail}{you@example.com}
\renewcommand{\CVpropic}{pictures/propic.jpeg}
\renewcommand{\CVsignature}{pictures/signature.pdf}
```

Keep the image files at the paths configured above. The `pictures/` contents
are ignored by Git, just like `personal.tex`. Without that file, the CV builds
without contact details, photo, or signature. Generated PDFs are also ignored,
so review the PDF before sharing it separately.
