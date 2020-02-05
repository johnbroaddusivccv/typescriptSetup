# TypeScript Setup

Node/Express/TypeScript/Nodemon environment with TS-Node

## Installation && Usage
```bash
git init
```
```bash
git clone https://github.com/johnbroaddusivccv/typescriptSetup.git
```
```bash
cd typescriptSetup
```
Use the package manager [npm](https://docs.npmjs.com/cli/link.html) to install the dependencies, which in this case is only [express](https://www.npmjs.com/package/express)


I suggest installing [TypeScript](https://www.typescriptlang.org/) globally
```bash
npm install -g typescript
```
```bash
npm i
```
We also install TypeScript Locally in our Project, along with Dev Dependencies.
```bash
npm i -D typescript ts-node nodemon @types/node @types/express
```



## Additional
if the following is not working for you after typescript is global installed
```bash
tsc --version
``` 
Install [npx](https://www.npmjs.com/package/npx) to get around it
```bash
npm i npx
```
```bash
npx tsc --version
``` 
Notice the build script is using [npx](https://www.npmjs.com/package/npx) to run tsc
```bash
"npx tsc -p ."
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
