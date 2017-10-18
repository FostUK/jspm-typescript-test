# JSPM Minimal test

Typescript and JS imported and running via systemjs with jsmp.io versioning support

## Install & run

From commandline navigate to the project directory

```
npm install
```

Install front end dependencies
```
jspm install
```
(You will need to install jspm globally if you don't already have it:)
```
npm install -g jspm
```
Files are served using [express](https://expressjs.com/) via:
```
npm run server
```

Navigate to [http://localhost:8080](http://localhost:93) (Port can be changed in *server.js*)

JS and Typescript files can b found in /lib.
Check the in browser console log for success confirmation.