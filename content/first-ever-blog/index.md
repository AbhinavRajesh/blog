As the title suggests this is my first ever blog post I think I should definetly introduce my self! I'm [Abhinav Rajesh](https://abhinavrajesh.xyz). I'm a passionate UI/UX Designer and Developer. I'm currently pursuing my B.Tech Degree in Computer Science Engineering from School Of Engineering, CUSAT and I'm a Sophomore.
<br /><br />
_About the blog now, the blog posts here would be mostly related to **tech**._

## What's in this Blog?

In this blog I would be talking about the technologies I have used and the how I deployed my blog and how you can do the same too! 🥰

### What technologies I used for this website?

I have used [Abell](https://abelljs.org) for this blog. Abell is an amazing and fast static site generator. It's still in beta and ngl it looks quite promising. Hopefully more amazing and exciting features would be available in the future soon!
<br /><br />
_You guys should definetly check out [Abell](https://abelljs.org)_
<br /><br />

### How did I deploy?

1. Get the starter files from Abell

   Abell has an amazing starter file for Blogs with dark mode already implemented.

   - So first we should install abell. Now for that, use the command<br/><br/>
     **Using npm**

     ```
     npm install -g create-abell-app
     ```

     **Using yarn**

     ```
     yarn global add create-abell-app
     ```

   - Now for getting the starter file

     ```
     npx create-abell-app my-blog --template abelljs/abell-starter-minima
     ```

   - **Change the files in the template accordingly**
     <br /><br />

2. Create GitHub Repository

   - Create a GitHub repository on your GitHub account
   - Push the content from this project to your repository.

   ```
    git init
    git remote add origin <your-github-project-url>
    git add .
    git commit -m "First Commit"
    git checkout -M main
    git push origin main
   ```

3. Create Project on Netlify (or other hosting platform)

   - Go to [Netlify](https://netlify.com/) (or any other hosting platform you like)
   - Create new project/site from your new GitHub repository to the project.
     <br /><br />

4. Set Deploy Options
   <br /><br />
   **Build Command:** `npm run build`
   <br /><br />
   **Publish Directory:** `dist`

## Deploy the Folder

- Open Netlify and login to your account. <br /><br />
- Run `npm run build` from root of your project.<br /><br />
- Drag-Drop new `dist` directory to Netlify window.<br /><br />

**Voilà! Your Blog app is ready and deployed!** 🎉
