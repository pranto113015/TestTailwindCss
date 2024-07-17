# TestTailwindCss Project

## This is a simple card design using HTML and Tailwindcss

### `Tailwind CLI` tool Installation Professional Setup

- Very first check the computer `node.js` is install ok.

- Code editor : `vs code`

- First creat the project `folder name` example : `TestTailwindCss`

- Create `index.html` file

- Create the `src` folder and inside the  create file `input.css` (this file is the tailwind input css file)

- Then open the vs code terminal copy and past the code
  
  ```
  npm install -D tailwindcss
  ```

   after running this code automatically create the folder `node_modules` and another two file `package.json` & `package-lock.json`
- Then again copy the code and past the Terminal

   ```
   npx tailwindcss init
   ```

   after running this code automatically create the file `tailwind.config.js` .

- Now open the `tailwind.config.js` file copy the code and past inside the file.

   ```js
      /** @type {import('tailwindcss').Config} */
   module.exports = {
   content: ["./**/*.{html,js}"],
   theme: {
      extend: {},
   },
   plugins: [],
   }
   ```

- Now select the `src` folder and open the `input.css` file copy the code and past inside the file.

    ```css
      @tailwind base;
      @tailwind components;
      @tailwind utilities;
   ```

- Then again copy the code and past the terminal

   ```css
   npx tailwindcss -i ./src/input.css -o ./output/output.css --watch
   ```

- after run the code the automatically create the folder `output` and inside automaically create the file `output.css`

- Now link up the  `output` folder `output.css` file with root `index.html` file if you confuse the copy the code and past the root index.html file after title tag.

   ```html
   <link rel="stylesheet" href="./output/output.css">
   ```

- Now this is `OK` to use the tailwindcss project file.

### `Tailwind CSS` Production Build with Vite Professional Setup 

#### Another Source Tailwind CSS Install Using CLI Project File [Link 1](https://www.youtube.com/watch?v=pvjitD8puik)

#### Another Source Tailwind CSS Production Build Project File [Link 2](https://www.youtube.com/watch?v=OO-I5mZLzXw)
