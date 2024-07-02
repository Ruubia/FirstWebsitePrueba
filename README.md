# FirstWebsitePrueba

## Project: Creating a One Page Website with Bootstrap

Practice your web development and Git skills by creating a single-page website.

## Instructions

1. Create a New Repository on GitHub:

- Go to [GitHub] (https://github.com/) and log in.
- Create a new repository by clicking the "New" button.
- Name your repository `FirstWebsitePrueba`.
- Make sure to initialize the repository with a README file.


2.  Clone the Repository:

- Clone the new repository to your local machine using the following command, replacing `your-username` with your GitHub username:

```sh
git clone https://github.com/your-username/FirstWebsitePrueba.git
```

3.  Project Setup:

- Navigate to the project directory:
```sh
cd FirstWebsitePrueba
```
  
4.  Create the File Structure:

- Create the necessary file structure for your project:
```sh
mkdir website
mkdir website/templates
touch website/templates/index.html
touch website/templates/styles.css
```

5.  Install and Run the Local Server:

- If you don't have `http-server` installed, install it globally using npm:
```sh
npm install -g http-server
```
- Run the local server to view your project in the browser:
```sh
  npx http-server --yes -c-1
```
- Open your browser and go to the local address provided by `http-server` to see the initial project structure.
  
6.  Develop the Project:
   
- Go to the `website/templates/index.html` file and add the basic HTML structure:
  ```html
  <html>
  <head></head>
  <body>
  ....
  </body>
  </html>
  ```
  
7.  Build the Page:

- Use the following Bootstrap examples and components to build your page:
  
  - Navbar: Use the [Bootstrap Navbar component] (https://getbootstrap.com/docs/5.3/components/navbar/).
  - Hero Section: You can use a background image and centred text. Example from [Jumbotron] (https://getbootstrap.com/docs/5.3/examples/jumbotrons/).
  - Main Content: Divide the content into sections using Bootstrap's grid system. Please take a look at [Containers and Grid] (http://surl.li/epcetu).
  - Portfolio: Use [Bootstrap Cards] (https://getbootstrap.com/docs/5.3/components/card/) to showcase projects.
  - Contact Form: Use the [Bootstrap Form component] (https://getbootstrap.com/docs/5.3/forms/overview/) to create the contact form.

8.  Styling and Customization:

- Customize the CSS styles as needed in the `website/templates/styles.css` file.
- Ensure the design is responsive and looks good on different devices.

9.  Integration and Deployment:

- Once you have completed the development, commit and push your changes to the GitHub repository:
  ```sh
  git add .
  git commit -m "Completed the one-page website"
  git push origin main
   ```

- Deploy your website using Vercel, Netlify, or GitHub Pages. Follow the specific instructions of the chosen service for deployment.

## How to Start This Project

- Create a new repository on GitHub, clone it, and follow the above instructions to start the development.
