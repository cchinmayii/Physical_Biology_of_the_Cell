# Physical Biology of the Cell - Course Notes

Notes compiled from the **Physical Biology of the Cell (PBoC)** course taught by **Rob Phillips and Jané Kondev** at the Max Planck Institute of Molecular Cell Biology and Genetics (MPI-CBG), Dresden, Germany, from October 5-9, 2026.

**[Official course website](https://www.rpgroup.caltech.edu/dresdenPBoC2026/)**

These are independently compiled course notes and are not official teaching materials.

[**View the course notes**](https://cchinmayii.github.io/Physical_Biology_of_the_Cell/)

<!-- [**Download PDF**](https://cchinmayii.github.io/Physical_Biology_of_the_Cell/notes.pdf) -->

The LaTeX source files are available in this repository. Updated versions of the compiled notes will be made available through GitHub Releases.

## About the Notes

These notes were originally typed during the five days of lectures and subsequently transcribed, expanded, and reorganized into a more coherent conceptual structure.

Rather than following the day-by-day chronology of the course, the compiled notes group related topics together and develop them in a conceptual sequence. They are intended as a general reference to the ideas, mathematical methods, and examples discussed during the course, rather than as a chronological record of individual lectures.

For readers who prefer to follow the original sequence, the daily course chronology is preserved in an appendix, and the original day-by-day notes are also included in the repository.

### Appendices

The compiled notes include five appendices:

1. **Mathematical methods reference:** An introduction to mathematical tools used throughout the course, intended particularly for readers without a strong mathematical background.
2. **Detailed derivations:** More complete mathematical derivations of results discussed during the lectures.
3. **Recommended readings:** A compiled list of books, papers, and other readings recommended during the course.
4. **Daily course chronology:** An overview of the material covered on each of the five days, for reference.
5. **Notation summary:** A reference for the mathematical notation and symbols used throughout the notes.

## Repository Structure

### Directories

| Directory | Contents |
|---|---|
| `appendix/` | Individual LaTeX files for the five appendices |
| `figures/` | Figures used in the compiled notes, primarily in PNG format |
| `sections/` | Individual LaTeX files for the main sections |
| `source-original/` | Original course notes organized chronologically by lecture day |

### Files

| File | Description |
|---|---|
| `main.tex` | Main LaTeX document that imports and compiles the sections and appendices |
| `bib.bib` | Bibliography database |
| `conceptual-outline.md` | Working outline documenting the conceptual reorganization of the notes |
| `README.md` | Repository documentation |

### Compiling the Notes

The document is written in LaTeX, with `main.tex` serving as the main compilation file. The individual sections and appendices are imported into this file.

The project can be compiled using a LaTeX distribution with the required packages and bibliography tools. For example, with `latexmk` installed:

```bash
latexmk -pdf main.tex
```

Alternatively, the source files can be uploaded to a compatible online LaTeX editor.

For readers interested only in the finished notes, the compiled PDF is available under [Releases](https://github.com/cchinmayii/Physical_Biology_of_the_Cell/releases/latest).

## Corrections and Contributions

Corrections, suggestions, and comments are welcome. If you find an error, an unclear explanation, or a missing reference, please open a [GitHub Issue](https://github.com/cchinmayii/Physical_Biology_of_the_Cell/issues).

## Acknowledgements

Thanks to Rob Phillips and Jané Kondev for teaching the course and for the discussions and ideas that form the basis of these notes. I also thank Sara Mahdavi for leading the hands-on computational sessions, and the organizers at MPI-CBG for making the course possible.

These notes are based on the lectures and do not cover the hands-on computational sessions. The corresponding code and exercises are available through the [official course website](https://www.rpgroup.caltech.edu/dresdenPBoC2026/code).

### AI Assistance

These notes were compiled from notes typed during the course, with the assistance of OpenAI's GPT-5.6 Sol for transcription, organization, and editing. Any errors or omissions are my own.

**Compiled by Chinmayi Subramanya, October 2026.**
