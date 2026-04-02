# biblatex-amsplain: a biblatex duplicate of amsplain style

The package is intended for a BibLaTeX implementation of `amsplain.bst`.

## Usage

Place the relevant `amsplain.bbx` and `amsplain.cbx` under working directory,
and load them with BibLaTeX.

```tex
\usepackage[
    style  = amsplain,
    doi    = false,
    isbn   = false,
    url    = false,
    eprint = false,
]{biblatex}
```

## License

LaTeX Project Public License 1.3c or later
