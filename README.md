<!---
##
## README.md
##
## Master's Thesis LaTeX Template
##
## Version 1.0.0
##
## 2024-06-01
##
--->

# Master's Thesis LaTeX Template

Primarily suited for theses in English for major programs in Swedish at Åbo Akademi FNT. Based on di_direktiv.pdf and updated according to later guidelines.

This is not an officially endorsed template, user discretion is advised. The template takes inspiration from similar works, and incorporates parts of these works. Thanks to these authors.

Remember - this is a template I have created for my own needs. You might have different requirements for structure and formatting. There is not a one template to rule them all.

This README contains descriptions of the template, and instructions of varying detail on how to get started with this template.

## Description

**Language: English**  
Note that the template contains mandatory Swedish parts, as required for master's programs in Swedish.  

**References: IEEE Style**  
The document uses IEEE style references.

### Contents

* Title page
  - Self explanatory
* Abstract
  - Abstract in English
* Referat
  - Abstract in Swedish
* Preface 
  - Foreword and acknowledgements etc, per your own wishes
* Glossary
  - Terminology, word list, or what you find it suitable for
* Main contents c01-Introduction through c06-Conclusion
  - Add, rename or remove chapters according to your thesis structure
* Sammanfattning
  - Summary in Swedish
* Bibliography
  - Reference list


## Template Structure

This is a modular template, with a main entry point and an attempt at a logical separation between different types of LaTeX contents eventually forming the final document.

`./template/a01-Thesis.tex`

LaTeX starting point. Defines the LaTeX document structure and contents to include. Imports the preamble which defines packages to use and contains more technical details.

`./template/meta/a00-Preamble.tex`

In addition to defining packages to use, the preamble contains much of the layout and styling of the document.
Ideally, you as a user of this template, would not have to touch this file, but it is recommended that you review the layout and styling of the document, and adjust fonts etc to your liking.

`./template/contents/`

The `contents` directory houses the contents of the document, with a file for each chapter/part. Review and edit each part with your own content. Parts can be added and ommitted from the document via the `a01-Thesis.tex` main LaTeX file.  
```
b00-Title.tex
b01-Abstract.tex
b02-Referat.tex
b03-Preface.tex
b04-Glossary.tex
c01-Introduction.tex
c02-Background.tex
c03-Theory.tex
c04-Implementation.tex
c05-Results.tex
c06-Conclusion.tex
d01-Sammanfattning.tex
d02-Bibliography.bib
```

`./template/figures/.MARKER`

This directory contains only a MARKER file - a placeholder. You can use this directory to store figures that are part of the document.

## Known Issues

Known issues and limitations with the template, including further work to do.

* No figures
* No appendices part
* Need for figures listing?
* Abbreviations instead of Glossary?

## License

TODO License

Currently a private project that is not publically available.

## Credits

TODO Credits

Currently a private project that is not publically available.

* JB _di_direktiv.pdf_

* LS _di_template_
  - `https://github.com/lsundman/di_template`
  - No License

* TT _Åbo Akademi - Bachelor/Masters Thesis_
  - `https://www.overleaf.com/latex/templates/abo-akademi-bachelor-slash-masters-thesis/`
  - Creative Commons CC BY 4.0

* Aalto University _Aalto Thesis LaTeX Template_
  - `https://wiki.aalto.fi/display/Aaltothesis/Aalto+Thesis+LaTeX+Template`

## Git Versioning

You can use Git for versioning your thesis work in a repository. Before that, familiarize yourself with git and especially the `.gitignore` file, so that no work is lost. 

TODO More on using the repo.

---

<!--- END --->