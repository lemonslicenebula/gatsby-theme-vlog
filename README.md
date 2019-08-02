# Gatsby Theme Vlog

Create a vlog and with this simple and customizable Gatsby Theme.

It includes:
- MDX support
- a demo site (located in `demo/`) that installs the theme
- Option to style with Theme UI

## Usage


1.  Create a Gatsby site.
    ```gatsby new cool-new-vlog```
    
2.  Change directory to the folder you just created and install the theme
    ```cd cool-new-vlog```
    ```yarn add @lemonslicenebula/gatsby-theme-vlog```

3.  Add theme to your ```gatsby-config.js```
    ```js
    module.exports = {
    siteMetadata: {
        title: "Title of your site",
        author: "Your Name",
     },
    plugins: [
     `@lemonslicenebula/gatsby-theme-vlog`,
    ],
    }
    ```

4.  Adding pages
    Create an ```.mdx``` file in your ```/src/pages/``` directory.
    For example ```/src/pages/index.mdx``` to create the home page.

5.  Run ```yarn develop``` and go to http://localhost:8000
    
