# Presentation

## Compile...

Requires `pandoc`.

```
$ pandoc -t revealjs -s -o presentation.html presentation.md -V theme=moon
```

## Run...

```
$ python -m SimpleHTTPServer
```

... then navigate to `localhost:8000/presentation.html`

- for speaker notes: press `s` on page while presentation is open

- for a PDF: load page (in **Chrome**) with `?print-pdf` appended

  Print -> ☑︎ Background Graphics -> Save as PDF
