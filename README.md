# quantum-exercises
Guided Exercises for Quantum Chemistry
v1.0.1 - August 2018

----------------------------------------------------------
Copyright and License
----------------------------------------------------------

Current version (c) 2018 Jennifer Laaser

This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

The current source for these materials is accessible on Github: https://github.com/jlaaser/quantum-exercises


---------------------------------------------------------
General Notes
---------------------------------------------------------

 - Guided Exercises for Quantum Chemistry is intended for use in a graduate-level introductory course in quantum chemistry.  These exercises take a "states-first" approach to quantum chemistry.
 
 - Every effort has been made to correct outstanding errors in these materials. However, if you find an issue that needs to be fixed, please create an issue in the GitHub issue tracker for this project: https://github.com/jlaaser/quantum-exercises/issues
 
 - Contributions are welcome! If you have an idea for a new exercise or want to improve an existing one, you're welcome to either (1) post your suggestion in the issue tracker (above) or (2) fork the github project and send a pull request once your changes are complete (though we encourage contacting us first to discuss the best way to integrate your ideas into the existing material).
 

---------------------------------------------------------
Compiling the Exercises
---------------------------------------------------------

 - The exercises are written LaTeX and can be compiled using pdflatex via the command line or your favorite TeX IDE.  If you are new to LaTeX, Texmaker (http://www.xm1math.net/texmaker/ ) is a relatively user-friendly platform to start with.
 
 - The main document is quantum-exercises.tex:
 
   - The individual exercises are stored in individual .tex files in the "includes" directory. To avoid compilation errors, make sure this directory has been downloaded and is in the same folder as quantum-exercises.tex.
 
   - To compile the full set of exercises, compile quantum-exercises.tex as-is. This will result in a pdf including a title page and all exercises.
   
   - To compile only a single exercise, uncomment the "\includeonly" statement before "\begin{document}" and update the file path to the path of the exercise you want to include. Then compile quantum-exercises.tex as normal. This will produce a PDF containing only the exercise listed in the \includeonly statement, without the title page.
   
   - To compile a subset of the exercises, comment out (put a % sign in front of) the "\include" statements for any exercises that you want to omit from the output and then compile quantum-exercises.tex. This will result in a pdf including a title page and all exercises that were not commented out.

 - Compiled PDFs off the full set of exercises will be uploaded with each official release; see https://github.com/jlaaser/quantum-exercises/releases

---------------------------------------------------------
Contact
---------------------------------------------------------

Questions?  Interested in contributing?  You can reach the author at:

E-mail: j.laaser@pitt.edu
Web:	www.pitt.edu/~jel183
Github:	github.com/jlaaser


---------------------------------------------------------
Release Notes
---------------------------------------------------------

None yet - check back after the first official release goes up.