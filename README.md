npx create-react-app my-react-app
cd my-react-app

npm install gh-pages --save-dev


"homepage": "https://<username>.github.io/<repository-name>/"
"scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d build"
   }

npm run deploy