To create the sevn website:

1) First initialize the hugo new project with the comand line
hugo new site mywebsite

2) inside the folder of the project, download the template
git init
git submodule add -b main https://github.com/nunocoracao/blowfish.git themes/blowfish

3) remove the hugo.toml file in the folder

4) copy the config/_default/ folder with all the .toml file inside from the theme folder in the folder of the project

5) decomment the line theme = "blowfish" # UNCOMMENT THIS LINE in hugo.toml in config/_default/ folder

6) at this point you can compile locally the website running
hugo server -D

