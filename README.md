# React Router Navigation Bug

This repository demonstrates a common error in React Router DOM v6:  missing navigation links in nested routes, making it impossible for the user to navigate back to the previous page. 

## Issue:

The App.js file contains a simple example with two routes ('/' and '/about').  While you can go to '/about', there is no way to return to the home page from the '/about' page. 

## Solution: 

The bug is resolved by adding navigation links (using `react-router-dom`'s `Link` component) in both the Home component and the About component to allow users to freely navigate between pages. 