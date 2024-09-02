# Persian LaTeX Template for University of Tehran - Physics Department (Master's Thesis)

This repository provides a LaTeX template designed for master's theses
in the Physics Department at the University of Tehran. It is configured
to support Persian language typesetting and adheres to the formatting
guidelines required for academic submissions in the department.

## File Structure Overview

### `SetupFiles/`

This directory contains configuration files for setting up the LaTeX
document, including packages, custom commands, and environments.

  - **`Packages.tex`**: Includes all the LaTeX packages required for the
    document, providing necessary functionality such as support for
    Persian text, figures, and tables.
  - **`Setups.tex`**: Contains various document settings and
    customizations, such as layout options, margins, and stylistic
    settings.
  - **`Commands.tex`**: Defines custom LaTeX commands and macros to
    simplify and standardize repetitive elements in the document.
  - **`Environment.tex`**: Sets up custom environments for specific
    formatting of sections, lists, or other structured elements in the
    thesis.

### `TexFiles/`

This directory holds the core content of the thesis, organized into
separate files for modularity and ease of management.

  - **`Basmala.tex`**: Includes the Basmala (بسم الله الرحمن الرحيم) at
    the beginning of the document.
  - **`PersianTitle.tex`**: Contains the Persian title page with the
    thesis title, author, and institution information.
  - **`Originality.tex`**: Provides the statement of originality
    required for academic theses.
  - **`Dedication.tex`**: A section for dedicating the thesis to
    someone.
  - **`Acknowledgments.tex`**: Contains acknowledgments for
    contributions and support received.
  - **`PersianAbstract.tex`**: Includes the Persian abstract summarizing
    the research work.
  - **`Chapter1.tex`** to **`Chapter6.tex`**: Each file represents a
    chapter of the thesis, facilitating easier management of the
    document.
  - **`Reference.bib`**: A BibTeX file with all the references cited in
    the thesis, used to generate the bibliography section.
  - **`Appendix1.tex`**: Contains additional material or supplementary
    information.
  - **`EnglishAbstract.tex`**: Provides the abstract in English,
    ensuring accessibility to a broader audience.
  - **`EnglishTitle.tex`**: Contains the English title page, if
    required.

### `Fonts/`

This directory includes font files used in the document.

  - **`[Font Files]`**: Contains font files (.ttf, .otf, etc.) used for
    specific typographic needs or to maintain consistency with
    departmental formatting guidelines. These fonts are loaded and
    applied through LaTeX configuration files.

### `Pictures/`

This directory is used for storing image files included in the thesis.

  - **`[Image Files]`**: Contains images, figures, and diagrams
    referenced in the thesis. Supported formats may include .png, .jpg,
    .pdf, etc. Images are typically included in the text using LaTeX
    commands and can be placed within chapters, appendices, or other
    sections as needed.

### Instructions

  - **Adding Packages**: If you need to add or update LaTeX packages,
    modify the `Packages.tex` file in the `SetupFiles` directory. This
    will ensure that the new packages are included in the document.

  - **Writing Document Content**: For writing and editing the content of
    your thesis, use the files in the `TexFiles` directory. Each file
    corresponds to a different section or chapter of the thesis.

  - **Compiling the Document**: To compile the thesis, run the
    `main.tex` file. This will integrate all the sections and
    configurations into a single document.

  - **Compiling with LaTeX Editors**:
    
      - **Overleaf**: You should not encounter any issues with Overleaf;
        it handles compilation automatically.
    
      - **Local LaTeX Installation**: If you are using a LaTeX editor
        installed on your local machine (e.g., TeXMaker, TeXstudio), you
        need to use the following command for
            compiling:
        
            xelatex.exe -shell-escape -synctex=1 -interaction=nonstopmode %.tex

        This command ensures that XeLaTeX is used with the necessary
        options to handle Persian text and other features correctly.

Feel free to adjust the instructions based on your specific needs and
preferences. If you have any further questions or need additional help,
let me know\!
