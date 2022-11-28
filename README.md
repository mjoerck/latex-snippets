![badge](https://img.shields.io/github/license/mjoerck/latex-snippets)

# **Snippets**
This is my collection of snippets for LaTeX-editing in Visual Studio Code

## Description
LaTeX is most likely the best way to write and format any kind of text that has got math in it. This repository is for snippets that speed up my workflow and automate a lot of typing. 
   
---    
## Usage
This collection of snippets is designed to work with the VSCode extension [HyperSnips](https://github.com/draivin/hsnips). You must download the snippets and in the settings of HyperSnips specifiy that it should use the file ```latex.hsnips```. 

You first need to download the inquirer package. Run the command `npm init -y` in the terminal to create a package.json file. Next run the command `npm i inquirer@8.2.4` to install the inquirer package.
<br/>Here is a video demonstrating the program [link to Screencastify](https://app.castify.com/view/9dc7ce75-3e91-476a-9282-5872b829cf79)

---
## Examples 

```
snippet dm "Autoexpand display math" Ab
\[$1.\] $0
endsnippet
```

