## 1. Download SASS from GitHub 

> or if we have Node.js

`npm install -g sass`

## 2. Make a 'style.scss' file in project folder and for linking write below ↓

`npm run scss`

`sass --watch C:\project\sass\location\style.scss:C:\public\stylesheet\location\style.css`

## 3. Watching live and compiling SASS at a time →

> Open the 'package.json' file in a code editor and add below code (npm\node_modules\sass\package.json)

```
"scripts": {
  "test": "echo \"Error: no test specified\" && exit 1",
  "scss": "node-sass --watch scss -o css"
}
```

> make sure the path is OK with double slash. like :

`"scss": "node-sass --watch C:\\xampp\\htdocs\\team-pro-front-end\\css\\scss\\style.scss -o C:\\xampp\\htdocs\\team-pro-front-end\\css\\style.css"`

> To run the Script :

`npm run scss`

# Done!
