# How to use

1. Make a new repo with chosen name at GitHub; note: choose not to initialize it!
2. Clone this repo to a local destination
3. Rename the local repo to match the GitHub repo you created earlier
4. Run 'git remote set-url origin https://github.com/\<your username\>/\<name of the repo\>.git
5. Push the local repo to your GitHub repo with 'git push -u origin master>
6. Get the contents of the commons submodule for your local repo with 'git submodule update --init'
7. Rename file template.tex for whatever you wish the final .pdf to be called
8. Make the same change for the TARGET parameter in Makefile
9. Add content files to /content and pictures to /pictures
10. Remove the dummy files from /content and /pictures
11. Include or input the content files in toc.tex
12. Choose the options you want in /config/options.tex
13. Fill the fields in /config/meta.tex and /config/hypersetup.tex
14. Add authors to /config/authors.tex
15. Check the .gitignore file is ok and make changes if necessary
16. Choose the license you want and write it in LICENSE.md
17. Check the document is processed ok (either 'make' or 'lualatex -shell-escape \<name of book\>.tex' at the root of the repo)
18. Replace the contents of this README with whatever you want

# Work left to do with this repo and commons

1. Enabling other styles, titlepages, languages etc. (apart from the Vapaa matikka one in Finnish)
2. Construct examples for the associated libraries
