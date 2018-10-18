# npm-example
An example project using Node.js and npm

## Practice

- Clone this project:

```bash
git clone https://github.com/spy126/npm-example.git
cd npm-example
```

- Try to run a file app.js
```
node app.js
```

- See error output:
```
module.js:549
    throw err;
    ^

Error: Cannot find module 'express'
    at Function.Module._resolveFilename (module.js:547:15)
    at Function.Module._load (module.js:474:25)
    at Module.require (module.js:596:17)
    at require (internal/module.js:11:18)
    at Object.<anonymous> (/spy126-traning/npm-example/app.js:1:79)
    at Module._compile (module.js:652:30)
    at Object.Module._extensions..js (module.js:663:10)
    at Module.load (module.js:565:32)
    at tryModuleLoad (module.js:505:12)
    at Function.Module._load (module.js:497:3)
```

- Run a command and run app.js again:
```
npm install express

node app.js
```
