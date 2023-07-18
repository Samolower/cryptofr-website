# Crypto FR
## Prerequis
- Install docker engine : https://docs.docker.com/engine/install/ 
- Install nvm : https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/
- Install node using nvm : nvm install --lts
- Install npm : https://kinsta.com/blog/how-to-install-node-js/
- Install tailwind : https://tailwindcss.com/docs/installation

## Run & build
 - Build the image : docker build -t cryptofr:latest .
 - Run the image as a cointainer : docker run -i -t -p 3000:3000 <image ID>
 - Build tailwind continuously : npx tailwindcss -i ./style/main.css -o ./dist/output.css --watch
 - Test on http://localhost:3000/

## Utils
- Emoji : https://emojiterra.com/fr/
