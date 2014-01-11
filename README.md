# How to use

1. Rename file template.tex for whatever you wish the final .pdf to be called
2. Make the same change for the TARGET parameter in Makefile
3. Add content files to /content and pictures to /pictures
4. Remove the dummy files from /content and /pictures
5. Include or input the content files in toc.tex
6. Choose the options you want in /config/options.tex
7. Fill the fields in /config/meta.tex and /config/hypersetup.tex
8. Add authors to /config/authors.tex
9. Check the .gitignore file is ok and make changes if necessary
10. Choose the license you want and write it in LICENSE.md
11. Check the document is processed ok (either 'make' or 'lualatex -shell-escape <name of book>.tex' at the root of the repo)
12. Replace the contents of this README with whatever you want

# Work left to do with this repo and commons

1. Enabling other styles, titlepages, languages (apart from the Vapaa matikka one in Finnish)
