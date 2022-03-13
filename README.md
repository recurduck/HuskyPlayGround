git init
npm init -y
npm i husky -D
add npm script - "prepare": "husky install"
Unix:
npx husky add .husky/<hook> <command>
Windows: 
.\node_modules\.bin\husky add .husky/<hook> <command>