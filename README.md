# mfe
MFE_code
creation - 
ng new mono-workspace
cd mono-workspace

//creation of app
ng g application host-app --routing --style=scss
ng g application mfe-app --routing --style=scss

//running in local
ng s host-app -o  
ng s mfe-app -o


npm i webpack webpack-cli --save-dev

npm install @angular-architects/module-federation --save-dev


ng add @angular-architects/module-federation --project host-app  --port 4200
ng add @angular-architects/module-federation --project mfe-app  --port 4300


ng s host-app -o  
ng s mfe-app -o