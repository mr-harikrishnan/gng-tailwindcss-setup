1.git init - (ALL-ENTER)

2.terminal
  
  npm install tailwindcss @tailwindcss/cli

3.create src folder
  ->input.css file 
  

4.@import "tailwindcss";   (paste in src/input.css)

5.create html page in new folder name dist
create index.html

6.move from src/output.css file  to dist folder

7.next src/add tailwind.config.js

8.run the page using this link npx @tailwindcss/cli -i ./src/input.css -o ./dist/output.css --watch

9.check design

10.add "dev":"npx @tailwindcss/cli -i ./src/input.css -o ./dist/output.css --watch"
    in package.json file  in script object.

##  11.next run using  -   npm run dev    

