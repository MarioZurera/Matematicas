# Mathematics

My mathematics notes, written in LaTeX. I'm studying the Bachelor's Degree in Mathematics at UNED (taught in Spanish) and I also work through books on my own.

The repository is organized by **source**:

- **`UNED/`**: notes that follow a university course (syllabus, terminology and exams of the course). Written in **Spanish**.
- **`Books/`**: notes that follow a specific book, chapter by chapter, with worked exercises. Written in the **language of the book**.
- **`common/`**: LaTeX preamble and macros shared by every document.

## Index by topic

The same topic can appear in several sources, sometimes with different definitions or a different level of rigor. Each folder keeps its own source, and this index connects them.

**Discrete mathematics**
- [Matemática Discreta, UNED](UNED/Matematica-Discreta) (Spanish)

**Linear algebra**
- [Linear Algebra Done Right](Books/Linear-Algebra-Done-Right) (English)

## Building

Each folder has a `main.tex` file. Compile it with a standard LaTeX distribution (for example `latexmk -pdf main.tex`) inside the folder.


## Conventions

- Results cite the source they come from (book and theorem/page number), so it is clear where each statement is taken from.
- Proofs and exercise solutions are my own unless stated otherwise.

- Every document includes the shared preamble from `common/`.

## Sources and copyright

These are personal study notes, shared for non-commercial, educational purposes.

- The books and course materials referenced here are the property of their
  respective authors and publishers. Each document lists its sources in its
  bibliography.
- The notes follow the structure and numbering of those sources, but
  statements are written in my own words. Exercise statements are not
  reproduced; exercises are referred to by their number in the original source.
- If you are a rights holder and believe any content should be removed or
  changed, please open an issue.

## License

- LaTeX code (`common/`, preambles, macros): [MIT](LICENSE).
- Notes (the mathematical content written by me): [CC BY-NC-SA 4.0](LICENSE-notes).

This license applies only to my own work, not to the cited books or
course materials.


---
Notes by [Mario Zurera](https://github.com/MarioZurera).