# Haskell
Functional Programming Assignment 2

This program is the Web Application written in Functional Programming Language Haskell using Happstack web frame. The web service display the JSON data from the URL, it is able to save JSON data to the file and produces the HTML output.

Modules Installed:
* cabal
* happstack
* blaze
* http-conduit
* aeson

To RUN the program:
1. Save the source code from the file "Haskell Asignment v.2" into a file named "test.hs" on your local drive.
2. Create a file named "temperatures.json" in the same directory.
3. Open the terminal.
4. Go the the directory where you saved the files.
5. Type "ghc --make test.hs"
6. Type "./test.hs"
7. Open the browser and type URL "localhost:8000"
The application is now running on the localhost.

To check if the JSON data was corectly saved to the file open the temperatures.json file.
