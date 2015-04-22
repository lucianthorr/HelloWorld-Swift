<h2>Hello World in Swift</h2>
<p>
This is a simple Hello World project in Swift in order to experiment with how Xcode works with GitHub
<p>
The first problem I ran into was allowing Github to generate the .gitignore and Readme.md files. When I linked the GitHub repository to Xcode's Source Control, Xcode's Git could not push the Hello World project up because it needed to pull first. Unfortunately, the Git would error when trying to pull the .gitignore and Readme files down.
<p>
The solution was to create an empty Github repository and create the .gitignore and Readme locally in Xcode as part of the Hello World project. The confusing part was that when I made the .gitignore, Xcode would not display it in the file browser because it's a Hidden file. Therefore I had to then go into the terminal, open it via vim and paste a proper .gitignore list generated with http://gitignore.io
