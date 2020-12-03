# Project-Catwalk

Welcome to our e-commerce website! This website utilizes a plethora of front-end development tools to render an e-commerce website and will render dynamically depending on what product you are trying to view. The product data the website uses comes from an external API that the page connects to via a series of HTTP requests. The bulk of this project is coded in React, with help from Webpack, SCSS, Redux, Axios, and many other tools.

## Product Details

_by Liam Murray_

![Image of product details](./readme-assets/overview-main.png)

This is the Product Details portion of the page, and it gives some general information on the product you're currently viewing, including styles, sizing, quantity, and other miscellaneous features. This also includes an image gallery so you can cycle through the various images for a given product, as well as the various images for each style selected (the styles are located on the right hand side in the small circles). These subcomponents utilize a number of React Hooks that are intertwined and will appropriately handle a user's experience as they navigate through this portion of the page.

## Related Products

_by Deodat Ruplall_

![Image of related products](./readme-assets/related.png)

In this section of the page, a dynamic carousel of cards display some basic information pertaining to products related to the current product you are viewing. These cards can be clicked on and the currently viewed product will be updated. This is mostly done using a module called React-Router, which is why you can also change the currently viewed product via the url. In addition, you can see an outfit carousel below the related products, whic can be stored by clicking the "Add To Outfit" button (the browser's localStorage is used to keep track of this information for a given user).

## Ratings and Reviews

_by J. Armando Garcia-Jacquier_

![Image of ratings and reviews](./readme-assets/ratings.png)

At the bottom of the webpage, you can find the Ratings and Reviews for a given product. Every product has a collection of ratings and reviews linked to it that detail certain aspects users have experienced with the product. These can include ratings based on fit, comfort, quality, and a variety of characteristics that are displayed by averaging all of these ratings in a variety of bars on the left-hand side of the page. On the right-hand side, you can find a list of reviews that speak about the product. This list can be extended depending on how many reviews were given as well. Lastly, you can see a Star component that is calculated for a certain product, and this Star component can also be found on the other portions of the webpage.

## Installation

Describe the installation process
To start application run (the last two commands need to simultaneously run while in development):

- npm install
  - This command will load all necessary packages/modules into your file system so you can properly run the code to serve up the page. The "node_modules" and "package-lock.json" should be created after this command is run
- npm run react-dev
  - This code will utilize webpack and compile your files and put all dependencies into a simple 'bundle.js' file so that it the only script tag you need in your HTML
- npm run start
  - Lastly, this code will run your Express server, which will actually serve up the HTML and React App if you try and load it in the browswer

## Usage

To use application navigate to localhost:3000/products/:productId

# Thanks for visiting!
