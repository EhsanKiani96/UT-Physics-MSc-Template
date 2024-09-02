<link rel="stylesheet" type="text/css" href="styles.css">

# 🎓 <span class="custom-title">Persian LaTeX Template for University of Tehran - Physics Department (Master's Thesis)</span>

<span class="custom-text">This repository provides a LaTeX template
designed for master's theses in the Physics Department at the University
of Tehran. It is configured to support Persian language typesetting and
adheres to the formatting guidelines required for academic submissions
in the department.</span>

## 🗂️ <span class="custom-title">File Structure Overview</span>

### 📁 <span class="custom-subtitle">`SetupFiles/`</span>

<span class="custom-text">This directory contains configuration files
for setting up the LaTeX document, including packages, custom commands,
and environments.</span>

  - **📦 <span class="custom-file">`Packages.tex`</span>**:
    <span class="custom-text">Includes all the LaTeX packages required
    for the document, providing necessary functionality such as support
    for Persian text, figures, and tables.</span>
  - **⚙️ <span class="custom-file">`Setups.tex`</span>**:
    <span class="custom-text">Contains various document settings and
    customizations, such as layout options, margins, and stylistic
    settings.</span>
  - **🛠️ <span class="custom-file">`Commands.tex`</span>**:
    <span class="custom-text">Defines custom LaTeX commands and macros
    to simplify and standardize repetitive elements in the
    document.</span>
  - **🏗️ <span class="custom-file">`Environment.tex`</span>**:
    <span class="custom-text">Sets up custom environments for specific
    formatting of sections, lists, or other structured elements in the
    thesis.</span>

### 📚 <span class="custom-subtitle">`TexFiles/`</span>

<span class="custom-text">This directory holds the core content of the
thesis, organized into separate files for modularity and ease of
management.</span>

  - **📜 <span class="custom-file">`Basmala.tex`</span>**:
    <span class="custom-text">Includes the Basmala (بسم الله الرحمن
    الرحيم) at the beginning of the document.</span>
  - **📑 <span class="custom-file">`PersianTitle.tex`</span>**:
    <span class="custom-text">Contains the Persian title page with the
    thesis title, author, and institution information.</span>
  - **📝 <span class="custom-file">`Originality.tex`</span>**:
    <span class="custom-text">Provides the statement of originality
    required for academic theses.</span>
  - **❤️ <span class="custom-file">`Dedication.tex`</span>**:
    <span class="custom-text">A section for dedicating the thesis to
    someone.</span>
  - **🙏 <span class="custom-file">`Acknowledgments.tex`</span>**:
    <span class="custom-text">Contains acknowledgments for contributions
    and support received.</span>
  - **📝 <span class="custom-file">`PersianAbstract.tex`</span>**:
    <span class="custom-text">Includes the Persian abstract summarizing
    the research work.</span>
  - **📖 <span class="custom-file">`Chapter1.tex`</span>** to
    **<span class="custom-file">`Chapter6.tex`</span>**:
    <span class="custom-text">Each file represents a chapter of the
    thesis, facilitating easier management of the document.</span>
  - **📚 <span class="custom-file">`Reference.bib`</span>**:
    <span class="custom-text">A BibTeX file with all the references
    cited in the thesis, used to generate the bibliography
    section.</span>
  - **📄 <span class="custom-file">`Appendix1.tex`</span>**:
    <span class="custom-text">Contains additional material or
    supplementary information.</span>
  - **🌍 <span class="custom-file">`EnglishAbstract.tex`</span>**:
    <span class="custom-text">Provides the abstract in English, ensuring
    accessibility to a broader audience.</span>
  - **🌐 <span class="custom-file">`EnglishTitle.tex`</span>**:
    <span class="custom-text">Contains the English title page, if
    required.</span>

### 🖋️ <span class="custom-subtitle">`Fonts/`</span>

<span class="custom-text">This directory includes font files used in the
document.</span>

  - **🗂️ <span class="custom-file">\[Font Files\]</span>**:
    <span class="custom-text">Contains font files (.ttf, .otf, etc.)
    used for specific typographic needs or to maintain consistency with
    departmental formatting guidelines. These fonts are loaded and
    applied through LaTeX configuration files.</span>

### 🖼️ <span class="custom-subtitle">`Pictures/`</span>

<span class="custom-text">This directory is used for storing image files
included in the thesis.</span>

  - **🖼️ <span class="custom-file">\[Image Files\]</span>**:
    <span class="custom-text">Contains images, figures, and diagrams
    referenced in the thesis. Supported formats may include .png, .jpg,
    .pdf, etc. Images are typically included in the text using LaTeX
    commands and can be placed within chapters, appendices, or other
    sections as needed.</span>

### 📝 <span class="custom-subtitle">Instructions</span>

  - **🔧 <span class="custom-instruction">Adding Packages</span>**:
    <span class="custom-text">If you need to add or update LaTeX
    packages, modify the `Packages.tex` file in the `SetupFiles`
    directory. This will ensure that the new packages are included in
    the document.</span>

  - **✏️ <span class="custom-instruction">Writing Document
    Content</span>**: <span class="custom-text">For writing and editing
    the content of your thesis, use the files in the `TexFiles`
    directory. Each file corresponds to a different section or chapter
    of the thesis.</span>

  - **🛠️ <span class="custom-instruction">Compiling the
    Document</span>**: <span class="custom-text">To compile the thesis,
    run the `Main.tex` file. This will integrate all the sections and
    configurations into a single document.</span>

  - **🖥️ <span class="custom-instruction">Compiling with LaTeX
    Editors</span>**:
    
      - **💻 <span class="custom-file">Overleaf</span>**:
        <span class="custom-text">You should not encounter any issues
        with Overleaf; it handles compilation automatically.</span>
    
      - **🖥️ <span class="custom-file">Local LaTeX
        Installation</span>**: <span class="custom-text">If you are
        using a LaTeX editor installed on your local machine (e.g.,
        TeXMaker, TeXstudio), you need to use the following command for
        compiling:</span>
        
        ``` shell
        xelatex.exe -shell-escape -synctex=1 -interaction=nonstopmode %.tex
        ```
        
        <span class="custom-text">This command ensures that XeLaTeX is
        used with the necessary options to handle Persian text and other
        features correctly.</span>

<span class="custom-text">Feel free to adjust the instructions based on
your specific needs and preferences. If you have any further questions
or need additional help, let me know\!</span> 🎉
