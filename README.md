# 🎓 <span style="color: #003366;">Persian LaTeX Template for University of Tehran - Physics Department (Master's Thesis)</span>

This repository provides a LaTeX template designed for master's theses
in the Physics Department at the University of Tehran. It is configured
to support Persian language typesetting and adheres to the formatting
guidelines required for academic submissions in the department.

## 🗂️ <span style="color: #003366;">File Structure Overview</span>

### 📁 <span style="color: #003366;">`SetupFiles/`</span>

This directory contains configuration files for setting up the LaTeX
document, including packages, custom commands, and environments.

  - **📦 <span style="color: #0066cc;">`Packages.tex`</span>**: Includes
    all the LaTeX packages required for the document, providing
    necessary functionality such as support for Persian text, figures,
    and tables.
  - **⚙️ <span style="color: #0066cc;">`Setups.tex`</span>**: Contains
    various document settings and customizations, such as layout
    options, margins, and stylistic settings.
  - **🛠️ <span style="color: #0066cc;">`Commands.tex`</span>**: Defines
    custom LaTeX commands and macros to simplify and standardize
    repetitive elements in the document.
  - **🏗️ <span style="color: #0066cc;">`Environment.tex`</span>**: Sets
    up custom environments for specific formatting of sections, lists,
    or other structured elements in the thesis.

### 📚 <span style="color: #003366;">`TexFiles/`</span>

This directory holds the core content of the thesis, organized into
separate files for modularity and ease of management.

  - **📜 <span style="color: #0066cc;">`Basmala.tex`</span>**: Includes
    the Basmala (بسم الله الرحمن الرحيم) at the beginning of the
    document.
  - **📑 <span style="color: #0066cc;">`PersianTitle.tex`</span>**:
    Contains the Persian title page with the thesis title, author, and
    institution information.
  - **📝 <span style="color: #0066cc;">`Originality.tex`</span>**:
    Provides the statement of originality required for academic theses.
  - **❤️ <span style="color: #0066cc;">`Dedication.tex`</span>**: A
    section for dedicating the thesis to someone.
  - **🙏 <span style="color: #0066cc;">`Acknowledgments.tex`</span>**:
    Contains acknowledgments for contributions and support received.
  - **📝 <span style="color: #0066cc;">`PersianAbstract.tex`</span>**:
    Includes the Persian abstract summarizing the research work.
  - **📖 <span style="color: #0066cc;">`Chapter1.tex`</span> to
    **<span style="color: #0066cc;">`Chapter6.tex`</span>**: Each file
    represents a chapter of the thesis, facilitating easier management
    of the document.
  - **📚 <span style="color: #0066cc;">`Reference.bib`</span>**: A BibTeX
    file with all the references cited in the thesis, used to generate
    the bibliography section.
  - **📄 <span style="color: #0066cc;">`Appendix1.tex`</span>**: Contains
    additional material or supplementary information.
  - **🌍 <span style="color: #0066cc;">`EnglishAbstract.tex`</span>**:
    Provides the abstract in English, ensuring accessibility to a
    broader audience.
  - **🌐 <span style="color: #0066cc;">`EnglishTitle.tex`</span>**:
    Contains the English title page, if required.

### 🖋️ <span style="color: #003366;">`Fonts/`</span>

This directory includes font files used in the document.

  - **🗂️ <span style="color: #0066cc;">\[Font Files\]</span>**: Contains
    font files (.ttf, .otf, etc.) used for specific typographic needs or
    to maintain consistency with departmental formatting guidelines.
    These fonts are loaded and applied through LaTeX configuration
    files.

### 🖼️ <span style="color: #003366;">`Pictures/`</span>

This directory is used for storing image files included in the thesis.

  - **🖼️ <span style="color: #0066cc;">\[Image Files\]</span>**:
    Contains images, figures, and diagrams referenced in the thesis.
    Supported formats may include .png, .jpg, .pdf, etc. Images are
    typically included in the text using LaTeX commands and can be
    placed within chapters, appendices, or other sections as needed.

### 📝 Instructions

  - **🔧 <span style="color: #003366;">Adding Packages</span>**: If you
    need to add or update LaTeX packages, modify the `Packages.tex` file
    in the `SetupFiles` directory. This will ensure that the new
    packages are included in the document.

  - **✏️ <span style="color: #003366;">Writing Document
    Content</span>**: For writing and editing the content of your
    thesis, use the files in the `TexFiles` directory. Each file
    corresponds to a different section or chapter of the thesis.

  - **🛠️ <span style="color: #003366;">Compiling the Document</span>**:
    To compile the thesis, run the `Main.tex` file. This will integrate
    all the sections and configurations into a single document.

  - **🖥️ <span style="color: #003366;">Compiling with LaTeX
    Editors</span>**:
    
      - **💻 <span style="color: #0066cc;">Overleaf</span>**: You should
        not encounter any issues with Overleaf; it handles compilation
        automatically.
    
      - **🖥️ <span style="color: #0066cc;">Local LaTeX
        Installation</span>**: If you are using a LaTeX editor installed
        on your local machine (e.g., TeXMaker, TeXstudio), you need to
        use the following command for
        compiling:
        
        ``` shell
        xelatex.exe -shell-escape -synctex=1 -interaction=nonstopmode %.tex
        ```
        
        This command ensures that XeLaTeX is used with the necessary
        options to handle Persian text and other features correctly.

Feel free to adjust the instructions based on your specific needs and
preferences. If you have any further questions or need additional help,
let me know\! 🎉
