1. npm run build
2. Change "main" in package.json from "public/electron.js" to "build/electron.js"  
3. Update path to html file in build/electron.js from "../public/index.html" to "../build/public/index.html"  
4. npx run electron-builder  
5. Change "main" in package.json from "build/electron.js" to "public/electron.js" to reset for further dev.  
6. Setup exe will be in dist  