# Developer Guidelines
This article describes how to build a PTS-IP6 website

### Create a new React App
1. Create a new project directory in your favorite location:
````shell
$ npx create-react-app pts-ip6
$ cd pts-ip6
$ npm start
````
2. Then open http://localhost:3000/ to see your app.
3. Next, execute the following command to open the web part project in Visual Studio Code:
````shell
$ code .
````
You now have a project with the React web framework.
### File Structure
React doesn’t have opinions on how you put files into folders. That said there are a few common approaches popular in the ecosystem you may want to consider.
**To more information about this:** [reactjs](https://reactjs.org/docs/faq-structure.html)

**However** we will use a method grouping by file type.

In case you still have a doubt about how a screen should look like, take a look at the [Document](./References/FileStructure.md) 

### Web App Manifest
The web app manifest provides information about a web application in a JSON text file.
**To more information about this:** [ManifestFile](./References/ManifestFile.md)

### Generate a license file
To run this generator from the command line you must install both generate and generate-license:

1. Install generate-license
    ````shell
    # install generate and generate-license 
    $ npm install --global generate generate-license
    ````
2. Generate a [Apache License 2.0](https://choosealicense.com/licenses/apache-2.0)

    ````shell
    $ gen license:license-apache-2.0
    ````
**Guidance on choosing a license for your open source project.** [license](./References/LicenseFile.md)

### Install bootstrap library
Download the latest release.
````shell
    $ npm i bootstrap
````
Read the [Getting started page](https://getbootstrap.com/docs/4.0/getting-started/theming) for information on the framework contents, templates and examples, and more.

### Install SASS library 
The library that provides binding for Node.js to LibSass.
````shell
    $ npm install node-sass
````
**To more information about building sass files :** [sass-guidelin](https://sass-guidelin.es/#architecture),  [Github](https://gist.github.com/AdamMarsden/7b85e8d5bdb5bef969a0), [sass-boilerplate](https://github.com/HugoGiraudel/sass-boilerplate/tree/master/stylesheets)

### Page Structure and Site Design
Well-structured content allows more efficient navigation and processing
In case you still have a doubt about how a page should look like, take a look at the [w3.org](https://www.w3.org/WAI/tutorials/page-structure)

### install react router library
Routing is the capacity to show different pages to the user. That means the user can move between different parts of an application by entering a URL or clicking on an element.

As you may already know, by default, React comes without routing. And to enable it in our project, we need to add a library named [react-router](https://reacttraining.com/react-router/web/guides/quick-start).

````shell
    $ npm install react-router-dom
````
https://github.com/reactjs/react-router-tutorial
egghead.io





(https://www.w3.org/2020/maps/)
https://www.ogc.org/