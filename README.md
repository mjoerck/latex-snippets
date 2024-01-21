![badge](https://img.shields.io/github/license/mjoerck/latex-snippets)

# **Snippets**
This is my collection of snippets for LaTeX-editing in Visual Studio Code. This snippets configuration is heavily inspired by [Gilles Castel's vim setup](https://castel.dev/post/lecture-notes-1/). Furthermore, I have found some great snippets for fractions [here](https://stackoverflow.com/questions/62545965/latex-fraction-snippets-in-vscode) and I have used [this comment](https://github.com/draivin/hsnips/issues/107#issuecomment-1021000711) for the math context. 

## Description
LaTeX is most likely the best way to write and format any kind of text that has got math in it. This repository is for snippets that speed up my workflow and automate a lot of typing. 
   
---    
## Usage
This collection of snippets is designed to work with the VSCode extension [HyperSnips](https://github.com/draivin/hsnips). You must download the snippets and in the settings of HyperSnips specify that it should use the file ```latex.hsnips```. 

## Example

```
snippet dm "Autoexpand display math" Ab
\[$1.\] $0
endsnippet
```

