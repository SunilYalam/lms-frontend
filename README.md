# LMS Frontend

### Create Project 

1. npm create vite@latest
2. choose Project name- lms-frontend
3. select framework or library
4. select language 
5. cd project
6. npm install
7. npm run dev

### setup instructions

1. Clone the project
```
git clone https://github.com/SunilYalam/lms-frontend.git
```

2. Move into the directory
```
cd lms-frontend
```
3. install dependencies
```
npm i
```
4. run the server
```
npm run dev
```

### Setup instructions for tailwind Css

Tailwind official instruction doc - link

1. Install tailwindcss
```
npm install -D tailwindcss postcss autoprefixer
```
2. Create tailwind config file
```
   npx tailwindcss init
```
3. add file extensions to tailwind config file
```
   "./src/**/*.{html,js,jsx,ts,tsx}", "./index.html",
   ```
4. Add the tailwind directives at the top of the 'index.css' file
```
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
```

### Adding plugins and dependencies
```
 npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp
 ```
 ### Configure auto import sort esline

 1. Install simple import sort
 ```
 npm i eslint-plugin-simple-import-sort
 ```
 2. Add rule in `.eslint.cjs`
 ```
 'simple-import-sort/imports': 'error'
 ```
 3. Add simple-import sort plugin in `.eslint.cjs`
 ```
   plugins: [..., 'simple-import-sort']
   ```
 4. To enable auto import sort on file save in vscode

   -Open 'settings.json'
   -add the following config
 ```
   "editor.codeActionsOnSave":{
      "source.fixAll.eslint": true
   }
   ```

### You install packages if you want to uninstall package follow this cmd
```
npm uninstall postcss autoprefixer 
```
### and remove from package.json
```
npm install -D postcss autoprefixer
```
### after 
```
npx tailwindcss init -p
```