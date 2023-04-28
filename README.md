# python_style.sty LaTeX Package Documentation

This package, `python_style`, provides syntax highlighting for Python code in LaTeX documents. It is based on the `listings` and `xcolor` packages and comes with a pre-defined style for Python code blocks.

## Package Dependencies

- listings
- xcolor

## Colors

The package defines various colors for different elements in Python code:

- Comments: green
- Triple quotes: dark green
- Line numbers: red
- Strings: purple
- Keywords: dark red
- Background: white
- Blue keywords: dark blue
- Functions: orange
- Exceptions: bright red
- Lines: gray
- Types: magenta
- Boolean literals: teal
- Self keyword: green

## Usage

### Python Code Block Environment

To include a Python code block in your LaTeX document, use the following environment:

```latex
begin{python}
# Your Python code goes here
end{python}
```

### Inline Python Code

For inline Python code, use the `\pyth` command:

```latex
pyth{your_inline_code}
```

## Customization

The package allows for customization of the Python code style by modifying the `python_style` within the `lstdefinestyle` command. You can adjust the colors, font styles, spacing, frames, and other formatting options.

For more information on customizing `listings` package, consult its documentation: https://ctan.org/pkg/listings.
