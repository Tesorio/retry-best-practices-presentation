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

- for a PDF: reload page with `?print-pdf` appended, and then **Chrome** -> Print -> Save as PDF
