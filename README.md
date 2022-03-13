> `git init` <br />
> `npm init -y` <br />
> `npm i husky -D` <br />
> `add npm script - "prepare": "husky install"` <br />
**Unix:**<br />
> `npx husky add .husky/<hook> <command>` <br />
**Windows:** <br />
> `.\node_modules\.bin\husky add .husky/<hook> <command>`<br />


To check ot set on witch hooks should git hook pass through
<br />
> `git config gitflow.path.hooks (for set just add: .git/hooks or .husky)`