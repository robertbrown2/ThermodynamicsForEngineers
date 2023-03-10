# Thermodynamics for Engineers
A Thermodynamics textbook designed for a single-semester Thermodynamics course.

## Getting the Textbook
A recent version of the textbook will be available as "ThermoForEngineers_MO-DA-YR.pdf", with the MO-DA-YR indicating the date of the build.

## Making Changes
In order to make changes, the Latex files are all in the src folder.  The main file is `index.tex`, with each chapter listed under `ch?.tex`, and the chapter homeworks as `ch?HW.tex`.

Most of the figures are available as Adobe Illustrator files in the `fig/Illustrator` directory.  Those Illustrator files can be exported as PNG files, which are all stored in the `fig/PNGs` directory.  The names should mostly line up, though there will be some discrepancies (I plan on gradually fixing these discrepancies over time).

Some figures are stored only as JPGs or PNGs.  Those may be holdovers from Israel Urieli's original text, or other images grabbed from the public domain.
### By Cloning in Github
If you clone the repository, the PDF will be created after every commit.  You can find it under the Actions tab, clicking on the commit, and checking the artifacts.  The only artifact should be Thermodynamics.pdf.

### By Cloning to a Local Repository
If you clone to a local repository (onto your own computer), you will need to also download [tectonic](https://tectonic-typesetting.github.io/en-US/).  The book can be generated using the command-line-interface command `tectonic -X build`.  Additional documentation is available on the tectonic website.

The new file will be at `build/ThermoForEngineers/ThermoForEngineers.pdf`.

Alternatively, you can use your favorite Latex compiler.  However, you will need to include the `\_preamble.tex`, `\_postamble.tex`, and `index.tex` files in the "main" latex file.

### Contributing
I am actively using this textbook to teach a Sophomore-level Thermodynamics course.  I welcome critiques and comments.  If you would like to take a more active role in adding to the book, e-mail me at rlb16c@acu.edu.
