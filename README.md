# TestTailwindCss Project

## This is a simple card design using HTML and Tailwindcss

Tailwind CSS is essentially a utility-first CSS framework designed to help developers quickly build unique user interfaces without leaving there HTML files. It is a low-level, highly configurable CSS framework that provides you with all the building blocks you need to create custom designs, free of opinionated styles that you will constantly struggle to override.

Tailwind just processes a "raw" CSS file over a configuration file, creating an output in the process. It prevents the risk of breaking existing templates and not increases the bundle size.

### `Tailwind CLI` tool Installation Professional Setup

> [!IMPORTANT]
> Very first check the computer `node.js` is install ok.

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

-------------------------------------------------------

### Vite Is Next Generation Frontend Tooling

Vite is a build tool for front-end development that aims to provide a faster and more efficient development experience. It was created by Evan You, the same person behind the popular JavaScript framework Vue.js. Vite is specifically designed to be a front-end build tool for modern web development projects.

### `Tailwind CSS` Production Build with Vite Professional Setup

- First open the `package.json` file and add the following code under script section in your `package.json`

   ```json
   "scripts": {
    "start": "vite",
    "build": "vite build"
  }
   ```

  - >For Example Look Like :
![Example Demo Image.](https://cdn.hashnode.com/res/hashnode/image/upload/v1703593938397/564eee03-6969-46c5-baab-4ceca5780aea.png?auto=compress,format&format=webp)

- Now type the following command in your terminal after saving all the files, this command will start Vite.

   ```html
   npm run start
   ```

  - >For Example Look Like :
![Example Demo Image.](https://cdn.hashnode.com/res/hashnode/image/upload/v1703594042845/b18a5a97-3ec4-4367-94f7-8a718cbfa818.png?auto=compress,format&format=webp)

    This will create a local host for you where you can see your Tailwind CSS site.

- Now we will create the dist folder for production. For this run this command in your terminal

   ```html
      npm run build
   ```

  - >For Example Look Like :
![Example Demo Image.](https://cdn.hashnode.com/res/hashnode/image/upload/v1703594401060/eb825366-7fe4-4c4c-83fe-618d06d42f95.png?auto=compress,format&format=webp)

- Now a dist folder is created for production, now you can push the files in this folder on your GitHub repository and host it with GitHub Pages.

  - >For Example Look Like :
   ![Example Demo Image.](https://cdn.hashnode.com/res/hashnode/image/upload/v1703594508497/92c53899-ad1a-49d4-a08b-5d83f0e68195.png?auto=compress,format&format=webp)

> [!NOTE]
> If you make any changes to your site, you have to re-execute this step and again make a new `dist` folder and push it in your GitHub repository to see the necessary changes you made.

Observe the seamless process of creating a production bundle, where assets in the `'dist'` folder are compressed into a single line. This not only accelerates our project's loading time but also enhances overall efficiency.

### Conclusion

By following these steps, developers can confidently enhance their Tailwind CSS production and efficiently deploy projects with GitHub Pages, contributing to a more seamless and professional front-end journey.

> [!TIP]
>
> #### Another Source Tailwind CSS Install Using CLI Project File [Link 1](https://www.youtube.com/watch?v=pvjitD8puik)
>
> #### Another Source Tailwind CSS Production Build Project File [Link 2](https://www.youtube.com/watch?v=OO-I5mZLzXw)

## Contact

If you have any questions or need further clarification, please feel free to reach out to me

> 📪 Email : <pranto113015@gmail.com>

> 🔍 Linkedin : [Pranto Kumar](https://www.linkedin.com/in/pranto-kumar-a326801b3/)

  💙 Thank you for reviewing my project!
