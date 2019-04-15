npm run scss

sass --watch C:\xampp\htdocs\team-pro-front-end\css\scss\style.scss:C:\xampp\htdocs\team-pro-front-end\css\style.css

1. Download from GitHub 

	or
npm install -g sass

	if we have Node.js

2. make a 'style.scss' file in project folder and for linking write below

	sass --watch prject/sass/location:public/stylesheets/location

3. Watching and compiling SASS at a time

	- Open the 'package.json' file in a code editor and add below code (npm\node_modules\sass\package.json)

"scripts": {
  "test": "echo \"Error: no test specified\" && exit 1",
  "scss": "node-sass --watch scss -o css"
}

	- make sure the path is OK with double slash. like :

"scss": "node-sass --watch C:\\xampp\\htdocs\\team-pro-front-end\\css\\scss\\style.scss -o C:\\xampp\\htdocs\\team-pro-front-end\\css\\style.css"

	- to run the Script :

npm run scss

	- Done!
